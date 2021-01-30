<h1 align="center"> Markdown Preview Enhanced </h1>

![intro](https://user-images.githubusercontent.com/1908863/28495106-30b3b15e-6f09-11e7-8eb6-ca4ca001ab15.png)

<p align="center">
<a href="https://shd101wyy.github.io/markdown-preview-enhanced/#/"> English &nbsp;&nbsp; </a>  
<a href="https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/"> 简体中文 &nbsp;&nbsp; </a>  
<a href="https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-tw/"> 正體中文 &nbsp;&nbsp; </a>
<a href="https://shd101wyy.github.io/markdown-preview-enhanced/#/ja-jp/"> 日本語 &nbsp;&nbsp; </a> <br>
</p>

<p align="center">
<a href="https://atom.io/packages/markdown-preview-enhanced">atom</a>
&
<a href="https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced">vscode</a>
<br>
<br>
  <a href="https://a.paddle.com/v2/click/16413/111548?link=1227"><img src="https://img.shields.io/badge/LEARN-VSCODE%20POWER%20USER%20COURSE%20%E2%86%92-gray.svg?colorB=4D2AFF" alt="Become VSCode Power User"></a>
</p>

If you are interested, please try out our new prototype web app: [0xGG/crossnote](https://github.com/0xGG/crossnote)

## Introduction

---

This project is forked from [shd101wyy/vscode-markdown-preview-enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced). In this specific version, we enable you to use specific `referrer` in some image requests in order to render the images correctly. For more information, please visits [my blog](https://gyrojeff.top/index.php/archives/273/).

本项目 fork 自[shd101wyy/vscode-markdown-preview-enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)。在这个特定版本当中，我们支持使用特定的`referrer`来进行图片的请求，以在某些特定情况下正确渲染图片（比如说开启了防盗链的腾讯 COS / 阿里云 OSS）。更多信息，请访问[我的博客](https://gyrojeff.top/index.php/archives/273/).

You can set up the referrer policy in setting page, the following to properties are concerned:

- `markdown-preview-enhanced.restricted-prefixes`: If the image link has one of the following prefixes, it will be downloaded using referrer previously configured. Note: this is an array.
- `markdown-preview-enhanced.fake-referrer`: The referrer used to download images from restricted servers.

你可以在设置界面设置`referrer`的相关属性：

- `markdown-preview-enhanced.restricted-prefixes`: 如果图像链接是以这里面的链接的其中之一作为前缀的，那么将会使用先前配置的`referrer`进行下载
- `markdown-preview-enhanced.fake-referrer`: 需要使用的`referrer`

---

Markdown Preview Enhanced is an extension that provides you with many useful functionalities such as automatic scroll sync, [math typesetting](https://shd101wyy.github.io/markdown-preview-enhanced/#/math), [mermaid](https://shd101wyy.github.io/markdown-preview-enhanced/#/diagrams?id=mermaid), [PlantUML](https://shd101wyy.github.io/markdown-preview-enhanced/#/diagrams?id=plantuml), [pandoc](https://shd101wyy.github.io/markdown-preview-enhanced/#/pandoc), PDF export, [code chunk](https://shd101wyy.github.io/markdown-preview-enhanced/#/code-chunk), [presentation writer](https://rawgit.com/shd101wyy/markdown-preview-enhanced/master/docs/presentation-intro.html), etc. A lot of its ideas are inspired by [Markdown Preview Plus](https://github.com/atom-community/markdown-preview-plus) and [RStudio Markdown](http://rmarkdown.rstudio.com/).

Feel free to ask questions, post issues, submit pull request, and request new features.

For more information about this project and how to use this extension, please check out our documentation ⬇︎

## Documentation

To check out the documentation, visit

- [English](https://shd101wyy.github.io/markdown-preview-enhanced/#/)
- [简体中文](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/)
- [正體中文](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-tw/)
- [日本語](https://shd101wyy.github.io/markdown-preview-enhanced/#/ja-jp/)

Contact me if you are willing to help translate the documentation :)

## Keybindings

> The <kbd>cmd</kbd> key for _Windows_ is <kbd>ctrl</kbd>.

| Shortcuts                                         | Functionality              |
| ------------------------------------------------- | -------------------------- |
| <kbd>cmd-k v</kbd> or <kbd>ctrl-k v</kbd>         | Open preview to the Side   |
| <kbd>cmd-shift-v</kbd> or <kbd>ctrl-shift-v</kbd> | Open preview               |
| <kbd>ctrl-shift-s</kbd>                           | Sync preview / Sync source |
| <kbd>shift-enter</kbd>                            | Run Code Chunk             |
| <kbd>ctrl-shift-enter</kbd>                       | Run all Code Chunks        |
| <kbd>cmd-=</kbd> or <kbd>cmd-shift-=</kbd>        | Preview zoom in            |
| <kbd>cmd--</kbd> or <kbd>cmd-shift-\_</kbd>       | Preview zoom out           |
| <kbd>cmd-0</kbd>                                  | Preview reset zoom         |
| <kbd>esc</kbd>                                    | Toggle sidebar TOC         |

## Changelog

Please check the [Releases](https://github.com/shd101wyy/vscode-markdown-preview-enhanced/releases) page of this project.

## License

[University of Illinois/NCSA Open Source License](LICENSE.md)
