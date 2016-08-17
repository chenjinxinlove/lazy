# lazy
图片懒加载（图片出现在可视区域再加载）

#### 兼容性：兼容目前流行的全部浏览器，包括：兼容到IE6）


#### 使用方法：
- 引入相应的js文件  
```<script src="js/lazy.js"></script>```

- 初始化
```
Lazy.init(1000);
可以传入延时时间。默认是500ms

```

> **注意：**

```<img src="img/load.gif" data-lazy="img/2.jpg">```

**src 属性放预加载的图片，data-lazy放实际展示的图片**
