# lagouUI

lagouUI源文件 文档结构如下

```
.
├── README.md
├── gulpfile.js
├── package.json
└── src
    ├── img
    │   ├── arrow-icon.png
    │   ├── checkbox.png
    │   ├── icon-download.png
    │   ├── info.png
    │   └── tips-close.png
    ├── js
    │   ├── ui.baseUtils.js-----必需引用
    │   ├── ui.checkbox.js
    │   ├── ui.datepicker.js
    │   ├── ui.dropbox.js
    │   └── ui.multiSelect.js
    └── less
        ├── lagou.less
        ├── mixins
        │   ├── btn-icon.less
        │   ├── caret.less
        │   ├── clearfix.less
        │   ├── mixins.less-----必需引用
        │   ├── text-overflow.less
        │   └── vender-prefixes.less
        ├── modules
        │   ├── btn.less
        │   ├── checkbox.less
        │   ├── datepicker.less
        │   ├── dropbox.less
        │   ├── input.less
        │   ├── multiselect.less
        │   └── reset.less---必需引用
        └── variables.less
```


####说明
	除了必需引用外，其余都可以按需引用对应的less和js
