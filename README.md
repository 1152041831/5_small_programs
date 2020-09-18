# 5个编程小练习
## 1.对话框 ##

界面有两个按钮，点击时分别弹出提示对话框和登录对话框，其中登录对话框要求用户输入UserId和Password，如果UserId和Password不是“abc”、“123”，则使用Toast提示错误，否则提示成功。

**知识点**： 用AlertDialog.Builder来创建一个弹出消息框，从中编写2个输入栏EditText，通过if语句判断UserId和Password，最后用Toast来弹出登录是否成功。

## 2.Acitvity间的数据传输 ##

多个Activity之间来回传递数据，既能够将数据传递给指定的Activity，也能够获得Activity返回的数据。

**知识点**： 在Main_Activity相同目录下新建一个Another_Activity文件，为其编写xml界面样式，通过mainActivity中的按钮启动另一个activity并用intent对象传递参数。
