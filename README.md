# MiraiNative-MiraiAndroid
在MiraiAndroid上运行MiraiNative

### 简介
此项目允许在MiraiAndroid上运行符合酷QAPI的插件
请注意插件必须被重新编译(使用NDK)才能够正常使用

### 重新编译须知
在Android上, 由于Android linker问题, 你需要链接到CQP.dll, 无需设置rpath等信息, 动态库位置会在运行时自动解析(兼容安卓5.0+)

虽然正常来说应该叫so文件，但是请重命名为以dll为后缀的文件，并放入plugins文件夹即可

### 其他
如果想要在其他平台上使用，请参考[MiraiNative-CrossPlatform](https://github.com/w4123/MiraiNative-CrossPlatform)
