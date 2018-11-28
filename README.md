# Libstdc-.6.0.9-files
该项目用于Xcode 10+ 不支持使用lbstdc++插件报错异常解决方案

类似这种报错Info: `Error: ld: library not found for "-lstdc++.6"`

## Usage
根据调试方式不同，真机和模拟器文件放置路径存在差异，分别复制对应的Lib文件到下面的路径即可解决Xcode编译报错

### For Device
Put tbd copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/

### For Simulator
Put dylib copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/

Put tdb copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/

## Download
直接 *Clone or Download Zip* 进行文件下载

也可以点击[这里](https://github.com/Cui-y/Libstdc-.6.0.9-files/archive/master.zip)进行文件下载
