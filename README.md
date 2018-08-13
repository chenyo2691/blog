# 前端踩坑记
无限期记录一下自己踩过的坑，前人栽树后人乘凉。

## 编辑器
#### Visual Studio设置同步
使用Setting Sync 插件管理。里面的code或Id用文件记住。

## 移动端
### 常用css
```css
user-select: none; // 禁止文字被选中
outline:none; // 去除点击外边框,点击无轮廓
-webkit-touch-callout: none; // 长按链接不弹出菜单
-webkit-tap-highlight-color: rgba(0,0,0,0); // 去除点击高亮
```
### 导航栏高度 88px，标签栏高度 98px（iphone5和6常用）。

## 前端编码规范
  box-sizing:border-content
  元素上下间距：保持下个元素设置margin-top
  字体颜色透明度：不使用百分比，因为背景不同颜色会受到影响
  class命名：如nav-btn-fl表示按钮float:left
  js-class：有dom操作的类如此定义，无样式的js前缀的类
  公共class：熟悉公共class
  rem布局：设计稿说明字体最小像素，浏览器最小12px
  图形变形：object-fit:cover，并与运营们约定比例，建议正方形
