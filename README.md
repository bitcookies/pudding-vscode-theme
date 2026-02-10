<p align="center">
 <img width="100px" src="https://bitcookies.nousbuild.com/pudding-vscode-theme/icon.png" align="center" alt="Pudding Icon" />
 <h2 align="center">Pudding Theme</h2>
 <p align="center">A Pudding illustrations color theme for Visual Studio Code</p>
</p>
<p align="center">
  <a href="https://github.com/bitcookies/pudding-vscode-theme/releases"><img src="https://img.shields.io/github/v/release/bitcookies/pudding-vscode-theme?label=version" /></a> <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/Bitcookies/pudding-vscode-theme.svg" /></a> <a href="https://github.com/bitcookies/pudding-vscode-theme/issues"><img alt="Issues" src="https://img.shields.io/github/issues/bitcookies/pudding-vscode-theme?color=F48D73" /></a>
</p>
<p align="center">
  <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/README.zh-CN.md">简体中文</a> | <a href="https://github.com/bitcookies/pudding-vscode-theme/blob/main/README.md">English</a>
</p>



## 1. Pudding Theme

Visual Studio Code Pudding theme is constantly updated with a variety of color themes.

![screenshot](https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-1.png)

## 2. Color Scheme

### 2.1 Color

The color scheme of this theme comes from the original cartoon character, **Pudding**. The colors in the painted image of Pudding were extracted and then used to develop this pudding theme.

Since this color scheme was originally intended for painting, there may be some problems with inappropriate colors when applied to program themes such as Visual Studio Code, and subsequent updates will be made to optimize and adjust the best style of the theme.

### 2.2 Themes

|                            Theme                             |           Name           |
| :----------------------------------------------------------: | :----------------------: |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-2.png" width="400px"> |      Pudding Light       |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-3.png" width="400px"> |    Pudding Light · JK    |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-4.png" width="400px"> |       Pudding Dark       |
| <img src="https://bitcookies.nousbuild.com/pudding-vscode-theme/screenshot-5.png" width="400px"> | Pudding Dark · Christmas |

## 3. Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=Bitcookies.pudding-vscode-theme).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme). Currently the following themes are available.

   - Pudding Light
   - Pudding Light Aquarium
   - Pudding Dark

With the update of the pudding clothing stand, the future will launch more thematic color scheme.

## 4. Customized tmTheme

### 4.1 Select Color Sublime

Visit [Color Sublime](https://colorsublime.github.io) to pick your favorite tmTheme style and download it. After downloading, please delete the entire `<key>settings</key>` section at the beginning of the tmTheme file, as these settings will override the theme's color scheme.

Please delete the code at the beginning of the tmTheme file that looks like this.

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

### 4.2 Replace Color Sublime

After Clone this code repository, put the modified tmTheme file into `themes/tmTheme/` directory, then find the theme color scheme json file you want to modify under `themes/`, open it and modify the tokenColors link at the bottom to introduce your tmTheme file.

```json
"tokenColors": "./tmTheme/your.tmTheme"
```

## 5. Feedback

The theme of the color scheme must still have a lot of shortcomings, if possible, you can give some feedback and comments here. Or, your favorite clothing apparel and colors, you can make suggestions for feedback:

- [Github Issues](https://github.com/bitcookies/pudding-vscode-theme/issues)
- [VS Market](https://marketplace.visualstudio.com/items?itemName=Bitcookies.pudding-vscode-theme&ssr=false#review-details)

In the future I will also paint more characters clothing style, with the update of the pudding clothing stand, the future will launch more thematic color scheme.

## 6. Future Theme

The Aquarium theme has been removed in the `v3.x` version. If needed, please obtain it from the `v2.x` version.

See more of my illustrations.

<a href="https://github.com/pudding0503/pudding-illustration">
	<img width="300px" src="https://bitcookies.nousbuild.com/pudding-vscode-theme/link.png" alt="link" />
</a>

## 7. License

The code is available under the [MIT license](https://github.com/bitcookies/winrar-keygen/blob/master/LICENSE), but not including characters.

Pudding character are copyrighted to the author: [ONing](https://github.com/pudding0503).
