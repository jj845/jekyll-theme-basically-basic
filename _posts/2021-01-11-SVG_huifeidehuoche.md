---
title: svg之会飞的火车
excerpt_separator: "<!--more-->"
categories: _ SVG笔记
tags:
  -svg
---
#### 点击看详情哦~

<!--more-->
#### 会飞起来的svg你见过吗~

#### 下面是源代码
```
<div class="content">
    <svg id="scene" viewBox="0 0 400 400">
      <defs id="">
        <linearGradient id="linearGradient5176">
          <stop id="stop5172" offset="0" stop-color="#f5b26a" stop-opacity="1"></stop>
          <stop id="stop5174" offset="1" stop-color="#ff8500" stop-opacity="1"></stop>
        </linearGradient>
        <linearGradient id="linearGradient5160">
          <stop id="stop5156" offset="0" stop-color="#fff" stop-opacity="1"></stop>
          <stop id="stop5158" offset="1" stop-color="#ffac51" stop-opacity="1"></stop>
        </linearGradient>
        <linearGradient id="linearGradient5170" x1="599.978" x2="588.571" y1="998.09" y2="671.091" gradientTransform="translate(0 -722.52)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5176"></linearGradient>
        <linearGradient id="linearGradient5162-3" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="translate(230.404 -837.437) scale(1.14166)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
        <linearGradient id="linearGradient5162-35" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="matrix(.64392 0 0 .64392 602.087 -407.364)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
        <linearGradient id="linearGradient5162-35-1" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="matrix(.64392 0 0 .64392 199.73 -380.821)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
      </defs>
      <g id="background" class="background background-animation">
        <path id="rect1437" fill="url(#linearGradient5170)" fill-opacity="1" stroke="none" stroke-dasharray="none" stroke-miterlimit="4" stroke-opacity="1" stroke-width="17.213" d="M0 0h1200v400H0z" opacity="1"></path>
        <path id="mountains" fill="#c5563e" fill-opacity="1" stroke="none" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width="2.021" d="M460 110l-60 70H0l1.01 191.248C-.312 380.025-1 389.264-1 399h1197.978v-.01h2.012c-.28-.33-.762-218.46 1.01-218.99 0 0-420 0-426.516 2.05L680 80l-76.943 92.756-32.272-15.494-22.185 13.427z"></path>
        <path id="path16-5" fill="url(#linearGradient5162-3)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width="1.142" d="M480.312 39.1c14.823-8.843 17.322 7.185 34.25 11.417 17.168-10.212 17.999-.772 34.25 11.417H428.938c9.704-9.985 10.639-20.662 18.22-23.91 6.932-2.968 20.29 1.077 33.154 1.077z" class="cloud"></path>
        <path id="path16-9" fill="url(#linearGradient5162-35)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".644" d="M743.04 87.019c8.36-4.989 9.769 4.052 19.317 6.439 9.683-5.76 10.151-.436 19.317 6.439h-67.611c5.474-5.632 6-11.654 10.277-13.485 3.91-1.675 11.444.607 18.7.607z" class="cloud"></path>
        <path id="path16-9-0" fill="url(#linearGradient5162-35-1)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".644" d="M340.682 113.56c8.36-4.987 9.77 4.053 19.318 6.44 9.683-5.76 10.151-.435 19.317 6.44h-67.611c5.474-5.633 6-11.654 10.277-13.486 3.91-1.674 11.444.607 18.7.607z" class="cloud"></path>
      </g>
      <g id="foreground" stroke-dasharray="none" stroke-miterlimit="4" class="foreground foreground-animation">
        <path id="rect5875" fill="#8b413e" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="17.199" d="M0 315.071h1200v40H0z" opacity="1"></path>
        <path id="rect5877" fill="none" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="19.625" d="M0 353.943h1175.29v35.751H0z" opacity="1"></path>
        <path id="rect5881" fill="#f8a04e" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="18.378" d="M0 355.701h1200V400H0z" opacity="1"></path>
        <path id="path5904" fill="none" stroke="#fff" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".785" d="M430.23 372.997l56.005.992"></path>
        <path id="path5906" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity="1" stroke-width=".785" d="M465.915 381.918l64.43-1.486" opacity="1"></path>
        <path id="path5908" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M537.002 363.58h34.693" opacity="1"></path>
        <path id="path5910" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M579.625 370.518l41.135 1.488" opacity="1"></path>
        <path id="path5912" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M622.247 379.44l69.386.992" opacity="1"></path>
        <path id="path5914" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M751.602 378.945l48.074.989" opacity="1"></path>
        <path id="path5918" fill="#f8a04e" fill-opacity=".579" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M1041.534 367.546l64.925.992" opacity=".291"></path>
        <path id="path5920" fill="#f8a04e" fill-opacity=".579" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M1058.88 376.961l-48.57-2.479" opacity=".291"></path>
        <path id="path5918-9" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M215.075 367.008L280 368" opacity=".244"></path>
        <path id="path5920-3" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M232.421 376.423l-48.57-2.479" opacity=".244"></path>
      </g>
      <g id="train" fill-opacity="1" stroke="none" stroke-dasharray="none" stroke-miterlimit="2" transform="translate(100,100)">
		   <text id="TextElement" x="0" y="0" style="font-family:Verdana;font-size:24; visibility:hidden"> 
      <set attributeName="visibility" attributeType="CSS" to="visible" begin="1s" dur="5s" fill="freeze"></set>
      <animateMotion path="M 0 0 L 100 100" begin="1s" dur="5s" fill="freeze"></animateMotion>
      <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="-30" to="0" begin="1s" dur="5s" fill="freeze"></animateTransform> 
      <animateTransform attributeName="transform" attributeType="XML" type="scale" from="1" to="3" additive="sum" begin="1s" dur="5s" fill="freeze"></animateTransform> 
    </text> 
  
        <path id="rect9910" fill="#21e6f0" stroke-opacity="1" stroke-width="3" d="M117.669 300.574H280.52v9.047H117.669z" opacity="1"></path>
        <circle id="path4897" cx="56.112" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3" cx="97.027" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6" cx="300.598" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7" cx="345.598" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847" fill="#59353b" stroke-opacity="1" stroke-width="3.457" d="M0 228.474h400v75.309H0z" opacity="1"></path>
        <path id="rect9851" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M16.741 245.292h26.808v24.98H16.741z" opacity="1"></path>
        <path id="rect9851-5" fill="#7FFF00" stroke-opacity="1" stroke-width="3.412" d="M58.781 245.597h26.808v24.98H58.781z" opacity="1"></path>
        <path id="rect9851-3" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M100.821 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M142.861 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M184.291 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M226.941 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M268.981 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M310.899 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M351.233 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M0 220.811h400v8.639H0z" opacity="1"></path>
        <path id="rect9910-4" fill="#59353b" stroke-opacity="1" stroke-width="3.412" d="M-292.331 300.574h162.851v9.047h-162.851z" opacity="1"></path>
        <circle id="path4897-5" cx="-353.888" cy="306.724" r="12.276" fill="#3c2222" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3-0" cx="-312.973" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6-3" cx="-109.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7-6" cx="-64.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847-1" fill="#008000" stroke-opacity="1" stroke-width="3.457" d="M-410 228.474h400v75.309h-400z" opacity="1"></path>
        <path id="rect9851-06" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-393.259 245.292h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-5-3" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-351.219 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-3-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-309.179 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56-0" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-267.139 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2-6" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-225.709 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9-1" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-183.059 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1-5" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-141.019 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27-5" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-99.101 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0-4" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-58.767 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976-7" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M-410 220.811h400v8.639h-400z" opacity="1"></path>
        <path id="rect9910-4-6" fill="#59353b" stroke-opacity="1" stroke-width="3.412" d="M-702.331 300.574h162.851v9.047h-162.851z" opacity="1"></path>
        <circle id="path4897-5-5" cx="-763.888" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3-0-6" cx="-722.973" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6-3-9" cx="-519.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7-6-3" cx="-474.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847-1-7" fill="#F0FFF0" stroke-opacity="1" stroke-width="3.457" d="M-820 228.474h400v75.309h-400z" opacity="1"></path>
        <path id="rect9851-06-4" fill="#32CD32" stroke-opacity="1" stroke-width="3.412" d="M-803.259 245.292h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-5-3-5" fill="#7FF000" stroke-opacity="1" stroke-width="3.412" d="M-761.219 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-3-2-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-719.179 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56-0-5" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-677.139 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2-6-4" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-635.708 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9-1-7" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-593.059 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1-5-4" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-551.019 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27-5-4" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-509.101 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0-4-3" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-468.767 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976-7-0" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M-820 220.811h400v8.639h-400z" opacity="1"></path>
      </g>

   
  
    </svg>
  </div>
  ```
  <head>
 <meta charset="utf-8">
 <style>
 
	/* Check out my article on how to create this: https://roboleary.net/css/2020/11/17/parallax-animation.html */
