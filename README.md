# TriliumThemes
A few custom themes for the delightful [Trilium Notebook app](https://github.com/zadam/trilium).

Currently I am up to date with the **v0.28.3 release**

Current Themes Included:
------

**Purple Rain**
![Purple Rain Theme](https://i.imgur.com/DMT7xOp.png)
**Rainbow in the Dark**
![Rainbow in the Dark Theme](https://i.imgur.com/ahRW6gh.png)

The Code Editor is also themed:
![Code Lens Theme](https://i.imgur.com/qDyKVnv.png)
-------

## Instalation 
There are two methods you can use to install: 
1. You can use the example CSS files to make root level css with the @appCss attribute. **While this is easiest, you will not get the custom font for the code editor as you can use @import for fonts this method**
   * [Purple Rain's CSS File](https://github.com/Abourass/TriliumThemes/blob/master/examples/css/PurpleRain.css)
   * [Rainbow in the Dark's CSS File](https://github.com/Abourass/TriliumThemes/blob/master/examples/css/RainbowInTheDark.css)
2. You can overwrite the style css / and the options ejs file then use the build tools to build the source. This will let you choose the themes under options like any other theme. **I will do my absolute best to always keep my files up to date with the source**
   * Download the [/src](https://github.com/Abourass/TriliumThemes/tree/master/src) folder and overwrite the /src file in Trilium
   * Build using the build tools in Trilium

