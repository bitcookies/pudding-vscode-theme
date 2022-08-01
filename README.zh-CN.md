<p align="center">
 <img width="100px" src="https://bitcookies.nousbuild.com/pudding-vscode-theme/icon.png" align="center" alt="Pudding Icon" />
 <h2 align="center">布丁 VSCode 主题</h2>
 <p align="center">布丁插画风格的 Visual Studio Code 主题</p>
</p>
<p align="center">
  <a href="https://github.com/bitcookies/pudding-vscode-theme/releases">
  	<img src="https://img.shields.io/github/v/release/bitcookies/pudding-vscode-theme?label=version" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=Bitcookies.pudding-vscode-theme">
  	<img alt="Market" src="https://vsmarketplacebadge.apphb.com/version-short/Bitcookies.pudding-vscode-theme.svg" />
  </a>
  <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/LICENSE">
  	<img alt="License" src="https://img.shields.io/github/license/Bitcookies/pudding-vscode-theme.svg" />
  </a>
  <a href="https://github.com/bitcookies/pudding-vscode-theme/issues">
  	<img alt="Issues" src="https://img.shields.io/github/issues/bitcookies/pudding-vscode-theme?color=F48D73" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/README.zh-CN.md">简体中文</a> | <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/README.md">English</a>
</p>

## 1. VSCode 布丁主题

Visual Studio Code 布丁主题正在不断更新多款配色主题：

![screenshot](https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-1.jpg)

## 2. 配色方案

### 2.1 配色来源

此主题的配色方案，来自于原创的二次元人物 —— **布丁（Pudding）**。提取布丁绘画形象中的颜色，然后使用这些绘画配色开发了这款布丁主题。

由于此配色最初是为了绘画，因此应用到 Visual Studio Code 等的程序主题中，可能存在一些颜色不合适的问题，后续将会不断进行更新优化，调整主题的最佳样式。

### 2.2 主题列表

|                            Theme                             |          Name          |
| :----------------------------------------------------------: | :--------------------: |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-2.png" width="400px"> |      Pudding Dark      |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-3.png" width="400px"> |     Pudding Light      |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-4.png" width="400px"> | Pudding Light Aquarium |

## 3. 安装

1. 转到 [VS 市场](https://marketplace.visualstudio.com/items?itemName=Bitcookies.pudding-vscode-theme)。
2. 单击 “安装” 按钮。
3. 然后[选择一个主题](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme)。目前有以下主题可用：
   - Pudding Light
   - Pudding Light Aquarium
   - Pudding Dark

随着布丁插画的不断更新，未来也会继续退出更多主题配色。

## 4. 自定义

主题配色很好看，但是语法高亮样式不太适合我，这该怎么办呢？从 `v2.0` 版本开始，你可以自定义语法高亮样式了。

### 4.1 挑选 Color Sublime

访问 [Color Sublime](https://colorsublime.github.io) 挑选自己喜欢的 tmTheme 样式并下载。下载完成后，请删除掉 tmTheme 文件开头的 `<key>settings</key>` 部分的全部内容，因为这些设置会覆盖掉主题的配色。

请删掉 tmTheme 文件开头形如这样的代码：

```
<dict>
	<key>settings</key>
		<dict>
			<key>background</key>
			<string>#222222</string>
			......
			......
			<key>invisibles</key>
			<string>#3b3a32</string>
        </dict>
</dict>
```

### 4.2 替换 Color Sublime

Clone 此代码仓库后，将修改后的 tmTheme 文件放到 `themes/tmTheme/` 目录下，然后在 `themes/` 下找到你想要修改的主题配色 json 文件，打开后修改最底部的 tokenColors 链接，引入你的 tmTheme 文件即可。

```json
"tokenColors": "./tmTheme/your.tmTheme"
```

## 5. 反馈

主题的配色一定还会存在很多的不足，如果可以的话，您可以在此反馈一些建议和意见。或者是，你喜欢的衣装服饰和颜色，都可以进行建议反馈：

- [Github Issues](https://github.com/bitcookies/pudding-vscode-theme/issues)
- [VS Market](https://marketplace.visualstudio.com/items?itemName=Bitcookies.pudding-vscode-theme&ssr=false#review-details)

未来我也会绘画更多的人物衣装样式，随着布丁衣装立绘的更新，未来会推出更多主题配色。

## 6. 未来的主题配色

下面是未来可能的主题配色插画：

|                             插画                             |      作品名      |                      Pixiv                      |                           Behance                            |
| :----------------------------------------------------------: | :--------------: | :---------------------------------------------: | :----------------------------------------------------------: |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/6-pudding.jpg" width="240px"> |   《全身立绘》   | [查看](https://www.pixiv.net/artworks/99262676) | [查看](https://www.behance.net/gallery/146721913/Pudding-JK) |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/5-aquarium.jpg" width="240px"> |    《海洋馆》    | [查看](https://www.pixiv.net/artworks/99247123) |  [查看](https://www.behance.net/gallery/146662893/Aquarium)  |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/4-rabbit-cosplay.jpg" width="240px"> | 《那兔 Cosplay》 | [查看](https://www.pixiv.net/artworks/97722612) | [查看](https://www.behance.net/gallery/141910191/Rabbit-Cosplay) |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/3-drink.jpg" width="240px"> |    《喝饮料》    | [查看](https://www.pixiv.net/artworks/97722555) | [查看](https://www.behance.net/gallery/141909257/Drink-Pudding) |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/2-giftbox.jpg" width="240px"> |    《礼物盒》    | [查看](https://www.pixiv.net/artworks/95340507) |  [查看](https://www.behance.net/gallery/134497941/Gift-Box)  |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/1-classroom.jpg" width="240px"> |   《课后教室》   | [查看](https://www.pixiv.net/artworks/95340455) | [查看](https://www.behance.net/gallery/134497441/Classroom)  |

## 7. 许可

主题代码使用 [MIT license](https://github.com/bitcookies/winrar-keygen/blob/master/LICENSE)，但不包含立绘。

布丁人物立绘版权归作者所有：[Haoning Wu](https://github.com/pudding0503)