北服疫情防控通签到（最终版）
===============
脚本可以开着然后就不要关了，脚本会在每天的凌晨0点准时打卡
----
首先声明：此脚本没有任何的后门可以放心使用，并不会泄露你的个人信息。当然害怕的话就别用了。
---------------
此脚本仅针对北京服装学院的疫情防控通设计，其他学校的可以请回了。或者有能力的可以修改一下发布。无需注明出处。<br>

python的下载与环境配置
--------------------
 * 接下来是食用方法 
 * 第一步当然是先下载我的代码，点击这个界面的那个绿色的code按钮,然后选择Download zip这样子就下载完了。再解压一下，找到以py结尾的文件后就先放一边了等下再用。
 * **接下来是下载python，python网上有许多下载教程可以参考我就不再赘述。（其实是因为麻烦我不想写）**
 * 接下来我们需要打开终端，windows的可以同时按win和R键，在输入框中输入cmd即可打开。或者直接在开始菜单中直接搜索powershell，以管理员模式打开也是OK滴。
 * macos的直接cmommand加space就OK了。
 * 然后在新弹出的窗口中输入以下代码
 * `pip install requests`    
 * 不行的话把代码中的‘pip’换成‘pip3’
 * 到这里环境的准备工作做完了。
 * 接下来来到新的一轮配置（看着多其实不是很多哈）

地区和个人信息的配置
------------------
 <br> 1、用edge浏览器或者Chrome浏览器打开疫情防控通的网页:
[疫情防控通](https://wx.bift.edu.cn/site/applicationSquare/index?sid=3 "快点进去呀") 
 <br> 2、登录进去选择每日填报后进入下一个页面!
 <br> 3、**重点来啦，重点来啦！！！！！**
 <br> 4、**在进入填报信息的页面后使用edge和Chrome的点击F12或者点击右上角三个点选择开发人员工具然后浏览器的右边会显示这样的框**
       ![页面展示](https://user-images.githubusercontent.com/95861898/191517151-9097d923-ae69-42c6-9d38-9556108894ff.png)
 <br> 5、然后像上图一样选择网络>勾选保留日志>选择Fetch/XHR
 <br> 6、然后像日常的按照个人信息填报，当点下蓝色的提交信息后在右边的日志中会显示一个save的选项就像这样
       ![页面展示](https://user-images.githubusercontent.com/95861898/191519349-f2a4ad72-f7a0-4c1d-b3f6-5e68e9e08ef9.jpg)
 <br> 7、复制这个ismoved开头的东东到记事本中然后把’ismoved‘到’tw‘前的东西单独复制出来如果说‘tw’前的那个数据不是’date=‘那么在这里堆信息面找到‘date=’的字段把它和后面的时间删掉，就是‘20xxxxxx&’全部删掉。然后在‘tw’前面加上‘date=’。到这里就完成了。

<br> 8、这样子就分成了两个字段。一个是以’ismoved‘开头‘date=’结尾的。一个是以’tw‘开头的什么结尾的都行。（doge）
<br> 就像这样
![配置](https://user-images.githubusercontent.com/95861898/191530005-d593feeb-ff25-45b7-b84d-978240060c17.png)
<br> 9、打开以py结尾的文件
<br> * **USERNAME就是学号**
<br> * **PASSWORD就是密码（初始密码是身份证后八位）**
<br> * **FORMDATA1就是我说的以‘ismoved’开头的那一段（记得要写在单引号里）**
<br> * **FORMDATA2就是我说的以’tw‘开头的那段 （记得要写在单引号里）**
 <br> 接下来只要点F5脚本就可以顺利运行啦,运行后结果如图
 ![结果](https://user-images.githubusercontent.com/95861898/191538041-cdb3bfb8-fc60-417d-a668-344af0e0c5ab.png)

 
<br>                                                         ** 至此就全部结束啦 **
====================

有什么使用上的问题可以加我的微信，我会尽可能的解答，记得注明来意。（叫我写其他学校的脚本不通过啊，我又不为钱）
=
<img width="250" height="250" src="https://user-images.githubusercontent.com/95861898/191534157-8be85054-9f7f-4554-a17e-9d8bca3c61ea.jpg"/>

声明
=
任何直接或间接因使用此脚本的任何内容所导致的全部后果与此脚本的开发者无关，若使用者无法对使用此签到脚本后的任何后果负责，请不要使用关于此脚本的任何内容。若该脚本的任何内容侵犯了您的法律权益，请联系1007956998@qq.com，作者会第一时间删除侵权内容。





