---
author: Xzonn
date: 2021-06-10
image: hero_pc.jpg
image_height: 561
image_width: 1520
interviewees: 
- 手岛宏介
- 益田直生
last_modified_at: 2025-05-25 19:10
links: 
- - https://www.nintendo.com/jp/switch/awuxa/index.html
  - 《附带导航！一做就上手 第一次的游戏程序设计》官网
- - https://www.nintendo.com/hk/interview/awuxa/
  - "開發人員的訪談 : 附帶導航！一做就上手 第一次的遊戲程式設計"
sources: 
- - https://www.nintendo.com/jp/interview/awuxa/index.html
  - "開発者に訊きました : ナビつき！ つくってわかる　はじめてゲームプログラミング"
title: 开发人员访谈：附带导航！一做就上手 第一次的游戏程序设计
---
- **手岛宏介**（<span lang="ja">手嶋 宏介</span>）：任天堂企划制作部第4制作组。
- **益田直生**（<span lang="ja">益田 直生</span>）：任天堂企划制作部第4制作组。

> 任天堂（香港）于2021年7月16日公布了本文的[中文翻译版](https://www.nintendo.com/hk/interview/awuxa/)。

### 1. 把它翻转过来会如何呢？
##### 让开发者自己用语言来传达对任天堂创作方式的想法和坚持——“开发人员访谈”栏目。首次访谈要提问参与了《附带导航！一做就上手 第一次的游戏程序设计》开发的两位。
{: .question }

##### 首先请两位简单自我介绍一下，并谈一谈至今为止所负责的工作。
{: .question }

##### 益田
我是担任了《附带导航！一做就上手 第一次的游戏程序设计》的总监兼程序员的益田。之前负责[《Nintendo Labo》](https://www.nintendo.com/jp/labo/index.html)<sup>[※1](#ref-1)</sup>系列的规格讨论和程序开发。

> ※1　将纸箱和Nintendo Switch组合起来，可以制作钢琴、摩托车、机器人等各种各样的控制器（“Toy-Con”）来玩的游戏。“组合套装”“机器人套装”于2018年4月20日发售。
> {: #ref-1 }

##### 手岛
我是手岛，担任了副总监，负责导航课程的汇总。最近我负责制作了《Nintendo Labo》的“探索”（<span lang="ja">わかる</span>）<sup>[※2](#ref-2)</sup>的文本。

> ※2　《Nintendo Labo》的模式之一。通过理解Toy-Con的结构，可以发现新的玩法。
> {: #ref-2 }

##### 非常感谢。那么，首先先请简单介绍一下这次的软件吧。
{: .question }

##### 益田
好的。《附带导航！一做就上手 第一次的游戏程序设计》这款软件，只需要通过连接一种[被称作“小节点”的不可思议生物](https://www.nintendo.com/jp/interview/awuxa/photo/01.jpg){: .figure-link }，就可以轻松享受程序设计。

即使是觉得程序设计很难的人，也可以通过详细的导航和小节点来理解程序设计，最终自己制作游戏。

##### 这部软件的企划，是因为怎样的契机而开始的呢？
{: .question }

##### 益田
在《Nintendo Labo》第四作“VR套装”开发结束之后，我想到是否可以把VR套装中包含的[Toy-Con车库VR](https://www.nintendo.com/jp/interview/awuxa/photo/02.png){: .figure-link }部分分割出来，做成单独的商品。

Toy-Con车库VR是在大概了解了VR的Toy-Con的制作方式之后，由玩家用自己的想法，利用VR来制作并游玩游戏。我想要不局限于VR，而是将范围扩大。

##### 那是因为在Toy-Con车库还有什么未完成的内容吗？
{: .question }

##### 益田
不，倒不是还有什么未完成的内容，而是觉得是否可以用不同的方式来展现出来。VR套装的Toy-Con车库，是《Nintendo Labo》中最后的最后的应用环节，当时我的想法是“即使只有很少一部分人能玩到那里也好啊”。

但是试着举办了Toy-Con车库的[比赛](https://www.nintendo.com/jp/labo/contest_VR/index.html)后，我们发现玩家们在Toy-Con车库制作的原创游戏中，有很多反响不错的有趣的游戏，于是我们才知道不仅仅是“很少一部分人”，而是有很多人都想要体体验制作游戏的乐趣。

能不能让一边试错一边制作游戏的乐趣，变得更容易就能体验到呢……我们开始这样考虑。

##### 手岛
在《Nintendo Labo》的开发团队中，也有平时不设计程序的设计师们用Toy-Con车库制作了游戏。

当制作游戏的人在中途发现了无法理解的事情而停下来的时候，就会来问开发了Toy-Con车库的益田先生，然后就能逐渐理解并继续制作了……当时益田先生什么问题都能解决，简直就像是“帮助角色”一样（笑）。

##### 益田
我收到了来自设计师的提问，观看了比赛中玩家制作的游戏，再次觉得Toy-Con车库果然很有趣。

但是，要是能够更详细地把Toy-Con车库的“制作方法”表达出来的话，我想或许可以让其中有趣的地方更加扩大。

##### 也就是说，Toy-Con车库提出的问题是“制作方法的说明”这部分，而解决这个问题的方法就成为了这次的目标是吗？
{: .question }

##### 益田
是啊。《Nintendo Labo》是用纸箱Toy-Con来玩的游戏，只有很少一部分人能够使用Toy-Con车库来制作原创游戏，这需要首先了解硬件的构造，然后将其应用。但是，在担任设计师们的“帮助角色”时收到各种问题的过程中，我想到“要是把这个顺序翻转过来会如何呢？”

也就是说，在《Nintendo Labo》里首先要了解硬件的结构，最后才是制作软件。但是，在《第一次的游戏程序设计》里，我们把制作软件作为入口，先体验程序设计。

在《Nintendo Labo》中有着名为“制作”的“世界第一棒”的组装说明书，我想把这个技巧也应用到程序设计中的“制作”上。这样的话，就可以从与《Nintendo Labo》不同的角度来体验“制作、游玩、探索”了吧。

##### 正因为这种想法，在《Nintendo Labo》中流程最后才有的软件制作部分，这次在前面就出现了。
{: .question }

##### 手岛
是的，正如益田先生成为了设计师们的“帮助角色”一样，如果有了说明（导航）的话，我想大家一定能够更加享受那种可能性！

##### 那么，“附带导航！”中的“导航”是益田先生……？
{: .question }

##### 手岛
是的，那也可以说是益田先生的分身吧（笑）。

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/1_3_M.jpg" width="640" height="360" %}

##### 这样的话，我就很在意作为益田先生分身的导航了。“附带导航！”中的导航到底是什么样的呢？
{: .question }

##### 手岛
具体来说，导航就是[7种“附带导航的课堂”](https://www.nintendo.com/jp/interview/awuxa/movie/01.mp4){: .video-link }，它们是这款软件的主要内容，通过使用小节点来使游戏程序设计充满乐趣。可以使用导航从头开始帮助完成游戏。

##### 实际上，它能提供什么程度的导航呢？
{: .question }

##### 手岛
会有名为“鲍伯”的说明角色出现，他可以从头到尾，手把手地教学。程序设计时使用的是名为小节点的角色，像是“把小节点放到这里”“把这个小节点和这个小节点连在一起”这样，[鲍伯会根据玩家的操作在画面上移动，从头到尾地详细教学](https://www.nintendo.com/jp/interview/awuxa/movie/02.mp4){: .video-link }。

##### 原来如此，那样的话初学者也能完成游戏。顺便说一下，小学生也能享受程序设计吗？
{: .question }

##### 益田
在开发阶段，我们让一些对程序设计感兴趣的小学生们制作了一些内容。

##### 反响如何呢？
{: .question }

##### 益田
反响很不错。在那个场合下游戏实际上已经完成了。比起“完成了”，不如说是已经超过了小学生的水平了……（笑）

##### 手岛
大概是“下一个！下一个！”这样的感觉，那天准备的针对监视器的课堂已经满足不了他们了，我们还加上了处于开发阶段的未公开的课程，真是让人头疼（笑）。

##### 益田
注意力非常集中（笑）。

##### （笑）。
{: .question }

##### 手岛
除此之外，还有小学四年级的学生通过附带导航的课堂之后的自由编程部分制作出了自己的游戏，这让我切实感受到了“这个很酷啊”。

##### 原来如此，事实证明小学生也能做出来。
{: .question }

##### 手岛
当然每个人都有差异。

##### 这种个人差异，您认为可以通过导航来填补吗？
{: .question }

##### 手岛
是的，“附带导航的课堂”是能让小学一年级学生也能一边享受一边完成游戏的内容。

不仅如此，还有一个模式可以更详细地说明课堂上出现的机制和小节点的内容，而想要尝试的人可以挑战自由编程，可以选择游玩的方法，我期待这可以填补各种各样的个人差异。

### 2. 偶像团体
##### 请详细介绍一下刚才谈到的“小节点”。那些角色是怎么诞生的呢？
{: .question }

##### 手岛
在企划的初期阶段，我一直把“制作起来很开心”作为关键词，所以我一直在和设计师商量如何在程序设计画面上也营造出愉快的氛围。

但是，嗯……我感觉这样下去会很难……无论是《Nintendo Labo》中的“Toy-Con车库”，还是本作中的“小节点车库”，都是通过把被称作“节点”的各种功能组合在一起制作游戏，在闲谈中有人提出了“把那个‘节点’做成偶像团体的感觉吧”这种建议。

##### 偶像吗？
{: .question }

##### 手岛
是的。有人提出了“把有着各种功能的‘节点’拟人化，组成偶像团体一样的单元，然后制作原创歌曲会怎样呢？”这种建议。把各自的作用总结成歌的话，也能理解机制了……

##### 原来如此。确实，一想到这是作用和个性都不同的人聚集在一起，就能够明白了。
{: .question }

##### 手岛
最初是企划快要完成的时候，在闲谈中开的玩笑（笑）。先不说偶像团体，初次看到“节点”很难理解它的机制，如果把各种各样的“节点”的功能组成性格、角色、脸型，或许就能让人容易理解。要是能喜欢上的话，大概就会记住了吧……我们是这样想的。

因此，就有了“果然还是拟人化的角色好啊……”“这样的话，就给它起个好记的名字吧……就叫小节点！”这样的对话。

##### 确实那样会更容易记住呢（笑）。那些小节点会如何在课堂中登场呢？
{: .question }

##### 手岛
[在课堂中登场的小节点，会在课堂中讲解的程序设计的流程中，分别说明自己的功能。](https://www.nintendo.com/jp/interview/awuxa/movie/03.mp4){: .video-link }

另外，游戏中有叫做“[小节点指南](https://www.nintendo.com/jp/interview/awuxa/movie/11.mp4){: .video-link }”的地方，能够更详细地对课堂中出现的流程和小节点的功能进行讲解，也可以在那里学习他们的情况。

##### 顺便一提，小节点有几种呢？
{: .question }

##### 手岛
有80种以上！虽然不是所有的小节点都会在附带导航的课堂中出现，但是在课堂中没有出现的节点也可以在[名叫“小百科”的说明栏目](https://www.nintendo.com/jp/interview/awuxa/movie/04.mp4){: .video-link }中确认详细的功能。

例如，可以了解Joy-Con的振动功能、挥动Joy-Con的动作<sup>[※3](#ref-3)</sup>等，也有小节点使用了Nintendo Switch特有的功能，把这些功能组合起来，就可以制作出各种各样的游戏。

> ※3　Nintendo Switch Lite也可以通过另售的Joy-Con通过无线连接来达到同样的功能。
> {: #ref-3 }

##### 益田
如果能够理解小节点的作用并把他们组合起来的话，就已经可以制作出各种各样的游戏了。但是，不要被“必须要制作游戏”这样的固定观念束缚住，例如单纯在街道的风景中散步这样的程序也不错。

##### 对了，我从刚才开始就很在意，那边的彩色卡片是什么？
{: .question }

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/2_1.jpg" width="640" height="335" %}

##### 益田
这是实体版附赠的“小节点回顾卡片”（<span lang="ja">ノードンふりかえりカード</span>），每一张都是一种不同的小节点，正面是小节点的样子，反面是功能说明和使用方法的提示，以及登场的课堂。

{% include figure.html src="04.png" width="620" height="400" %}

##### 在附带导航的课堂结束后，可以使用这张卡片回顾课堂内容，是这样吧。
{: .question }

##### 益田
是的。在不玩游戏的时候，“话说今天出现的是按键小节点吧……”一边这样说，以便看着按键小节点的卡片回忆，然后再看背面，回想起“对对，按下按键之后做出反应的家伙”。如果这样的话就好了。

##### 像这样的编程软件，很多时候都会附带词典一样的使用说明书，但这次为什么偏偏要用卡片呢？
{: .question }

##### 手岛
虽然也有“单纯是喜欢这样”的原因，但如果做成卡片的类型的话，就可以像这样重新排列。

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/05.jpg" width="640" height="360" %}

##### 益田
对对，能重新排列是重点。想象一下，“把这个小节点和那个小节点组合在一起的话，能不能制作出什么有意思的游戏呢。”就是这样的感觉。

##### 手岛
不管是哪个课堂上出现的小节点，都会被印在卡片上，所以只要看了这个就会想到“在课堂1里出现的就是这个吧”，也可以只把特定课堂中出现的小节点挑出来排列在一起。

“课堂中提到的重来的机制就是它”，“画面滚动是它”等等，通过排列组合来考虑各种各样的事，我觉得这很方便。

##### 这样的话应该可以很开心地回顾吧。
{: .question }

##### 益田
不仅仅是有助于回顾，在卡片方框下方的部分有叫做“使用方法提示”的文字，如果按照提示实际操作设定程序的话，就可以让某些东西动起来。

没有在课堂中出现的小节点，虽然也可以在刚才说到的游戏内的说明栏目“小百科”中确认使用方法，但如果一边看着卡片一边按照提示试着设置的话，就会有“能用这样的方法”、“可以这样运作起来”的想法，更容易给人留下印象。

##### 每一张卡片上都有一个“使用方法提示”吗？
{: .question }

##### 益田
是的，所有的卡片上都有不同的提示。对于“附带导航的课堂”中出现的小节点，我们尽可能地使用了和课堂上同样的内容来进行功能说明，便于回顾；也有些小节点在课堂中没有出现，这部分是新编写的。

##### 好像可以很方便地使用。
{: .question }

##### 手岛
另外，“小节点回顾卡片”可以在[My Nintendo Store购买](https://store-jp.nintendo.com/list/hardware-accessory/other-hardware-accessory/HAC_A_AWUXA.html)，也可以购买游戏后再购买卡片。

##### 原来如此，这样的话购买了下载版的人也可以入手“小节点回顾卡片”了吧。那么，我已经知道了有很多小节点，能不能说明一下其中具有特征功能的小节点呢？
{: .question }

##### 益田
要说特征的话，我认为“[材质小节点](https://www.nintendo.com/jp/interview/awuxa/photo/06.jpg){: .figure-link }”和“[BGM小节点](https://www.nintendo.com/jp/interview/awuxa/photo/07.jpg){: .figure-link }”的功能比较好懂。

[“材质小节点”可以把自己绘制的画作显示在游戏中，然后贴在各种各样物体的表面随着物体移动](https://www.nintendo.com/jp/interview/awuxa/movie/05.mp4){: .video-link }。

[“BGM小节点”就是播放BGM](https://www.nintendo.com/jp/interview/awuxa/movie/06.mp4){: .video-link }。可以从旋律、主伴奏、副伴奏、节奏四个部分中选择自己喜欢的音乐，然后将它们组合起来编曲成BGM。可以按照自己的喜好选择和游戏搭配的音乐。

##### 手岛
我个人比较推荐“[开始时小节点](https://www.nintendo.com/jp/interview/awuxa/photo/08.jpg){: .figure-link }”。

##### “开始时小节点”？也有功能相当细致的小节点啊。
{: .question }

##### 手岛
是的。它的功能就是在游戏开始的瞬间来执行输出，虽然只是有勇无谋的家伙，不过它的那种气氛，包括视觉效果在内，非常可爱（笑）。

除此之外，就是“[计时小节点](https://www.nintendo.com/jp/interview/awuxa/photo/09.jpg){: .figure-link }”了吧。顾名思义，就是在指定的时间执行输出。它的性格细致入微，有些爱唠叨，不过相应地很有人情味，我很喜欢。

##### 益田
我推荐的是“[滴管小节点](https://www.nintendo.com/jp/interview/awuxa/photo/10.jpg){: .figure-link }”。这家伙可以知道被称为“标示”的东西有没有显示在滴管所在的地方……

虽然是面向高手的，但如果把“[计数小节点](https://www.nintendo.com/jp/interview/awuxa/photo/11.jpg){: .figure-link }”“[显示标示小节点](https://www.nintendo.com/jp/interview/awuxa/photo/12.jpg){: .figure-link }”和“[播放声音小节点](https://www.nintendo.com/jp/interview/awuxa/photo/13.jpg){: .figure-link }”组合起来的话，也可以创作出自己的原创音乐。虽然是小众的家伙，但是我很喜欢这些角色，而且如果能灵活运用这些功能的话，就会发现“只要肯下功夫，这样的事情也能做到啊”，能够得知小节点车库中不为人知的可能性。多多使用的话就会上瘾，这种感觉非常好……有点像是大人的小节点（笑）。

##### 手岛先生推荐的是可爱的角色，益田先生推荐的是功能深奥的角色，对吧。
{: .question }

##### 手岛
小节点们不仅会给出说明，在把它们连接起来的时候也会有各种各样的反应，性格和表情也各不相同，如果大家能乐在其中的话就好了。

##### 益田
请各位一定要去寻找属于自己的“推荐的小节点”。

### 3. 请一定要做到最后
##### 我听说将玩家引导到游戏最后是有讲究的，为了让玩家玩到最后，有没有在这方面进行努力呢？
{: .question }

##### 益田
确实……“制作游戏很开心”这种心情当然也很重要，我们还希望玩家在制作游戏的过程中能有“好好完成每一个功能的体验”，带着这种想法我们开发了这部作品。

##### “好好完成每一个功能的体验”，也就是说……？
{: .question }

##### 益田
“游戏制作”本身也很有趣，在制作过程中“完成每一个功能”也很有成就感，最重要的是完成的瞬间很快乐。作为开发者，我认为这是程序设计的有趣之处，也希望玩家能切实感受到这一点。

“在其他编程软件的教程中，很难完成到最后”，我们也听到了这样的声音。所以在这部软件中，我希望通过重复小小的完成体验，来让大家一定要把游戏制作到最后。

##### 原来如此。重点在于“完成这件事很开心”的感情。
{: .question }

##### 手岛
为了说明完成后的快乐和成就感，有一个小故事。

我之前参观了和“Yahoo!Kids”网站一起举办的《Nintendo Labo》的Toy-Con车库VR的体验会。我们让初学者的各位体验了一下在这次的软件中所说的“摇杆小节点 + 人小节点 = 通过摇杆操作使人移动”这样的简单编程。这样，一旦有人动起来的时候，会场中就会响起“哦哦！！”这样巨大的欢呼声，我也吓了一跳（笑）。

##### 对于开发者来说是理所当然的事情，但对于其他人来说就会非常惊奇吧。
{: .question }

##### 手岛
是的。没有学过编程的人，竟然会被“自己设计的程序能让物体移动起来”这种事所感动……！在那时这件事给我留下了深刻的印象。在这次的游戏开发过程中我们也运用了这个经验。

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/3_1_T.jpg" width="640" height="360" %}

##### 这个发现很重要啊。
{: .question }

##### 手岛
体验自己动手一个个组装起来的样子，对于我自己来说也是非常有趣的体验，我觉得不必迷惑，一定要做到最后，做到完成，才能体验到。

在程序设计中，有一种学习方法俗称“抄经”（<span lang="ja">写経</span>），就是通过抄写范例的程序代码来学习编程。这个方法很有效，可以作为参考。

##### 原来如此，只要抄写下来，就一定能到达最后。
{: .question }

##### 手岛
是的。只是，抄写的时候容易有“即使输入错了也很难发现”这样的事发生，如果输入有误的话程序就没有办法完成了。

当然，自己来检查哪里出错了，对于学习程序设计来说也很有帮助，但是对于这部软件来说，可以使用导航来避免输入错误产生的迷惑，让“完成的体验”近在眼前。

##### 所以，就是通过细致地导航，将玩家引导到“完成游戏”的阶段吧。
{: .question }

##### 手岛
是的。[“附带导航的课堂”的7个课堂中，有些步骤5分钟左右就可以完成，](https://www.nintendo.com/jp/interview/awuxa/movie/07.mp4){: .video-link }通过不断积累，逐渐向下一个步骤推进，我们采取了这样的形式。通过重复小小的完成体验，逐渐接近游戏的完成，就是这样的构造。

##### 但是，如果过程中中断了，经过了好几天之后，会不会因为忘了前一个课堂的内容而无法继续进行下去呢？
{: .question }

##### 益田
确实，后一节课是以前一节课的内容为前提进行的，但是不会出现想不起来前一节课的内容就无法继续进行的事情。

我们尽可能地减少了不唤起记忆就无法进行的情况，只要按照当时的指示的话就可以继续进行。

##### 原来如此，那就放心了。
{: .question }

##### 益田
实际上，也有人评论说，随着课程水平的提高，为了自己理解程序设计，巩固知识，不是应该渐渐地模糊指示，让玩家逐渐自己来操作吗？

但是，如果为了提高操作的自由度而隐藏了指示，而让人不知道该怎么做，最后放弃制作游戏的话，就得不偿失了……

##### 即使是塑料玩具，如果说明书只写到一半的话，就绝对无法完成，不知道制作方法的话也就无法享受乐趣了。正是因为能够完成，才会乐在其中。
{: .question }

##### 益田
是的。在这部软件里，我们也注重了要让玩家不管怎样到最后为止都不会出错，无论如何都能亲自动手完成……这样的结构。

另外，[在课堂和课堂之间还有被称为“小测验”的问题](https://www.nintendo.com/jp/interview/awuxa/movie/08.mp4){: .video-link }，在那里可以感受到“自己理解并完成”的体验。

### 4. 程序设计的乐趣
##### 如果在“附带导航的课堂”中完成了所有游戏，接下来应该做什么呢？
{: .question }

##### 益田
作为下一个阶段，我们准备了“自由编程”。当然，突然想要自己从头开始制作游戏也不错，但还是建议先把“附带导航的课堂”中制作的游戏[复制之后改编](https://www.nintendo.com/jp/interview/awuxa/movie/10.mp4){: .video-link }，从这里开始。

在课堂中制作的游戏也会作为自己制作的游戏保存在自由编程模式中，我觉得用它来尝试制作新的游戏也不错。

##### 手岛
如果把课堂中出现的这个小节点和那个小节点组合起来的话，会变成什么样的动作呢？像这样，首先试着实验性地玩一玩也不错。

如果不理解的话，随时都可以返回课堂或小节点指南，也可以通过说明栏目的“小百科”或“小节点回顾卡片”确认功能。

##### 原来如此。与其突然从零开始创造了不起的东西，不如先从改编开始一点一点地尝试比较好。
{: .question }

##### ……只不过，如果逐渐习惯了改编，很让人在意究竟能发展到什么程度。通过这样可以制作出市面上真正的游戏吗？也会有玩家有这样的反应吧。
{: .question }

##### 益田
我认为应该无法达到和市面上发售的Nintendo Switch游戏相同的水平。在自由编程中，小节点最多512个、连接小节点的线最多1024条，有着这样的限制……

不过，如果只是将喜欢的游戏的一部分提取出来，试着制作同样的结构，我觉得是有可能的。

比如，试着再现塞尔达<sup>[※4](#ref-4)</sup>的其中一个机关之类的……倒不如说，在这种限制下如何想方设法制作也是一种乐趣。

> ※4　《塞尔达传说》。初代于1986年发售，一边解决谜题一边进行冒险的动作冒险游戏。
> {: #ref-4 }

##### 在有限制的情况下，能否再现自己喜欢的游戏呢？这样想的话，或许就能像解谜一样乐在其中了吧。
{: .question }

##### 手岛
关于自由编程能发展到什么程度，因为这部软件中一开始就加入了物理引擎<sup>[※5](#ref-5)</sup>，所以它很适合制作跳跃、破坏物品这样的动作游戏。

> ※5　在图形表现中，根据现实世界的物理法则使物体运动的运算。通过使用物理引擎，可以真实地表现物体滚动、破坏方块、被风吹等各种动作。
> {: #ref-5 }

##### 原来如此。复杂的运算部分不需要自己去做。
{: .question }

##### 益田
反过来说，因为无法把大量的文本存放在一个游戏中，因此我觉得它不适合制作RPG<sup>[※6](#ref-6)</sup>或文字冒险游戏<sup>[※7](#ref-7)</sup>。

> ※6　Role Playing Game（角色扮演游戏）的简称。在故事中玩家操纵自己扮演的角色，通过冒险获得成长经验的游戏类型。
> {: #ref-6 }
> ※7　以包含了着插图和音乐的文章为中心，根据玩家的选择来阅读不断变化的故事的游戏类型。
> {: #ref-7 }

##### 手岛
……不不不，也许会有人把各种小节点组合起来实现突破（笑）。

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/4_1_M.jpg" width="640" height="360" %}

##### 益田
确实，Toy-Con车库VR的时候也有很多玩家制作的作品，让开发者们感到非常惊讶。“竟然能做出这种东西……”就像这样（笑）。

##### 即使有限制，也一定会有人想办法突破吧。
{: .question }

##### 益田
我非常期待有人能创作出让开发团队都感到惊讶的游戏。

##### 话说回来，如果自己制作了什么，就会有种想要让别人看到的想法，那么需要以怎样的形式被别人看到呢？
{: .question }

##### 手岛
制作出来的作品可以通过互联网或本地连接共享。

如果是使用互联网的情况<sup>[※8](#ref-8)</sup>，[在上传到任天堂的服务器之后，就会获得一个游戏ID](https://www.nintendo.com/jp/interview/awuxa/movie/09.mp4){: .video-link }，将那个ID交给对方并输入之后，就可以下载那个游戏，是这样的机制。

> ※8　若要使用互联网连接，需要另外加入“[Nintendo Switch Online](https://www.nintendo.com/jp/hardware/switch/onlineservice/index.html)”（收费）。
> {: #ref-8 }

##### 对于已下载的游戏，能否查看它的程序是如何组成的呢？
{: .question }

##### 手岛
当然。这是非常重要的一点。

##### 益田
我想会出现很多能够制作出充满魅力的游戏的人，即使只是下载他们制作的游戏也非常有趣，但我希望大家不仅玩游戏，也一定要看一下它的机制是什么样的，并试着模仿一下。

##### 对于同一个游戏，大家一起一点点改进，像这样的事情可以做到吗？
{: .question }

##### 益田
[下载下来的作品，也可以像课堂里制作的一样复制之后改编](https://www.nintendo.com/jp/interview/awuxa/movie/12.mp4){: .video-link }，因此可以在上面增加小节点，也可以在同一个游戏中减少小节点，或许可以更有效率地完成作品。

##### 挑战能否将复杂的程序简化，也是一种学习吧。
{: .question }

##### 益田
虽然有很广阔的可能性，但是在《第一次的游戏程序设计》中制作的游戏，其目的并不是和作为商品发售的游戏相提并论，也不应该局限于“游戏就应该是这样”的框架，我希望大家能够享受自由创作的乐趣。

##### 手岛
是啊。我觉得互联网上确实会有各种各样的作品出现。但是，我并不认为没有规则和动作就不算是游戏。

##### 益田
比如说，可以画很多喜欢的花来组成花田，也可以在游戏中加上UFO飞行的动画，我觉得仅仅是这样就已经非常不错了。

当然，把自己制作的作品给别人看，听听他们的感想，来制作更有趣的游戏吧！我觉得从这些事中获得动力也很重要，但更重要的是，希望大家能够享受自己动手获得的属于自己的发明和发现。

##### 希望大家能按照自己的想法来完成游戏，是这样的吧？
{: .question }

##### 手岛
是的，只要制作的人觉得是游戏的话，什么都可以是游戏！希望大家都能够享受属于自己的游戏，以及属于自己的发现。

##### 原来如此，我明白了，只要轻松地制作自己想要的东西就好。我很期待互联网上会出现什么游戏。
{: .question }

{% include figure.html src="https://www.nintendo.com/jp/interview/awuxa/img/4_2_T.jpg" width="640" height="360" %}

##### 手岛
我认为很多编程软件的重点都是最终“能做出什么样的有趣的作品”，也就是结果。

但是，在讨论这部软件的企划时，我们考虑到了在程序设计的过程中感受到的试错和发现的乐趣、完成一个作品本身的乐趣、以及程序设计本身的乐趣等。

因此，《第一次的游戏程序设计》着眼于“程序设计的乐趣”，我希望能够支持这份乐趣。

##### 所以就有了“附带导航！”吧。
{: .question }

##### 那么，最后请两位谈一谈希望什么样的玩家来玩吧。
{: .question }

##### 益田
完全不知道如何编程的人，连编程这个词是什么意思都不知道的人，或者是正在考虑培养孩子编程能力的人……我希望这些人能够尝试一下这部作品。

只要接触了《第一次的游戏程序设计》并愉快地一边玩游戏一边尝试制作游戏，我认为就可以自然地理解编程是什么。

##### 手岛
一听到程序设计，我想很多人会觉得“不知道从何开始”“总觉得不想开始”。为了这些人，我们准备了能够一直玩到游戏最后的“附带导航的课堂”。

而且，正如标题《第一次的游戏程序设计》所说，如果这部作品作为初次接触程序设计的起点，能够成为玩家开始编程的契机就好了。

##### 非常感谢。
{: .question }