#Android笔记
google的databinding mvvm绑定，等价于后两个

RxAndroid
Retrofit 2  异步任务
等库
Dagger2  依赖注入，实在很复杂 学习曲线陡峭
MVP思想

用Retrofit类创建接口服务, 指定Gson为转换器, RxJava为适配器


是Square开发的网络请求库, 简化了网络请求的使用，A type-safe HTTP client for Android and Java



异步请求

不用RxJava


dagger2，并不涉及MVP，同时结合了当前流行的 Retrofit 2.0 、RxAndroid 等库（回想刚开始的时候做Android自己封装AsyncTask和使用BroadCast简直和原始人刀耕火种无异啊

Dagger已经加入Google I/O, 是Square开发的依赖注入库, 发布2.0版本

Dagger2是Dagger1的分支，由谷歌公司接手开发，目前的版本是2.0

库
总线bus


dependency injector for Android and Java. http://square.github.io/dagger/

RecyclerView 与 CardView 小组件为 v7 支持内容库的一部分


DirectionalViewPager代替ViewPager
gallery代替viewpager

Android 5 新出的
RecyclerView 、CardView（不是GridView） 、Palette

RecyclerView只负责回收和重用的工作{   因为 Gallery 被淘汰了,替代ListView，也可以实现GridView同等效果
RecyclerView需要 support-v7
dependencies标签下添加compile 'com.android.support:recyclerview-v7:23.3.0'

对于RecyclerView，谷歌决定使用新的RecyclerView.Adapter基类来取代旧的Adapter接口。所以，SimpleCursorAdapter、ArrayAdapter都将成为历史，或者至少不会是他们现在的这种使用方式。

目前RecyclerView.Adapter还没有默认实现，以后可能会添加

RecyclerViewPager 替代  Android.support.v4.view.ViewPager
https://github.com/lsjwzh/RecyclerViewPager



}


谢谢，我想表达的是，虽然XML Pull的API变了，但翻翻最新的API文档，再琢磨一下就会用了。（后来我干脆不用XML，而是用JSON字符串跟后端服务器通讯，在Android端用gson来解析JSON）

虚拟机图标注释，说明：
向左的三角  返回
原形  语音助手
方块  多任务列表

房子  手机主界面，主屏幕
多条横线  切换

别人的后台管理：
admin
12345

下载安装好Git，安装的时候选添加到Windows的环境变量里
D:\Software\Git
https://git-for-windows.github.io/
msysgit (Git for Windows)
C:\>git-gui，右键桌面后，列表无效
别人上传的时候，好像没有上传gradle

然后配置一下Git.exe的路径

HTTP的方法  RESTful API
get
post
put
delete

后端 开发和部署的工作

Chrome下调试REST api

https://api.bmob.cn/1/users/
https://api.bmob.cn/1/classes/GameScore/e1kXT22L
访问 https://api.bmob.cn 域名，不是Bmob首页的域名

1 第一版API
classes 看做是文件夹，是表的集合classes/GameScore  访问classes 文件夹下的GameScore表
users users表
/classes和/users并列，一个级别

测试：
url
https://api.bmob.cn/1/classes/person/Yq3vCCCL
get请求头
X-Bmob-Application-Id
f2adf0c6f2f2f373586819100cc61eab
X-Bmob-REST-API-Key
8e303f51d14a8ed096b2fceb965b51ad
返回的数据   strJson字符串
{"ID":2,"createdAt":"2016-05-22 15:31:38","name":"B","objectId":"Yq3vCCCL","updatedAt":"2016-05-22 15:31:38"}
格式化后
{
    "ID":2,
    "createdAt":"2016-05-22 15:31:38",
    "name":"B",
    "objectId":"Yq3vCCCL",
    "updatedAt":"2016-05-22 15:31:38"
}


app ID
f2adf0c6f2f2f373586819100cc61eab
REST API Key
8e303f51d14a8ed096b2fceb965b51ad

任何东西，只要能发起HTTP请求（get或post），就你可以使用Bmob提供的接口（REST API）和进行数据交互


postMan插件或者在linux系统环境下调试，curl在windows环境下请求存在数据格式转换的问题。

Chrome插件     RESTClient插件
postMan  调试get和post请求的   RESTful APIs的  Postman helps you develop APIs faster.
https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm?utm_source=chrome-ntp-icon


