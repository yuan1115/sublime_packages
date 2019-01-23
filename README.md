### 常用包整理

	sublime Text3  常用包整理，附带包控制文件和channel_v3.json

#### Package Control

	来说一下手动安装，只需要将附带文件夹Package_Control中的Package Control.sublime-package放到"\\Sublime Text 3\Installed 
	Packages"目录下，还有一点，就是当使用包控制安装包时提示找不到包，可以将channel_v3.json复制到本地，之后在Package Control
	的包设置中添加如下：

	"channels": [
		"D:\\channel_v3.json"
	],	

	PS：上面的路径就是本地channel_v3.json的路径	

#### SideBarEnhancements

    侧栏右键功能增强，非常实用

#### Material Theme + FileIcons Mono

    主题美化 + 文件图标


#### ChineseLocalization

	语言包，可以切换中文，英语，日语等语言

#### Terminal + cmder

    Terminal是一个在sublime中打开cmd的插件。顺便安利一波软件cmder，安装之后你再也不需要忍受win的那个又黑又丑的Terminal了.
    下面是Terminal的配置

    {
      "terminal": "C:\\MyAPP\\cmder\\Cmder.exe",   //这个是cmder.exe所在路径
      "parameters": ["/START", "%CWD%"]
    }

    快捷键：
    ctrl+shift+t   在文件所有的目录打开cmder
   
#### FileHeader

    功能：新建带有文件头的文件，添加文件头

#### Markdown + MarkdownLivePreview

    通过安装z这个两个插件可以编辑Markdown文本，在编辑Markdown文本的同时可以实时预览编辑效果
    简单设置：Preferences → Package Settings → MarkdownLivePreview → Setting，打开后将左边default的设置代码复制到右边User栏，
    找到"markdown_live_preview_on_open": false,把false改为true，保存

#### Emmet

    一种快速编写html/css的方法
    注意：安装Emmet的同时，也会自动安装其依赖PyV8 binary库，安装PyV8库会用较长时间，可以在Sublime左下角看到安装进程状态

#### Ctags

    函数跳转，我的电脑上是Alt+点击 函数名称，会跳转到相应的函数

#### Doc​Blockr

    注释插件，生成幽美的注释。标准的注释，包括函数名、参数、返回值等，并以多行显示，省去手动编写

#### Doc​Blockr_python

    python注释插件

#### SublimeLinter + SublimeLinter-flake8 + autopep8

    python代码格式化，以及检测错误行，警告。python还需要安装flake8库    

#### sublimeGit

    在sublime中使用git

#### GitGutter

    在行号前形象地显示当前的改动差异，直接查看当前行的最近一次改动负责人和提交记录。

#### SublimeCodeIntel

    代码自动补全插件，选择 Perference-Package Settings-SublimeCodeIntel-Settings-User,复制以下配置:    

    {
        "codeintel_language_settings": {
            "Python3": {
                "python3": "C:\\Python36\\python.exe",
                "codeintel_scan_extra_dir": [
                    "C:\\Python36\\DLLs",
                    "C:\\Python36\\Lib",
                    "C:\\Python36\\Lib\\site-packages",
                    "C:\\Python36",
                    "C:\\Python36\\Lib\\*",
                ],
                "codeintel_scan_files_in_project": true,
                "codeintel_selected_catalogs": []
            },
            "PHP": {
	            "php": "D:\\Install\\phpStudy\\PHPTutorial\\php\\php-5.6.27-nts\\php.exe",
	            "codeintel_scan_extra_dir": [],
	            "codeintel_scan_files_in_project": true,
	            "codeintel_max_recursive_dir_depth": 15,
	            "codeintel_scan_exclude_dir":["D:\\Install\\phpStudy\\PHPTutorial\\php\\php-5.6.27-nts\\"]
	        }
        }
    }  
