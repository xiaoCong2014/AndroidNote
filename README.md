# AndroidNote
Android笔记_备忘之类的






mvvm无法识别{
AS2.0就能识别 双向数据绑定库

把mvvm双向绑定的布局xml和Activity里的相应代码注释或者删除

Error:(8, 41) 错误: 程序包com.apistore.sdk.demo.databinding不存在
在gradle里关了mvvm后再开，编译没出错

没有根据我的设置，到指定环境变量里找gradle
也没去我手动在IDE了设置的路径找
而是自己下载的

无法识别
根标签layout 首字母要小写
}

import android.support.annotation.Nullable;
添加依赖，对着module按F12，本质上是在gradle那行代码





AS文件名变成蓝色

项目让程序运行起来{
先把mvvm双向绑定的布局xml和Activity里的相应代码注释或者删除

分析：
库都在
做了：
全改成23
xml里面，无关的Activity和<service>都注释了，不注册，这样就无法识别，然后C里不要调用它们
}


//include ':ReclerViewPractice'
第二个module，类似eclipse的项目

让程序可用，屏幕太小，在电脑桌面上，
先，分辨率改成400  400左右
用鼠标拉伸虚拟机窗口

总之就是改低一点，改小一点
太小：
1200  1920
800  1280


从AS里打开 单独的SDK manager ， 失效
无法解决，通过SDK目录下的两个exe分别打开
sdk环境变量肯定没错



这个需要用的时候再搞，是个支持库   android_m2repository_r07 
Failed packages:
- Android Support Repository (extras;android;m2repository)

ABI用x86  还是x86_64？


{
在AS里，双击包名也打不开包
果然是因为类似延迟这种原因，也可能是BUG
还有个BUG----shift拖着鼠标选中，这个也无效

在左侧的资源浏览器里
右键，单击

回车
F12
双击不行，只是远程的时候不行，在电脑上试试。
无法开发AS里的文件 , 双击和单击都试过了，双击文件打不开，xml和Java都一样
很可能是gradle的版本出错

重启电脑？
清理项目
重新导入项目，重新扫描目录
点击左上角的同步按钮
重启AS
重新打开项目无效，仍然无法打开

分析
gradle没错
compileSdkVersion 19
buildToolsVersion "23.0.2" 或 23.0.3
}



Gradle sync failed: failed to find Build Tools revision 23.0.0 rc3
  Consult IDE log for more details (Help | Show Log)
--配置一下Gradle的路径，F:\libs\gradle-2.12
%Gradle%

Error:failed to find Build Tools revision 23.0.0 rc3
<a href="install.build.tools">Install Build Tools 23.0.0 rc3 and sync project</a>
配置成已经安装好的
23.0.3
24
什么是Android Build Tools
怎么查看自己已有的版本
android标签下的 buildToolsVersion '23.0.3'
android {
    buildToolsVersion '23.0.3'
}

AS运行的时候，已经生成好的APK安装不上去，说是已经安装过旧版本，是否卸载
点击卸载后马上报错说未知错误，还是无法安装
实体机没有足够的应用空间安装，不是存储空间


Error:Error converting bytecode to dex:
Cause: com.android.dex.DexException: Multiple dex files define Landroid/support/v4/accessibilityservice/AccessibilityServiceInfoCompat$AccessibilityServiceInfoVersionImpl;

Error:Execution failed for task ':app:transformClassesWithDexForDebug'.
> com.android.build.api.transform.TransformException: com.android.ide.common.process.ProcessException: java.util.concurrent.ExecutionException: com.android.ide.common.process.ProcessException: org.gradle.process.internal.ExecException: Process 'command 'C:\Program Files\Java\jdk1.8.0_31\bin\java.exe'' finished with non-zero exit value 2

转码的问题
乱码的情况:
�


Error:(45, 25) 错误: 程序包R不存在
代码中的 R 字母 全变红
或者
R文件id找不到 比如 R.layout.main 这个R.java里的int类型的数据找不到 :
清理一下项目
{import的R包错了 , IDE的提示信息有时候错了, 误导程序员导入 SDK里的android.R包 ,不能是"import android.R" , 而瑛姑类似"import com..demo.R;"  , 然后清理一下项目
}
可能是xml文件里面有错,这个真的很难检查出来



用 百度市场的 api 来访问天气和地图


get请求
用了百度市场的 api
原生的不行
okhttp不知道怎么设置header

