# CSS权威指南

1. CSS视觉格式化模型
    用来处理文档并将它显示在视觉媒体上的机制。


2. 替换元素
    浏览器根据元素的标签和属性，来决定元素的具体显示内容。
    替换元素是其内容不受CSS视觉格式化模型控制的元素。
    在源代码中不能直接看出它要显示的内容，eg. img通过src属性告诉浏览器显示什么内容的图片。
    通过修改某个属性值，呈现的内容就可以被改变的元素。
    典型的可替换元素有：<img>、 <object>、 <video>、 表单元素：<textarea>、<input>。
    某些元素只在特殊情况下变现为替换元素：<audio>、<canvas>。
    通过css content属性来插入的对象称作匿名可替换元素。

3. 不可替换元素
    不可替换元素是其内容受CSS视觉格式化模型控制的元素。
    在源代码中可以直接看出它要显示的内容。

4. HTML和XHTML中块级元素不能嵌套在内联元素里。
   CSS中对显示元素的嵌套不存在任何限制。

5. display默认值为inline，默认的其内容会显示为行内文本。

6. link标签的ref属性规定当前文档与被链接文档之间的关系。
   多个样式表会合并规则，并将其全部应用于文档。

7. 