https://www.baidu.com

curl -X POST \
curl -X https://www.baidu.com
curl -X http://www.baidu.com
curl -X http://www.csdn.net/article/2013-03-06/2814373-baas-for-mobile-backend-development
curl http://www.centos.org

curlhttp://www.baidu.com

中文乱码
curl http://www.csdn.net/article/2013-03-06/2814373-baas-for-mobile-backend-development

curl 不支持https

curl -X GET\
    -H "X-Bmob-Application-Id:f2adf0c6f2f2f373586819100cc61eab" \
    -H "X-Bmob-REST-API-Key: 8e303f51d14a8ed096b2fceb965b51ad" \
    -H "Content-Type: application/json" \
   https://api.bmob.cn/1/classes/person/Yq3vCCCL

curl -X GET    -H "X-Bmob-Application-Id:f2adf0c6f2f2f373586819100cc61eab"    -H "X-Bmob-REST-API-Key: 8e303f51d14a8ed096b2fceb965b51ad"    -H "Content-Type: application/json"   https://api.bmob.cn/1/classes/person/Yq3vCCCL



curl -X GET



F:\Software\PowerCmd_2.2_green

owerCmd绿色版自带的curl 命令行工具



DataBinding
大家会不会在自己项目中使用Android新推出的DataBinding? http://www.zhihu.com/question/33538477 （分享自 @知乎 安卓客户端）

MVVM后 , 怎么控制控件? 文档里好像有说


suffix    ------- 色1 fi ks
n.    后缀，词尾;
vt.    加后缀，加词尾;
suffixing ----色1 fi sing
(动名词) 加后缀



data-binding
<layout xmlns:android="http://schemas.android.com/apk/res/android">
<layout xmlns:android="http://schemas.android.com/apk/res/android">
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android">


它是个库 , 这样方便给没有这个API的安卓系统用

洛杉矶不行
win10群上那个的国外光线
凤凰城很好

通过QQ
欣毅换手机
  http://swift-cloud.space/index.php  没有技术支持 , 有些网站不能上的话 , 很难反馈回去
https://developers.google.com/
https://developer.android.com/
谷歌官方文档
VPN翻墙
pac代理





经历
平时项目, 小公司才看重这个
奖项
成绩
上海那个大公司不考算法 , 要的是java软件工程师
大公司不怎么看 , 因为不知道是不是抄的 . 

福富的简历赶紧投呀 , 10月份就来了



