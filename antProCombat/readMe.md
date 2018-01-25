### ant项目实战 参考文档-项目实战
##### 安装dva-cli
```
npm install dva-cli -g
```
##### 创建新应用并启动应用
```
dva new <projectName>
cd <projectName>
npm start
```
##### 使用antd
###### 通过npm安装antd和babel-plugin-import。babel-plugin-import是用来按需加载antd的脚本和样式的。
```
npm install antd babel-plugin-import --save
```
###### 编辑.webpackrc,使babel-plugin-import插件生效
```
"extraBabelPlugins": [
  ["import", { "libraryName": "antd", "libraryDirectory": "es", "style": "css" }]
],
```
##### 定义路由

##### 编写UI Component

###### 