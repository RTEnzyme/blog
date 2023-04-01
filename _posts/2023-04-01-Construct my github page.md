---
title: "Construct my github page"
date: 2023-04-01
---

# 1. Theme
我采用了许多开源的博客脚手架和一些小组件。
- [Tomotoes-HomePage](https://github.com/Tomotoes/HomePage) for [](https://rtenzyme.github.io)
- [react-terminal](https://github.com/Tomotoes/react-terminal) for [](https://rtenzyme.github.io/about)
- [github-pages](https://github.com/skills/github-pages) for [](https://rtenzyme.github.io/blog)

# 1. The main page
选择[Tomotoes-HomePage](https://github.com/Tomotoes/HomePage)的原因是它看上去挺cool的。并且我对主页面的考量是用一个主页面串起来多个页面。所以可以看到除了[](http://github.com/RTEnzyme/rtenzyme.github.io)，我还有其他两两个仓库分别用来构建`/about`和`/blog`两个子页面。

这个framework的构建，主要需要node.js构建。具体来说有以下的步骤：
```shell
git clone https://github.com/Tomotoes/HomePage.git
cd HomePage
npm install
npm run dev
```

在`build`之前，需要在相应的配置页面进行客制化。并且换上自己的头像照片。

# 2. Terminal for about
在看别人的博客时，看到了个用Terminal交互来进行自我介绍的页面。由于我本来也是命令行的重度使用人士，所以十分心动。所以将该Terminal集成到了我的github page中。由于它源文件只是个`react`的组件，所以将其集成到`react`应用中对我这个react小白来说还是不简单的。

不过经过一段时间的debug，还是成功集成到了页面中。该Terminal首先会弹出一些我个人的基础信息。然后可以通过一些命令，来进一步地了解我的一些信息。

# 3. Blog 
Blog页面我用的非常简约的页面，我的考量是blog是为了输出知识，读者的注意力不应该被华丽的UI所吸引。所以我采用了[](https://jekyllrb.com/)中最简洁的主题。

写blog的话，便可以通过在repository中的`_posts`目录下用Markdown格式进行书写。所以Blog写起来还是挺容易的。

# 4. 感想
在完成 OSS101 课程作业的过程中，我搭建了自己的个人主页，并且使用 GitHub Pages 进行了部署。这是我第一次尝试搭建个人网站，虽然在过程中遇到了一些困难，但最终我成功地完成了这个任务。

通过这个项目，我学习了如何使用 Git 和 GitHub 来管理自己的代码，并且学习了如何使用 Jekyll 来搭建静态网站。我还学会了如何使用 HTML 和 CSS 来设计和布局网站，并使用了一些开源工具和主题来美化我的网站。

搭建个人主页的过程中，我发现最重要的是耐心和实践。尽管我没有任何前端开发的经验，但是我在遇到问题时，通过谷歌搜索和 Stack Overflow 等工具，一步步解决了问题，并且不断地实践和调试。最终，我的个人主页变得越来越美观和功能强大。

通过这个项目，我不仅学到了如何搭建个人主页，更重要的是，我学会了如何克服困难和挑战自己的能力。在这个过程中，我深深感受到了开源软件的力量和魅力，也更加珍视和尊重开源社区的精神和价值观。