给 ImageView 设置图片 , 动态的
imageView.setBackgroundResource(R.drawable.weather_icon);
imageView .setImageResource(getResources().......

废弃 HttpUrlConnect和HttpClient( 在android6.0中被废弃 )

volley是谷歌官方在2013年推出的
不适合上传和下载
能缓存图片和网络
可以返回字符串 , 然后它自动帮我们封装为一个oJson
怎么填写get请求头的数据

Vibrator



onCreate()  , 初始化在这里做 , 因为此时Activity不可见 , 所以动画的初始化别在这里,  而应该在onStart(). 
官方注释中，明确建议 setContentView()、findViewById() 要在 onCreate() 中被调用. ( 但在onStart()中不会报错 )

onStart() 被调用时，Activity可能是可见的，但还不能交互， onResume() 的注释中都明确地说了这不是Activity对用户是可见的最好的指示器 .


Android Studio : 原生快捷键才支持
logt TAG静态字符串
logd
setting   import 
logm  打印方法名和参数


c+a+空格 联想   eclipse中是a+/
c+y 删除当前行

 
Ctrl+j ( 不一定要先按ctrl+j , 可以直接输入fbc等"指令" )  Insert Live Template  插入模板 ( 其实就是代码段 , IntelliJ自动帮你生成 )
自动生成代码 , 根据代码模板 , IDE自带一些模板的 , 可以自己添加和修改
输入 todo 
//TODO 和 //TODO +时间
前面那种是我
我自定义了
sys等于eclipse的syso
fin等于AS原来的fbc
为什么光标会自动定位到需要补充的位置?比如 : 我想输入sys后生成
System.out.println(""); 并且光标不是在最后,而是在两个引号中间 ,
就像输入AS原生的fbc后生成
() findViewById(R.id.); 并且光标跳到第一个小块号里面 , 而不是最后
##########
自定义的 Live Template
todo 
//TODO+空格

main
Public static void main(){

}

描述
Public static void main(){}

syso
System.out.println("");

##################################################
简化开发
完全可视化开发的话 , 就没必要IDE帮我们这么智能地联想代码段了
可视化 , 完全自动 , 也就没必要自己搞了
自己封装一些常用代码
IDE的代码段 , VS . 而IntelliJ是通过快捷键自动生成一行
注解的方法


cs+回车 自动补全分号
a+回车  自动辅助提示 , 比如类型转换findViewById(...)

c+t 提示参数
为什么不是像eclipse一样统一用 a+回车 ? 而且t也不是参数这个单词的首字母

a+下  类间方法的移动
c+上

看别人的项目 看源码
单步调试 , IDE自动帮我跟踪各个方法
人脑跟踪代码逻辑 , 
IntelliJ , 从类内里的调用该方法的地方( 方法体出现在新小窗口 . 光标跳转到方法体 , 还可以回来 . 列出所有方法 , 默认不显示匿名方法  ) sayHello();  到 Public void sayHello(){ //输出语句 };
eclipse 似乎没有小窗口 , 其他都有
记事本打开代码 , 纸和笔记录对象和方法之间的调用逻辑 , 调用顺序



使用IDE的各种高级功能 :
鼠标选菜单栏  快捷键 
eclipse重点是前面( 分类很清楚 , 稍微熟悉一下后就不会忘记 ) , IntelliJ重点是后面

想DIY自己的IntelliJ , 把各种高级功能弄到菜单栏里 , 然后项的边上同时显示快捷键 , 看久了也就记住了
这样两个都有
(鼠标+GUI)   和   CMD

项目里面新建   lib和module
还可以导入别的

#########################################################################

ViewPage 类
在 support-v4 包里面

聚合数据
http://v.juhe.cn/weather/index?format=2&cityname=%E8%8B%8F%E5%B7%9E&key=您申请的KEY

http://v.juhe.cn/weather/index?format=2&cityname=%E8%8B%8F%E5%B7%9E&key=c48b23966e4ee5e43b1d44b307548a87







AS 添加 第三方包 依赖
右键module  
open module  setting
depend 加号, 搜索并添加进来 , 自动配置 , 直接使用


集成录音宝
http://www.871bb.com/



win7上用swift , 还不成熟
Android将来可能用swift, 而不是java

就算没有自己手动写 setContentView(R.layout.debug) 也会有默认的界面( 全白或者全黑的空界面, 主Activity )



as真的不玩了 很吃内存,环境变量出问题
虽然有gradle和很快的Android模拟器


完善功能
说明文档继续写

#lock#1
#del#
#locate#
#alarm#1
#back#1

项目测试:
可以: /测试成功
设置 密码
找回密码
能到主界面{
	设置按钮的功能
	清理掉信息之类的
	
}
重点是锁屏



5和9
5短信拦截 不能像黑客一样拦截
9远程定位 失败


锁屏 广播接收者接收到操作码后,调用服务,然后调用窗口管理器,不能在Activity锁屏,因为可以按回退按键


拓展功能不要,做天气那个


1555
521
5558
15555215558

#lock#

#lock#1

6  密码错误

歌曲
I’m yours 

backup 备份


#########################################################################################################
Android开发 /Android笔记 Android技术 安卓开发 Android基础知识 Android笔记 Android技术笔记
Activity闪退 解决方法:
xml配置错误,没有配置第一个Activity
xml和布局文件里多了一些东西,但不报错


写到了 百度经验 里:
快速地找Android studio的　R.java文件：
按顺序点击: (注: 如果面板已经打开,点击后会缩回去)
Android Studio 最左侧工具箱里的Project，会打开＂Project面板＂(字是旋转了90度的)
它的最左上角,默认应该是Project，单击它，选择Package
点击app文件夹下的你的包名，会看到该项目已有的所有.java文件，其中有R.java文件．

快速地找Android studio的　R.java文件：
按顺序点击: (注: 如果面板已经打开,点击后会缩回去)
1，Android Studio 最左侧工具箱里的Project，会打开＂Project面板＂(字是旋转了90度的)
2，它的最左上角,默认应该是Project，单击它，选择Package
3，点击app文件夹下的你的包名，会看到该项目已有的所有.java文件，其中有R.java文件．

R.java文件的路径: (相对于项目路径)
项目文件夹\app\build\generated\source\r\debug\包名\R.java
######################
清理 手机还是内存卡:\Android\data\com.sina.eduvideo.downloaderprovider\downloads
p2p缓冲
ten 注意不要把qq接收的删了

######################
Application
能打电话吗
发短信?

application的onCreate在activity的onCreate之前执行
里面放所有Activity一起的东西,不是用静态字符串,因为容易把这些字符串归到某个类
要注册一下
<application
	android:name="com.bdmap.view.MapApplication"
	...
一些每个Activity都要做的事情放在Application对象(要自己写个类来继承它)的onCreate()里
######################


######################
在CSDN上插入代码 高亮显示
要能方便地导出数据
修改要方便
能很容易被别人检索到

在eclipse里调试Android代码
1.  输出调试信息:
2.  Log.v(TAG,"a的数值"+)
吐司 Toast.makeToast
3.  System.out.println() 在控制台输出信息,这个很可能失效,无任何信息


####eclipse里调试Android代码:
输出调试信息:
 1. Log  
```java
Log.v("TAG","a的数值: "+a)
```
 2. 吐司 Toast.makeToast
 3. 在控制台输出信息,这个很可能失效,无任何信息
`System.out.println()`
######################
<intent-filter>
	<action android:name="android.intent.action.MAIN" />

	<category android:name="android.intent.category.LAUNCHER" />
</intent-filter>

######################
自带的模拟器叫
emulator-5554
emulator-5556

listView 300差不多

Log.e("TAG",);

//TODO 注意这边可能null
都大写
在Tasks视图,窗口里

Conversion to Dalvik format failed: Unable to execute dex
关于Suppressing notification from package com.xxx.xxx by user request.的异常
闪一下就没了
解决方案: 拖拉控件的时候,IDE有BUG,给我多了个标签: resource
注释 配置文件 的过滤器的时候,没注释好

  
String ->Integer  Integer.parseInt("1")
Integer ->String  String.valueOf(1)
综合:String temp =String.valueOf(Integer.parseInt(age)+1);


引用在XML里面引用图片:
android:src=@mipmap/pic:

在java代码里引用图片: //通过 Activity对象的Resources对象,根据R文件里的这图片的ID(int类型)得到
getResources( R.drawable.pic );/


public android.content.SharedPreferences getPreferences(int mode) {};

Toast对象的使用: /吐司
/	**
	* Toast对象是相继出现的,不会同时.位置移动一下就好了.setGravity()的第2,3个参数是X,Y(数学坐标系,Y向上增长),以第一个参数为原点.
	* setGravity()和show()返回void,所以不能用链式编程. Toast.makeText(..).setGravity(..).show();
	* setGravity()和show()可以不分先后调用顺序,即 show()不一定要放在最后.就像是XML的设置属性一样
	* 或者Toast.makeText(__).show(__).setGravity();
	Gravity.BOTTOM 中下,最底下,贴线了
	
	
	当有多个Toast对象的时候,默认是从代码的上面开始执行,按顺序,前一个消石后才有下一个,可以显示在同一个位置
*/

//Context context
显示的时间短:
Toast.LENGTH_SHORT

显示的时间长:
Toast.LENGTH_LONG

Toast.makeText(getApplicationContext(),"", Toast.LENGTH_SHORT).show();

Toast.makeText(context,"", Toast.LENGTH_SHORT).show();



Toast toast1= Toast.makeText(getApplicationContext(),"1", Toast.LENGTH_SHORT);
toast1.setGravity(Gravity.CENTER, 0, 0);
toast1.show();

Toast toast2= Toast.makeText(getApplicationContext(),"2", Toast.LENGTH_SHORT);
toast2.show();
toast2.setGravity(Gravity.CENTER, 0, 100);


Toast toast___= Toast.makeText(getApplicationContext(), "0,0", Toast.LENGTH_SHORT);
toast___.setGravity(Gravity.BOTTOM, 0,0);
toast___.show();

Toast toast_close= Toast.makeText(getApplicationContext(), "0, -300", Toast.LENGTH_SHORT);
toast_close.setGravity(Gravity.BOTTOM, 0, -300);
toast_close.show();

Toast toast_= Toast.makeText(getApplicationContext(), "0, 300", Toast.LENGTH_SHORT);
toast_.setGravity(Gravity.BOTTOM, 0, 300);
toast_.show();

BroadcastReceiver 要注册

Service类:
需要注册
	似乎只能静态注册:可以在配置文件里
	<service ></service>
 
	无法像BroadcastReceiver一样同时有动态注册,通过Activity
	


Service 是运行在主进程的main线程上的,Activity也是
如果Service要开启耗时间的任务,要调用new thread(重写run方法).start();  因为它自己是在主线程上的
Activity调用startService(Intent)实例化Service类,自动调用Service对象的onStartCommand

DDMS的syso很可能没有结果System.out.println("something"); 应该用吐司,然后把Activity对象传进去


mHandler.sendEmptyMessageDelayed(GO_SETTING, 2000);

其他线程向主线程发信息(Message),通过Handler对象.
把Handler对象看做主线程,把它的"发送消息sendMessage(Message)" 看做"接收消息"

Activity之间传数据,可以用

设置定时器:
Timer timer = new Timer();  
timer.scheduleAtFixedRate(new MyTask(), 1, 5000);  
private class MyTask extends TimerTask{  
	@Override  
	public void run() {  
		setTitle("Welcome to Mr Wei's blog " + title);  
		title ++;  
	}
}

mmt-sd指向到
storage sd卡

安装app到模拟器(当前只有一台模拟器被连接)
adb install -r G:\0_temp\signal_Android.apk

c+s+c 清理项目

eclipse中, findViewById后强制类型转换  的 快捷键
比如:
把
Button btn= findViewById(R.id.Button1);
弄成
Button btn= (Button) findViewById(R.id.Button1);
ctrl+1后回车,一般联想出来的就是你想要的,所以应该"马上"回车,节省时间

本质上是用 eclipse的"Quick Fix快速修复"这个功能, 它的默认快捷键是ctrl+1 (是数字1,不是英文字母 L 的小写) . 如果快捷键无效的话, 在菜单栏的 Window->preferences->general->keys 的搜索框里查找"Quick Fix"然后设置自己喜欢的快捷键.

listView.setOnClickListener(new OnClickListener() {




eclipse的输入联想 content assist
. <=abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ
里面有个空格,故意不让它在首尾,不然会被无视掉
##############################
小米3 app软件的安装目录
/mnt/shell/emulated/0/Android/data/ 
##############################
小米手机一回到桌面就"正在加载桌面"
{
解决方案: (我的手机是小米3电信版)	设置-其他高级设置-开发者选项-关掉"不保留活动"-把"后台进程限制"设置改为"标准限制".
会这样的原因:
系统一直不停地清理手机内存,为了马上腾出内存,所以不保留后台的进程.
}
##############################
view界面是声名式开发
另一种是命令式开发(不只是能用在view上,在C和M也能用),举例: new A().start()

声明式开发 命令式开发
声明式编程 命令式编程

用原生的安卓系统做开发(虚拟机和物理机),因为用小米的系统,你很难找到应用的目录,比如com.example.HelloWorld

安卓版本和API版本: 
http://www.baidu.com/s?wd=%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%AC%E5%92%8CAPI%E7%89%88%E6%9C%AC%3A&ie=UTF-8
Android_4.4		API_19		KITKAT

Android_
API_

Android_4_4_API_19
Android__API_

template_


包名里的小数点慎重地使用,
比如包名里像表达: Android_4.4,应该改为Android_4_4

minimum reuired SDK 最低版本 , 这个应用只能第到
target SDK
complile with 自己本机上的SDK
Android 6 的安装包可以在Android 4上用,因为(6)向下兼容(4)

Theme 主题  最好设置为None

向下兼容:比如 Android 6 的安装包可以在Android 4上用
一直往上叠加,所以叫做"向下"兼容,4在6的下面
Android 6
Android 5
Android 4
.
.
.
(小数点表示省略号,还有版本数字更小的,比如2)


android-studio-ide-143.2544347-windows



15555215554
15555215556
15555215558


#back#1


左边的是这部手机收到的
右边是发送出去的
两边都会记录下来

头像在右边,说明是发送


用真机测打电话和发短信
GPS定位
传感器


不能在eclipse中启动一个 库项目
都是在属性面板里面设置
把A项目设置为 库项目
B项目引用它

库项目不能有错


新建Android项目后:
在xml里加所有权限
确定一下发布的Android API版本是不是19

2014年谷歌I/O大会推出Android 5.0后，谷歌直接删除 Dalvik
代替它的是ART编译器。它能够加快安卓应用程序的运行度，但安装和优化过程略长一些，大型的应用程序往往需要几分钟。
本次Android 7.0采用的ART JIT编译器，则在两方面达到了兼顾。

ART代表Android Runtime
这一机制叫Ahead-Of-Time (AOT）编译
总的来说ART的功效就是“空间换时间”

##################################################
Android Studio 导入项目后 :

eclipse导入别人的Android项目后 :      /导入项目
留意一下Android_SDK路径是否自动切换为我的路径 , 比如对方的在D盘 , 我的在F盘

在 uses-sdk 标签里 : ( 如果是Android Studio , 还要在gradle的各个xml里面改 )
android:minSdkVersion="19"
android:targetSdkVersion="19"

在 Application 标签下面添加各种权限

这个项目的编码方案可能要改为UTF-8 , 不然中文可能会乱码

找入口 , 在 AndroidManifest.xml 里搜索 android.intent.action.MAIN

常用代码: /常用代码段

在MyApplication里 :  一定要叫这个名字  , 因为xml和代码里写死了

public Tools tools=null;
@Override
public void onCreate() {
    super.onCreate();
    tools= new Tools(this);
}

在 application标签里 配置 MyApplication
android:name="com.example.bugweather.MyApplication"

在各个Activity :
外面 :
Tools tools =null;
onCreate() 方法体里:
tools =( (MyApplication)getApplication() ).tools;
别都在 onCreate()外写,会出错 , 不知道为什么 , 应该是类的加载顺序

这样 , 就不用在每个Activity里 new 对象 , 如 :
Tools tools=new Tools(this);

Activity里 :
Context context=this;
Tools tools=( (MyApplication)getApplication() ).tools;

		
<activity
	android:name=""
	android:label="" >
		<intent-filter>
			<action android:name="android.intent.action.MAIN" />

			<category android:name="android.intent.category.LAUNCHER" />
		</intent-filter>
</activity>

<intent-filter>
	<action android:name="android.intent.action.MAIN" />

	<category android:name="android.intent.category.LAUNCHER" />
</intent-filter>

布局方面 :
android:orientation="vertical"
android:orientation="horizontal"

LinearLayout

<TextView
	android:id="@+id/textView1"
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:text="hello_w" />

<Button
	android:id="@+id/button1"
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:text="Button" />




import android.os.Handler;

Handler handler = new Handler() {
	public void handleMessage(android.os.Message msg) {
		switch (msg.what) {
		case 1:
			tools.toast("in Handler");
			break;

		default:
			break;
		}
	};
};

在执行的时候 onCreate 方法里 , Activity里
handler.sendEmptyMessageDelayed(1, 1000);



adb shell
adb uninstall com.apistore.sdk.demo

List of devices attached
60A5AF01        device
adb devices


当前Android Studio的各种最新的环境 , 2016.5.3 


喜好配置
C:\Users\Administrator\.AndroidStudio2.1\config


为什么Egret开发的游戏在某些Android设备上特别卡？
{
在 Android 早期版本（ 4.4 之前） ，Android WebView 并不 100% 支持 HTML5 特性，如 WebGL、PageVisibility 、 WebSocket 等。
 
Google 为了解决这些问题，在 4.4 版本中，完全删除了原有的 WebView ，将其替换为了 chromium 架构的新 WebView。
 
由于这个修改的工作量过大，在部分特性在尚未全部完成的情况下，Android 就发布了 4.4.2 版本作为过渡，这导致了部分特性在 4.3版本是存在的，但是4.4.2 反而丢失了。 其中我们遇到的情况就是 Canvas 硬件加速特性丢失。
 
在 Android 4.4.4 版本中，google 完全完成了 WebView的架构迁移，Canvas硬件加速特性被重新置入 WebView中。
 
由于 HTML5 游戏依赖于 Canvas 渲染，而是否存在硬件加速对渲染结果有几十倍的差异，所以 HTML5游戏在 Android 4.4.2 系统上卡顿的问题由于操作系统限制，几乎不可能在应用层解决。
}


得到xml文件里的字符串 
getResources().getString( R.string.wilddog) )


Android标签和dependencies标签同级，并列
