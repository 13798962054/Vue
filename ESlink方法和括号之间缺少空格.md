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
### 3、安装vetur、eslint插件，修改user配置文件。
- 修改完成后代码页会有ESLint的报错提示。
- 通过ctrl+shift+p，输入ESLint:Fix all auto-fixable Problems，可以自动修复eslint检查出来的错误。
```json
{
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "hediet.vscode-drawio.local-storage": "eyIuZHJhd2lvLWNvbmZpZyI6IntcImxhbmd1YWdlXCI6XCJcIixcImN1c3RvbUZvbnRzXCI6W10sXCJsaWJyYXJpZXNcIjpcImdlbmVyYWw7YmFzaWM7Zmxvd2NoYXJ0XCIsXCJjdXN0b21MaWJyYXJpZXNcIjpbXCJMLnNjcmF0Y2hwYWRcIl0sXCJwbHVnaW5zXCI6W10sXCJyZWNlbnRDb2xvcnNcIjpbXCJGRkZGRkZcIixcIkYwRUQ5MFwiLFwiQ0M5QjM5XCJdLFwiZm9ybWF0V2lkdGhcIjoyNDAsXCJjcmVhdGVUYXJnZXRcIjpmYWxzZSxcInBhZ2VGb3JtYXRcIjp7XCJ4XCI6MCxcInlcIjowLFwid2lkdGhcIjoxMTY5LFwiaGVpZ2h0XCI6ODI3fSxcInNlYXJjaFwiOnRydWUsXCJzaG93U3RhcnRTY3JlZW5cIjp0cnVlLFwiZ3JpZENvbG9yXCI6XCIjZDBkMGQwXCIsXCJkYXJrR3JpZENvbG9yXCI6XCIjNmU2ZTZlXCIsXCJhdXRvc2F2ZVwiOnRydWUsXCJyZXNpemVJbWFnZXNcIjpudWxsLFwib3BlbkNvdW50ZXJcIjowLFwidmVyc2lvblwiOjE4LFwidW5pdFwiOjEsXCJpc1J1bGVyT25cIjpmYWxzZSxcInVpXCI6XCJcIn0ifQ==",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "javascript.updateImportsOnFileMove.enabled": "always",
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "hediet.vscode-drawio.theme": "dark",
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter.notebook.ipynb"
    },
    "files.eol": "\r\n",
    "markdown-preview-enhanced.enableExtendedTableSyntax": true,
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    }
}
```