volley

http://www.oschina.net/android

http://www.oschina.net/code/snippet_12_5909

无法调试
难道是要等一下
难道是要重装软件


正在前台的应用无法调试 , 调试刚开始的时候 , 物理机上有很短暂的提示说要不要强制关了当前的程序( 这个应该是上一个 , 不是最新的 )

如果应用在后台也是
F6下一行
F5跟进标准库里的函数方法体里面


请求URL api 定位功能  , 不是JavaScript api
别用ok了 , 用原生的 , 可以加请求头
ok不知道为什么无法使用 
OkHttpClient okHttpClient = new OkHttpClient();


啊
Unicode   \u554a
UTF-8       &#x554A;
后面那是显示出来的样子

在okHttp3 的请求头里加浏览器标示
User-Agent:
Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/45.0.2454.101 Safari/537.36

No changes to deploy
debug的时候 , 没有改变的话就没法进行
Android Studio设置断点 , 点击调试 , 应用停止运行


setContentView(R.layout.main);  无法找到 main.xml
因为IDE不小心在R前面添加了 android , 本质上是R.java所在的包搞错了 , 不在android包下


Android Studio里使用 okHttp3 ( 不是2 )  okhttp 2 和okhttp3区别?
把下载好的okHttp-3.2.0.jar包和okIO-1.6.0.jar( 前者依赖后者 ) 弄到 \app\libs 目录下 , 再在Android Studio把它们添加到依赖里面 .  成功 ,因为 new OkHttpClient(); 这句没报错
试试3  compile 'com.squareup.okhttp3:okhttp:3.2.0'
fail to resolve   compile 'com.squareup.okhttp:okhttp:2.7.5'
https://github.com/square/okhttp
http://square.github.io/okhttp/

<head>
  <meta http-equiv="content-type" content="text/html;charset=utf-8" />
</head>


gbk
utf-8


别人的是打开 , IE是下载
http://api.map.baidu.com/location/ip?ak=E4805d16520de693a3fe707cdc962045&ip=202.198.16.3&coor=bd09ll


返回的是Unicode编码 的strJson

没有吐司? 我怎么知道我配置成功了没  //TODO 监听器里不能Toast
不给截图 , Android Studio就几句话
我不知道怎么配置so文件 , 官方自己不做 , 那给个别人的博客的链接也行呀
不是托管在GitHub上 , 别人无法帮官方改正 , 补充


配置比较麻烦 , 但这是为了安全
用官方的例子
参考那个例子 , 天气 , 但版本是旧的

 
build.gradle( 配置module的 , 不是 Project的 )文件中Android结点下添加
sourceSets {
 
main {
 
jniLibs.srcDirs = ['libs']
 
}
}
 build.gradle中配置SO



C:\Users\Administrator\.android>keytool -list -v -keystore debug.keystore

cd /d  C:\Users\Administrator\.android
keytool -list -v -keystore debug.keystore
证书指纹:
         MD5: 39:CD:5C:4F:D6:0B:6A:18:B7:A1:C3:B6:AB:EE:5C:75
         SHA1: FE:9A:B6:0B:84:FE:F9:C6:0B:0F:E2:30:2B:1D:24:50:CC:AD:B4:75
         SHA256: B6:D6:23:5E:1F:6F:AF:5E:93:85:0F:10:46:EA:BC:30:7A:84:22:63:2A:
CD:BC:30:09:E0:2C:DD:EE:90:54:69
         签名算法名称: SHA256withRSA
         版本: 3

包名  com.apistore.sdk.demo
安全码：   
FE:9A:B6:0B:84:FE:F9:C6:0B:0F:E2:30:2B:1D:24:50:CC:AD:B4:75;com.apistore.sdk.demo
百度定位SDK的key :
F7kVVCUTwyZ8cvVNERW61DZSKUgFv7C3

把GBK字符串转码为UTF-8

Could not open Selected VM debug port (8700). Make sure you do not have another instance of DDMS or of the eclipse plugin running. If it's being used by something else, choose a new port number in the preferences.

运行按钮无法使用
最后选中module , 然后运行按钮就能用了
因为找不到默认的Activity , 在xml里配置一下就行了


本质上是因为碎片化 , 大家的版本不同
兼容低版本 , 但低版本没有新的SDK , 就把新的SDK , 主题 , 之类的打包到一个项目里 , 不是某个jar库

