<!--
 * @?: *********************************************************************
 * @Author: Weidows
 * @Date: 2021-01-03 01:36:18
 * @LastEditors: Weidows
 * @LastEditTime: 2021-09-02 17:39:29
 * @FilePath: \VScode-Extension-Tamplate\README.md
 * @Description:
 * @!: *********************************************************************
-->
<h1 align="center">

🥞VScode-Extension-Tamplate

vscode 插件开发模板

</h1>

[github-shield]: https://img.shields.io/github/stars/Weidows/VScode-Extension-Tamplate
[github-url]: https://github.com/Weidows-projects/VScode-Extension-Tamplate
[vscode-shield]: https://img.shields.io/visual-studio-marketplace/r/Weidows.theme-weidows?logo=visual-studio-code
[vscode-url]: https://marketplace.visualstudio.com/items?itemName=Weidows.theme-weidows

> [![Github Repo][github-shield]][github-url] [![VSCode Plugin][vscode-shield]][vscode-url]
> For more information, [click here][github-url]

---

# 使用

1. fork 或者 clone 本仓库

2. 把需要的地方做一些修改,比如 package.json 有很多必填/必改项.

3. 创建仓库 secret,名字为 `TOKEN`,值为获取的 PAT [(如何获取: ♻VScode 插件开发流程.)](https://weidows.github.io/post/tools/vscode/extension-develop/#%E5%8F%91%E5%B8%83)

4. 打开 GitHub Action,然后 draft 一个 release,填写完后 publish,就会触发任务自动打包插件并发布.
