# 第一步：在首页点击进入”Blender渲染”
![](https://github.com/ateam310/test1/blob/master/1.png) 
# 第二步，创建自己的项目
1.点击“新建项目”，输入项目名称，进入下一步
![](https://github.com/ateam310/test1/blob/master/2.png) 
2.输入项目名称，点击确定进入 "下一步"
![](https://github.com/ateam310/test1/blob/master/3.png) 
# 第三步，上传文件
1.点击“上传文件夹”<br>
图4<br>
2.下载并安装传输插件<br>
图5<br>
图6<br>
3.刷新界面，再次点击“上传文件夹”，服务器文件路径（包括盘符）会默认和本地文件保持一致。<br>
>文件若使用的绝对路径，则不支持B、C、D盘</br>
>不支持网络路径。比如\\192.168.0.2\..  \\机器名\..等</br>
>Blender的整个工程目录在用户制作时本地路径为：L:\Blender_test</br>

    上传后，刷新页面，服务器上路径也为：L:\Blender_test<br>
图7<br>
图8<br>
图9<br>
# 第四步，提交渲染任务。
1.勾选需要提交的渲染文件，点击“下一步”按钮。<br>
图10<br>
2. 配置渲染用的软件和插件，以及其它参数设置，点击“下一步，提交任务”<br>
>说明：
>>渲染设置：配置场景文件需要用到的3D软件及插件</br>
工程路径：若文件制作时贴图等路径为相对路径，则需要设置工程路径</br>
渲染帧：设置要渲染的帧范围。若不填写，则直接按文件中设置的默认帧范围来渲染</br>
优先渲染：若需要优先测试一帧或多帧查看效果，则可以填写，最多只提供三台机器来渲染优先帧</br>

  分析完成后手动提交：勾选此项后，任务分析完成后会暂停，此时可再次修改渲染相机等参数，再提交任务。
