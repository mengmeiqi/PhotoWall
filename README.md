# PhotoWall
    照片墙
# 知识点：
## 1.transform 动画
### a.transform:rotate(30deg/-30deg);顺时针/逆时针旋转30°
### b.transform-origin:旋转原点，两个参数，可以是数值，也可以为百分数，也可以为left,center,right,top,bottom
### c.transform:translate();指的是移动的位移，两个参数，可以是数值或百分数  translateX() reanslateY()
      transform:translate(50px,100px);向右50，向下100
      transform:translate(-50px,-100px);向左50，向上100
      transform:translate(50%,50%);移动父元素的百分之多少
### d.transform:scale();放大或缩小,可以是一个参数，或者两个参数   scaleX() scaleY()
      transform:scale(0.5);长宽缩小二倍
      transform:scale(-2);长宽放大二倍，并且顺时针旋转180°
      transform:scaleX(2); transform:scaleY(3);
### e.transform:skew(30deg,45deg);  扭曲 两个参数
## 2.transition 过渡
### 什么时候触发transition?在属性发生变化时，css或js都可
### transition:执行过渡的属性，过渡时间，速率变化，延迟时间；
### transition-property:属性/all;
### transition-duration:~s ;
### transition-timing-function: ease | linear (匀速)| ease-in (慢-快)| ease-out(快-慢) | ease-in-out | step-start | step-end | steps(<integer>[, [ start | end ] ]?) | cubic-bezier(<number>, <number>, <number>, <number>)