---
layout: post
title: animation
tags: HTML5
categpry: HTML5
---

        这家伙好懒，什么都没有留下...
         

<html>
    <head>
        <meta charset="utf-8">
        <title>animation.html</title>
    </head>
    <body>
        <div id="divhead">
            <div id="ani1">
                <section>
                    <h6><span>寅</span>桃花庵歌</h6>
                        <div id="pd"><br/>桃花庵裹桃花仙</div>
                        <div id="pd">桃花坞裹桃花庵</div>
                </section>
            </div>
            <div id="ani1_1"></div>
            <div id="ani1_2"></div> 
        </div>
        <br/>
        <br/>                          
        <div id="ani2">
        </div>
        <style>
#divhead {position: fixed; left: 50%; padding: 50px;}
section h6{ text-align: center;padding-top: 7px; color: white; font-family: "楷体"}
section h6 span {font-size: 20px;font-family: "华文行楷"}
#pd { text-align:center;width: 25px; float: left; margin: 0; padding: 0; font-size: 20px;font-family: "楷体"}
#ani1 {
    width: 50px;
    height: 50px;
    position: relative;
    background-color: red;
    -webkit-animation-name: firstani;
    -webkit-animation-duration:20s;
    -webkit-animation-timing-function:linear;
    -webkit-animation-delay:1s;
    -webkit-animation-iteration-count:infinite;
    -webkit-animation-direction:alternate;
    -webkit-animation-play-state:running;
    -webkit-animation-fill-mode:none;
    -o-animation-name:firstani;
}

@keyframes firstani {
    0%   {top:0px;   left:0px; }
    8%   {top:0px;   left:150px;  background-color: orange;}
    10%  {top:50px;  left:150px;  background-color: yellow;}
    14%  {top:50px;  left:250px;  background-color: lime;}
    19%  {top:100px; left:350px;  background-color: #F08080;}/*组1*/
    20%  {top:100px; left:350px;  background-color: #F08080;}
    23%  {top:100px; left:400px;  background-color: orange;}
    26%  {top:50px;  left:400px;  background-color: yellow;}
    28%  {top:50px;  left:350px;  background-color: lime;}
    29%  {top:50px;  left:350px;  background-color: lime;}/*组1*/
    34%  {top:200px; left:275px;  background-color: #48D1CC;}
    38%  {top:150px; left:175px;  background-color: #1E90FF;}
    39%  {top:150px; left:175px;  background-color: #1E90FF;}
    46%  {top:200px; left:75px;   background-color: #9932CC;}
    50%  {top:300px; left:0px;    background-color: hotpink;}
    54%  {top:200px; left:-75px;  background-color: #9932CC;}
    61%  {top:150px; left:-175px; background-color: #1E90FF;}
    62%  {top:150px; left:-175px; background-color: #1E90FF;}
    66%  {top:200px; left:-275px; background-color: #48D1CC;}
    71%  {top:100px; left:-350px; background-color: #F08080;}/*组2*/
    72%  {top:100px; left:-350px; background-color: #F08080;}
    74%  {top:100px; left:-400px; background-color: orange;}
    77%  {top:50px;  left:-400px; background-color: yellow;}
    80%  {top:50px;  left:-350px; background-color: lime;}
    81%  {top:50px;  left:-350px; background-color: lime;}/*组2*/
    86%  {top:50px;  left:-250px; background-color: lime;}
    90%  {top:50px;  left:-150px; background-color: yellow;}
    92%  {top:0px;   left:-150px; background-color: orange;}
    100% {top:0px;   left:0px;    background-color: red;}
}

#ani1_1{
    height: 25px;
    width: 25px;
    position: relative;
    -o-animation-name:ani1;
    -webkit-animation-name:ani1;
    -webkit-animation-duration:20s;/*周期*/
    -webkit-animation-delay:1s;
    -webkit-animation-timing-function:linear;
    -webkit-animation-iteration-count:infinite;
    -webkit-animation-direction:alternate;
    -webkit-animation-play-state:running;
    /*-webkit-animation-fill-mode:;动画之外
    */
}

@keyframes ani1{
    0%   {top: 25px; left: 375px;}
    18%  {top: 25px; left: 375px; background-color: transparent;}
    19%  {top: 25px; left: 375px; background-color: #00BFFF;}
    28%  {top: 25px; left: 375px; background-color: #00BFFF;}
    29%  {top: 25px; left: 375px; background-color: transparent;}
    69%  {top: 25px; left: -375px; background-color: transparent;}/*开始*/
    72%  {top: 25px; left: -375px; background-color: #00BFFF;}
    81%  {top: 25px; left: -375px; background-color: #00BFFF;}
    82%  {top: 25px; left: -375px; background-color: transparent;}/*结束*/
    100% {top: 25px; left: -375px;}
}

#ani1_2{
    height: 25px;
    width: 25px;
    position: relative;
    -o-animation-name:ani2;
    -webkit-animation-name:ani2;
    -webkit-animation-duration:20s;/*周期*/
    -webkit-animation-delay:1s;
    -webkit-animation-timing-function:linear;
    -webkit-animation-iteration-count:infinite;
    -webkit-animation-direction:alternate;
    -webkit-animation-play-state:running;
    /*-webkit-animation-fill-mode:;动画之外
    */
}

@keyframes ani2{
    0%   {top: 25px; left: 325px; background-color: transparent;}
    18%  {top: 25px; left: 325px; background-color: transparent;}
    19%  {top: 25px; left: 325px; background-color: lime;}
    20%  {top: 25px; left: 325px; background-color: lime;}
    22%  {top: 25px; left: 375px; background-color: transparent;}
    23%  {top: 25px; left: 425px; background-color: orange;}
    24.5%  {top: -25px; left: 425px; background-color: transparent;}
    26%  {top: -75px; left: 425px; background-color: yellow;}
    27%  {top: -75px; left: 375px; background-color: transparent;}
    28%  {top: -75px; left: 325px; background-color: #F08080;}
    29%  {top: -75px; left: 325px; background-color: #F08080;}
    30%  {top: -75px; left: 325px; background-color: transparent;}
    70%  {top: 25px; left: -325px; background-color: transparent;}/*开始*/
    71%  {top: 25px; left: -325px; background-color: lime;}
    72%  {top: 25px; left: -325px; background-color: lime;}
    73%  {top: 25px; left: -375px; background-color: transparent;}
    74%  {top: 25px; left: -425px; background-color: orange;}
    75.5%  {top: -25px; left: -425px; background-color: transparent;}
    77%  {top: -75px; left: -425px; background-color: yellow;}
    78%  {top: -75px; left: -375px; background-color: transparent;}
    80%  {top: -75px; left: -325px; background-color: #F08080;}
    81%  {top: -75px; left: -325px; background-color: #F08080;}
    82%  {top: -75px; left: -325px; background-color: transparent;}/*结束*/
    100% {top: -75px; left: -325px; background-color: transparent;}
}


    
        </style>  
        <br/>  
        <br/>
    </body>
</html>

