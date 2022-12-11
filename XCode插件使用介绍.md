# XCode插件使用介绍

[XcodeColors](https://github.com/robbiehanson/XcodeColors)：给 Xcode 控制台添加颜色

[XToDo](https://github.com/trawor/XToDo)：这个插件不仅高亮 **TODO**、 **FIXME**、 **???**，还高亮 **!!!** 注释

[Backlight](https://github.com/limejelly/Backlight-for-XCode)：高亮当前正在编辑的那一行

[CocoaPods ](https://github.com/kattrali/cocoapods-xcode-plugin)插件：依赖管理助手

[ACCodeSnippetRepository](https://github.com/acoomans/ACCodeSnippetRepositoryPlugin)：把代码同步到 git 仓库

[GitDiff](https://github.com/johnno1962/GitDiff)：在 Xcode 高亮当前修改和上次提交之间的不同之处

[KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode)：自动补全图片名

[Peckham](https://github.com/markohlebar/Peckham)：更便捷地导入头文件

[FuzzyAutocomplete](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)：自动补全

[Dash](#)

[AMAppExportToIPA](https://github.com/MellongLau/AMAppExportToIPA-Xcode-Plugin)：在Xcode的project navigator界面中直接右键点击xxx.app -> Export IPA就可以生成对应的IPA文件的Xcode插件。

[HOStringSense](https://github.com/holtwick/HOStringSense-for-Xcode)：可以完美编辑正则表达式，多行文本，HTML等字符串，还提供字符串长度快速提示。

[MCLog](https://github.com/yuhua-chen/MCLog)： MCLog 是一款可以让你轻松过滤Xcode控制台日志输出的Xcode插件。虽然目前已经可以搜索到控制台日志输出的文本，但是仍然还有大量你不感兴趣的日志。MCLog是对此问题的一个简单解决方案。使用简单的字符串来过滤控制台，并显示你真正想看到的日志.

[AMMethod2Implement](https://github.com/MellongLau/AMMethod2Implement)： 可以自动的将.h或者.m、.mm里边需要写入的方法自动填充进来。可以选择要导入的方法，然后按 Ctrl+A 或者 Edit > AMMethod2Implement > Implement Method.就会自动填充方法.也可以自行设置快捷键。目前版本支持h文件声明方法自动生成实现，m或者mm文件已写好的方法生成方法声明到h文件， extern NSString * const， @select(method:) 和 [self methodName] 实现代码生成。

[Auto-Importer](https://github.com/citrusbyte/Auto-Importer-for-Xcode)： 可以搜索和自动导入头文件的一款Xcode插件。

[ColorSense](https://github.com/omz/ColorSense-for-Xcode)：具有可以用颜色选择面板直接插入颜色代码和颜色代码显示颜色预览功能。

[VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode)： VVDocumenter是一款输入///就会自动生成javadoc风格注释的Xcode插件。

[AMLocalizedStringBuilder](https://github.com/MellongLau/AMLocalizedStringBuilder-Xcode-Plugin)：AMLocalizedStringBuilder 是可以帮助你将语言本地化文件Localizable.strings生成object-c的类AMLocalizedString的Xcode插件，这样可以直接使用R_String.am_<#你的本地化字符串key#>获取对应key的值，还可以随时点击Alt或Option按键查看当前字符串的值

[R.swift](https://github.com/mac-cain13/R.swift)：类似AMLocalizedStringBuilder，不过是swift版本的，功能也更丰富，不仅支持Localized strings映射，还支持其他资源的映射，支持的列表如下：

```
- Images
- Custom fonts
- Resource files
- Colors
- Localized strings
- Storyboards
- Segues
- Nibs
- Reusable cells
```

[CopyIssue](https://github.com/hanton/CopyIssue-Xcode-Plugin): 方便你搜索的任何错误或警告的问题，可以复制完整的问题描述，或者可以自动打开你的默认浏览器并通过Google（默认快捷⇧⌥G）或Stackoverflow（默认快捷⇧⌥S）搜索你选择的问题。



## **如何安装**

安装方法目前有两种：

- 从github下载源代码进行安装

```
$ git clone git@github.com:插件地址
```

打开插件项目运行，运行成功后程序会自动把插件文件拷贝到这个路径下：

```
~/Library/Application Support/Developer/Shared/Xcode/Plug-ins
```

重新启动Xcode使插件生效。

- 通过Xcode插件管理器 Alcatraz 进行安装，安装完成后也要重新启动Xcode使插件生效。