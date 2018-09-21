---
title: <<深入浅出webpack>> 购买链接modal层隐藏bug
date: 2018-09-13 10:56:40
tags: ['bug']
---

#### 1. 今天同事在github star了一篇技术文档[《深入浅出webpack》](http://webpack.wuhaolin.cn/), 讲真写得非常好，立马star（这是一个好习惯~~） 只是：

<div align=right width = "20px" height = "20px">![bug](bug.png)</div>

#### 2. 虽然拉动侧边滚动条依然可以隐隐约约看到后面的内容， 但是总觉得不好, 本着尝试的态度， 控制面板直接删除图书链接dom

<div align=right width = "20" height = "20">![bug](blur.png)</div>

#### 3. 发现后面还有一个模态层， 那就一起删了吧

<div align=right width = "20" height = "20">![bug](clear.png)</div>

#### 4. 看着清静多了， 可是， 滚动一下

<div align=right width = "20" height = "20">![bug](bug.png)</div>

#### 5. 又回来了， 这不行啊， 显然在scroll上做了文章， 那就看看吧

    var $bookBody = window.document.getElementsByClassName('book-body')[0];

    function closeModal() {
      if ($modal) {
        $modal.remove();
        $modal = null;
      }
      shouldClose = true;
    }

    function showModal(content, closeable) {
      if ($bookBody.getElementsByClassName('gitbook-plugin-modal').length > 0) {
        $bookBody.getElementsByClassName('gitbook-plugin-modal')[0].style.display = 'block';
        return;
      }
      $modal = window.document.createElement('div');
      $modal.style.left = $bookBody.offsetLeft + 'px';
      $modal.style.width = $bookBody.clientWidth + 'px';
      $modal.className = className;
      $modal.innerHTML = '<div class="gitbook-plugin-modal-content">' + content + '</div>';
      $bookBody.appendChild($modal);
      if (closeable) {
        $modal.onclick = closeModal;
      }
    }

    function checkModal() {
      if (shouldClose) {
        return;
      }
      // URL 检查
      for (var i = 0; i < excludeUrls.length; i++) {
        var exReg = new RegExp(excludeUrls[i], 'g');
        if (exReg.test(decodeURI(window.location.href))) {
          return;
        }
      }
      showModal(html, closeable);
    }

    // 事件监听检查
    $bookBody.addEventListener('scroll', checkModal);

#### 6. 这是添加了全局bookbody上的监听事件， 消失后会重新创建， 那就让它放到最下面吧


<div align=right width = "20" height = "20">![bug](over.png)</div>

<div align=right width = "20" height = "20">![bug](clear.png)</div>

#### 7. 完美，modal层消失， 于是赶紧给提issue，实践证明， 前端做安全控制就是坑， 以后这一块还是交给后端大佬来做吧！ 这么好的资源， 还是希望大家支持正版， 虽然我把这个modal在自己的机子上给整没了， 但是保证内容我可是没有看哦~



## 注： 本博客没有注册百度收录， 只注册google收录， 流量极少， 想来在除作者我本人之外，第一个用户看到之前， 作者应该已经把bug修复了吧。

    




