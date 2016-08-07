#Qt 中界面类名的修改



> Qt 中如果想要使用多个已经写好的界面类，往往会发现界面类的名称要么是“MainWindow”，要么是“Widget”，或者是“Dialog”。那么重名的界面类在一起就会在所难免。或者你想修改界面类的名称。那么一定要切记不可直接修改界面类的名称。否则和容易出错。


正确的解决方法如下：

* 1.修改.ui文件名称为xxxmainwindow.ui/xxxwidget.ui/xxxdialog.ui ：在工程树下右* 键修改即可。当然也可以为其他名字，总之要清晰明了有个性。

* 2.修改.h,.cpp名称与.ui文件名称对应：同样是在工程树下右键修改即可。

* 3.修改界面类名：右键类名，选择Refactor(重构器)->Rename Symbol under cursor(Ctrl+Shift+R)。

![](http://i.imgur.com/U5hMUJj.png)

然后在此处即可方便的修改。然后类名即可全部被替换修改。

![](http://i.imgur.com/XlzUuej.png)

![baidu](http://img.popoho.com/allimg/120613/1A1435916-2.gif "小马编程")

 