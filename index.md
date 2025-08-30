## 欢迎来到我的主页

目前我还没有很多项目，所以其实主页上也不知道要放些什么，所以暂时先这样吧。

后面的内容先让它们保持默认的样子好了。

结果好像一上来就踩坑了www，为什么我的.md文件不会被自动变换成网页格式！

我还不会html语言所以其实也没什么办法，只能以后有空再慢慢调整了...

好像没事了，没有被自动变换应该只是更新的比较慢罢了。

另外还看到别人有把域名添加到记录集，我也不知道怎么操作，甚至不知道有什么用w

### 踩坑记录

2022/08/16

我的git默认分支名是master，但当时在github上创建主页的时候它给我的默认分支名是main，虽然在git上成功根据分支名把主页项目拉取到本地了，但VScode的默认分支名也是master，于是没办法在那里推送...不过好在目前主页只会写.md文件，暂时应该不会添加什么别的文件，直接用Typora编辑然后用git推送就好了，不用VScode也没关系。

push失败了，其实原因是因为git默认分支是master，push的时候虽然指定了分支名为main但好像没起作用，第一次百度看有说是因为没有README文件，我还真信了，创建了一个可能没什么用的README，然后发现还是失败。又去百度才发现是因为默认分支的问题，于是把git的默认分支也改成main了，就成功了。

```markdown
git branch -m master main
```

所以我还是先把README删掉吧。

然后发现当我把git的默认分支修改为main之后，VScode的默认分支也同样被修改为code了。所以第三次提交是为了测试VScode的推送是否可行。结果是不可行，报错：

```
Please make sure you have the correct access rights and the repository exists.
```

百度说是因为.ssh出问题了，但我保持怀疑，用git推送如果没问题那就应该不是公钥的问题。

然后又是经典的VScode报错Permission denied (publickey)。我记得上次解决这个问题并没有在.ssh文件夹中加什么config，但具体怎么解决的忘记了，所以先观望一段时间。

这次的解决方案是先在VScode终端中用git命令推送一次（会要密码），然后就可以直接在VScode左边栏里面快捷操作了。也是不对的。

暂时的解决方案是用网址推送而不是ssh：

```
git remote set-url origin https://github.com/******.git
```

### 碎碎念日记

2022/08/18

今天又是需要汇报的日子，上午把没看完的论文看了看，10点就开始困了，半梦半醒总之到了10点半，想干点啥又不想继续看论文了，就想着干脆来更新一下主页吧。

最近有点热度的番莉可丽丝还没开始看，想等个自由点的时间再看。昨天组了一套DDD卡组也还没上手试试。感觉记录这些是不是有点太杂了www，不过反正现在主页也没人看，干脆想写啥就写啥呗。

不知道能不能在主页加上直接发布和回复的功能，这是不是要学一下html语言呢？感觉总是会用到的，其实看看学学应该也还不错。而且粉红恶魔的个人主页居然是蓝色的，是不是有点不符合呢w

但是如果要用html来写的话，网站好像就需要自己动手从头搭建了，总之首先先搭个框架出来吧。等等，我是不是直接在github自动创建的页面上F12把代码copy下来就可以了？从零开始的复制粘贴教程开始！

不知道默认会以.md文件为主还是以.html文件为主呢？总之先上传！

看来默认是.html文件，那这边就只用来记录吧，然后同步到那边，有点像目标网络呢。总之正式开始网页开发啦！首先是换背景！

<p>2022/08/19</p>

<p>这两天趁着老师不在办公室，偷偷看了一点html的教学视频。不过说真的，那个教程真就面向电脑小白啊，虽然讲得巨详细但是在我看来废话挺多的就是了...</p>

<p>然后至于又来更新的理由，是因为下午老师来办公室了，没办法看视频，又不想看论文，就来把之前在.md文件里面写的内容同步过来了。</p>

<p>说起来，DDD卡组还真有点复杂，一时间玩不明白，干脆又分了几张卡合了大宇宙人和虚无空间玩鸟去了，虽然内战有点坐牢但打别的卡组基本上对面看你能展开就跑了ww，上分虽然卡手不顺但还是挺快乐的。</p>

<p>2022/08/22</p>

<p>好困，完全没法看论文，一看就想闭眼。但其实也没啥想更新的内容，浅浅记录一下周末行程吧。</p>

<p>上周六下午来了实验室，结果老师也在，本来打算把doubleQ剩下的部分敲完就开摆的，只好继续敲PER，今天才半成，PER跑起来巨慢，可能因为每一个episode都要额外进行很多操作，然而性能又没有什么提升，可能还没触及它的优势区。</p>

<p>周日去同学家打了一下午卡五星，有点意思，但就是有点没意思。</p>

<p>发现之前下载的世界计划缤纷舞台真的是养成类音游，主要是真的有miku，不过我三档hard难度full combo你就只给我c的评级？感情分数不考打歌全靠养成是吧...</p>

<p>2022/09/15</p>

<p>很久没有更新了，已经上了三周课了。在中秋看好了房，之后一天搬出去一个人住了。那天晚上跟汪和胡吃了个饭，还射了箭，挺有意思。</p>

<p>一个人住也已经好几天了，感觉还挺棒，总之起码睡得很舒服，头不疼了腰背也不疼了。</p>

<p>但还是很可惜地没能完全平安无事，得了带状疱疹，第一天打针还因为中午没吃饱而头晕，第二天医生给我把吊水换成了口服，现在可见光治疗做完了，肌肉针也打完了，明天看情况要不要去复查吧。</p>

<p>2023/04/04</p>

<p>暑假结束，开学生病，搬出去住之后，好像就开始摆烂了，起起伏伏几阵，现在状态也算不上好，心态是比较积极，但不那么向上了，好像没有动力学习和工作。</p>

<p>3月新认识一个朋友，说来也是机缘巧合，她在海底捞跟捞面师傅学捞面，我就觉得这人肯定很有趣，然后被怂恿着加了微信，但后续才知道她原来是以前在海底捞做过兼职。</p>

<p>说起来，今天想着来记录的事情是午睡时候做的梦。这次算是梦到了死亡的过程吧，躺在马路边上，汽车从头顶疾驰而过，有点害怕但又没办法移动身体，眼前是雨后树上的樱花（或许是海棠花？毕竟现在正是海棠花的季节）。
   雨水冲刷掉空气中的灰尘之后，色彩也变得鲜明起来，冷色调的环境，配上粉红色的花，感觉还挺浪漫。只不过视野变得模糊起来，从右眼开始，出现一团黑色，逐渐什么也看不见了，接着就醒过来了。
</p>

<p>2025/08/31</p>

<p>时隔多年的更新。</p>

<p>今天无意间点开了当时创建的个人主页，其实我一直都没有忘记，但是就是不想点开，今天手滑点开了，或许也是缘分。</p>

<p>已经上班一个多月了，感觉上班累是累，但是心态比较轻松，比起读研时候还是好不少。</p>

<p>另外，跟女朋友的恋爱时长都已经有582天了，从2024.1.28确定关系以来，这一路走得不算一帆风顺，但好歹现阶段状态保持的不错，估计今年过年就能见家长了。</p>

<p>今天也算是一个复活更新，也许后面还会不定期更新碎碎念日常。</p>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/PinkTheDemon/PinkTheDemon.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
