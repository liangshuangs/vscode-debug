/*
 * @Anthor: liangshuang15
 * @Description: 
 * @Date: 2022-09-06 15:03:39
 * @LastEditTime: 2022-09-06 15:03:42
 * @FilePath: /webpack-study/test.js
 */
<!--
 * @Anthor: liangshuang15
 * @Description: 
 * @Date: 2022-09-06 11:47:21
 * @LastEditTime: 2022-09-06 15:20:48
 * @FilePath: /vscode-debug/README.md
-->
# vscode-debug
vscode 有一个关键的特性就是它的强大的调试功能，vscode内置的调试器能帮助你加快编辑、编译和调试循环。
## debugger 调试拓展
vscode内置的debugger支持node.js运行时以及javascript,typescript、其他能转换为javascript的语言。

## 启动debug
下面的文档是基于内置的node.js调试器，但是其他的特性和思想也支持其他调试器。

创建一个demo
创建launch.json，大多数使用场景都会选择创建launch.json，因为vscode会在当前的工作空间中本地保存这些配置信息，具体保存在.vscode中;
- 创建launch
![image](image/launch-configuration.png)
- 选择调试器
![image](https://code.visualstudio.com/assets/docs/editor/debugging/debug-environments.png)