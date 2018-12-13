# FBXFileNormalizer

手贱移动了一下SDK目录,忘了怎么配置了,不过还好之前编译的还能用,直接下载就好了... ヽ(°◇° )ノ 

[FBXNormalizer.exe](https://github.com/JiongXiaGu/FBXFileNormalizer/blob/master/MD/FBXNormalizer.exe)
[libfbxsdk.dll](https://github.com/JiongXiaGu/FBXFileNormalizer/blob/master/MD/libfbxsdk.dll)
把他们两个放在需要正常化模型的目录运行,记得备份!!!

将FBX文件内容命名标准化(就是去掉有些网站在模型上命名的修改,比如说某 MixXXX)

1.删除节点名称的前缀(':'符号之前的内容);<br>
2.更改动画名称为文件名;<br>
3.覆盖源文件 或者 新建;<br>

配合 FBX SDK 使用: https://www.autodesk.com/developer-network/platform-technologies/fbx-sdk-2019-0
环境配置 : http://help.autodesk.com/view/FBX/2019/ENU/?guid=FBX_Developer_Help_getting_started_installing_and_configuring_configuring_the_fbx_sdk_for_wind_html
FBX API : https://help.autodesk.com/view/FBX/2017/ENU/