* {
  box-sizing: border-box;
}

body {
  background-color: rgb(197, 217, 255);
  overflow-x: auto;
}

.content {
  position: relative;
  height: 200px;
  width: 200px;
  margin: 60px auto;
}

#scene {
  position: absolute;
  height: inherit;
}

#background {
  animation: background-shift 8s linear infinite forwards;
}

#train {
  animation: train-shift 4s linear infinite forwards;
}

#foreground {
  animation: foreground-shift 2s linear infinite forwards;
}

@keyframes background-shift {
  to {
    transform: translateX(-800px);
  }
}

@keyframes train-shift {
  to {
    transform: translateX(820px);
  }
}

@keyframes foreground-shift {
  to {
    transform: translateX(-800px);
  }
}

	</style>
</head>
<body>

 <div class="content">
    <svg id="scene" viewBox="0 0 400 400">
      <defs id="">
        <linearGradient id="linearGradient5176">
          <stop id="stop5172" offset="0" stop-color="#f5b26a" stop-opacity="1"></stop>
          <stop id="stop5174" offset="1" stop-color="#ff8500" stop-opacity="1"></stop>
        </linearGradient>
        <linearGradient id="linearGradient5160">
          <stop id="stop5156" offset="0" stop-color="#fff" stop-opacity="1"></stop>
          <stop id="stop5158" offset="1" stop-color="#ffac51" stop-opacity="1"></stop>
        </linearGradient>
        <linearGradient id="linearGradient5170" x1="599.978" x2="588.571" y1="998.09" y2="671.091" gradientTransform="translate(0 -722.52)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5176"></linearGradient>
        <linearGradient id="linearGradient5162-3" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="translate(230.404 -837.437) scale(1.14166)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
        <linearGradient id="linearGradient5162-35" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="matrix(.64392 0 0 .64392 602.087 -407.364)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
        <linearGradient id="linearGradient5162-35-1" x1="216.83" x2="216.878" y1="788.242" y2="781.411" gradientTransform="matrix(.64392 0 0 .64392 199.73 -380.821)" gradientUnits="userSpaceOnUse" xlink:href="#linearGradient5160"></linearGradient>
      </defs>
      <g id="background" class="background background-animation">
        <path id="rect1437" fill="url(#linearGradient5170)" fill-opacity="1" stroke="none" stroke-dasharray="none" stroke-miterlimit="4" stroke-opacity="1" stroke-width="17.213" d="M0 0h1200v400H0z" opacity="1"></path>
        <path id="mountains" fill="#c5563e" fill-opacity="1" stroke="none" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width="2.021" d="M460 110l-60 70H0l1.01 191.248C-.312 380.025-1 389.264-1 399h1197.978v-.01h2.012c-.28-.33-.762-218.46 1.01-218.99 0 0-420 0-426.516 2.05L680 80l-76.943 92.756-32.272-15.494-22.185 13.427z"></path>
        <path id="path16-5" fill="url(#linearGradient5162-3)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width="1.142" d="M480.312 39.1c14.823-8.843 17.322 7.185 34.25 11.417 17.168-10.212 17.999-.772 34.25 11.417H428.938c9.704-9.985 10.639-20.662 18.22-23.91 6.932-2.968 20.29 1.077 33.154 1.077z" class="cloud"></path>
        <path id="path16-9" fill="url(#linearGradient5162-35)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".644" d="M743.04 87.019c8.36-4.989 9.769 4.052 19.317 6.439 9.683-5.76 10.151-.436 19.317 6.439h-67.611c5.474-5.632 6-11.654 10.277-13.485 3.91-1.675 11.444.607 18.7.607z" class="cloud"></path>
        <path id="path16-9-0" fill="url(#linearGradient5162-35-1)" fill-opacity="1" stroke="#ff8300" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".644" d="M340.682 113.56c8.36-4.987 9.77 4.053 19.318 6.44 9.683-5.76 10.151-.435 19.317 6.44h-67.611c5.474-5.633 6-11.654 10.277-13.486 3.91-1.674 11.444.607 18.7.607z" class="cloud"></path>
      </g>
      <g id="foreground" stroke-dasharray="none" stroke-miterlimit="4" class="foreground foreground-animation">
        <path id="rect5875" fill="#8b413e" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="17.199" d="M0 315.071h1200v40H0z" opacity="1"></path>
        <path id="rect5877" fill="none" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="19.625" d="M0 353.943h1175.29v35.751H0z" opacity="1"></path>
        <path id="rect5881" fill="#f8a04e" fill-opacity="1" stroke="none" stroke-opacity="1" stroke-width="18.378" d="M0 355.701h1200V400H0z" opacity="1"></path>
        <path id="path5904" fill="none" stroke="#fff" stroke-linecap="butt" stroke-linejoin="miter" stroke-opacity="1" stroke-width=".785" d="M430.23 372.997l56.005.992"></path>
        <path id="path5906" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity="1" stroke-width=".785" d="M465.915 381.918l64.43-1.486" opacity="1"></path>
        <path id="path5908" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M537.002 363.58h34.693" opacity="1"></path>
        <path id="path5910" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M579.625 370.518l41.135 1.488" opacity="1"></path>
        <path id="path5912" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M622.247 379.44l69.386.992" opacity="1"></path>
        <path id="path5914" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M751.602 378.945l48.074.989" opacity="1"></path>
        <path id="path5918" fill="#f8a04e" fill-opacity=".579" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M1041.534 367.546l64.925.992" opacity=".291"></path>
        <path id="path5920" fill="#f8a04e" fill-opacity=".579" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M1058.88 376.961l-48.57-2.479" opacity=".291"></path>
        <path id="path5918-9" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M215.075 367.008L280 368" opacity=".244"></path>
        <path id="path5920-3" fill="#f8a04e" fill-opacity=".506" stroke="#fff" stroke-opacity=".639" stroke-width=".785" d="M232.421 376.423l-48.57-2.479" opacity=".244"></path>
      </g>
      <g id="train" fill-opacity="1" stroke="none" stroke-dasharray="none" stroke-miterlimit="2" transform="translate(100,100)">
		   <text id="TextElement" x="0" y="0" style="font-family:Verdana;font-size:24; visibility:hidden"> 
      <set attributeName="visibility" attributeType="CSS" to="visible" begin="1s" dur="5s" fill="freeze"></set>
      <animateMotion path="M 0 0 L 100 100" begin="1s" dur="5s" fill="freeze"></animateMotion>
      <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="-30" to="0" begin="1s" dur="5s" fill="freeze"></animateTransform> 
      <animateTransform attributeName="transform" attributeType="XML" type="scale" from="1" to="3" additive="sum" begin="1s" dur="5s" fill="freeze"></animateTransform> 
    </text> 
  
