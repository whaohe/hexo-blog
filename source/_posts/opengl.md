---
title: opengl
date: 2018-05-20 13:21:13
tags:
---
总结了一些OpenGL的学习资源，备忘。<a id="more"></a>
** _[学习 OpenGL 用哪个版本好？](https://www.zhihu.com/question/22005157)_ **

### [](#学习网站推荐-特指-modern-opengl-的学习，即OpenGL-3-0-以上，-和-可编程渲染流水线-： "学习网站推荐(特指 modern opengl 的学习，即OpenGL 3.0 以上， 和 可编程渲染流水线)：")学习网站推荐(特指 modern opengl 的学习，即OpenGL 3.0 以上， 和 可编程渲染流水线)：

1.[https://learnopengl.com/](https://learnopengl.com/)
2.[https://www.gamedev.net/resources/_/technical/opengl/opengl-33-tutorials-r3754](https://www.gamedev.net/resources/_/technical/opengl/opengl-33-tutorials-r3754)
3.[http://www.opengl-tutorial.org/](http://www.opengl-tutorial.org/)
4.[https://alfonse.bitbucket.io/oldtut/](https://alfonse.bitbucket.io/oldtut/)
5.[http://mbsoftworks.sk/index.php?page=tutorials](http://mbsoftworks.sk/index.php?page=tutorials)
6.[http://huangwei.pro/categories/modern-opengl-tutorials/](http://huangwei.pro/categories/modern-opengl-tutorials/)
7.[https://www.google.com/?gfe_rd=cr&amp;ei=sTC7V8ybBarP8geWmqyADg#newwindow=1&amp;q=%E7%8E%B0%E4%BB%A3OpenGL](https://www.google.com/?gfe_rd=cr&amp;ei=sTC7V8ybBarP8geWmqyADg#newwindow=1&amp;q=%E7%8E%B0%E4%BB%A3OpenGL)
8.[http://wiki.jikexueyuan.com/project/modern-opengl-tutorial/tutorial1.html](http://wiki.jikexueyuan.com/project/modern-opengl-tutorial/tutorial1.html)
9.[https://my.oschina.net/sweetdark/blog?disp=1&amp;catalog=386026&amp;sort=time&amp;p=1](https://my.oschina.net/sweetdark/blog?disp=1&amp;catalog=386026&amp;sort=time&amp;p=1)

### [](#图形学 "图形学")图形学

1.[http://www.scratchapixel.com](http://www.scratchapixel.com)

> ### [](#建议先把图形学的一些基本原理给搞明白 "建议先把图形学的一些基本原理给搞明白")建议先把图形学的一些基本原理给搞明白
> 
> 其中个人，以及所有我认识的搞图形学的人一致认为十分重要、强调一万分都不为过的两个知识点是：
> 1.OpenGL渲染管线！！！！！！
> 2.物体-世界-相机-裁剪-视口 坐标变换！！！！！！
> 毕竟OpenGL只是个API，是工具，把原理搞明白了，理解了，工具上手会快很多。即便你将来想转DirectX也就是换个API，换汤不换药，大致思想是一致的。
> 另外要看书的话，红宝和蓝宝书早期版本以固定管线为例讲解的就可以不要看了，直接从shader搞起吧。
> 
> ### [](#入门用NEHE的建议 "入门用NEHE的建议")入门用NEHE的建议
> 
> 虽然十分经典，但经典也意味着老旧，全是固定管线内容，且不成体系。如果需要和一些固定管线的老代码打交道，那NEHE还是值得一看的。
> 至少从GL 2.0看起（目前已经4.3了）。一定得熟悉VAO/VBO/FBO等等。我曾耗费很多时间学固定管线，但学了shader后才感觉走上了正道，才是真正地零距离接触到了pipeline。当你去自己生成MVP、自己实现Phong Shading时，和简单的用一下glTranslatef, glLightfv这些API的感觉是不一样的
> OpenGL蓝宝书已有第六版，红宝书有第八版，均完全剔除固定管线内容，全面介绍shading language。
> 
> ### [](#个人觉得，必须需要学习的一些基础知识包括： "个人觉得，必须需要学习的一些基础知识包括：")个人觉得，必须需要学习的一些基础知识包括：
> 
> （1）model，view，projection 变换；
> （2）和几何变换对应的矩阵和向量的运算。cross，dot 等。
> （3）渲染 pipeline 的流程，各个阶段的职责工作。
> （4）depth 缓冲。
> 
> ### [](#入门第一步：CG语言与GPU的概念 "入门第一步：CG语言与GPU的概念")入门第一步：CG语言与GPU的概念
> 
> 不了解硬件就去给硬件编程简直就是在耍流氓。
> 看下这一本吧：
> 《GPU 编程与CG 语言之阳春白雪下里巴人》
