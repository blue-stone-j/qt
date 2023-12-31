# qt
这是一个以qt为主题的库。我使用的编译器版本为5.12，qt5应该都是可以直接编译的。

### example
1. 这一个文件夹的内容是关于qt使用的示例，本身也是一个qt项目。<br/>
2. `widgets`这个文件夹保存了一些控件。对于每个控件，有`.cpp`、`.h`、`pri`三个文件，使用时在`.pro`文件中include即可使用。每个控件的代码都有比较详细的注释，可以根据自己的需要修改。如果你认为注释意义不清或有缺少，欢迎提出，我会尽快增加或修改注释。我把控件展示在了主窗口中。稍后会在我的博客中详细介绍这些控件的用途和特性。
3. 常用的函数以及控件的用法。

### c-qt
一个qt示例程序。完全使用CMake编译执行qt程序，不再依赖qt自带的编辑器，可以很方便地添加其它功能，比如可以把ros功能包和qt界面相结合。使用的qt版本为5.12。

### displayPC
一个显示点云的qt程序。

### 未完待续
这一部分是一些实际的qt项目。