然后开发环境中的项目本来只能发布到API 22 上 , 无法兼容低版本 , 因为项目里调用了新的SDK , 而低版本没有 . 但添加了依赖后就能使用了

是依赖项目 , 不是依赖jar包( 库 ) .android-support-v7-appcompat项目 , 里面有ActionBarActivity类
已经添加 support.v7包 到构建路径了
import android.support.v7.app.ActionBarActivity;

天气项目
笔试
其他项目

16:11:52 Adb connection Error:远程主机强迫关闭了一个现有的连接。
16:11:53 Connection attempts: 1



重启AS无效
手机连不上

模拟器上会快一点吗

清理一下小米平板的空间

在xml配置文件里面改包名
package="com.dingxiaoyu.iweather1"

AS提示说我已经安装过这个软件了 , 是因为平板上已经有这个包名的文件夹 , 卸载的时候没有删除干净 . 
手动去找费时费力 , 而且可能根本找不到 , 因为是小米自己改的系统

平板应用空间不够?
同样一根线 , 手机就可以 , 之前手机上没有安装这个软件
改app版本号 ( 但明版还是连不上 )
重启电脑 
线有问题
不然就清理缓存
重启AS软件
重启平板

包名重复
平板安装不上



Installation error:      INSTALL_FAILED_INSUFFICIENT_STORAGE
getUrlSourceCode       Please check logcat output for more details.
getUrlSourceCode       Launch canceled!


https://ke.qq.com/webcourse/index.html#course_id=23825&term_id=100007429&taid=149550761270545&vid=m1400hammll

getUrlSourceCode
HtmlParser  
getHtmlContent (URL url, String encode) 

用OKHttp 重新实现 , 代码应该会简洁很多
要模拟浏览器的行为 , 请求头要有

之前ok出错
为什么不能直接 get网页 , 然后直接打印? 因为get请求头里没有浏览器的符号吗


IDE单步调试功能
这样看代码的话 , 流程很清晰


Android 用debug模式启动应用 , 调试的时候  Source not found :
添加SDK文件夹下的source文件夹

octvm_drv
common drv: platform_autosave_handle -> not implemented

tag   WifiController
Not handled here 155652

难道是因为编码

Can't bind to local 8600 for debugger


okhttp发get请求 , 应用

Invalid layout of preloaded class: use -XX:+TraceClassLoading to see the origin of the problem class

TAG :
AndroidRuntime
 :
java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.example.checkupdata; is package not installed?

应用名 :
com.example.checkupdata






初始化在onCreate()里 , 不然可能出错


INSTALL_FAILED_INSUFFICIENT_STORAGE

Unable to access Android SDK add-on list
取消掉 , 然后设置一下 离线版的Android SDK 的本地路径




谷歌地图API 无法在中国用
Android上要VPN翻墙


应用空间不足 ( 不同于存储空间 ) , 卸载应用 . 多卸载几个
Android Studio INSTLL_FAILED_INSUFFICIENT_STORAGE

之前试过 , 但无效 :
manifest 里添加一行 :
android:installLocation="preferExternal"


以后默认是Android Studio出错 , eclipse尽量不用



安装AS的时候说java及其相关的找不到
java版本要1.7及以上

别人的AS项目的 gradle版本跟我已有的所有版本都不同( 比如2.0 ) , 而我并不想联网自动下载旧版本 或者 拷贝别人的gradle到C:\Users\Administrator\.gradle\wrapper\dists\gradle-2.0-all\<该项目都有的一串字符,AS加载项目的时候自动生成的>, 就改一下配置文件的最后一行 , 把版本改成已有的 .
原理 :
默认情况下 , AS根据
...\<项目文件夹>\gradle\wrapper\gradle-wrapper项目文件的

来加载gradle的东西 . 最上面的最优先 . 所有根据头两行 , 从
C:\Users\Administrator\.gradle\wrapper\dists   目录下加载gradle的东西








Error:Gradle version 2.10 is required. Current version is 2.2.1. 
If using the gradle wrapper, try editing the distributionUrl in D:\wildDog\demo-android-login-master\gradle\wrapper\gradle-wrapper.properties to gradle-2.10-all.zip
--用选项一的建议（IDE给出的建议，选项，自动提示的）
选项一：Fix Gradle wrapper and re-import project
选项二：Gradle settings





