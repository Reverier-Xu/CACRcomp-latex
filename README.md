# 中国密码技术竞赛作品赛 LaTeX模板

本仓库包含三个文件（夹），分别是：

- imgs：放图片
- template.tex：模板
- template.pdf：一切正常的情况下，模板编译出来的pdf应该长这样

## 使用说明

修改模板中的作品信息（一定记得修改左上角的作品编号与类别），然后往里面塞内容即可。

不需要手动写编号，也不需要手动改论文引用的数字，latex会自动添加的。

推荐使用XeLaTeX引擎进行编译，由于引擎bug，每次编译需要重复跑两次：

```shell
$ xelatex template.tex
...
$ xelatex template.tex
...
```

原因是第一次交叉引用信息不完全，只跑一次编译出来的PDF没有目录和论文引用。

## About

Licensed under MIT

```
Copyright (C) 2022 Reverier-Xu(reverier.xu@woooo.tech)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
