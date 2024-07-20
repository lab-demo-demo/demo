- 网站搭建
  - [保姆级教程：从零构建GitHub Pages静态网站-CSDN博客](https://blog.csdn.net/qq_20042935/article/details/133920722)
- 界面渲染
  - [Installation | Jekyll • Simple, blog-aware, static sites (jekyllrb.com)](https://jekyllrb.com/docs/installation/)
  - [Adding a theme to your GitHub Pages site using Jekyll - GitHub Docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
  - [如何使用Jekyll在GitHub Pages上搭建网站（个人博客）_jekyll github-CSDN博客](https://blog.csdn.net/qq_33919450/article/details/127859193)
- Organization
  - [超详细！Github团队协作教程（Gitkraken版） - thousfeet - 博客园 (cnblogs.com)](https://www.cnblogs.com/thousfeet/p/7840932.html)



界面渲染可以从简,也就是按照类似["FEMU闪存仿真平台介绍及使用文档"\] (nnss-hascode.github.io)](https://nnss-hascode.github.io/FEMU-Doc/FEMU-Doc.html)中一样, 通过remote-jekyll的主题来自动地从md文件转换为html文件,可以不用在本地进行网页的调试, 如果需要进行侧边栏, 主题页选择等工作, 就还是需要通过jekyll的文档进行构建, 即这里只是一个孤立的静态页面



TODO:

1. 按照教程中的方法, 构造出来的静态页面地址是 https://han-yyds.github.io/han_circle.github.io/demo.html, 也就是说这里存在冗余的路径名, 而在FFMU中是没有的
   1. 如果把repo的名字改成demo, 则https://han-yyds.github.io/demo/demo.html 能够访问到, 所以只要是我的仓库基于github.io即可? 再造一个repo试试
   2. 新建repo需要设置pages, 选择公开root分支即可, 但是现在所构造出来的网站都是基于我的个人io, 如何选择其他io?
2. FFMU中大概是一个两层的结构, Lab/Doc, 每个Doc都是一个repo, Lab应该是一个Organization?
3. 

