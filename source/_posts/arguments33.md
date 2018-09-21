---
title: Think Again III： How to Reason Inductively (3)
date: 2018-08-31 02:41:00
tags: ['arguments', 'coursera', 'Duke', 'Think Again III']
---

[coursera 课程链接](https://www.coursera.org/learn/inductive-reasoning)

<div align=center width = "30" height = "30">![top](in.jpg)

# Chance and Choice

CONTENT: This week will cover chance and choice—in other words, probability and decision making. Probability is useful for measuring the strength of inductive arguments and also for deciding what to believe and what to do. You will learn about the nature and kinds of probability along with four simple rules for calculating probabilities. An optional honors lecture will then explain Bayes’ theorem and the common mistake of overlooking the base rate. Next we will use probabilities to evaluate decisions by figuring their expected financial value and contrasting financial value with overall value.

LEARNING OUTCOMES: By the end of this week’s material, you will be able to do:

solve some classic paradoxes of probability
apply simple rules of probability
use Bayes’ theorem to calculate conditional probabilities
avoid fallacies of probability
apply probabilities to calculate expected financial values
distinguish financial value from overall value
use simple rules to aid decisions under uncertainty
OPTIONAL READING: If you want more examples or more detailed discussions of these topics, we recommend Understanding Arguments, Ninth Edition, Chapters 11 and 12

## Taking Chances

### Why Probability Matters

Hi. So far in this course, we've discussed a wide variety of inductive arguments. First of all, we looked at statistical generalization from a sample. Then we looked at application of the generalization down to a particular case. Then we looked at inference to the best explanation. An argument from analogy. 

Last week we turn to causal reasoning which involved the positive necessary and sufficient condition test. And in addition, at the very end, we looked at concomitant or con-commitment variation, which involved a kind of manipulation in drawing conclusions about what causes what. 

So we've seen a lot of kinds of induction. And that's got to raise the question. What's in common to all the different types of induction that makes them induction? 

What we saw, the inductive arguments, unlike deductive arguments, are defeasable. And they don't even aim at being valid. Instead, they just try to be strong. 

But strength comes in different degrees and we haven't really learned anything yet about what exactly strength is. 

Well, it turns out that one way of understanding inductive strength. 

Is that an argument is strong in proportion to the probability that its conclusion is true, given its premises. 

So inductive strength can be understood in terms of probability. And so for this week, we're going to turn to the notion of probability which will help us understand inductive arguments. 

But probability is important in a lot of other ways, too. I mean, just think about going on a picnic tomorrow. You want to know what the probability of it raining is. Because if the probability of rain is very high, you might not want to go on your picnic. Instead, stay inside. 

Okay, so probability affects our beliefs, and it affects our decisions. And that makes it important to understand probability, and try to figure it out. 

But that's a problem. Because if you just rest on your intuitions about probability, you're going to get messed up. You're going to make mistakes. Almost everybody messes up probability until they start thinking about it a little bit more seriously. Let me give you a few examples where people get confused about probability. [SOUND]. Seven, alright. [SOUND] [INAUDIBLE]. Seven, alright. Another seven, unbelievable, cool. 

Three sevens in a row, and seven's a winning number so, that's great but, you know, the odds of getting four sevens in a row are really slim so, I bet the next one's not going to be a seven. Right? No. 

Just because the first three were a seven, doesn't tell you the next one's not going to be. Sure, it's unlikely to get four in a row, but once you've got the first three, then the likelihood of getting the fourth seven, is just the same as the likelihood of getting a seven on any roll, whatsoever. 

Some people make that mistake. They think that just because they got three in a row, it's not going to come up that way again the fourth time. And other people make the opposite mistake. They say, Eh, the dice are hot tonight! I got three sevens in a row! Next one, I'm going to get a seven too! I'm going to put all my money on seven! Don't do it, you'll lose your money. Because even if the first three are sevens, dice don't get hot. The odds of getting a seven on the fourth one are exactly the same after you've gotten three sevens as if you didn't get three sevens. And both of these mistakes Three sevens, so the next one's not going to be seven. Three sevens, so the next one's going to be seven. They're both mistakes. Because the odds on the fourth roll are not affected by the odds on the first three rolls. And people who think otherwise, they're just going to get fooled by gamblers. It's not just in gambling, too. It's also in basketball. People think, oh, he's hot. He's made a lot of shots in a row, he's hot. He's going to make the next one. And then they'll tell that player, you take the shot because you're hot tonight. Well that's a little more controversial in basketball, but some statistics suggest that people don't really have hot hands in basketball. They just make the percentage that they make. And you're going to get strings. But that doesn't mean you're hot in any way. Like I said, that's controversial, but with dice at least we know the dice do not get hot. And so, don't waste your money making' that mistake. That's called the gambler's fallacy, and don't do it. 

Okay, deck a cards. And here I am. I'm going to shuffle the cards. Okay, there we go. There we go. I'm going to shuffle the cards again. Got these cards all shuffled. And now I'm going to deal out two hands, okay? Nine, a queen, an eight, a queen. A five, a queen, a jack, a queen, a four, an ace. Wow! Look at those hands. That's amazing. You think, they're about equally probable? What's the likelihood of that hand coming up? Most people would say, that's pretty slim. It's unlikely that you're going to get a hand with four queens and an ace. What about this hand? That's the kind of hand I get all the time when I play Poker. So most people are going to think, that kind of hand is a lot more likely. But actually, they're equally probable. Getting exactly this hand and exactly that hand have the same probability. 

The reason people think this one is less likely than this one is that you get that kind of hand a lot in poker, namely, a hand that's junk, that's useless. 

You get a winning hand like this not very often in Poker. And so people think that this one is less likely than this one. Because this hand is more representative of the type of hand that I get when I'm playing and that most people get when they're playing. But that's what's called the representativeness heuristic. You think it's more probably because it's more representative of the kind of thing that you encounter and experience. 

Another famous example of the representativeness heuristic comes from Kahneman and Tversky. It's about Linda the bank teller. They tested a large number of subjects. What they did is simply describe Linda. 

Linda is 31 years old, single outspoken, and very bright. As a student, she majored in philosophy, she was deeply concerned with issues of discrimination and social justice, and she also participated in antinuclear demonstrations. 

They asked their subjects to rank the following statements with respect to probability, you know, which one is more probable than which of the others. 

Linda is a teacher in an elementary school. Linda works in a book store and takes yoga classes. Linda is active in the feminist movement. Linda is a psychiatric social worker. Linda is a bank teller. Linda is an insurance sales person. And Linda's a bank teller and is active in the feminist movement. And when people ranked all of these, they tended to put, Linda is a bank teller and is active in the feminist movement as more likely than Linda is a bank teller. 

That can't be. I mean just think about it. It's got to be less likely that she's a bank teller and active in the feminist movement than simply that she's a bank teller. Because in every possible state of affairs where she's a bank teller and active in the feminist movement, she's also a bank teller. 

So there have to be some possibilities where she's a bank teller, but not active in the feminist movement. So it has to be more likely that she's a bank teller, than that she's both a bank teller and she's also active in the feminist movement. Now why do people make this mistake so often? 

It's largely because when they trust their intuitions about probability, those intuitions are based on what they take to be representative. Someone with a background like Linda who is deeply concerned with issues of discrimination and social justice, are likely to be active in the feminist movement. Whereas bank tellers are not typically known for being active in the feminist movement. So it would be more typical for her to be both, than for her to just be a bank teller. 

And so they base their probability judgment on the representativeness heuristic and that's what leads to the common mistake. One final common mistake about probability is illustrated by what has come to be known as the Monty Hall problem, or sometimes the three door problem. Here's the set-up, which comes from an old TV show called Let's Make a Deal. 

There are three doors on the stage. Let's call them door A, door B, and door C. 

And behind one of the doors is a car. And if you get the right door, you get to keep the car. But behind the other two doors is a goat. And if you get those doors, you go home with a goat. 

Now, we're assuming that you'd rather have a car than a goat. You might be one of those weird people, but let's assume you want a car and not a goat. Imagine that you picked door A. And then the host, Monte Hall, opens door C, and reveals behind door C, a goat. 

Now, you know that there's door A and door B left, one of them has a car, one of them has a goat. Monte Hall turns to you, and he offers you the chance to switch from door A, the one that you picked, to door B. And the question is, should you switch? 

And this is actually, caused a lot of controversy, because some people think you should switch, some people think you shouldn't switch. I'm not going to tell you, because that's going to be one of our exercises. And, the point of this lecture is just to show you that you can't trust your intuitions. Because so many people will get it wrong in the Monte Hall case, in the representativeness heuristic and so many people commit the gamblers fallacy, that you need to take probability seriously. And in the next lecture we'll start looking at some definitions of what it is and the lectures after that we'll look at rules for probability. Because you need that kind of thing if you can't trust your intuitions. 

嗨 这门课到目前为止 我们已经讨论了多种多样的归纳论证这门课到目前为止 我们已经讨论过了品类繁多的归纳论证 一开始 我们从一个例子中看过了统计归纳 我们通过具体事例分析概括的应用然后我们通过一个特殊的例子看过了归纳的应用 再然后我们又学习了最佳解释推理再然后我们又看过了推论的最佳解释 学习了类比论证一个来自类推法的论证 

上一周我们学习了因果推理上周我们转到因果推理 它包括 其中包括了必要和充分条件的肯定检验积极必要条件和充分条件的检验 最为补充 在最后 我们看过了共变或附随变化作为补充 在最后 我们看过了伴随或者承诺变动 它通过一种操作它包括了一种 来判定谁是谁的原因在给“什么导致什么”下结论的过程之中的操纵 

所以我们已经了解了多种归纳方式所以我们已经看过了许多种归纳 看到这些我们不禁要问 在所有不同类型的归纳法的归纳中 它们的共性是什么？它们的共同点是什么？ 

我们看到的归纳论证 不像演绎论证那样是可作废的 它们甚至不在乎有效性它们甚至不是为了有效性 相反 它们仅是追求论证的力度相反 它们仅仅是试着达到强有力 

但是力度有强弱 而且但是力度有不同的程度 我们还没有真正学习什么是力度我们并没有真的学到力度究竟是什么 

那么 可以这样理解归纳力度那么 这里呈现出一条理解归纳的力度的方法 

在论证的前提下一个论证的令人信服程度与 论证的力度与结论为真的可能性成正比给定前提下结论为真的概率成比例 

因此归纳力度可以被理解为一种概率因此归纳论证的影响力可以被理解为一种概率 于是在这周 我们将学习 概率的概念 它会帮助我们理解归纳论证 

但是概率在其它很多方面中也非常重要 我是说我的意思是 假设明天将要去野餐 你想要知道下雨的概率是多少 因为如果下雨的概率很高 你可能就不会想要去野餐 而是待在室内 

那么好 概率影响着我们的观念和决定那么好 概率影响了我们的信念 也影响了我们的决定 所以理解概率就变得十分重要了这使得理解概率变得很重要 而且要试着去搞明白它 

但是这是一个问题 因为如果你仅用直觉去体会概率因为如果你仅仅是基于对概率的直觉理解 你将会把事情搞砸 你会犯错你将会犯错 几乎每个人都在概率上犯过糊涂 直到他们开始认真的思考它 让我给你们一些人们被概率搞迷糊的例子 [声音] 七 对吧 [声音] [无法识别] 七 对吧 又一个七 难以置信 真酷 

连续三个七 而且数字七象征着胜利连续三个七 而且七是一个赢的数字 那很好 但是你知道 得到连续四个七的可能性非常小 我打赌下一个数字将不会是七 对吧? 不是的 

仅仅是因为前三个数字是七 并不是说下个就不是七了并没有告诉你下一个不会是 当然 连续四个七也不大可能当然 它不太可能会得到连续四个 但是一旦你已经得到前三个但是一旦你已经得到前三个  那么得到第四个七的可能性得到第四个七的可能性 跟得到任何一个七的可能性是一样的 

有些人就犯了这样的错有一些人就犯了这样的错 他们那么想仅仅因为他们得到了三个一连串的七他们想仅仅因为他们得到了连续三个七 第四次可不会还那样走运它将不会在第四次还那样 而另一些人犯了 相反的错误 他们说 今晚骰子手气很好！ 我得到了三个连串的七 下次我还会得到一个七我得到了连续三个七！ 下一个我还会得到一个七！ 我要把我的全部钱压在七上 不要那么做 你会输钱的我将把我的全部钱压在七上 不要那么做 你将会输掉你的钱 因为即使前三个都是七 骰子也没有好运气 得到第四个七的概率 和你得到三个七或者没有得到三个七的概率是一样的在你得到三个七或者没有得到三个七之后时候是完全一样的 这两个错误 得到三个七 因此下一个将不会是七这两个错误 三个七 因此下一个将不会是七 得到三个七 因此下一个将会是七三个七 因此下一个将会是七 这两个说法都是错的它们都是错的 因为扔第四次点数的可能性因为扔第四次点数的可能性并不受 并不受前三次的影响前三次的影响 而如果人们这样去想 他们只会被赌徒们愚弄而如果人们不这样去想 他们只会被赌徒们所愚弄 不仅在赌博中是这样 在篮球比赛中也是这样这也不仅仅在赌博中 它也在篮球比赛中 人们想 天哪 他手气很好 他连续得了很多分 他手气不错 他投的下一个还能进他运气很好 他将要投进下一个 然后他们将告诉那个球员 你得到进球因为你今晚手气很好然后他们会告诉那个球员 你得到进球因为你今晚手气很好 其实 这在篮球比赛中是有一点争议的 但是一些统计数据表明 在篮球比赛中人们并不是真手气好但是一些统计数据表明 在篮球比赛中人们并不是真的有手气好的情况 他们仅仅是实现了他们的得分率 你将接连进球你将进一系列的球 但是这不意味着你在某种程度上手气好但是这不意味着你在某种程度上的手气好 像我说的这样 那是有争议的就像我说的 这是有争议的 但是从骰子来说我们至少知道骰子不会手气好 因此 不要浪费你的钱来犯错 这称之为赌徒谬论 不要这样去做 

那么好 一副扑克牌 我现在在这里 我将要洗牌 我洗啊洗 我洗啊洗 我将再次洗牌 把这些牌全部打乱 现在我将分给两只手 九 一个Q 一个八 一个Q 一个五 一个Q 一个J 一个Q 一个四 一个A 哇 看看这两只手 这非常令人吃惊 你认为它们是相等的几率吗？ 这只手上得到的结果的可能性是多少呢？ 许多人会说 那几率太小了 你不大可能会在一只手上得到四个Q和一个A 那这只手呢？ 好像我平时打牌总是得到这些牌 因此大多数人会想 更可能得到的是这只手的情况 但事实上 它们的几率是相等的 

得到这手牌和得到那手牌的概率是一样的 关于理由 人们认为这手牌比那手牌的可能性小是因为 

你得到这类牌的时候更多 换句话说 这手牌很烂 没有用  你不经常在扑克游戏中得到像这样的一手赢牌 于是人们觉得这手牌的可能性低于那手牌 因为这手牌的类型更具代表性 在我玩扑克的时候 更多的人也在他们打牌的时候得到这样的牌 但是这就是所谓的代表性启发法 你认为这更有可能 因为这一类在你所遭遇过和 

经历过的事情中更具代表性 另一个代表性启发的著名例子 来自卡尼曼和特维斯基 这是关于一个叫琳达的银行柜员 他们测试了大量的类别 

他们所作的是简单描述琳达 琳达31岁 单身 率真 并且非常漂亮 作为一个学生 她的专业是哲学 她非常关注 歧视以及社会公正的问题 

她也参与了反核示威 他们怀着对概率的敬意询问了他们的所有类别来给接下来的陈述排序 

你们知道的 哪一个比另一个更有可能 琳达是一个小学的老师 琳达在书店工作并上瑜伽课 琳达在女权运动中很活跃 琳达是一个精神病的社会工作者 琳达是一个银行柜员 琳达是一个保险销售员 而且琳达是一个银行柜员 并在 女权运动中很活跃 当人们给这些排序时 他们倾向于选择 

把琳达是一个银行柜员并在 女权运动中很活跃 而不是琳达是一个银行柜员 那不应该是这样的 我的意思是去想一想这件事 她是银行柜员并是女权运动活跃者的概率 比简单的她就是个银行柜员的概率要低 

因为在每个可能的事件状态里 当她是一个银行柜员 和一个女权运动活跃者 她也是一个银行柜员 因此 银行柜员 但不是一个女权运动活跃者 因此 更可能的是她是一个银行柜员 比起 

她又是银行柜员又是女权运动者来说 为什么人们如此经常的犯这样的错误呢？ 很大程度是因为他们相信自己对概率的直觉 这些直觉基于他们觉得有代表性的事物 有着琳达这样背景的人 即深度关注 歧视问题和社会公正的人 很有可能 是一个女权运动的活跃者 然而银行柜员据大家所知并不是代表性的 女权运动活跃者 

因此对她来说更具代表性的 是同时二者兼而有之 而不是仅仅是个银行柜员 因此他们基于他们在代表性启发上的概率判断 就导致了这种许多人共同犯的错误 最后一个 关于概率的共同性错误被广为人知的 

蒙蒂·霍尔问题所描述 或者有时候叫做三门问题 这个问题来自一个叫《让我们达成交易》的早年电视节目 是这样设定的 

舞台上有三个门 我们称之为A门 B门 C门 其中一扇门后面是一辆汽车 如果你选对了门 你就可以拿走汽车 

另两个门后面是山羊 如果你选择这两扇门 就牵上山羊回家 现在 我们假设你更想要一辆车而不是山羊 你可能是一些奇怪的人中的一个 但是 让我们假设你想要一辆汽车而不是一头山羊 

想象你选了A门 然后主持人蒙蒂·霍尔打开了C门 后面是一只山羊  现在你知道有A门和B门剩下 一个后面有汽车 一个后面是山羊 蒙蒂·霍尔转向你 他给你一个机会 

可以改变选择 把你现在选的A门改为B门 问题来了 你该不该换呢？ 这事实上也引发了很多争论 因为 一些人认为你应该换 一些人认为你不应该换 我不打算告诉你们 因为这将会是我们的一个练习题 这一讲想要讲的仅仅是 告诉你们不能相信自己的直觉 因为如此多的人在蒙蒂·霍尔问题上犯了错 在这个代表性启发上犯了错 很多人犯下了赌徒谬误 你需要去认真的考虑概率 在下一讲我们将开始着眼于一些这是什么的定义 那之后的一讲我们将看看概率的定理 

### What Is Probability?

We need to start our study of probability with a little terminology. How do we talk about probability? 

We learned early in the course in the second week about guarding terms, where people say things like, well it might be the case that a meteor's going to hit your house, so you need meteor insurance. But might's just possibility, and that's different from probability. If you ask how probable is it that a meteor is going to hit your house, the answer is going to be pretty low. But how do you say how low it is? 

One way to talk about probability is to say the number of times that it might happen out of the number of times that occur. So you might say three times out of ten. This horse will win the race three times out of ten. In ten races, it'll win three times. You can also do that in terms of three in ten, or simply, there's a 30% chance. Three times out of ten, 30% chance, same thing. But the way we're going to put it, for the rest of these lectures, is to talk about the probability of 0.3. Probabilities range from zero to one. 

One means it's absolutely certain that it's true. If you say the probability is one that means it's going to happen. Zero means there's no chance it's going to happen, it's certain that it won't happen, that it's not true. 

So, every probability has to be between that. Between it's absolutely certain that it won't happen and it's absolutely certain that it will happen, when you're somewhere in the middle, you're between zero and one, you've got different levels of probability. That's the way we talk about it. Now, probabilities come in many different kinds. The first kind of probability we're going to call a priori probability. Because you figure it out prior to experience. Prior to any kind of experimentation. So, take, for example, a coin. It's got tails, it's got heads. You flip it, and what do you get? Well, you can't see, but that time, I actually got tails. 

What's the probability it'll come up tails? We tend to just assume that it's a fair coin, which means that the probability of coming up tails is equal to the probability of coming up heads. 

So if they're equal, when you add them together you should get one, because it's absolutely certain that you're going to get either heads or tails. One of the other and that means that you assume the probability is 0.5. But all that's just assumption. You're just assuming that the outcomes are equally likely. 

Now, let's turn from coins to dice, little bit more complicated, six sides. You roll one of them and if you get a two, as I just did, then the odds of getting a two when there's six sides, if you assume they're all equally probable is going to be one out of six. What if you rolled two of them, like we did when we were discussing the gambler's fallacy. Oh, my gosh, I got seven again, pretty cool. [LAUGH]. And what's the likelihood of that? Well, how many ways are there to get seven on a pair of dice? 

You can get one and six. You can get two and five. You can get three and four. But you can also get four and three, five and two, six and one. So there's six ways to get a seven on two dice, and there are 36 possibilities, six times six, so, the probability of getting a seven when you roll two die are six out of 36, or 1 6th. But notice that we're just assuming that these dice are fair. It gets a little more complicated when you have to give up that assumption. 

So let's start with coins, no tricks up my sleeve. It's a normal coin, heads, tails. What are the odds of getting heads? [SOUND]. Well, two possibilities, heads or tails. We assume they're equally probable. The odds of getting a head are one in two. We can figure out the probability just by assuming that heads and tails are equally likely. And that's a priori probability. And now let's get violent. If you take the coin and you put it in your pliers, like this, but check the desk. And you get your hammer and you start [NOISE] and you bend the coin okay. Good see, now it's bent okay, now let's check the probability again. Here's our bent coin, now we flip it. What are the odds that it's going to come up heads? Heads, heads, heads. Pretty good. Heads. Well I can't get it to do it. But sometimes it'll come up tails and we don't know how often. Looks like most of the time when it comes up heads but sometime it'll come up tails. How often, we don't know. The only way to figure that out is to flip it hundreds and hundreds of times and see what percentage come up. That's because once you bend the coin it's not a priori probability. You can't just assume that the coin has equal chances of landing heads or tails. You have to turn it into a statistical probability and look at the frequency of the actual flips for that particular bent coin. Here's one more example of the difference between a priori probability and statistical probability. 

One of my favorite games, Pass the Pigs. I highly recommend it, it's a really fun game. Now, what about this? You roll the pigs, and sometimes you get 

a snouter, or a leaner, or a jowler, or a razorback or a trotter, they're different results and, ooh there we go, a double razorback, that's pretty good. And you roll them, ooh look at that a leaning jowler, that's a lot of points there. And we, you have to roll them a long, a lot of different times in order to get the probabilities. And we actually did that. We did 1817 rolls. We got one side up 1174 times, trotter 150. Razorback 441, snouter a 39, leaning jowler 13. So what are the odds of getting a leaning jowler on one roll of a Pass the Pig? 13 out of 1817. Now notice that you could never do that a priori, just by assuming probabilities. You have to do an actual experiment and look at the frequencies because this probability is not a priori probability, it's a statistical probability. And the nice thing about statistical probability is you can apply it to a lot of things besides coins and dice, right? What's the probability it's going to rain tomorrow? 

Well, how do they figure that out? They do a lot of observations and when it rains, under what kinds of circumstances. And they ascribe a probability on the basis of how many times it's rained in similar circumstances in the past. And what's the probability this batter's going to get a hit in baseball? 

Well, they look at his batting average over the previous part of the season. Especially under certain circumstances versus right-handers, pitchers versus left-handed pitchers and you get a probability that he's going to get a hit this time. The same for cricket, if you've got a bowler, a spin-bowler or a speed-bowler. Well, this batter might be better against one than the other, and you can figure the probability against the different types of bowlers. So, in sports you use statistical probabilities a lot. And in life you use statistical probabilities a lot. When you try to decide what kind of car to buy and you want to know what's the likelihood that this particular car will breakdown in the first year, you go to Consumer Reports. And you see how many cars of this sort breakdown in the first year. So we use statistical probabilities for a lot of different areas. Really a priori probabilities are only applicable when you can assume that the outcomes are equally likely. 

And that's the real difference between a priori probability and statistical or empirical probability. One of them is just based on assumptions that the outcomes are equally likely. That's a priori probability. 

The other is based on empirical evidence about how often things happen, the frequency of events in the world. That's statistical or empirical probability. But no matter which kind of probability you're talking about, a priori or empirical. They still have to follow the same general rules. And it's those rules that we're going to study for the next few lectures. 

我们要从术语开始学习概率 我们要如何谈论概率呢？ 

我们在这门课第二周讲过 让步的术语。举例来说 就像一颗流星 要撞击你的房子 所以你需要买流星保险 但是这只是一种可能性，而且这和概率不一样。 如果你要问 有多大可能流星会撞到你的房子上 答案就是可能性很低。 但是你怎么形容有多低呢？ 

一种方法就是形容 在多少次流星落地时有多少次房屋会被击中 所以你可能会说十分之三。 这匹马有十分之三的概率会赢 在十次比赛中 有三次它会赢 你也可以说成是十分之三，或者30%的概率。 十分之三和30%的概率是一样的。 但是我们接下来会用概率来讨论 用0.3的概率来表示。概率的范围从0到1. 

1表示命题完全正确。 如果你说概率是1，那么这件事一定会发生的。 0意味着某件事不会发生 这件事 而这个命题并不正确。 

所以，每一个概率都处于0和1之间。 在完全确定和完全不可能之间 你肯定会处于中间的某个位置。 你在0和1之间 有不同的概率水平 我们用这种方式来讨论概率 概率有很多种 第一种概率我们叫做先验概率 因为你在经历之前就明白它了 在进行任何实验之前就知道了。 举例来说，一枚硬币有反面。 也有正面。你把它抛起来会得到什么？ 好吧，你看不见，但是这一次来了个反面。 

得到背面的概率是多少呢？ 我们假设这是一个公平硬币，意味着 出现背面的概率和出现正面的概率相等。 

如果它们相等，加起来 就会得1， 因为非常清楚你要么得正面要么得背面。 意味着你假设概率是0.5 但这只是假设而已。 你只是假设结果是一样的。 

现在我们从硬币说到骰子 6个面更加复杂一些 你扔出一个骰子得到2 我刚扔出来个2，那么在6个面中扔出2的几率， 如果你假设出现任意面概率均等的话，那么就是1/6. 如果你扔2个骰子， 就像我们讨论赌徒谬论时那样 哦，天啊，我扔出来了7，好酷 哈哈 这种情况的概率是多大呢？ 那么 有几种办法能得到7？ 

你可以扔1和6 也可以扔2和5 3和4 也可以是4和3 5和2 6和1 所以一对骰子有6种方式能得到7 总共有36种可能性，6×6 所以，扔出7来的可能性就是6/36，或者1/6 注意我们只是假设了骰子是公平的 你放弃这个假设的时候问题就会变得更复杂一些 

让我们从硬币开始，我的袖子里没有藏机关。 这是个正常的硬币，有正面和背面。 正面的几率是几？ [琴声] 两种可能，正面或背面。我们假设它们的可能均等。 扔出正面的几率是1/2 我们可以假设正面和背面出现的机会相同 机会相同来得出概率 这就是先验性概率。现在我们来玩暴力一点的。 如果你把硬币放到钳子里。 就像这样 小心桌子 准备好锤子 [NOISE] 然后你就可以弯折硬币了。 现在它弯好了。现在让我们看看概率。 这是我们的弯曲硬币 我们来扔扔看 得到正面的几率是多少？ 正面 正面 正面 很好 正面 好 我不打算继续了。 不过总会有背面出现的，我们不知道有多经常出现。 看起来大多数时间会扔出正面，但是有时会出现背面。 我们不知道有多频繁 唯一的办法就是扔硬币 几百次，来看出现的百分比。 因为你一旦弯折硬币之后这就不是一个先验性概率了。 你不能假设 正面和背面出现的几率相等 你必须用数据统计概率 并且抛这枚弯折的硬币来看频率。 再说一个例子 关于先验性概率和统计学概率的 

我最喜欢这个游戏了 把猪给我递过来 我力荐这个好玩的游戏 现在 怎么样？你扔这两只猪 有时候 

你会扔出来鼻子 有时候是里脊 有时候是猪蹄 会有不一样的结果。哦我们得到了一个双里脊，真是不错。 然后来扔一下它。哦瞧啊 一块瘦下颚 这能得很多分耶 我们要一直扔它们 转很多次来得出概率 我们真的这么干了 扔了1817次。 我们得了1174次单面上，150次猪蹄， 441次里脊 39次猪鼻 13次瘦下颚 所以扔一次得到瘦下颚的几率是几呢？ 13/1817 注意这里你不能使用先验概率了，不能只是假设一个概率。 你必须得做一个实验来找出频率 因为这种概率 并非先验概率，它是统计概率。 统计概率的好处就是你能在 硬币和骰子以外的地方用它，不是吗？ 明天下雨的概率是多少？ 

他们怎么知道的呢？ 他们在下雨时观察了很多次那是在什么样的条件中 然后他们估算出来在相似的条件下 过去有多少次会下雨。 击球手击中棒球的概率又是多少呢？ 

他们会找出这季度前部分他击中球的平均数。 尤其是在特定环境下 右撇子投球手vs.左撇子投球手 你会得到一个他这一回击中球的概率。 板球也是一样。如果你有一个投球手，一个旋转投球手或者一个快速投球手。 这一击跟这个人打比跟另一个人打更有把握。 你可以算出在不同的投球手之间的击中率。 我们在运动中经常用到统计概率 在生活中 也可以用到许多概率。 当你想决定买哪一种车时 你也想知道 这一种车在第一年坏掉的可能有多大。 你可以去查消费者报告 你能看到有多少辆这种车在第一年内就坏掉了 我们在许多不同的领域中使用概率。 只有在能够假设得到的结果几率均等的时候， 我们才能使用先验概率 

这是先验概率和统计概率 或者说是 经验概率之间存在很大不同。 基于结果概率均等假设的 是先验概率 

基于经验证据得出 事情发生的频繁程度的， 是经验概率。 但无论你讨论的是哪一种 先验或者经验 它们都必须遵循一样的法则。 我们在接下来的几节课中来学习这些法则。 

## Rules of Probability

### Negation

All the different kinds of probability are governed by the same basic rules. But what are these basic rules? We're going to look at four basic rules. The first one governs, simply, negation. 

So you toss a coin, and you get tails. What's the probability that you get tails? We said, one in two or 0.5. Now, what's the probability that you do not get tails? 

Well that means that's the probability that you get heads. So it's also 0.5, it's 1 minus the 0.5 probability of tails gives you the 0.5 probability of not getting tails, that is, of getting heads. 

Well that's really simple, because there are only two possibilities. What about a die? 

You roll a die and you get a two. 

What's the probability that you'd get a two? Well, it's one in six. 

What's the probability that you would not get a two? Well, not getting a two, is getting either one, or three, or four, or five, or six. So there are five possibilities of not getting a two. And that means. That that's five times out of six you do not get a two. So the probability of not getting a two is one minus the probability of getting a two. The probability of getting a two is one in six. So the probability of not getting a two is five in six. 

So our rule is basically that the probability that an event will not occur. Is one minus the probability that the event will occur. And we can put that in symbols, like this. You put Pr, for probability, and then in parentheses you put what it's the probability of. 

We're going to use h for hypothesis, or the event that we're testing the probability for, and the little squiggle or tilde means not. 

Just like it did when we were talking about propositional calculus a few weeks ago. So the probability of not the hypothesis is equal to one minus the probability of the hypothesis. That's basically the rule for probabilities of negations, and we explained why it holds because certainty is one. The thing happening and the thing not happening have to add up to one because it's gotta either happen or not happen. So, one minus the probability that it happens, has gotta be the probability that it does not happen. So hope now, the rule makes sense. And that you can apply it in a couple of exercises. 

### Conjunction

The rule for the probability of conjunctions is a little more complicated. One reason is that there are really two cases we have to keep separate. We're going to look first at the case of independent events, and we have to begin by saying what it means to call them independent. 

To call them independent, is simply to say that the probability of one does not affect the probability of the other. 

So if you flip a coin or roll a die, you get a certain number and then you pick up the coin or the die and you flip it or roll it again. Then the second result, is not affected by the first result. So those are independent events. And with cards, if you take a deck of cards [SOUND], and you pick out a card, two of spades. Then you take that two of spades and you put it back in the deck. You shuffle, it's going to be independent, whether you get it again, because what you picked out the first time doesn't affect what you pick out the second time. But, if you take a deck of cards, and you pull out the king of spades, and you take that card, and you throw it away. And don't put it back in the deck, then if affects all the probabilities of the remaining cards, because now you have fewer cards than you had before. 

So that's the difference between independent events and dependent events. So we're going to look at independent events first, and look at the rule for the conjunction of independent events. 

And the rule for this case is pretty simple. If two events are independent, then the probability that both events will occur in that order, cause we're talking about this one and then that one. We'll talk a little bit more about that later, but we're assuming that. 

The product that they both will occur is the product of the probability of the first event, times the probability of the second event. And notice, that the both occur is tied to the product, or multiplying the two probabilities together. And the reason for that is that it's less likely that they will both occur, then that one of them will occur separately. 

And when you multiply the two probabilities, between zero and one, you're going to get a lower probability that they both occur. Then for either one of them occurring, you know, all by itself. 

We can restate this rule symbolically using the symbols that we used before for the probability of negation. Namely, the probability of hypothesis one and hypothesis two both being true, is the probability of hypothesis one times the probability of hypothesis two. Now let's apply it to some cases. 

Suppose you flip a coin and you get heads. You flip another coin, and you get heads again. What's the probability of getting heads twice on two flips of a coin? Well, the probability is 0.5 for the first flip of getting heads. It's 0.5 of the second flip of getting heads. And then, the probability of getting both is going to be 0.5 times 0.5 or 0.25. So the probability of getting two heads in a row, is 0.25, on two flips of a fair coin. 

A little more complicated example, uses cards. Here we have a standard deck of cards. 

Ace, two, three, four, five, six, seven, eight, nine, ten, jack, queen, king. So there are 13 different types of cards, and there are four different suits. Spades, hearts, diamonds and clubs. So we can remember that the probability of having one of these types of cards chosen, assuming that they're shuffled properly, is one out of 13. And the probability of getting a particular suit, say a club, is one out of four, because there are 13 clubs out of 52 cards. Clubs are one suit out of four, so the probability of picking a club is one in four, and the probability of picking a particular card, say a 3 is one in 13. Again, a deck of cards. Suppose I pull out a 4, and then I pull out, a club. 

Now in a standard deck of cards, there's 13 cards, we're assuming no jokers, so the odds of getting a 4, are one in 13. There are four suits, spades, hearts, diamonds and clubs. So the odds of picking a card that's a club is one in four. What's the probability of picking a four, and then picking a club. 

Well it's going to be one in 13 times, one in four. And that means it going to be one in 52. So the odds of that combination occurring, right, in that order. Is going to be one over 13 times one over four equals one in 52. That example shows you how to calculate the probability of a conjunction with independent events. But what if the events are not independent? That is, what if the probability of one affects the probability of the other? Here's a question. 

Joe, can run a mile in less than five minutes about half the time. 

When he runs, and he's timed, half the time he's under five minutes, half the time he's over five minutes. 

So what's the probability he can run a mile in less then five minutes on a given occasion 0.5, but what's the probability he can run one mile in under five minutes. And then, run another mile in under five minutes right after that. 

Well, if you did this calculation you would have 0.5 x 0.5 and that means 0.25. But you know that's not right, because he's going to be dead tired after the first mile. There's no way that the probability of running the second mile in under five minutes is just as high. Whether or not he just finished running a mile. 

So those events are not independent, and that example shows you why you need a new formula to calculate the probability of a conjunction When events are not independent, but instead their probabilities depend on each other. The same distinction between independence and dependence applies to our old friend cards. So, just to simplify matters, lets start with a very limited deck. It just got four aces. Its got the ace of spade the ace of hearts, the ace of diamonds, and the ace of clubs. And notice that the ace of hearts, and the ace of diamonds, are red, and the ace of spades and the ace of clubs, are black. So, knowing that, out of these cards, if we shuffle them, and don't look at them, what's the probability of picking a red ace? Well, one and two, right? Because two of them are red out of the four. Now, sorry. Oh, a red one. I picked a red one. Now, let's put it back in the deck and shuffle them together, okay? What's the probability now of picking another red ace? 

Again, one in two. So if you look at the possibilities all laid out, the first pick is in the columns, right? So the left-most column is if you pick an ace of spades on your first pick. Second column is ace of hearts on your first pick. Third column is ace of diamonds on your first pick. Fourth column is ace of clubs on your first pick. And then your second pick is the rows. And again it's either spades, hearts, diamonds, or clubs. So there's 16 possible combinations of picks here, in order. And, how many of them, are picks, where you have, two red aces. Well, this is one, this is one, this is one, and this is one. So, the four possibilities in the middle, are the possibilities where you've picked an ace, it's red. Both on your first pick and also on your second pick, so the odds of doing that are four out of 16 or one out of four. Or 0.25 just like we calculated using the formula. But, what if there's no independence? Let's start with the same four aces. Okay, and, what's the probability of picking a red ace, still one in two. So, let's suppose I pick the ace of hearts, throw it away, do not, put it back in the deck, and now I've only got three aces left. What's the probability of picking a second red ace, without looking? Well, it's going to be one in three, because one of them and the other two are not. There are three cards left, one of them is a red ace. The probability is 1 out of 2 times one out of 3 equals 1 out of 6. Instead of the 1 out of 4 that we had when they were independent and you put the card back. 

So we need a different formula to generalize for this case where there's dependents, okay? 

And this formula is going to use the conditional probability, which is just a fancy way of saying what I just mentioned to you, right? The conditional probability of picking a red ace on the second pick, given that I pick a red ace on the first pick and threw it away, is one in three. 

Is how many times does x occur picking a red ace on the second pick, out of the cases where I picked an red ace on the first pick and threw it away. And that's going to be your one in three. So that's the conditional probability. And now the formula, the probability of both of the two events occurring is the product of the probability of the first event occurring. Times the conditional probability of the second event occurring, given that the first event occurred. 

That's where you use the conditional probability. And notice when the events are independent. Like conditional probability of the second event occurring given that the first event occurred, is just going to be the same as the probability of the second event occurring. 

Because the first event doesn't affect the second event. So, that first formula for independence, is just an instance of this formula. Where the conditional probability of the second given the first, is identical with the probability of the second. So that's why it's a generalized formula. It actually includes the first formula, but when they're independent, it's just simpler to think of the first formula alone. 

We can also symbolize this rule. We can say that the probability of hypothesis one and hypothesis two is equal to the probability of hypothesis one, times the probability of hypothesis two given hypothesis one. And that straight up and down line, in this formula is what indicates conditional probability. This sort of formula here, means, the probability of hypothesis two, given hypothesis one. 

So you can use this rule to calculate the probability of any old conjunction, whether they're independent or not. 

But, when they are independent, you might want to use that simpler rule, which was the first version of the probability of conjunction. 

与的概率规律更加复杂 其中一个原因是我们必须将其分成两种情况 先来看一下第一种情况：独立事件 首先来说明一下什么是独立性 

所谓独立事件 就是指 一个事件的概率不会影响另一个事件的概率 

所以 比如弹硬币或者掷骰子 会得到某个数字 然后将硬币或者骰子捡起 再弹一次或者再掷一次 第二次的结果不会受到第一次的结果的影响 所以它们是独立事件 对于纸牌来说 先拿一付纸牌 再吸气 挑选出两张黑色纸牌 再将这两张黑色纸牌放回原来的牌堆中 洗牌 你能否再摸到一张黑色纸牌这件事是独立的 因为 你第一次摸牌这个事件不会影响到你第二次摸到的牌 但是 如果在一付牌中 挑出 黑桃K 并将这张牌拿走 扔掉 也就是说不放回原来那付牌中 那样它就会影响到所有 剩余纸牌被摸到的概率 因为现在拥有的纸牌数比原来少 

这就是独立事件和非独立事件之间的区别 所以我们先来看一下独立事件 和独立事件相与的规则 

这种情况下的规则非常简单 如果两个事件是独立的 那么这两个事件 接连着发生的概率 注意我们是说先发生这个事件 再发生那个事件 以后我们会再提到这一点　现在我们先假设是这个样子 

它们都会发生的概率是 第一个事件发生的概率和 第二个事件发生的概率的乘积 注意到 两个事件都发生是跟乘积相关的 也就是两个概率相乘 原因是 很少情况下 两个事件都发生然后其中一个事件单独发生 

将两个处于0到1的 概率相乘时 你求得的 它们都会发生的概率就更低了 它们中的任一个事件是否会发生 完全取决于它们自己 

我们可以用符号重新阐述这条规则 这些符号在我们求取否的概率的时候用到过 也就是说 假设一和假设二都 为真的概率 是假设一为真的概率乘以 假设二为真的概率 我们将在一些例子中运用这个规则 假设弹一枚硬币 得到正面朝上 

再弹一枚硬币 得到的仍是正面朝上 那么连续抛两枚硬币 得到两次正面朝上的概率是多少呢？ 第一次抛硬币得到正面朝上的概率是0.5 同样第二次得到正面朝上的概率也是0.5 所以两次得到正面朝上的概率是 0.5 * 0.5 = 0.25 所以在两次抛硬币中 得到两个正面朝上 的硬币的概率是0.25  举一个关于纸牌的更加复杂的例子 

这里我们有一付标准的纸牌 A, 2, 3, 4, 5, 6, 7, 8, 9, 

10, J, Q, K 所以共有 13种不同类型的纸牌 有四套不同花色的牌 黑桃，红心，方片，梅花 所以我们可以记住 抽中一张某种类型的卡片的概率是 1/13 这是在假设它们被充分洗好的前提下 抽中某个特定花色的牌 比如说方片 是 1/4 因为52张纸牌中有13张是方片 方片是四套花色中的一种所以抽中一张方片的 概率是1/4 选中某特定的牌　 比如说3的概率是1/13继续说这一付牌 假设我抽出一张4 然后再抽出 一个方片那么在一付标准的纸牌中 假设没有小丑牌 共有13张牌 

所以得到一张4的概率是1/13 共有四种花色的牌黑桃，红心，方片，梅花 所以抽到一张方片牌的概率是1/4 那么先抽到一张4再抽到一张方片的概率是多少呢？ 它将会是1/13 1/4 也就是说它 

将会是1/52 所以这两个事件以这种顺序发生的概率是 1/13 * 1/4 = 1/52 那个例子展示了如何计算 那个例子展示了如何计算 两个独立事件相与的概率 但是如果两个事件并不独立会怎么样呢？ 也就是说 如果一个事件的概率会影响到另一个事件的概率会怎么样？ 这里有个问题 这里有个问题 

当他跑步的时候 他进行计时　一半的情况 

他是少于五分钟 另一半情况 他超过五分钟 所以在一给定场景中 他可以在五分钟内跑一英里的概率是 

0.5 但是他 在五分钟内跑了一英里 然后又 在五分钟内跑了另一个一英里的概率是多少？ 

好吧 如果进行计算 得到的是 0.5 * 0.5 = 0.25 但是其实并不对 因为他 跑完第一个一英里后会非常累 他无法在五分钟内完成 第二个一英里的概率非常高 不管怎样 他刚跑完一英里 

所以这些事件不是独立的 那个例子 表明需要一个新的公式去 计算两个事件相与的概率 当这两个事件 并不独立 相反他们的概率取决于对方时 上述独立性和 依赖性之间的区别同样适用于我们的老朋友：纸牌 所以 为了简化问题 我们先拿一付非常有限的纸牌 它只有四张A  它有黑桃A 红心A  方片A和梅花A 注意到红心A和方片A是红色的 黑桃A和梅花A是黑色的 所以我们知道这一点 洗好牌后　 抽出一张牌 别看 那么这是一张红色的A的概率是多少？ 二分之一 对吗？ 因为四张纸牌中有两张是红色的 现在 对不起 哦 红色的 我抽到一张红色的牌 现在 我们将它放回牌堆中 洗牌 那么现在抽到另一张红色的A的概率是多少？ 

同样 二分之一 所以 如果看一下列出来的所有概率 第一次抽取是用列表示 对吗？ 最左边一列表示第一次抽取到一张黑桃A 第二列是第一次抽取到红心A 第三列是第一次抽取到方片A 第四列是第一次抽取到梅花A 第二次抽取是用行表示 同样　它是黑桃，红心，方片或者梅花 所以总共依次存在16种可能的抽取组合 那么总共有多少种组合使得你抽取到两张红色的纸牌？ 好吧 一个 两个 三个 四个 所以 中间四种可能性是 你抽取到两张红色的A的概率 包括第一次抽取和第二次抽取 所以 这个事件的概率是4/16 或者说1/4 或者0.25 就跟我们用那个公式计算的结果一样 但是 如果不存在独立性呢？ 我们举同样的四个A的例子 好的 抽取到一张红色的A的概率是多少呢？还是二分之一 所以 假设我抽取到一张红心A 将它丢掉 不再放回原来的牌堆中 那么现在只剩下三张A了 不看牌 抽取到第二张红色的A的概率是多少呢？ 好吧 结果是三分之一 因为其中一张 是红色的 剩下两张不是 也就是总共剩下三张牌 有一张是红色的A 所以概率是1/2 * 1/3 = 1/ 6 而不是我们原来算出的1/4 

即在它们是相互独立 将纸牌放回的那种情况下 所以我们需要一种不同的公式去 

一般化这种情况 当事件之间存在依赖关系的情况 好吗？ 这个公式将使用到条件概率 这其实就是我刚跟你们提到的花俏的说法 对吗？ 在第一次抽取到一张红色的A 并将其扔掉的情况下 

第二次抽取到一张红色的A的条件概率是三分之一 即在我第一次抽取到一张红色的A 并将其扔掉的情形下 第二次抽取到一张红色的A 这个事件出现多少次 结果将是三分之一 这就是条件概率 现在这个公式 两个事件都发生的概率 是事件一发生的概率 

和事件二在事件一发生的条件下　 的条件概率的乘积 这就是需要用到条件概率的地方 注意到当两个事件是相互独立的 就像事件一已经发生的条件下 

事件二的条件概率 跟事件二发生的概率相同 因为事件一不会影响到事件二 所以独立事件的公式是 这个公式的一个例子 是事件二在事件一发生的条件下的条件概率跟 事件二单独发生的概率相同的特殊情况 所以说它是一个一般化的公式 

它实际上包括第一个公式　但是当事件相互独立的时候 单独用第一个公式更加简单 我们也能将这个公式符号化 假设一和假设二都成立的概率 等于假设一成立的概率 乘以假设二在假设一成立的前提下成立的概率 将其写成一条直线　[不会] 

在这个公式中表明条件概率 这里的这个公式 表示 

在假设一成立的前提下的假设二成立的概率 所以可以用这个 

### Disjunction

Our next rule for probability concerns the probabilities of disjunctions. That is, the probability that either one thing or another will happen. 

And as with the case of the probability of conjunctions, we have two cases. We need a different rule when these two events are mutually exclusive. Then when they're not mutually exclusive. We're going to look first, at cases that are mutually exclusive, and what that means, is simply, that they cannot occur together. The probability of them both occurring is zero, it can't happen. Now, the formula 

for that simpler case. When you cannot 

pick both an ace of diamonds and an ace of hearts on a single pick. 

Here's another example. It's a special case. 

We've been talking so far about permutations. Which are ordered sets. So the two events in a conjunction would be, flipping heads first, and then tails second. We can also look at combinations where order doesn't matter. Flipping one heads and one tails out of two flips, but it doesn't matter. What the order is. Then we have heads and tails in two flips, which means either a heads and then a tails, or a tails and then a heads. So we've got a disjunction. And we can figure out the probability of this combination, which is unordered, by looking at the Disjunction of those two possibilities. Here's a chart showing the possibilities. If you take heads on flip one, you're in the left-hand column. Tails on flip one, you're in the right-hand column. 

Heads on flip two, you're on the top row. Tails on flip two, you're on the bottom row. Which of these for the two flips includes a heads and a tails where the order doesn't matter? And the answer is the upper right has tails on flip one and tails on flip two, and the lower left Has tails on flip two and heads on flip one. So it's those two possibilites, this one and this one, out of the four, that include the combination. One heads and one tails in any old order. And the disjunction is calculated by saying, what's the probability of this, 0.25, one in four, and the probability of this, 0.25, one in four, and you add them together. Because the probability of doing either one or the other Is going to be the sum, just like the formula says. Next we have to look at the general formula that applies whether or not the two events are mutually exclusive. 

And that's pretty simple. We're going to call it 3G for the generalized version of Rule three. 

What it says is that the probability of either one event occurring or the other event occurring is. The sum of the probability of the first event occurring plus the probability of the second event occurring minus the probability that they both occur. Or in symbols probability of H1 or H2 is equal to the probability of H1 plus the probability of H2 minus. The probability of the conjunction of h1 and h2. So we're going to have to use that previous rule for conjunction to figure out what gets subtracted. But the more basic question is why are we subtracting in the first place? 

And you can think about that in this example. 

What's the probability of getting heads on either the first flip or the second flip, in two flips, of a fair coin? Well, one way to figure this out might be to say, well what's the probability of getting it on the first flip? 

Well, that's 0.5. What's the probability of getting it on the second flip? Well, that's 0.5. So let's add 'em together. And the probability of getting it on either the first flip or the second flip is 0.5 plus 0.4 equals 1. So it's absolutely certain That we're going to get a heads on either the first flip or the second flip of two flips of a fair coin. But you know that's not right. because sometimes you get two tails in a row. 

So that can't be the right way to calculate the probability. That's why you need to subtract the conjunction. because otherwise you're going to get the wrong answer. 

The right way, then, is .5, heads on the first flip, .5, heads on the second flip, minus the probability of both. But the questions is, why do you have to subtract? And this little chart should show you why you have to subtract, because the probability of getting heads, on the first flip, is the left hand column. That's the upper one, you get heads on the first flip, the lower one, you get heads on the first flip. 

The probability of getting heads on the second flip, is given by the top row. 

The first one, you get heads on the second flip. 

The second one, you get heads on the second flip. 

So, if you want to add them together, you're adding together this one, and you're adding it to this one. That gives you 0.5 of getting heads on the first flow, then you add it to the probability of this one plus this one. 

And that gives you .5 of getting heads on the seond flow. But then if you add them together to get the probability of getting heads on either the first slip or the second flip, you've double counted. The one in the upper left in red. You countered it in the probability of the first flip and also in the probability of the second flip. And you don't want to double count it because then you'll get the wrong answer. So I hope this chart illustrates y in order to generalize the formula for disjunction. We need to subtract the probability that both of the events will occur. 

Here's another example. Out of a standard deck of cards, what's the probability of picking either a six or a club? Well, you know that there are four sixes. And thirteen different types of cards so the probability of picking six, is one and thirteen. 

What's the probability of picking a club? Well there are thirteen clubs and four suits. So the probability of picking a club. 

Is one in four. And if we add those probabilities together, we'll get 4 plus 13 makes 17 out of 52 cards. But that's not right because. You just double counted the six of clubs. 

You counted it as a club and you also counted it as a six. 

So in order to get the probability of picking either a six or a club, you need to add the probability of getting a six One in 13 to the probability of getting a club. One in four and subtract the probability of them both happening. Namely, getting the six of clubs. One in fifty two, because otherwise, you'll be counting that six of clubs. 

So now I hope you understand the rationale behind this generalized version of the rule for probabilities of disjunctions and I hope you'll be able to do a few exercises using that rule. 

我们下一条规则讨论的是相或的概率 也就是说 一种情况发生或者另一种情况发生 

与相与的概率情况相同 我们有两种情况 当两个事件互斥时我们需要其他的规则 而当各事件不互斥时则不需要 首先我们来看 事件相互斥的情况 这就是说 很简单 这些事件不能同时发生 它们同时发生的概率 是零 即这种情况不可能发生 现在 对于 这种简单情况 

下的 （音乐） 当只抽取一张牌时 

你不可能同时抽到方片A和红桃A 此时适用 

这里还有另一个例子 这是个特殊情况 

我们一直在讨论排列 它是有序集 所以两个相与的事件是先抛出正面 然后 第二次抛出反面 我们同时也来看一下组合 组合 事件发生的顺序无所谓 扔两次硬币 一正一反 正面反面出现的顺序无所谓 扔两次硬币 我们得到一正一反 即 要么先正后反 或先反后正 所以我们得到了一个并集 我们可以通过两个事件的概率相或 来算出这个组合的概率 这是无序的 这里有个图表显示 事件的概率 如果你扔硬币第一次结果是正面 那么就看左边一列 第一次是反面 就看右边一列 

第二次是正面 看上面一行 第二次是反面看 下面一行 这里面 哪些包含了一正一反的情况 顺序无所谓 答案是右上角第一次反面第二次正面 和左下角 第二次反面第一次正面 所以有两个概率 是四个里面的这一个和这一个  包含了那种组合 任何顺序的一正一反 相或的概率是这样计算的 这个的概率是0.25 四分之一  这个的概率是0.25 四分之一 把二者加起来  因为二者之一发生的概率 是它们的和 正如公式所说 下面我们要讲普遍适用的 公式 无论两事件是否互斥 

非常简单 我们把规则三的概括命名为3G 

它的内容是 一个事件或者另一个事件发生的概率 是第一个事件发生的概率 加上第二个 事件发生的概率 减去 两事件同时发生的概率 用符号表示即 H1或H2的概率 等于 H1的概率加H2的概率减去 H1和H2相与的概率 我们将使用前面 相与的法则来计算最后一项减去的值 但更重要的问题是我们为什么要做这个减法 

你可以通过这个例子来理解 

（扔两次硬币）第一次是正面或第二次是正面的概率是多少 第一次是正面或第二次是正面的概率是多少 一种方法是 首先找出第一次是正面的概率是都少 

是0.5 第二次是正面的概率呢 是0.5 我们来把它们相加 第一次或 第二次是正面的概率是0.5加0.5等于1 所以我们肯定会在两次中有一次是正面 要么第一次要么第二次 硬币质量均匀 但是你知道这是不对的 因为有的时候 你会连续扔两次反面 

所以这个方法来算这种情况的概率是不对的 这就是你为什么要减去两事件相与概率的原因 因为否则的话你得到的结果是错误的 

正确的方法 是 0.5 第一次正面 0.5 第二次正面 减去两者同时发生的概率 但是问题是为什么 你必须减去最后那一项 这张小表个会告诉你为什么你必须要减项 因为 第一次是正面的概率 在左边一列 上面这一个 你第一次是正面 下面这个你第一次是正面 

第二次是正面的概率是表里的第一行 

第一个 第二次是正面 

第二个 第二次是正面 

所以如果你试图把它们加起来 你事实上加了这一项 和这一项 得到 0.5 这是第一次是正面的概率 然后你 在这个概率的基础上加了这一项和这一项 

你又得到一个0.5 这是第二次是正面的概率 但如果你企图把它们加起来 来计算 第一次或者第二次出现正面的概率 你就重复计算了 左上角的这一项 你把它算在第一次是正面的概率里的同时 也把它算在第二次是正面的概率里了 你不会想重复计算的 因为你会得到错误的结果 我希望这个表说明了为什么 在归纳相或的公式时 我们需要减去两事件同时发生的概率 

来看另一个例子下面再举另一个例子 在标准的一副牌里抽到 6或者是梅花的概率是多少 已知一副牌里有四个6 有13种不同的牌 所以 抽到6的概率 是1/13 

抽到梅花的概率是多少呢 一共有13张梅花牌 有四种花色 所以抽到梅花的概率 

是1/4 如果我们把两个概率加起来 我们得到4 加13 得到17/52 但这是不正确的 因为你重复计算了6和草花同时出现的概率 

你在算梅花出现概率的时候和算6出现的概率的时候都把它计算在内 

所以为了求得抽到6或者草花的概率 你需要 把抽到6的概率 1/13 和抽到草花的概率 1/4 加起来 然后减去 它们同时发生的概率 即 抽到梅花6的概率 1/52 因为不然的话你就重复计算了那个草花6 

我希望你们理解了这个相与概率法则的纳版本 背后的原理 同时我也希望 你们能够使用这个法则做一些练习 

### Series

The three rules that we've studied, are going to be enough to calculate the probabilities for any combination of propositions in propositional logic. Because we've covered negation, and then conjunction, and then disjunction. And if you use them in various combinations, you can cover all of propositional logic. But it's still useful to look at one particular case. Namely, the probability of something happening in a series. 

Let's look at a simple example, involving a very short series, only two events, and contraception. Assume that you want to prevent contraception, and that you use two different methods. What's the probability of conception being prevented by using two methods at once? And let's assume that the probability is 0.9 of the first method working alone and the probability is 0.9 of the second method working alone. How do you calculate the probability of preventing conception when you use both methods? One move might be to say, let's add them together. 0.9 plus 0.9 is 1.8. So maybe the probability of preventing conception using them both is 1.8. No way! Of course not. The maximum probability is one. Probabilities vary between 0 and 1. So 1.8 probability just doesn't make any sense. That can't be right. 

Another possibility is to say we're going to multiply' em. The probability of preventing conception by using both methods is 0.9 times 0.9, which is 0.81. 

That can't be right either. Why not? Because that would mean that there's less chance of preventing conception by using both methods, namely. 81, than there was using one of the methods alone. 9. If you use both methods the probability of preventing conception oughtta to go up. 

So how do we calculate the probability of one of these contraceptive methods working, and preventing conception when we use them both? 

The right way to do this is to first of all, look at the probability of one of these methods failing. 

So instead of looking at the probability of it working being 0.9, we say the probability of it not working is 1 minus 0.9 or 0.1. Now, what's the probability that they both fail? Well, the probability that they both fail is then going to be. 1 times. 1, which is. 01. And now, we can say, what's the probability of them not both failing? 

That's going to be 1 minus. 01. Or 0.99. So that's how we calculate the probability of preventing conception, when you use both methods. 

Let's state this method in a formal rule. The probability that an event will occur, at least once, in a series of independent trials, is 1 minus the probability that it will not occur in that series. Notice that we're assuming that the trials are independent. This rule is only going to work when the trials are independent. And what you do is you take the probability that it will not occur, and subtract it from 1. And that gives you the probability that the event will occur at least once in the series. Which symbolically, it's 1 minus the probability of not H raised to the N, the number of trials. Because to get the probability that it will not occur in any of those trials, you have to raise it to the power of the number of trials. So in our case it was. 1 times. 1 equals. 01. But if you use three methods, it would be. 1 times. 1 times. 1. That means. 1 raised to the third power Or if you use four methods, it'll be 0.1 times 0.1 times 0.1 times 0.1, 0.1 raised to the 4th power. So you can see how you can generalize from our simple case of two contraceptive methods to use this formula to determine the probability of an event occurring in a series of independent trials. So one more quick example. What's the probability of getting heads on a coin at least once if you flip it five times? There's one. Two. That didn't flip, I'm going to do that again. There we go. Three. 

Four. 

Five. Now, I didn't show you whether it got heads or tails. What's the probability that one of those was a heads? Well, what's the probability for each flip that it was not a heads? 0.5. There're five flips. Raise it to the fifth power, 0.5 times 0.5 times 0.5 times 0.5 times 0.5. You can figure that out on a calculator, I'm not even going to try to do it in my head right now. 

And then you subtract that from one, and it gives you the probability that you get at least one heads in five independent flips. 

And notice what it does is if it's six flips, it's going to be even more likely, and seven is going to be even more likely because you're going to be raising 0.5 to the sixth power or the seventh power in order to apply the rule. 

So, that's just another example of how you take this rule regarding series, and calculate the probability of the event occurring at least once in the series of independent trials. 

我们学过的三条规则就足够 计算逻辑命题中 任何一种组合的命题的概率 因为我们已经学过否定、合取和析取 如果你把它们用在各种组合命题中 就能得到所有的逻辑命题 但是单看其中一例也是有用处的 也就是，一个事件在一系列事件中发生的概率 

让我们来看看一个很简单的例子 这个例子中只有两个事件和避孕 

假设你想避孕 现在你有 两种不同的 避孕措施 那么使用两种措施和只使用第二种措施 成功避孕的概率分别是多少呢？ 你怎么计算使用两种避孕措施时的避孕率？ 一种算法是 把两种措施的概率相加 0.9加0.9 等于1.8 所以运用两种避孕措施的避孕率是1.8 不可能！ 当然不可能 因为概率的最大值才1 概率只能处于0到1之间 所以1.8的概率简直是无稽之谈 这不可能正确 

另一种可能的算法是 把两种概率相乘 那么使用两种避孕措施成功避孕的概率就是 0.9乘以0.9 得到0.81 

这也不对 为什么？因为这代表 使用两种避孕措施的避孕率是0.81  比使用一种措施的避孕率0.9低 如果你使用两种措施 那避孕率应该是更高才对 

那么我们在使用两种避孕措施时 怎么计算 避孕率呢？ 

正确的计算方式是 首先 看其中一种避孕措施的失败率 

而不是看成功率0.9 那么失败率就是1减成功率0.9 也就是0.1 那么两种措施都失败的概率是多少？ 那就是 两种失败率相乘 0.1乘以0.1 得到0.01 那么现在 两种措施都没有失败的概率是多少呢？ 那就是1减去0.01 得到0.99 所以这才是我们计算使用两种避孕措施时 的成功率 现在让我们用正式的规则来描述 

这种计算方法 一个事件在一系列独立事件中至少发生一次的概率 是1减去 该事件在该系列事件中不会发生的概率 但是注意 我们假设事件都是独立的 这一规则只有在各个事件都是独立的情况下才奏效 

你需要做的就是计算出事件不会发生的概率 然后用1减去它 然后你就得到了该事件在系列事件中 至少发生一次的概率 也就是说 1减去 没有发生的概率H的N次方 N是系列事件的数量 因为要得到事件在系列事件中不发生的概率 就必须把事件概率用事件数量的次方进行计算 所以在我们这次计算中 是0.1乘以0.1 等于0.01 但是如果你使用三种避孕措施 就是0.1乘以0.1乘以0.1 也就是0.1的三次方 如果你使用四种措施 那就是0.1乘以0.1乘以0.1乘以0.1 也就是0.1的4次方 那么现在你可以思考一下 怎么从这个两种避孕措施的简单例子中总结出 如何使用公式来计算出一个事件在一系列独立事件中发生的概率 现在我们再举一个小例子 如果抛五次硬币  至少得到一次正面朝上的概率是多少？ 1次 2次 这次不算 重新来 3次 

4次 

5次 好了 刚才我没有给你们看是哪一面朝上 那么其中一次正面朝上的概率是多少？ 先看看 单次不是正面朝上的概率是多少？ 是0.5 现在有5次 计算0.5的5次方 也就是0.5乘以0.5乘以0.5乘以0.5乘以0.5 你可以用计算器计算  我现在不打算进行心算 

然后用1减去这个结果 你就得到了 5次中至少有1次正面朝上的概率了 

注意 如果是6次 那至少一次正面朝上的概率就更大 如果是7次 概率就更大一些 你须按照规则 计算出0.5的6次方 或者0.5的7次方 

这个例子说明了  如何在系列事件中运用这条规则 计算出 一个事件在一系列独立事件中至少发生一次的概率 

### Bayes Theorem (Optional)

Coins and dice provide a nice simple model of how to calculate probabilities, but everyday life is a lot more complicated and it's not taken up with gambling. At least, I hope your life is not taken up with gambling. So in order to make probabilities more applicable to everyday life, we need to look at, slightly more complicated methods. Now, because these methods are more complicated, this lecture is going to be an honors lecture, it's optional. It will not be on the quiz, so don't get worried about that. 

But it is still useful, and it's fascinating, and it'll help you avoid some mistakes that a lot of people make and that Either commit a crime, or not commit a crime, but also whether they're going to pass, do well in school, or fail. We always use these tests when we don't know for certain, but we want some kind of evidence, or some kind of indicator. The problem is none of these tests are perfect. They always contain errors of various sorts. And what we're going to have to do is to see how to take those errors of different sorts and build them together into a method and then a formula for. Calculating how reliable the method is for detecting the thing that we want to detect. 

This problem is a lot like the problem we faced earlier when we were talking about applying generalizations to particular cases because here we're going to be applying probabilities to particular cases. 

So it'll seem familiar to you in certain parts, but you'll see that this case is a little tricky. 

The best examples occur in medicine. So just imagine that you go to your doctor for a regular checkup. You don't have any special symptoms, but he decides to do a few screening tests. 

And unfortunately, and very worryingly, it turns out that you test positive on one test for a particular form of cancer, a certain kind of medical condition. 

Well, what that means is that you might have cancer. Might, great. You want to know whether you do have cancer. But of course, finding out for sure whether or not you have cancer is going to take further tests. And those tests might be expensive, they might be dangerous, they're going to be invasive in various ways. So you really want to know what's the probability, given that you've tested positive on this one test, That you really have cancer. 

Now clearly that probability is going to depend on a number of facts about this type of cancer, about the type of test and so on. And I am not a doctor. I am not giving you medical advice. If you test positive on a test go talk to your doctor, don't trust me because I'm just making up numbers here. But let's do make up a few numbers and figure out what the likelihood is of having cancer given that you tested positive. So let's imagine that the base rate Of this particular type of cancer in the population is 0.3%, that is, three out of 1,000, or 0.003, and they say that's the base rate. Well it's sometimes called the prevalence of the condition in the population. That's simply to say that out of 1,000 people chosen randomly in the population, you'd get about three that had this condition. 

It's just a percentage of the general population. 

So that's the condition, what about the test? Well the first thing we want to know is the sensitivity of the test. The sensitivity of the test we're going to assume is 0.99. And what that means is that Out of 100 people who have this condition, 99 of them will test positive. So this test is pretty good at figuring out, from among the people who have the condition, which ones do. 99 of those 100 people who have the condition. Will test positive. The other feature is specificity, and what that means is the percentage of the people who don't have the condition who will test negative. 

The point here is you're not going to get a positive result for people who don't have the condition. Right? Because you want it to be specific to this particular condition and not get a bunch of positives for people who have other types of conditions or no medical condition at all. So the specificity we're going to assume, in this particular case we're talking about, is also 99%. Now. 

What we want to know is the probability that you have a cancer a condition given that you tested positive on the test but notice that the sensitivity tells you the probability that you will test positive given that you have the condition we want to know. The opposite of that, the probability that you have the condition given that you tested positive, and that's what we have to do a little calculation to figure out. But, before we do that calculation, I want you to think about these figures that I've given you: the prevalence in the population. The sensitivity of the test. The specificity of the test. And just make a guess. Just start out by writing down on a piece of paper what you think the probability is that you would have the cancer given that you tested positive on the test. 

Take a minute and think about it and write it down. 

But we don't want to just guess. About medical conditions, about probabilities that really matter as much as this one did. Instead we want to calculate what the probability really is. So let's go through it carefully and show you how to use what I'll call the box method. In order to calculate the real likelihood that you have. The condition given that you got a positive test result. 

What we need to do is to divide the population into four different groups. 

The group that has the condition and tested positive. The group that has the condition and tested negative. The group that doesn't have the condition and tested positive, and the group that doesn't have the condition and tested negative. 

And this chart, will show you, a nice simple way of organizaing all of that information. Because, this row, the top row, 

tells you all the people who tested positive The bottom row, tells you the people who tested negative. Then, the left column, gives you the people who do have the medical condition, in this case some kind of cancer. And the right column, tells you the people who do not have that condition. 

Now what we need to do is to start filling it out with numbers. 

Now the first thing we need to specify is the population. In this case we want to start with a big enough population that we're not going to have a lot of fractions in the other boxes. So let's just imagine that the population is 100,000. Make it a million or 10 million. It doesn't matter. Cause, we're going to be interested in the ratios with the different groups. 

We can use that 100,000 to fill out the other boxes, if we know the prevalance, or the base rate. 

Because, the base rate tells you what percentage of that 100,000 actually do have the condition and don't have the condition. 

We imagined, remember we're just making up numbers here, but we imagined that the prevalence of this condition is 0.3%. And that means out of 100,000 people, there will be 300 who do have the medical condition. 

Well, if there are 300 who have it and there are 100,000 total, we can figure out how many don't have the medical condition by just subtracting. Between 99,700 do not have the medical condition. Okay? Now, we've divided the population into our two columns. The ones that do and the ones that don't have the medical condition. 

The next step is to figure out how many are going to test positive and how many are going to test negative. Out of each of these groups. For that, we first need the sensitivity. The sensitivity tells us the percentage of the cases that have the condition who will test positive. 

So the people who have the condition are the 300. The ones who test positive are going to go up in this area. and we know from the sensitivity bin 0.99 or 99% that the number in that area should be 99% of 300 or 297. And of course if that's the number that test positive then the remainder are going to test negative and that means that we'll have three. Which shouldn't surprise you because of 99% of the cases that have it test positive, then 1% will test negative, and 1% of 300 is 3. 

Good. So we got the column done. Now, the next question is going to be the specificity. We can use the specificity to figure out what goes in that next column. If the specificity is 99 And we know that 99,700 people do not have the condition out of our sample of 100,000. Well that means that 99% of 99,700 are going to. Test negative because the specificity is the percentage of cases without the condition that test negative. And that means that we'll have 98,703 among the people who do not have the condition who test negative. How many are going to test positive? The rest of them. So 99,700 minus 98,703 is going to be 997. And of course that shouldn't be surprising again because 1% of 99,700 is 997. Well we got two boxes left to fill out. How do you fill out those? Well this box in the upper right is the total number of people in this population of 100,000 who test positive. And so we can get that by adding the ones that do have the condition and test positive And the ones that don't have the condition in test positive, just add them together, and you get 1,294. And you do the same on the next row, because that blank is the area that has all the people who test negative. And three people who have the condition test negative. 98,703 people who do not have the condition test negative. So the total is going to be 98,706. And we can check to make sure that. We got it right, by just adding them together. 1,294 plus 98,706 is equal to 100,000. Phew, we got it right. Okay, so now we've divided the population, into, those people who have the condition, those people who don't have the condition And we know how many of each of those groups test positive and how many of each of those groups test negative. 

The real question is what's the probability that I have cancer or the medical condition given that I tested positive. How do we figure that out? Well The total number of positive tests was 1,294 and the people who tested positive who really had the condition was 297. So it looks like the probability of actually having the condition Given that you tested positive is 297 out of 1294 or 0.23. That's 23%, less than one in four. Is that what you guessed? Most people, including most doctors When they hear that the test is 99% sensitive and 99% specific, we'll guess a lot higher than one in four. >> Oh my gosh! I'm a doctor, and I never would have thought that! >> Now, don't worry. She's not a physician. She's a metaphysician. 

>> But in this case. The probability really is just one in four that you had that medical condition. Now how did that happen? The reason was that the prevalence or the base rate was so low that even a small rate of false positives, given the massive numbers of people who don't have the condition Will mean that there are more false positives, three times as many as there are two positives. And that's why the probability is just one in four, actually, a little less than one in four. But you have the medical condition even when you tested positive. I want to add a quick caviar here, in order to avoid misinterpretation. because the point here is that, if you have a screening test, for a condition with a very low base rate or prevalence, and you don't have any symptoms that put you in a special category, then, you need to get another test before you jump to any conclusions about having the medical condition. 

Because, if you have that other test, then the fact that you tested positive on the first test puts you in a smaller class, with a much higher base rate, or prevalence. And now, the probability's going to go up. 

Most doctors know that, and that's why, after the first test, they don't jump to conclusions, and they order another test Test but many patients don't realize that and they get extremely worried after a single test even when they don't have any symptoms. 

So that's the mistake that we're trying to avoid here and that's surprising but 

it actually applies to many different areas of life. 

It applies, for example, to medical tests with all kinds of other diseases. Not just cancer or colon cancer, but pretty much every disease where the prevalence is extremely low. It applies also to drug tests. If somebody gets a positive drug test, does that mean they really were using drugs? Well, if it's a population where the base rate or prevelance of drug use is quite low, then, it might not. 

Course, if you assume that the previlance or base rate is quite high, then you're going to believe that drug test. But you need to know the facts about what the previlence Where base rate really is in order to calculate accurately the probability that this person really was using drugs. 

Same applies to evidence in legal trials, take eyewitnesses for example, it's very tricky, someone's trying to use their eyes as a test for what they see. They might identify a friend, or they might just say that car that did the hit-and-run accident was a Porsche. 

Well, how good are they at identifying Porsches? 

If they get it right most of the time, but not always, and sometimes they Don't get it right when it is a Porsche, then we've got the sensitivity and specificity of what they identify. And we can use that to calculate how likely it is that their evidence in the trial really is reliable or not. 

Another example is the prediction of future behavior. 

We might have some kind of marker. That a certain group of people with that marker, have a certain likelihood of committing crimes. But, if crimes, are very rare in that community, and every other, then a test which has A pretty good sensitivity and specificity still might not be good enough when we're talking about something like crime that's actually very rare and is a very low prevelence or base rate in most communities. And the same applies to failing out of school. 

Our SAT scores or GRE scores are going to be good predictors Of who's going to fail out of school. 

Well, if very few people fail out of school. So that the prevalence and base rate is very low. Then even if they're pretty sensitive and specific, they might not be good predictors. So this same type of problem arises in a lot of different areas. And I'm not going to go through more examples right now but we'll have plenty of examples in the exercises at the end of this chapter. 

I want to end though by saying a few things that are a bit more technical about this method. First, there's a lot of terminology to learn, because when you read about using this method In other areas for other types of topics, then you'll run into these terms, and it's a good idea to know them. 

So first, 

the cases where the person does have the condition and also tests positive are calls hits, or true positives. Different people use different terms. The cases where, the person tests positive, but they don't have the condition are called, false positives or false alarms. 

The cases where a person Really does have the condition, but test negative are called misses or false negatives. And 

the cases where the person does not have the condition and the test comes out negatives are called true negatives. because they're negative and it's true that they don't have the condition. 

If we put together the false negatives, and the true negatives, we get the total set of negatives. And, if we put together the true positives, and the false positives we get, the total set of positives. 

And of course, we have the general population Within that population a percentage that have the condition and a percentage that don't have the condition. Now, what's the base rate? The base rate in this population is simply the set that have the condition divided by the total population Which is Box 7 divided by Box 9. If we use e for the evidence and h for the hypothesis being true that the condition really does exist, then that's the probability of h, and the sensitivity is going to be the total number of true positives divided by the total number of people with the condition. Because it's the percentage of people who have the condition and test positive. 

OK? So that's the probability of e given h, and it's box one. Divided by box 7. The specificity in contrast is the ratio of it being a true negative to the total number of people who do not have the condition. That is, the probability of not e, that is not having the evidence of a positive test result. Given not h, given that you're in the second column, where the hypothesis is false, because you don't have the condition, so that's Box 5 divided by Box 8. That's the specificity. So we can define all of these in terms of each other. The hits divided by the total with that condition is going to be the sensitivity. And you can use this terminology to guide your way through this box. And the big question is again going to be what's the solution? What's the probability of the hypothesis having the condition, given the evidence, that is a positive test result, that's going to be Box 1 divided by Box 3. And as we saw in the case that we just went through, that gives you the probability of having the medical condition, or colon cancer, given a positive test result. That's called the posterior probability, or in symbols, the probability of the hypothesis given the evidence. So I hope this terminology helps you understand some of the discussions of this, if you go on and read about it in the literature. This procedure that we've been discussing Is actually just an application of a famous theorem called Bayes Theorem after Thomas Bayes, a 18th century English clergyman, who was also a mathematician who proved this extremely important theorem in probability theory. 

Now some of you out there We'll use the boxes, and it'll make sense to you. But some Corsairians, I assume, are mathematicians, and they want to see the mathematics behind it. So now, I want to show you how to derive base theorem from the rules of probability that we learned in earlier lectures. So for all you math nerds out there, Here goes. You start with rule 2G. 

Apply it to the probability that the evidence and the hypothesis are both true. And by the rule, that probability is equal to, the probability of the evidence, times the probability of the hypothesis given the evidence. 

You have to have that conditional probability because they're not independent. 

Then you simply divide both sides of that by the probability of the evidence. A little simple algebra. And you end up with the probability of the hypothesis, given the evidence, is equal to the probability of the evidence and the hypothesis, divided by the probability of the evidence. 

Now we can do a little trick. This was ingenious. Substitute for e, something that's logically equivalent to e. Namely one or the other has to be true. 

And that means that the evidence and the hypothesis or the evidence and not the hypothesis is going to be equivalent to e. So this is equivalent to this. And because they're equivalent we can substitute them within the formula for probability without affecting the truth values. So we just substitute. This formula in here for the e up there. And we end up with the probability of the hypothesis given the evidence is equal to the probability of the evidence and the hypothesis divided by the probability of the evidence and the hypothesis or the evidence and not the hypothesis. And that's not supposed to make much sense, but it helps with the derivation. The next step is to apply rule 3, because we have a disjunction. And notice the disjuncts are mutually exclusive. It cannot be true, both, that the evidence in the hypothesis is true, and also the evidence and not the hypothesis is true, because it can't be. Both h and not h. So we can apply the simple version of rule three. 

And that means that the probability of (e&h) or (e&~h) is equal to the probability of (e&h + the probability of (e&~h). We're just applying that rule three for disjunction that we learned a few lectures ago. 

Now we apply rule 2G again, because we have the probability of a conjunction up in the top. 

And, since these are not independent Of each other. We hope not. If it's a hypothesis of the evidence for it, then we have to use the conditional probability. And using rule 2G we find that the probability of the hypothesis given the evidence is equal to the probability of the hypothesis times the probability of the evidence given the hypothesis. Divided by, the probability of the hypothesis, times the probability of the evidence given the hypothesis, plus, 

the probability of the hypothesis being false, that is the probability of not H, times the probability of the evidence given not H, or the hypothesis being false. And that's a mouthful. And it's a long formula, but that's the mathematical formula that Bayes proved in the 18th century and it provides the mathematical basis for that whole system of boxes that we talked about before. 

But if you don't like the mathematical proof and that's too confusing for you, then use the box. And if you don't like the boxes, use the mathematical proof. They're both going to work. Just pick the one that works for you. In fact, you don't have to pick either of them. because remember, this is an honor's lecture, it's optional, and it won't be on the quiz. But if you do want to try this method, and make sure that you understand it. Then we'll have a bunch of exercises for you, where you can test your skills. 

## Chancy Choices

### Expected Financial Value

We've talked about using probability to determine what to believe. Such as, whether to believe that a certain form of contraception will work, or will probably work. Or, whether to believe that you have cancer when a doctor has done a test and you got a positive result, which can be pretty scary. But you still have to figure out whether to believe that you really do have cancer. 

Now, probability can be very useful in the formation of beliefs, but it's also extremely useful in making decisions. So in this lecture, we want to talk about the use of probability to make decisions or choices. There are three kinds of decisions or choices that we need to discuss. First of all, decisions with certainty. Second, decisions with risk. And third, decisions with ignorance, or, as those are sometimes called, decisions with uncertainty. 

And we'll talk about the first two and then I will just say a few words about the third. First, lets look at decisions with certainty. 

A decision with certainty is one where you know exactly what is going to happen. You know what the effects are going to be and you know it definitely. It's not that its probably going to happen, you know its going to happen. You know the good effects and the bad effects, so there's no uncertainty, everything's certain. For example, suppose you go to a restaurant, an Italian restaurant, with a friend of yours, and you have to decide whether to order pasta or pizza. 

Some really nice eggplant parmesan on top of pasta that you like at this restaurant. They also have really good mushroom pizza. So you have to think about that. But you know that if you order the eggplant parmesan pasta, then they're going to bring it to you. And you know that if you order the mushroom pizza, they'll make one for you. And you've got enough money for both of them, so there's no uncertainty. You know what you're going to get. Still might be a difficult choice, because, well, you might not be sure whether you feel more like the eggplant parmesan pasta tonight or the mushroom pizza. And you're going to be also potentially a conflict of values. Maybe the eggplant parmesan pasta costs more than the pizza, in which case you have to decide, well, even though I like it more, do I want to spend that money right now? 

You got a conflict between what you feel like and how much it's going to cost. Or, there might be a conflict with your friend. Your friend wants to buy the mushroom pizza and split it with you, because he doesn't want an entire pizza himself. 

But you really feel like the eggplant parmesan, and so now you've got a conflict between your loyalty to your friend. You want to support your friend, and help your friend get what he wants. 

And yet, you feel like the eggplant parmesan yourself. So, these decisions can be very difficult in some cases, but there's no uncertainty. You still know that if you order the eggplant parmesan, you're going to get eggplant parmesan, or if you order the pizza, you're going to get pizza. 

Right? There's no uncertainty at all. No, of course there's uncertainty. 

You might order the pizza and it comes burnt. Yuck! I hate burnt pizza. And you might order the eggplant parmesan and it turns out that they really messed up the sauce and it's got way too much salt in it tonight. Maybe they have a new chef back in the kitchen who's going to mess up one but not the other. 

It's not really certain that when you order it, you're going to get what you wanted, or that you're going to like it. 

Now, this is just a fact about life. There's nothing really certain in this life. You might think that you know exactly what's going to happen, but there's always at least some chance that it's not going to turn out the way you thought. 

And so what do you do about that? Well, some people just stipulate. If I order the pizza, I'll get the pizza, and it'll be good pizza. Well, you can of course stipulate that, but then it just makes the whole situation unrealistic, cause in real life, you're never going to know for certain. 

So another possibility is to say we're just going to ignore these slight chances that the pizza's going to come back burned. I've been at this restaurant a hundred times before. They've always done it just right. And so what are the odds they're going to burn it this time? Pretty slim. 99 percent chance they're going to do it the right way. Well, you might want to say, I'm just going to ignore the 1% chance of getting burned, because it's not going to make any difference. I still want the pizza. Or I still want the eggplant, whichever. 

The other thing you might do is say, look, nothing is certain, but the probabilities are balanced. They go on both sides. After all, there's a chance of burning the pizza. There's also a chance of burning the eggplant. So in some cases it might make perfectly good sense to ignore these uncertainties because they're not going to affect your decision making process. Still, it's important to realize that in life, throughout life, in all areas of life, there's always going to be some uncertainty, and that means there's going to be a probability that if you look at it seriously is going to play into the decision-making process. The kinds of cases that we want to focus on are the cases of risk, where there is a probability of failure and a probability of success for the different plans that you have to choose among. 

All realistic examples now, are actually decisions under risk, especially the most important ones. 

So what is a decision under risk? It's simply a case where, you're not absolutely certain what's going to happen. 

It's not definitely this effect will occur, that effect will occur. You'll get your pizza, it'll taste good. You'll get your pasta, it'll taste good. Instead, there's a probability of each outcome. There's a probability that the pizza will get to the table. There's a probability that the pizza will taste good. There's a probability that the pizza will never make it to the table, but get dropped by the waiter. Or that the pizza will taste horrible because it was burned, then you have a decision under risk. 

And how do we make these decisions under risk? Well, there are a lot of different theories, but one pretty common one is to apply expected value theory. Now we're going to see that there are lots of different values, and it's hard to see how to handle them all. But let's start with a really simple case. Let's assume for now that all that matters is money. One common way, perhaps the most common way, of figuring this out is to calculate the expected monetary value or the expected financial value. And that calculation's pretty simple. It's the probability of winning times the net gain, if you do win, 

minus the probability of losing times the net loss if you do lose. And here we're talking about gains and losses in terms of money. But why do we say net loss and net gain? 

Well, imagine you buy a lottery ticket and you win $20 million and they send you a check for $20 million. Well, how much did you win? It sounds like you won $20 million, but not really. You never got that dollar back that you paid for the ticket. So really, you only won $19,999,999. Now that's, pretty trivial if you just won the lottery. No big deal. But now, imagine a different circumstance where you're playing poker. You bet $10, and the opponent raises it to 20, and you're bluffing, so you want to bet big, so you bet $200, put that all in the pot too, and 

your opponent backs down, and you pull in the entire pot. How much does it got in it? $230. Well did you win $230? No, cause you put $210. You only won $20. The net winnings are how much you pull in minus how much you put in before you pulled in your winnings. So, it's 230 minus the 210 you put in. You only gained 20. A lot of people forget that in poker and they end of thinking that they win a lot by bluffing when actually they didn't win as much as they thought they did. 

In any case we have to look at the net gain and the net loss when applying this formula for expected financial value. Let's do a few examples of calculating expected financial values and let's do them with a deck of cards, because we're familiar with that. There are 13 different cards and four different suits: spades, hearts, diamonds and clubs. 

So you have to remember that to calculate the probabilities. Let's imagine that you can make this bet. 

If you bet $1 you'll win $5 net if you pick a spade. 

And notice that it's net that means either you put $1 in and then you take $6 out and your net gain is five or you say if it's not a spade I'll give you $1 if it is a spade you give me $5. Either way, if you pick a spade you're going to be $5 up. What's the expected financial value of this bet? 

Well, we know that the odds of picking a spade is one in four. 

That's the odds of winning, because if you pick a spade you win. And the net gain is $5. So to calculate the expected financial value we need to multiply this 1/4, the odds of picking a spade, times 5, the number of dollars that you win, net, if you win. And then we have to subtract the odds of losing. 3/4, cause if you pick a heart, a diamond or a club, then you'll lose. And what do you lose? You lose $1. So 1/4 times 5 is 5/4, 3/4 times 1 is 3/4. Subtract 3/4 from 5/4, you get 2/4, and that, of course, is 1/2. So the expected financial value of this bet is 1/2. Now, compare that bet to another bet. In this bet, if you bet $1, you're going to win 10, that sounds pretty good. Instead of winning 5, you're going to win 10. But you only win $10 net if you pick an ace. And there are 13 cards, so we have to redo the calculations. And the probability of picking an ace is 1 in 13. The amount you win is 10. That's your net winnings, remember. 

You have to subtract the probability of losing, 12 in 13 because you're going to lose if it's any card other than an ace. 

And the amount you'll lose is $1 net. 10 times 13 is 13/10. Subtract 12/13 times 1, which is 12/13, and you get -2/13. Notice that's negative 2/13. That means the expected financial value of that bet is negative. You ought to expect to lose money over the long run if you play that kind of bet a lot. Third example. This time, you can bet $1 and win $51 net, if you pick an ace of spades. But you can't pick any old ace or any old spades, it's got to be the ace of spades. So now, what's the financial value of that bet? 

The expected financial value is probability of winning, 1 over 52, times the amount you win net, which is 51, minus the probability of losing, 51 over 52, times the amount lose net, if you lose. 51 times 1/52 is 51/52. 51/52 times 1 is 51/52. Subtract them and you get 0. So in this bet, the expected financial value of the bet is zero. 

Okay? Now we can compare these three bets by asking, which bet should you make? 

Well, the first bet was favorable. A bet's favorable if its expected value is greater than zero. And that means that it's in your interest to bet, at least if your only interest is money. A bet's unfavorable if its expected value is less than zero. 

And a bet is neutral or fair if its expected value is zero. And if you have a bet that's favorable, a bet that's unfavorable, and a bet that's neutral, it shouldn't be surprising that the one you should pick is the one that's favorable, where the expected value is greater than zero, if you're going to bet at all. And that's the next question that we have to turn to. 

我们已经谈过了使用概率来决定该相信什么 比如说 是否该相信某种 特定的避孕方式会有用 或者可能有用 或者 是否该相信你确实患了癌症 当医生给你做测试 结果呈阳性的时候 这可是很可怕的 但你还是得弄明白是否该相信自己真的患了癌症 

那么此时 概率对于观念的建构就变得非常有用了 对于做决策就更是绝佳的参考工具 所以在这一讲里 我们想要谈谈 在决策或者说做选择时对概率的使用 这儿有三种我们将要讨论的决策或者说选择 首先是 确定性决策 第二个 风险性决策 以及第三个 无知型决策 这个有时也被称为 不确定性决策 

我们要具体探讨的是头两个 第三个我会简单提及 首先 我们仔细看下确定性决策 

确定性决策是指你完全知道决策完下一步会发生什么 你完全清楚知道会有怎样的效果 这并不是所谓可能会发生 而是你知道它一定会发生 你知道会有什么好的效果 也知道它不好的效果 所以这样就没有什么不确定的东西了 一切都板上钉钉 举个例子 假设你去到一家餐厅 一家意大利餐厅 和朋友一起 你就必须要决定是点意面还是披萨 

这儿有你爱吃的可口的帕尔马茄子干酪意面 他们也有很棒的蘑菇披萨 所以你不得不考虑 但你知道如果你点了 帕尔马茄子干酪意面 他们就会上这道面 你也知道如果你点了蘑菇披萨 他们也会为你做 对这两道菜你准备了足够的钱 所以没什么不确定的  你知道你会得到什么 但这仍是一个困难的选择 因为 今晚你可能不确定自己到底是更想吃意面多一点儿 还是蘑菇披萨多一点儿 你可能要面对价值冲突 也许茄子干酪意面 会比披萨贵一点儿 这种情况下你不得不决定 好吧 虽然我更爱吃意面 但现在我想多花钱吗？ 

在你喜欢的东西和它消耗的价值之间你面临着冲突 或许 还有和朋友之间的冲突 你的朋友想和你分吃蘑菇披萨  因为他自己吃不了整个披萨 

但你又真的很想吃茄子干酪 那么现在 在对朋友的忠诚上你面临着冲突 你想要支持他 帮助他得到他想要的 

然而 你自己却更想吃茄子干酪 所以 某些情况下做决策可能是十分困难的 但并没有什么不确定的东西 你仍然知道如果你点了茄子干酪 你就会得到茄子干酪 而如果你点了披萨你就会得到披萨 

对吧? 一点儿变数都没有 不 当然是会有不确定存在的 

也许你点了披萨 发现它烤焦了 啐！ 我讨厌烤焦的披萨 或许你点了茄子干酪 结果发现它们一团糟 今晚汁里盐放得太多了 也许厨房里来了个新厨师 把一样弄得很糟糕但另一样还行 

当你点餐时就能得到你想要的 或是你会喜欢你点的 都不真是那么确定的 

好吧 仅是生活中的事实罢了 生活中没有什么事是完全确定的 你也许认为你完全知道接下来会发生什么 但总有那么一些可能 最终的结果和你以为的大相径庭 

所以你该怎么办呢？ 于是一些人明确要求 如果我点的是披萨 我会得到披萨 而且还是个好吃的披萨 你看 你当然可以这样要求 但这只会让 情况变得不那么实际 因为在现实生活中 你永远没办法确定 

所以还有种可能性就是我们直接忽略掉 像是披萨烤焦这样的极小可能事件 我是这家餐厅的常客了 他们总是做得很好吃 所以这次他们烤焦披萨的几率能有多大呢？ 非常小 99%的可能他们能做得很好 好吧 你也许想说 我忽略了1%的烤焦的可能性 因为这样根本不会有什么差别 我还是想吃披萨 或者我还是想吃茄子干酪 随便哪种 

另一件你想做的事 是说 看吧 没什么是确定的 但是概率是均衡的 它们在两边 毕竟 总有烤焦披萨的可能 还有一种做法 茄子烧过火的可能 所以在某些情况下 忽略这些不确定的东西 是相当明智的 因为它们不会影响到你的决策过程 但是 意识到这一点很重要 那就是 在一生中 在生活的各个领域中 总是会有不确定性 这就意味着概率的存在 如果你留心的话 而概率将参与到决策过程中来 我们关注的案例则是风险性案例 也即 在你可选的所有不同计划中 都既有失败的可能也有成功的可能 

所有现实生活中的例子 实际上都是风险性决策 特别是那些十分重要的决定 

那么什么是风险性决策呢？ 简言之 就是你不能对将要发生的事完全确定 

这个结果未必会发生 那个结果也是 你会得到披萨 而且还很好吃 你会得到意面 味道不粗 然而 每个结果都是有概率的 披萨能被送到桌上 是有概率的 披萨尝起来不错是有概率的 披萨送不到桌上 被服务员弄掉地上了 也是有概率的 或许披萨味道糟糕极了 因为烤焦了 因此你在做一个风险性决策 

那么我们怎样去做风险性决策呢？ 针对它有多种理论 但最常用的是应用期望值理论 我们将看到许多不同的数值 处理起它们来十分困难 但我们先从一个简单的例子开始 我们假定我们只关心钱 搞明白这些的一个普通的办法 可能是最普通的解决办法了 就是计算货币期望或者说财务期望 计算过程十分简单 就是用赢的概率乘以净收益 如果你赢了 

减去输的概率乘以净亏损 如果你输了的话 这里我们说的收益和亏损均是用钱表示 但我们为什么要强调净亏损和净收益呢？ 

好的 设想你买了一张彩票 赢了2千万美金 他们给你寄来了2千万美金的支票 那么 你到底赢了多少？ 听起来你好像赢了20,000,000美金 但不是 你买彩票花的那一元钱再也回不来了 所以实际 你只赢了19,999,999美金 当然 如果你中了彩票这点钱微不足道 没什么大不了 现在 设想一个不一样的情形 你在打扑克 你赌10美金 对手抬价到20美金 你虚张声势 想赌大点儿 所以你又赌了200元 也算进了赌注总额里 

你的对手放弃了 你拿走了所有钱 总共有多少呢？230美金 那么你赢了230美金吗？ 不 因为你放了210美金在里面 你只赢了20美金 净赢得就是你拿到的总额减去 你赢之前你加进去的赌注 所以 就是230减去你加进去的210 你只得到了20 在扑克里很多人都忘了也没有想过 他们通过虚张声势赢的一大笔钱 并不真的有他们自己以为的那么多 

无论如何我们必须要看下当我们使用这个财务期望公式时的 净收益和净亏损 我们举几个计算财务期望的例子 就用一副牌来举例 因为我们都很熟悉它 有13种不同的纸牌和 四种不同的花色：黑桃 红桃 方片 和梅花 

记住这点 我们来计算概率 设想你们来玩这个赌局 

赌注1美金 如果你抽中黑桃你就有5美金的净收益 

注意到净意味着要么你赌了1美金 然后你拿走6美金 得到5美金的净收益 要么就是你说不是黑桃 我给你1美金 如果是黑桃你给我5美金 任选其一 只要你抽中黑桃你就有5美金进账 那么这个赌局的财务期望是多少呢？ 

我们都知道抽中黑桃的几率是四分之一 

也就是赢的概率 因为抽中黑桃就是赢了 净收益是5美金 那么为了计算财务期望我们要用它乘以1/4 即抽中黑桃的概率 乘以5 5是你赢得的钱数 净的 如果你赢了的话 我们还得减掉输的概率 3/4 因为如果你抽中红桃 方片或是梅花 你就输了 你输了多少？1美金 1/4乘以5 就是5/4 3/4乘以1就是3/4 从5/4中减去3/4 得到2/4 也即1/2 所以这场赌局的财务期望是1/2 现在拿这个和另一个赌局比较一下 这个赌局里你赌1美金 你能赢10美金 听上去不错 不是5了 你能赢10 但除非你是抽中A 你才能拿到10美金 净的 这儿有13种牌 我们要重新计算 抽中A的概率是1/13 你赢的量是10 这是净赢得 记住了 

还得减去输的概率 12/13 因为其他不是A的牌抽到了都算输 

你净输的量是1 10乘以1/13是10/13 减去12/13乘以1 即12/13 你得到-2/13 注意到这是负的2/13 这意味着 这场赌局的财务期望是负的 长远看来如果你总是这么赌的话会亏钱 第三个例子 这次 你赌1美金 净赢得51美金 如果你抽中黑桃A 但不能是其他A或是其他黑桃 必须得是黑桃A 那么这个赌局的财务期望是？ 

期望是赢的概率1/52 乘以 你净赢得的量51 减去输的概率 51/52 乘以你净输的量 如果你输了的话 51乘以1/52 得51/52 51/52乘以1是51/52 两者相减得0 因此这一局的财务期望是0 

明白? 比较这三个赌局 试问如果是你 你会参加哪个？ 

好吧 第一个比较有利 比较有利的赌局是它的期望大于0 这意味着对你比较有利 如果你只在乎钱的话 期望值小于0的赌局是比较不利的 

0期望值的赌局是中性的 或者说是公平的 如果你可以选择有利的 不利的和中性的赌局 毫不惊讶的是 你选择期望值大于0的赌局 也即有利的赌局 如果你真打算赌的话 这就是我们将要考虑的下一个问题 

### Expected Overall Value

In the previous lecture, we saw that if you're going to bet then you ought to pick a favorable bet over an unfavorable bet and even over a neutral or fair bet. 

The next question is, do you want to bet at all? 

And there, we have to look at other values besides money. 

Let's consider this case. Suppose that you can't just bet a dollar, this game's not for fun, these are serious gamblers, your minimum bet is $100,000. And now, if you draw a spade you win a million dollars net. 

Cool. Well, what's the expected financial value? 

One chance in four of picking a spade. The amount you win net is a million dollars. You have to subtract the probability of losing three out of four, because you lose if you pick a heart, a diamond, or a club, times the amount you bet, which is 100,000. Pretty neat. This bet's got an expected financial value of $175,000. Now that sounds like a great bet, but is it really a great bet? It is favorable, but it's only favorable financially. Imagine, that $100,000 is all the money you got in the world. It's what you use to pay your rent with, it's all your retirement money, and if you lose it you're going to be out on the street with nothing. Then should you bet this money? No! Absolutely not. 

It just doesn't make sense to take that kind of risk with this money if you're going to be out on the street, if you lose, because you've got three chances in four of losing. Sure, you might win, you might be better off, but you've got an awful lot to lose and that's why you shouldn't make this bet, because there's just too much to lose. And what does that mean? Think about what it means that there's too much to lose, it's not that there's too much money to lose, because you've just calculated the financial value of the bet. 

What really is the loss is security. You're not going to have a place to live. 

You're not going to know how to make ends meat or buy your next meal. That's the problem, is there are lots of other values besides money and in these situations where we say you've got too much to lose, it's those other considerations in addition to money that make it a bad bet. 

Now let's look at the other side. In some cases, you don't have too much to lose, you've got too much to win. That is, the amount that you in just might not add up in the way that you thought it would. This is the phenomenon called, diminishing marginal utility. And what that means is that each increment decreases as you get more and more and more of those increments. You just don't need that much. 

One example is hamburgers. If you're really hungry and you don't have anything to eat you might want a hamburger, but what about two hamburgers? Is two hamburgers twice as good as one hamburger? Not really, I mean maybe you want two hamburgers, that would be nice, but it's not twice as good. And what about three hamburgers? Is that three times as good as one hamburger? And what about four or five or six or seven or eight or nine or ten? What about ten hamburgers? Are ten hamburgers ten times as valuable to a hungry person as one hamburger? No. because you're going to get full before you ever eat that tenth hamburger. So the marginal utility of a hamburger goes down. The first one might be very valuable to a hungry person with nothing to eat. The second one's a little less. The third one's a little less. The fourth one's a little less. And the difference between nine and ten might be totally negligible because they're all going to go bad before you eat all ten of them. The same thing happens in lotteries. 

Let's compare two lotteries. In the first lottery, if you buy one ticket for $100 then you have one chance in a million of winning $300 million. That sounds like a pretty good bet. 

Compare it to this lottery, if you buy one ticket for $200 then you have a one in two million chance of winning a billion dollars. 

Which of these lotteries has a higher expected financial value? The one with the larger expected financial value is lottery B. 

Does that mean that you ought to spend the extra money to play in lottery B instead of lottery A? 

Well, that depends, I suppose, how much more valuable is $1 billion to you than $300 million? $300 million is a lot of money. I could buy pretty much anything I ever wanted if I had $300 million. I'm not sure why I would want all that extra money, it's like a tenth hamburger. I wouldn't really need it. So which of these lotteries should you pick if that's the way you see the relationship between the winnings? 

Well, even though the expected financial value is greater in lottery B, you might reasonably pick lottery A because you have a bigger chance of getting the $300 million. 

And the difference between $300 million and $1 billion doesn't matter that much to you. 

Not everybody's going to share that value judgement, but if it doesn't really matter much to you whether you have $300 million or $1 billion, then it makes sense to go for lottery A. 

And this shows, yet again, that there's more to life than expected financial value. The other values in life are captured in the notion of overall value. The actual overall value or sometimes called utility of an act is simply all of the good and bad effects that the act actually has. The values of those effects. Positive values and negative values calculated together. 

And the expected overall value of the bet or of an action, sometimes called the expected utility of the act, is all of the good and bad effects of the act multiplied by the probability of each of those effects. 

So you bring not just the values into play, but also the probabilities. 

And if you're really going to decide what you ought to do, you shouldn't be looking just at money. You should be looking at all the different values, including security, as we mentioned or how much good the money's really going to do you if you're going to have $300 million anyway. There's lots of other things to consider. The problem is, how do you calculate that? How are you going to actually to calculate overall value or expected overall value? 

Here's an example to show how hard it is. Imagine that you have a friend that you love playing with after school and you then get an offer of a job and you can make a bunch of money by doing the job after school, but then you won't get to play with your friend. Well, how are we going to figure this out? Let's calculate the expected overall value? 

What's the probability that if you take the job you won't be such good friends with them anymore because you won't be playing as much and then you'll lose your friend and what's the value of that friend? You gotta multiply the probability of losing your friend by the value of that friend. Whoa, how you going to do that? How do you put a dollar value on that friendship? How do you figure out the probability that your friend's going to leave you and not be as close, anyway, as he was before? 

Well, you just can't do that. You can't really put it into numbers like that. Now, some economists have very sophisticated techniques for taking preferences and attaching values to those preferences and then multiplying by probabilities, and so I don't want to say it cannot be done. But the point here is just, it's a lot more difficult than figuring out whether you ought to make a bet in a simple little poker game or even whether you ought to put your money into the lottery. 

When we start talking about real decisions about friends and about other values in life, some of them can not be reduced to money and then it's hard to put a number on them and it's hard to do the actual calculations. So I don't want to suggest that any of this decision theory regarding expected utility is going to actually be applied in real life. Another reason that's worth mentioning is that third kind of decision that I mentioned at the beginning of the lecture namely, decisions with ignorance. Sometimes you don't even know the probabilities and if you don't know the probabilities you can't enter the probabilities in the formula for expected utility or expected financial value or expected overall value. If you don't know the probabilities how are you going to calculate? You can't. You know there are lots of tricky rules that people have proposed for decisions under uncertainty or decisions with ignorance, as I call them, but none of those are really conclusive and there's big disputes about which one is the right rule. So a lot of this discussion is going to be inconclusive. You might have wished that I would come in here and tell you, here's how you figure out exactly what to do in every area of your life. Well, I'm sorry, but I just can't do it and nobody else can either. Nonetheless, if you think in terms of the various factors that we've been discussing, financial value, other kinds of values, probabilities of the different outcomes, maybe at least you'll be able to avoid some of the worst mistakes that people make in decisions. 

在前一讲中 我们了解到要是你想跟人打赌 你得挑一个对你有利而非不利的赌局 甚至都不是一个公平公正的赌局 

下一个问题是 你真的想赌么？ 

然后 我们就得关注金钱以外的事情 

让我们来看看这个案例 试想你不只要赌一块钱 这不是过家家酒 这是个正式的赌局 你最低得押注$100,000 现在 如果你赢了 你就坐收一百万元的奖金 

哇 好棒耶 但是 这时候财富的期望是多少呢？ 

(抽扑克抽到黑桃算赢)你有四分之一的赢面 如果赢了 就能拿到一百万元 你得从这个值中减去那可能性为四分之三的输面的情况 如果不幸抽到了红桃 方块 或是草花 你就输了 把四分之三乘以你的赌注$100,000 很清楚了吧 这个赌局的财富期望值是$175,000 看上去这个赌局相当有吸引力 但真的是这样么？ 这对你很有利 但这只是在金钱的层面上 想想 总共有$100,000 这就是你全部的积蓄了 你得用它来付房租 来养老 要是你输掉了 你就要一贫如洗地被扫地出门了 那你还会赌上这些钱吗？ 当然不会不要! 绝对不是 

我没必要去参加这么一个赌局 拿这么多钱去承担这么多风险 一不留神就会被扫地出门 因为你的输面有四分之三那么大 当然 你有可能会赢 会发财 但要是你输了就惨到家了 所以你千万别去赌 你输不起 那意味着什么呢？那意味着什么呢？ 什么叫你输不起呢 不是说你可能会输很多钱 你已经算过这场赌局的财富期望了 

你输掉的是你生活的保障 你会无家可归 

你会朝无食饲 夕无归宿 那才是问题所在 除了金钱以外还有很多价值需要考虑 考虑一下金钱以外的事 这就是我称之为输不起的赌局 

现在再来看看另一种局面 有时候 你不是输得太多 而是赢得太多 就是说 你投入的资本 并不如你所预期的那种方式增值 这种现象称为边际效用递减 也就是说 每一次的增值 增量都会减少 可你并不需要这些增值 

举个汉堡包的例子吧 如果你很饿 而且什么都没得吃 你也许想要一个汉堡 那两个汉堡怎么样？ 吃两个汉堡是不是比吃一个好上两倍？ 不是吧 我是说 也许你会想要两个汉堡 那很棒 但这不比吃一个汉堡好两倍 那三个呢？ 那比吃一个汉堡好三倍吗？ 那四个五个六个七个八个九个十个呢？ 不是的 对一个饿鬼来说 吃十个汉堡比吃一个好上十倍？ 才怪 因为你在吃第十个汉堡之前早就吃饱了 所以汉堡的边际效用降低了 第一个汉堡对一个饿死鬼来说绝对是天降甘露 第二个的效用就减少了一点 第三个又少了一点 第四个更是如此 第九个和第十个汉堡几乎就没差了 

因为在你吃它们之前 已经饱到恶心了 乐透也是这样 我们比较看看两种乐透彩票 第一种 如果你花$100 买彩票 

你有百万分之一的概率能赢三亿美元 听上去真不错 

那再看看第二种 如果你买$200的彩票 你有二百万分之一的概率能赢十亿美元 

哪一种乐透的财富期望比较高？ 当然是后者 

那这是不是就意味着你应该花更多的钱 去买后面一种乐透呢？ 好吧 那得看情况 对你来说 十亿美元比三亿美元多了多少价值呢？ 三亿美元已经是个天文数字了 要是我有三亿美元 我想买什么就买什么 我不知道我为什么想要更多钱 这就像那第十个汉堡一样 我根本不需要它 

所以如果是你 在比较过两种中奖所得后 你会选哪种彩票呢？ 即便后者的财富期望更高 

你可能还是会理性地选择前者 你有更大的机会中三亿美元的奖金 

三亿美元和十亿美元 对你来说其实没有太大区别 也许有人不认同我的财富观念 但如果对你来说三亿美元和十亿美元 

没有太大差别 你应该买前一种彩票 这再次告诉我们 除了财富期望 生活中还有很多要考虑的东西 生活中这些(金钱之外的) 价值 被称之为 整体价值 真正的整体价值 或者叫行为效用 就是指这个行为带来的所有好处和坏处 

这些影响的价值 正负面影响的价值统算在一起 一个赌局或是一个行为的整体价值期望 或者叫行为效益的期望 就是该行为所有正负面影响 按照它们发生的概率加权相乘后的总和 

所以你不仅要考虑各种价值 还要考虑对应的概率 

如果你真的要去做一个决定了 你不止要关注金钱 你还得关注其他不同的价值 包括我们提到过的安全性 或者要是你无论如何都会拿到三亿美元 那些钱对你来说意味着什么 有好多东西得考虑 问题来了 你怎么计算它？ 你怎么实际计算整体价值或是整体价值的期望？ 

来看看这个例子你就知道有多难了 假设你有一个朋友 你喜欢放学后跟他一起玩 然后你被一家公司里录用了 如果你放学后去工作的话就能挣好多钱 但这样的话你就不能跟这个朋友玩耍了 你怎么办？ 我们来算算整体价值的期望吧 

你去工作之后  你跟朋友们的关系疏远的概率是多大呢 你们不能常常一起玩了 你会失去这个朋友  怎么用价值度量朋友？ 你得用失去这个朋友的几率 乘以这个朋友的价值 哇 那怎么办得到？ 你怎么用金钱来衡量一段友情？ 你怎么知道你的朋友疏远你的概率？ 你们之间不会如从前那样亲密无间？ 

你看 这怎么办得到嘛 你没法将其数字化 现在 一些经济学家 提出某些非常复杂的理论 来衡量人们的偏好 并且给这些偏好附上价值 然后乘以相应的概率 我是想说这可以办到 重点是 这比判断你要不要 去参加一场赌花色的赌局 或是买乐透 要困难得多 

当我们开始讨论实际的例子 好比说你的朋友们 以及生活中的其他价值 我们就会发现 其中一些 完全没有办法用金钱来换算 你很难给他们标个价格 也不能做个算术题就搞定一切 所以我并不是想告诉你们 这些涉及效用期望的决策理论 能够在实际生活中有什么应用 值得一提的还有一点 就是我在讲座开始时 提到的第三种决策 称之为 无知的决定 有时候你甚至不知道事情发生的概率 你也就不能把它们朝公式里一代了之 来求出效用的期望 或是财富的期望或是整体价值的期望 如果你不知道各个事件的概率 你该怎么计算呢？ 你没办法的 你知道人际交往中有很多微妙的规律 人们建议用这些规律 在面临不确定时 正如我说的 无知地作出决策 没有一个是能令人信服的 究竟哪种规律是正确的 至今尚有很大的争议 所以众多相关的讨论是无效的 你们也许会希望我走进课堂 然后告诉你 生活中的各种情境下如何决策 抱歉 但我做不到 因为没人能告诉你怎么做 尽管如此 如果你考虑一下我们先前提到的诸多因素 财富 

### The Sausage Argument: A Student Argument About Decision Making

We studied chance and choice, and a lot of students send in very nice arguments regarding choice or decision making. 

But here's one that you definitely should not miss because. 

This one could save you from horrible disaster. Without this lesson you could become a target for wild dogs. >> Hi. My name's Anton. In this video, I'll argue that it is essential to carry a sausage with you at all times. 

Most dogs are nice creatures, but some of them have an aggressive character. 

An aggressive dog is especially angry when it is hungry. 

When an angry dog runs after you, you can throw it a sausage if you have one. A sausage smells more promising than a human, therefore, the dog will probably stop to examine and consume the sausage. 

Meanwhile, you'll get a chance to escape. 

If you do not have a sausage, 

the risk of being bitten by an angry dog is much greater. Therefore, it is essential to always carry a sausage. By the way, the sausage should be carried in an airtight container. 

So that it doesn't attract dogs instead. 

Thanks for watching, and don't forget your sausage. [INAUDIBLE] >> That argument got over a 130 votes, and it's easy to see why. It was clear, forceful. And humorous. 

Now I especially like the guarding terms. Because our term didn't claim that all dogs are going to bite you, most dogs are nice. They more claim too much, and you didn't say that the dogs will always go into the sausage because sometimes they might bite you anyway But it'll probably help you, so it was a very nice use of guarding terms. And I also loved the bit at the end about the plastic container. And we'll get to that later but, but the reason that's so important is that a potential objection is that the sausage is going to attract wild dogs Box. So it's not enough really to carry a sausage. His conclusion is you have to carry a sausage in a plastic container. And for that, it's a pretty good argument, but it's got weaknesses like every argument. And in this case, the weakness is it depends on some suppressed premises. 

Now we say, when we were talking about suppressed premises in week three that that's perfectly fine. There's nothing wrong suppressed premises as long as they're not controversial in creating any problems, but it's worthwhile to bring them out. 

And in one response to a comment, Artem admits 

that he has certain suppressed premises. 

In response to Brian Peck, Artem writes, as for the second part of the argument, you're absolutely correct in suggesting that some suppressed premises should be added to make the argument valid. Indeed, I assumed that the person is not a masochist. And, that they do not have better means of protection. I would even add that better here Does not necessarily mean more efficient, that is more effective at keeping dogs away. Most people probably wouldn't want to shoot every dog running after them. A sausage is much more humane. So, yes, I would add at least two suppressed premises. The person wants to reduce the risk of being bitten by an angry dog. They're not [UNKNOWN]. [INAUDIBLE] And the person has no better means of anti-dog protection or prefers not to use them. 

Those are the supressed premises. He admits them and that also, that's okay because sometimes you need to supress premises in order to keep your argument from being too long. In this case, to keep it from being over 100 words. 

The lesson that I want to draw from this argument concerns another kind of argument, practical reasoning involving choices or decisions. We studied cases of gambling and looked at expected financial value and saw that the expected financial value involves the probability of winning and the net gain of winning. Minus the probability of losing times the net gain of losing. And, that's all fine for gambling. But, here, there're no probabilities. So, how can that formula that we learned for gambling with cards and dice and lotteries, really help us make decisions of this sort? And the answer is, it can help us because it tells us what to look for, arguments for decisions need to consider probabilities of winning, probabilities of losing, in this case probability of the sausage working, probability of it not working, and it also needs to consider The gains, that is the net gains, if it works, and the net losses if it doesn't work. 

But now, what's the probability of it working, what's the probability of it not working? What's the probability of suffering if you don't have a sausage with you? Or that's going to vary and this point of it depends, of it varying and depending on the contacts was brought out by another student comment. 

Joe writes, one of the lessons I've learned from the Construct Your Own Argument Forum is how much the reader's setting can influence the interpretation and the impact of an argument. Where I live, I don't need to worry about wild dogs. 

Yesterday, I listened to a radio story about the wild dogs in Mexico City. 

Emily just mentioned Santiago in the post above and now I'm curious about the dog situation where Artem lives. Regardless of where Artem lives, I'm pretty sure the argument was meant to make us smile, but it's interesting to see how setting influences the creation of an argument. As well as its interpretation. 

Absolutely. Couldn't agree more, Joe. That's what's interesting about this. And the point matters, because our students are from all over the world, more than 165 countries, and each of them has to decide what the probability of getting attacked by wild dogs is, in their own situation. 

There are almost no wild dogs where I live as far as I know, so I don't really need to bring a sausage unless I want to be super safe. But, in some areas, there are lots of wild dogs, and in those areas, you might need to bring, not just one sausage, that's not going to do it. You need to bring two sausages. 

And then, you can bring three sausages, then you can bring four. And pretty soon, you've gotta take sausages. And, you have to carry them around with you 

all over your back, until you're covered with sausages. Because, there're so many wild dogs, you don't want to run out. Of course, you ought to put them in plastic containers, but I'll do that later. The point here is that the context tells you whether you need any sausages at all, and how many sausages you need. 

And what part of the context tells you that? Well, the question is, what's the probability of running into one wild dog? What's the probability of running into two or more wild dogs? That probability is going to tell you how many sausages you need. So that factor of probability that we saw with gambling is also something that you need to use to figure out how many sausages to bring with you. 

We also needed to figure out the probability of the sausage actually working. 

That depends on how effective and reliable it is. And, that depends maybe on the type of sausage and the type of dog. We'll have to take all that into consideration. But, it also depends on the person and how they handle the sausage. 

This was brought out in a comment in a discussion forum, by Emily. 

But I do have a question, what if I get hungry and eat I sausage? 

Or say, one dog chases me, I throw it a sausage and another angry dog sees it happen and starts to chase me. How many sausages to carry to ensure that I enough sausage and for all angry, hungry dogs at all times? More sausages in, say, Santiago chili than in Santiago, California? 

Where can I find statistics about dog attacks to back up my numbers? Should there be a government stipend for sausages purchased to deflect dog attacks, funded by those who break leash laws? 

I can see all sorts of possibilities opening up. 

Well, we've talked about the problem of there being more than one dog. But now we've got another problem. What if somebody who holds their sausage to keep the dog away decides, I'm hungry. 

You're not in trouble. 

Well Emily, nothing is fool proof, that is, nothings going to work if you're a fool. All that Archims method can do is tell you, how to keep the dogs away. If you eat your sausage. There is nothing we can do for you, or for the dogs for that matter. So I don't think the fact that you might eat your sausage, shows you there's anything wrong with, or times argument, instead it shows us something wrong, with the people that eat their sausages while surrounded by wild dogs. 

Another lesson is that the strength of an argument like this depends on the available alternatives. There might be other ways of keeping wild dogs away, and we always have to think about those options. To overlook a better way of achieving the same goal is a kind of fallacy. 

I don't know what to call it But it makes a bad argument. And this point was brought out by several of the student comments on a terms of argument. Jose wrote, the thing is, the sausage might eventually rot or get torn. 

Or, as Emily would say, get eaten. 

Therefore, I'd suggest spikes on the shoes or a pepper spray, 

both are more versatile and can protect you from the angry but not hungry dogs. 

That's a good point Jose, but Artem has a nice response. Hi, Jose. Of course, spiked shoes and pepper spray will do the job. But they're much less humane than a sausage. Besides, if the dog is angry because it's hungry, the sausage will solve the problem, 

so that other people who encounter this dog will run a smaller risk of being bitten. In contrast, Violent defense methods would probably make the dog even more angry. 

And now I think Acum has a good point. 

The pepper spray might work, but it might make the dog even more angry and then you'll be worse off than before. 

So how can we choose among these different alternative methods. Of saving ourselves from wild dogs. 

Think back to the formula for expected value. 

You need to know not just the probabilities, but also the gains and losses, but wait a minute! The point here is that it's the net gain that matters. 

If you throw the sausage out Then you have a gain, because you're not bitten, 

and the dog has a gain, because he gets the sausage, and nobody gets hurt. 

But if you use pepper spray or spiked shoes, then sure, you have a gain, you're not bitten, but the dog has a loss. And if we're looking at this from a moral point of view, we ought to consider the dogs loss as well as your gain, and that means we have to subtract, that loss from the gain. Just like we subtracted the cost of betting from the winnings, when we were talking about betting. So that formula by emphasizing that its the net gain that matters, as well as net loss for that matter. Matter tells us that we have to consider all the different gains and loses to all the different people if we want to treat those different people and animals impartially. And when we subtract the cost of the dog, the pepper spray or getting kicked by spiked boats, then it sure sounds to me like Sausage Wins out over pepper spray and spiked boots. Or shooting the dogs, for that matter. So, I'm on our temp's side. 

You always ought to bring a sausage wherever you go. 

Here, you can have one of these. 