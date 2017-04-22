# CSS-order
css 属性书写顺序推荐

根据 MDN 中 [CSS参考](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) 归纳整理。
## update  
添加 sublime CSScomb 插件的属性排序配置 CSScomb.sublime-settings.json
## summary  

| 布局定位  
　　| 定位方式：position  
　　| 元素浮动：float  
| 盒子模型  
　　| 盒子类型：display  
　　　　| 弹性盒子 ：flex  
　　　　| table盒子：table...  
　　　　| list盒子 ：list-style...  
　　| 盒子属性：box-sizing  
　　　　| 内容宽度：width...  
　　　　| 内容高度：height...  
　　　　| 内边距  ：padding  
　　　　| 边界    ：border...  
　　　　| 轮廓    ：outline...  
　　　　| 外边距  ：margin...  
　　　　| 背景    ：background...  
　　　　| 阴影	 ：box-shadow  
　　　　| 透明度  ：opacity  
　　　　| 滤镜    ：filter  
　　| 盒子内容  
　　　　| 行列划分：colums...  
　　　　　　| ...  
　　　　| 溢出处理：overflow  
　　　　| 特定元素垂直对齐：verical-align  
　　　　| 字体渲染：text-rendering  
　　　　　　| 排版模式  ：writing-mode...  
　　　　　　| 字体属性  ：font  
　　　　　　　　| ...  
　　　　　　| 文本颜色  ：color  
　　　　　　| 字体样式集：font-feature-setting  
　　　　　　| 文本控制  
　　　　　　　　| 空白符处理  ：white-space  
　　　　　　　　| 文本溢出处理：text-overflow  
　　　　　　　　| 字间距      ：letter-spacing  
　　　　　　　　| 西文处理  
　　　　　　　　　　| ...  
　　　　　　　　| 文本对齐    ：text-align...  
　　　　　　| 文本装饰  
　　　　　　　　| 引用符号  ：qutoes  
　　　　　　　　| 制表符宽度：tab-size  
　　　　　　　　| 首行缩进  ：text-indent  
　　　　　　　　| 重点标记  ：text-emphasis...  
　　　　　　　　| 横线装饰  ：text-decoration...  
　　　　　　　　| 文本阴影  ：text-shadow  
　　　　| 图片元素  
　　　　　　| 缩放算法：image-rendering  
　　　　　　| 预设方向：image-orentation  
　　　　| 其他属性  
　　　　　　| 元素替换：object-fit...  
　　　　　　| 重叠权重：z-index  
　　　　　　| 元素缩放：zoom  
　　　　　　| 裁剪    ：clip  
　　　　　　| 尺寸调整：resize  
　　　　　　| 鼠标手势：cursor  
　　　　　　| 可见性  ：visibility  
　　　　　　| 计数器  ：counter-reset...  
　　　　　　| 文本容器：content  
　　　　　　| 优化准备：will  
　　　　　　| 事件穿透：pointer-events  
　　　　　　| 渲染样式：appearance  
　　　　　　| 属性重置：all  
    | 盒子变形  
　　　　| 空间状态：transform-style  
　　　　| 模型变形：transform...  
　　　　| 空间透视：perspective...  
| 动态效果  
　　| 过渡效果：transition...  
　　| 动画属性：animation...  

更加详细的属性和参数请见 order.css  

