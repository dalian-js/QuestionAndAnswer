Q: what's different between id and class in CSS?

--

https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes

http://www.zhihu.com/question/19550864

    ID具有唯一性，Class具有普遍性。
    ID是唯一的，所以尽量在结构外围使用，通常用于页面布局。
    Class是可重复的，所以尽量在结构内部使用，通常用于样式定义。
    ID的样式优先级高于Class。
    你有一个网页，上面3个按钮，要让它们高宽相同，就用 class；其中的“提交”按钮的背景更亮，就用id来指定css。

