# AndroidStudio ShortCut

当然网上也有很多关于 Android Studio 快捷键的文章，但感觉太冗杂，而且不同的平台快捷键又不一样，导致对着 Mac 打 Win#Eclipse 的快捷键不起作用。所以本篇文章整理的目的在于，`列出使用频繁的快捷键`并`告诉你在哪里设置它们`，而且`文字看不懂的还有动画`，这样即使你用的键盘跟我不一样，你也知道应该去哪里设置相应的键位。

全局说明：

- 我用的是 Mac，键位是 Mac OS X 10.5+，如下图
  
- 若你要修改对应的快捷键，去 Settings->Keymap 中修改，如下图
  
  ![keymap](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_androidstudio-keymap.png)

### 0x01 定位目标

| 功能                                       | 快捷键          | 位置                                       |
| ---------------------------------------- | ------------ | ---------------------------------------- |
| [搜索类(Enter class name)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+O.gif) | Cmd+O        | Main menu->Navigate->Class               |
| [搜索方法或字段(Enter symbol name)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Option+O.gif) | Cmd+Option+O | Main menu->Navigate->Symbol              |
| [搜索文件、目录(Enter file name)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+O.gif) | Cmd+Shift+O  | Main menu->Navigate->File                |
| [Search Everywhere](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Shift+Shift.gif) | Shift+Shift  |                                          |
| [查看字段、方法、类、文件都在哪些地方被使用了(全局)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Option+F7.gif) | Option+F7    | Main menu->Edit->Find->Usages            |
| [查看字段、方法、类、文件都在哪些地方被使用了(当前文件)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+F7.gif) | Cmd+F7       | Main menu->Edit->Find->Find Usages in File |
| [搜索任意快捷键(Enter action or option name) 很强大！知道快捷操作关键字即可！](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+A.gif) | Cmd+Shift+A  | Main menu->Help->Find Action             |

### 0x02 查看结构

| 功能                                       | 快捷键                                      | 位置                                       |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [查看定义](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+B.gif) | Cmd+B                                    | Main menu->Navigate->Declaration         |
| 跳转到具体实现位置 | Cmd+Option+B                                    | Main menu->Navigate->Implementation         |
| [智能选取](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Option+Up.gif) | Option+Up/Down                           | Editor Actions->Extend Selection/Shrink Selection |
| 查看本类结构                                   | [Cmd+F12](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+F12.gif) [Cmd+7](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+7.gif) | Main menu->Navigate->File Structure   Other->Structure |
| 查找和替换                                    | Cmd+F Cmd+R Cmd+Shift+F Cmd+Shift+R      | Main menu->Edit->Find/Replace            |
| [查看doc](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_F1Ctrl+J.gif) | F1 Ctrl+J                                | Main menu->View->Quick Documentation     |
| 查看当前类的继承关系                                    | Ctrl+H      | Main menu->Navigate->Type Hierarchy           |
| 查看方法调用关系                                    | Ctrl+Option+H      | Main menu->Navigate->Call Hierarchy           |

### 0x03 视图切换

| 功能                                       | 快捷键           | 位置                                       |
| ---------------------------------------- | ------------- | ---------------------------------------- |
| [显示目录窗口](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+1.gif) | Cmd+1         | Other->Project/Home Directory            |
| [显示收藏窗口](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+2.gif) | Cmd+2         | Other->Favorites                         |
| [显示AndroidMonitor](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+6.gif) | Cmd+6         | Other->Android Monitor                   |
| [显示类结构](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+7.gif) | Cmd+7         | Other->Structure                         |
| [最近查看文件窗口](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+E.gif) | Cmd+E         | Main menu->View->Recent Files            |
| [最近修改文件窗口](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+E.gif) | Cmd+Shift+E   | Main menu->View->Recent Changed Files    |
| [在当前编辑器切换标签](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+[%3A].gif) | Cmd+Shift+[/] | Main menu->Window->Editor Tabs->Select Previous Tab/Select Next Tab |
| [切换到顶部导航栏](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Up.gif) | Cmd+Up/Down   | Main menu->Navigate->Jump to Navigation Bar/Jump to Source |
| [视图切换Switcher](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+Tab.gif) | Ctrl+Tab      | Other->Switcher                          |

### 0x04 编辑代码

