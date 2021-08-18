# Missing space before function parentheses
## 一、报错问题
- 方法和括号之间缺少空格。
## 二、解决方法
### 1、手动在方法和括号之间加一个空格
### 2、配置ESlink
- 在VUE项目中找到eslintrc.js文件，在rules对象中加入如下规则。
- 需要注意的是，修改配置文件需要重新启动VUE。
```js
'space-before-function-paren': 0
```
### 3、
