# mymodal 插件
基于bootstrap4的一款弹窗插件，可以自定义弹窗内容，加入input，自定义关闭，自定义按钮等。

# 使用
1. 引入bootstrap4相关的css和js
2. 引入mymodal.js
3. 使用：
let modalId = $.lyModal({
    title: '警告',
    content: '被踢出 <i class="fa fa-exclamation text-danger fa-lg"></i> <br/>你的账号在另外的地方登录.',
    hasCancel: false,
    backdrop: false,
    keyboard: false,
    size: 2,
    hasConfirm: true
});

具体方法参考js内部的注释，或者可以自行拓展。

# 计划
有空加上loading和弹窗打开网页等功能
