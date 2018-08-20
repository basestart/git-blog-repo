---
title: 从0开始， 最简易的redux学习总结
date: 2018-08-20 13:02:37
tags: ['redux', '总结', '最接地气']
---
<div align=center width = "30" height = "30">![redux](redux.png)</div>


网上讲述redux的文章实在是太多了， 多到很多有经验的程序员已经无法体会新手程序员初次接触redux时的纠结， 至少我第一次接触redux的时候， 内心的崩溃的， 这到底是神马？ 一会儿store， 一会儿reducer， 一会儿react-redux，为什么要搞这么复杂呢。 而且， 很多博客实例代码， 是以脚手架模块化的方式展示的， 谁能告诉我如何先搭建一个可以运行redux的集成环境（哭...）， 然后说一下如何安装redux， 然后讲redux是什么， redux的数据流运行流程？

为什么在面对这么多热心分享的博客， 我当时依然是懵逼的呢？ 后来总结了一下， 发现至少有两个方面的原因：

1. 很多博主在写博客的时候， 忽略了很多默认读者已经掌握的知识，比如脚手架， redux安装，但事实并不是这样， 恰恰是这些前置知识拦住了初学者的步伐（找一个集成redux的项目脚手架当时真的好难啊）。
2. 很多博主有关redux的文章是从已经掌握redux或者已经理解了redux设计理念的视角来总结学习经验的， 但初学者缺乏的恰恰是如何从jq， 从原生js过度到理解并体会redux理念视角的过程， 从这个角度来写的博客非常少。但这是初学者最容易理解和接受的方式。

所以问题出来了： 能不能抛开脚手架谈redux， 能不能从最直观初始的起点（传统数据流管理）逐步过渡到redux（单一数据流管理）， 这就是我写这篇学习总结的出发点。

接下来从一个最最简单的demo开始， 看传统的数据流是一步一步往redux过渡的， 以及这么过渡是出于什么样的考量：

下面代码完成一个非常小的功能： 点击+按钮， 数字加一， 点击-按钮， 数字减一

```
<!DOCTYPE html>
<html>
<head>
	<title>	redux-abc </title>
	<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.8.0.js"></script>
</head>
<body>
	<div>
		<button id="add">+</button>
		<button id="sub">-</button>
		<div id="show"></div>
	</div>
<script>
	var count = 0;

	var add = $('#add');
	var sub = $('#sub');
	var show = $('#show');

	add.click(() => {
		count ++;
		render()
	})

	sub.click(() => {
		count --;
		render()
	})

	function render () {
		show.text(count);
	}

	render();
</script>
</body>
</html>
```



