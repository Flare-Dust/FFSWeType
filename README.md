# FFSWeType

微信输入法跟随系统字体 Xposed 模块，理论全版本通杀。

## 原理
通过 Xposed 拦截目标方法，执行前强制将文本样式设为系统默认字体。

## 使用
1. 启用模块，作用域勾选微信输入法（`com.tencent.wetype`）
2. 通过Lspatch或者其分支注入
