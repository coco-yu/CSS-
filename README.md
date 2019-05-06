# CSS权威指南

1. CSS视觉格式化模型
    用来处理文档并将它显示在视觉媒体上的机制。


2. 替换元素
    浏览器根据元素的标签和属性，来决定元素的具体显示内容。
    替换元素是其内容不受CSS视觉格式化模型控制的元素。
    在源代码中不能直接看出它要显示的内容，eg. img通过src属性告诉浏览器显示什么内容的图片。
    典型的可替换元素有：<img>、 <object>、 <video>、 表单元素：<textarea>、<input>。
    某些元素只在特殊情况下变现为替换元素：<audio>、<canvas>。
    通过css content属性来插入的对象称作匿名可替换元素。

3. 不可替换元素
    不可替换元素是其内容受CSS视觉格式化模型控制的元素。
    在源代码中可以直接看出它要显示的内容。

4. test  11111111111111111
