```json
{
  /**
  * 重要配置
  */
  // 窗口缩放比例
  "window.zoomLevel": 0.7,
  // 编辑器右上角小地图
  "editor.minimap.enabled": true,
  // 工作台主题
  "workbench.colorTheme": "Visual Studio Dark",
  // 编辑器字体大小
  "editor.fontSize": 12,
  // 编辑器默认缩放字符数（一个制表符tab等于的空格数）
  "editor.tabSize": 2,
  // 编辑器自动换行
  "editor.wordWrap": "on",
  // 控制差异编辑器中是否把前导空格或尾随空格的改动显示为差异
  "diffEditor.ignoreTrimWhitespace": false,


  /**
  * 不重要的配置
  */

  // 建议小部件的字号，如果设置为0，则使用editor.fontSize的字号大小
  "editor.suggestFontSize": 12,
  // 文件自动保存，有off、afterDelay（需要搭配files.autoSaveDelay一起使用，以ms计数）、onFocusChange、onWindowChange四个选项
  "files.autoSave": "off",

  "bracketPairColorizer.activeScopeCSS": [
      "borderStyle : solid",
      "borderWidth : 1px",
      "borderColor : {color}; opacity: 0.5"
  ],

  // 在保存时运行的代码操作类型
  "editor.codeActionsOnSave": null,

  // 在保存文件时，裁剪尾随空格
  "files.trimTrailingWhitespace": true,
  // 在保存文件时，裁剪尾随的空行
  "files.trimFinalNewlines": true,

  // // 定义函数参数括号前的空格处理
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "typescript.format.insertSpaceBeforeFunctionParenthesis": true,

}
```
