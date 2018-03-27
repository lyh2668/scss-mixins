# 准备收集一些常用的mixins
1. [内角弧度mixins](./src/inner-round-corner.scss)
``` scss
/**
 * $color 颜色
 * $radius 弧度
 * $positions: 从 'top-left', 'top-right', 'bottom-left', 'bottom-right'     
 * 选出任意N个有效值填入即可
 **/
@mixin inner-round-corner ($color, $radius, $positions...)
// 调用example
@include inner-round-corner(red, 5px, 'top-left', 'top-right');
```