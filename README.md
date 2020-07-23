xelatex-guide-book
==================

## 更新日志

### 第四次修订版

1. 引入epub书籍兼容制作流程。
2. Texlive升级到2020版，有一两处小bug，已修复。
3. 其他问题完善

### 第三次修订版

数学模式内容极大丰富和完善。



## 补充信息
临时有些补充信息就先方便放在readme这里了。



### tikz制图
tikz制图专门做了一个gallery项目，请点击 [这里](https://github.com/a358003542/tikz_gallery)。

### 字体推荐

现在 google 和adobe 合作开发的开源字体 思源宋体和思源黑体很火，推荐使用这两个字体，效果还是不错的。读者可以到他们的 [官网](https://source.typekit.com/source-han-serif/cn/) 上看一下，github地址在 [这里](https://github.com/adobe-fonts/source-han-serif) ，不过下载要1G多，也可以到 [百度网盘这里](https://pan.baidu.com/s/1smo7EMD) 下载，这是我整理的一些字体。具体配置如下：

```latex
\setCJKmainfont[ItalicFont=方正楷体简体]{思源宋体 CN}
\setCJKsansfont{思源黑体 CN}
\setCJKmonofont{方正楷体简体}
```

其中思源宋体 CN没有italic shape，如上指定为方正楷体简体，方正楷体简体也是开源的。经过试验效果还是挺好的，整个字体给人的感觉简约大气。经过编译还有一个warning：没有sc shape，什么small caps 字形，这个思源宋体 CN也没有，但那个small caps字形太不常用了，所以不用管也是可以的。

**windows 下安装字体记得点击为所有用户安装，新安装字体没发现后来折腾了好久，最后发现是没有选择为所有用户安装。xetex是能够自动使用系统安装好了的字体的，然后记得运行下 fc-cache即可。**

## 内容简介


我試圖收集整理各方面來的xelatex相關的信息，包括自己的實踐經驗總結，作爲後學者的指南手冊。

1. xelatex指南.pdf

本项目文章主体部分。

2. texmf 文件夹 

整个复制到ubuntu主目录即可使用。

3. 制作幻灯片

里面有些初步的制作幻灯片的样例。

 4. tikz制图

有段时间我沉迷于此，里面有很多tikz制图的样例。

 5. exam类

如何制作试卷，如何制作讲义

6. endnotes宏包

制作尾注的一个宏包



