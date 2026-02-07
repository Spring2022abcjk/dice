# dice
A [maubot](https://github.com/maubot/maubot) that rolls dice. Has built-in calculator.

## Usage
The base command is `!roll`. To roll dice, pass `XdY` as an argument, where `X`
is the number of dice (optional) and `Y` is the number of sides in each dice.
Most Python math and bitwise operators and basic `math` module functions are
also supported, which means you can roll different kinds of dice and combine
the results however you like.

## ✨ 更新日志
更新说明 (v1.1.1)
Python 3.8+ 兼容性修复：修复了由于 ast.Num 废弃导致的 TypeError: NoneType doesn't define __round__ 错误。现在可以完美运行在最新的 Python 环境中。

新增帮助指令：输入 !roll help 即可查看详细的用法指南和示例。

代码优化：改进了 AST 访问逻辑，支持 ast.Constant 解析。

## 📜 许可
本项目继承原作者的 GNU Affero General Public License v3.0。