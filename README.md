# 5个编程小练习
## 1.对话框 ##

界面有两个按钮，点击时分别弹出提示对话框和登录对话框，其中登录对话框要求用户输入UserId和Password，如果UserId和Password不是“abc”、“123”，则使用Toast提示错误，否则提示成功。

**知识点**： 用AlertDialog.Builder来创建一个弹出消息框，从中编写2个输入栏EditText，通过if语句判断UserId和Password，最后用Toast来弹出登录是否成功。

## 2.Acitvity间的数据传输 ##

多个Activity之间来回传递数据，既能够将数据传递给指定的Activity，也能够获得Activity返回的数据。

**知识点**： 在Main_Activity相同目录下新建一个Another_Activity文件，为其编写xml界面样式，通过mainActivity中的按钮启动另一个activity并用intent对象传递参数。

## 3.使用Intent隐式启动 ##

掌握使用Intent隐式启动的方法

**知识点**： 使用Intent隐式启动，系统会智能匹配与intent-filter内容相符合的进行输出，用户可以自行选择启动那个，关键就是在intent-filter过滤器里面编写条件。

## 4.内部存储文件操作 ##

实现向内部存储卡写入学号、姓名等信息并读取、显示这些信息。

**知识点**： 用FileOutputStream创建对象后，openFileOutput()函数为写入数据做准备而打开文件，如果文件存在就打开，不存在就创建一个。openFileInput()函数为读取数据做准备而打开文件。

## 5.使用Handler处理消息 ##

使用Handler在新线程中发送消息，然后在主线程中处理消息。

**知识点**：
