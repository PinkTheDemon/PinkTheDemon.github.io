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