| 功能                                       | 快捷键                  | 位置                                       |
| ---------------------------------------- | -------------------- | ---------------------------------------- |
| [LiveTemplate](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+J.gif) | Cmd+J                | Main menu->Code->Insert Live Template    |
| [Generate](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+N.gif) | Cmd+N                | Main menu->Code->Generate                |
|  覆写父类方法 | Cmd+N                | Main menu->Code->Override Methods                |
| [智能提示](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Option+Enter.gif) | Option+Enter         | Other->Show Intention Actions            |
| [关闭当前活动窗口](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+W.gif) | Cmd+W                | Main menu->Window->Editor Tabs->Close    |
| 格式化代码                                    | Cmd+Option+L         | Main menu->Code->Reformat Code           |
| [将当前代码段上下移动](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+Up.gif) | Cmd+Shift+Up/Down    | Main menu->Code->Move Statement Up/Move Statement Down |
| [将当前行上下移动](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Shift+Option+Up.gif) | Shift+Option+Up/Down | Main menu->Code->Move Line Up/Move Line Down |
| [插入多个光标协同编辑](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Shift+Option+左键.gif) | Shift+Option+左键      |                                          |
| [从当前位置剪切到末尾](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+K.gif) | Ctrl+K               | Editor Actions->Cut up to Line End       |
| Surround With| Cmd+Option+T               | Main menu->Code->Surround With       |

### 0x05 重构

| 功能                                       | 快捷键          | 位置                                    |
| ---------------------------------------- | ------------ | ------------------------------------- |
| [移动文件](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_F6.gif) | F6           | Main menu->Refactor->Move             |
| [拷贝文件](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_F5.gif) | F5           | Main menu->Refactor->Copy             |
| [重命名](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Shift+F6.gif) | Shift+F6     | Main menu->Refactor->Rename           |
| [修改方法签名](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+F6.gif) | Cmd+F6       | Main menu->Refactor->Change Signature |
| [修改参数类型](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+F6.gif) | Cmd+Shift+F6 | Main menu->Refactor->Type Migration   |
| 引入一个局部变量                                 | Cmd+Shift+V  |                                       |
| 引入一个参数                                   | Cmd+Shift+P  |                                       |
| 引入一个类变量                                  | Cmd+Shift+F  |                                       |
| 引入一个方法                                   | Cmd+Shift+M  |                                       |
| 引入一个常量                                   | Cmd+Shift+C  |                                       |
| [显示重构菜单](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+T.gif) | Ctrl+T       | Main menu->Refactor->Refactor This    |

### 0x06 查看代码

| 功能                                       | 快捷键                   | 位置                                       |
| ---------------------------------------- | --------------------- | ---------------------------------------- |
| [查询某方法参数信息](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+P.gif) | Cmd+P                 | Main menu->View->Parameter Info          |
| [跳到方法定义](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+B.gif) | Cmd+B                 | Main menu->Navigate->Declaration         |
| [跳到变量的定义类](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+B.gif) | Cmd+Shift+B           | Main menu->Navigate->Type Declaration    |
| [跳到方法在父类或接口的定义处](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+U.gif) | Cmd+U                 | Main menu->Navigate->Super Method        |
| [跳到上/下一方法](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+Up.gif) | Ctrl+Up/Down          | Main menu->Navigate->Previous Method/Next Method |
| [跳到上/下一次光标查看处(阅读源代码时非常有用)](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Option+Left.gif) | Cmd+Option+Left/Right | Main menu->Navigate->Back/Forward        |
| [跳到指定行](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+L.gif) | Cmd+L                 | Main menu->Navigate->Line                |
| [显示方法层级结构](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Cmd+Shift+H.gif) | Cmd+Shift+H           | Main menu->Navigate->Method Hierarchy    |
| 调用层级结构                                   | Cmd+Option+H          | Main menu->Navigate->Imports Hierarchy   |

### 0x07 Run & Debug

| 功能                                       | 快捷键       | 位置                        |
| ---------------------------------------- | --------- | ------------------------- |
| [Run](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+R.gif) | Ctrl+R    | Main menu->Run->Run       |
| build                                    | Cmd+F9    |                           |
| [Debug](http://7xivx9.com1.z0.glb.clouddn.com/androidstudio_Ctrl+D.gif) | Ctrl+D    | Main menu->Run->Debug     |
| 单步进入                                     | F7        | Main menu->Run->Step Into |
| 单步跳过                                     | F8        | Main menu->Run->Step Over |
| 跳过本次debug                                | F9        | 有待商榷                      |
| debug时执行选中的语句                            | Option+F8 | 有待商榷                      |
