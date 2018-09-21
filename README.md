# vuejs-ebook
## 使用方法：
首先安装依赖：  
```
npm install
```
然后启动服务：
```
npm run dev
```
浏览器输入：localhost:8080进行访问
## 各文件介绍：
```
/static/2018_Book_AgileProcessesInSoftwareEngine.epub
```
epub电子书文件  

```
/src/assets/styles/icon.css
```
项目图标  

```
/src/assets/styles/global.css
```
项目所需全局样式，包括px2rem方法和点击各图标的动画效果  

```
/src/assets/styles/reset.css
```
清除默认样式  

```
/src/components/TitleBar.vue
```
呼出菜单时的上部分菜单组件（只有一些图标，暂无功能）  

```
/src/components/MenuBar.vue
```
呼出菜单时的下部分菜单组件（包括字号设置、主题选择和阅读进度设置）  

```
/src/components/Content.vuw
```
下部分菜单中的目录选择组件  

```
/src/Ebook.vue
```
电子书渲染组件

## 参考来源：
[慕课网-快速入门Web阅读器开发](https://www.imooc.com/learn/1038)
