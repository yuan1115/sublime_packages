#### 常用包整理

	sublime Text3  常用包整理，附带包控制文件和channel_v3.json

##### Package Control

	来说一下手动安装，只需要将附带文件夹Package_Control中的Package Control.sublime-package放到"\\Sublime Text 3\Installed 
	Packages"目录下，还有一点，就是当使用包控制安装包时提示找不到包，可以将channel_v3.json复制到本地，之后在Package Control
	的包设置中添加如下：

	"channels": [
		"D:\\channel_v3.json"
	],	

	PS：上面的路径就是本地channel_v3.json的路径	

##### ChineseLocalization

	语言包，可以切换中文，英语，日语等语言