<path id="rect9910" fill="#21e6f0" stroke-opacity="1" stroke-width="3" d="M117.669 300.574H280.52v9.047H117.669z" opacity="1"></path>
        <circle id="path4897" cx="56.112" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3" cx="97.027" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6" cx="300.598" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7" cx="345.598" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847" fill="#59353b" stroke-opacity="1" stroke-width="3.457" d="M0 228.474h400v75.309H0z" opacity="1"></path>
        <path id="rect9851" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M16.741 245.292h26.808v24.98H16.741z" opacity="1"></path>
        <path id="rect9851-5" fill="#7FFF00" stroke-opacity="1" stroke-width="3.412" d="M58.781 245.597h26.808v24.98H58.781z" opacity="1"></path>
        <path id="rect9851-3" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M100.821 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M142.861 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M184.291 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M226.941 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M268.981 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M310.899 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M351.233 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M0 220.811h400v8.639H0z" opacity="1"></path>
        <path id="rect9910-4" fill="#59353b" stroke-opacity="1" stroke-width="3.412" d="M-292.331 300.574h162.851v9.047h-162.851z" opacity="1"></path>
        <circle id="path4897-5" cx="-353.888" cy="306.724" r="12.276" fill="#3c2222" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3-0" cx="-312.973" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6-3" cx="-109.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7-6" cx="-64.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847-1" fill="#008000" stroke-opacity="1" stroke-width="3.457" d="M-410 228.474h400v75.309h-400z" opacity="1"></path>
        <path id="rect9851-06" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-393.259 245.292h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-5-3" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-351.219 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-3-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-309.179 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56-0" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-267.139 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2-6" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-225.709 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9-1" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-183.059 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1-5" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-141.019 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27-5" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-99.101 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0-4" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-58.767 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976-7" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M-410 220.811h400v8.639h-400z" opacity="1"></path>
        <path id="rect9910-4-6" fill="#59353b" stroke-opacity="1" stroke-width="3.412" d="M-702.331 300.574h162.851v9.047h-162.851z" opacity="1"></path>
        <circle id="path4897-5-5" cx="-763.888" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-3-0-6" cx="-722.973" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-6-3-9" cx="-519.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <circle id="path4897-7-6-3" cx="-474.402" cy="306.724" r="12.276" fill="#3c2327" stroke-opacity=".651" stroke-width=".448" opacity="1"></circle>
        <path id="rect9847-1-7" fill="#F0FFF0" stroke-opacity="1" stroke-width="3.457" d="M-820 228.474h400v75.309h-400z" opacity="1"></path>
        <path id="rect9851-06-4" fill="#32CD32" stroke-opacity="1" stroke-width="3.412" d="M-803.259 245.292h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-5-3-5" fill="#7FF000" stroke-opacity="1" stroke-width="3.412" d="M-761.219 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-3-2-2" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-719.179 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-56-0-5" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-677.139 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-2-6-4" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-635.708 245.841h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-9-1-7" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-593.059 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-1-5-4" fill="#fcb12a" stroke-opacity="1" stroke-width="3.412" d="M-551.019 245.597h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-27-5-4" fill="#f79742" stroke-opacity="1" stroke-width="3.412" d="M-509.101 245.604h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect9851-0-4-3" fill="#fec56b" stroke-opacity="1" stroke-width="3.412" d="M-468.767 244.987h26.808v24.98h-26.808z" opacity="1"></path>
        <path id="rect4976-7-0" fill="#fbbf95" stroke-opacity="1" stroke-width="14.425" d="M-820 220.811h400v8.639h-400z" opacity="1"></path>
      </g>

   
  
   </svg>
  </div>
  </body>