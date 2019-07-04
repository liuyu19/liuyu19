---
title: SVG之跳动的圆
excerpt_separator: "<!--more-->"
categories: 
  - SVG制作
tags:
  - SVG
---
### 跳动的圆！
这个圆有呼吸效果，而且可以旋转变大。
<!--more-->
<section class="page__content" itemprop="text">

    <head>
		<style type="text/css"><div> svg{
    width: 400px;
    height: 400px;
     -webkit-transition: -webkit-transform 1s, width 1.5s, height 2s;
    transition: width 3s, height 1.8s, transform 2.5s;}svg:hover {
    width:400px;
    height:400px;
    -webkit-transform: rotateX(1600deg);
    transform: rotateY(1600deg);
    color:blue;}</div></style>
    </head>
    <body>
    <svg width="400" height="400">
    <circle cx="200" cy="200" r="50" style="fill:#ff6600" >
        <animate
                attributeName="r"
                attributeType="XML"
                from="50"
                to="80"
                begin="0s"
                dur=".5s"
                repeatCount="indefinite"
        />
    </circle>
     </svg>
     <div style="width: 0px; height: 0px; overflow: hidden">
     </div>
    </body>
    <div style="width: 0px; height: 0px; overflow: hidden">
    <iframe src="https://isux.tencent.com/articles/isux-table-border.html" frameborder="0"></iframe>
    <iframe src="https://isux.tencent.com/articles/web-image-application.html" frameborder="0"></iframe>
    </div>
    </body>

