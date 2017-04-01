# nodePPT 
focked from https://github.com/ksky521/nodePPT

## 在ksky521/nodePPT版本基础上做了部分修改，以符合我个人做slide的习惯
1. 分隔每页PPT的内容由[slide]改为---，这样使得在直接用typro这样的编辑器查看时，
  也是一篇正常的文档，而不是有很多多余的[slide]字符
2. 增加了一个主题easy，并把它作为默认主题。这个主题：
  - 以light主题为基础
  - 文字排版默认靠左

## 原始版本的一些功能将不被支持
1. 页内分隔符"---",不再支持，因为与slide分隔符冲突
2. 单页面的专场效果不再支持

## TODO
1. 图片文件的寻址路径与markdown文件相对路径一致，方便作为markdown文件分发
2. 左右两栏的排版，因为我的slide有时候需要左边图，右边文字这样的排版