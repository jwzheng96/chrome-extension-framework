# chrome-extension-framework

This is a framework model for developing chrome extensions using Vue and already packaged in webpack. Developers can build extensions based on this prototype.


## 目录结构
```
│  .babelrc.js
│  .gitignore
│  package.json
│  webpack.config.js
│  
├─src
│  │  manifest.json
│  │  
│  ├─background
│  │      background.js
│  │      
│  ├─content
│  │      content.js
│  │      
│  ├─option
│  │      App.vue
│  │      option.html
│  │      option.js
│  │      
│  └─popup
│          App.vue
│          popup.html
│          popup.js
│          
└─static
    └─img
            icon.png
```


## 使用

```bash
## 安装依赖
npm install 
## 打包运行
npm run build
```
