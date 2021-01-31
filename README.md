# remembrance_the_climate

### change

mobile.css
````css
.mobile .canvas {
  width: 820px;
  /* 移动端滑动优化 */
  touch-action: none; 
}
````

script

````js
// set the transition var
var transitionTimeNormal = ' 700ms ease 0s';
var transitionTimeFaster = ' 1s ease 0s';
var transitionTimeSlower = ' 1.5s ease 0s';

// 优化动画参数，可以对下这个页面的动画参数。
https://seacoast.climatefutures.us/#/durham-11
````

开启硬件加速
> 当前 script.js 写的动画，使用的是 translate 2d，可以替换成 translate3D，可以借助 GUP 加速，显著提升效果
使用文档
https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate3d()
