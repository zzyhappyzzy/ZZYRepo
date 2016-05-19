# ZZYRepo
个人cocoapods私有仓库repo

# 使用
Podfile文件内容示例
```
platform :ios, '7.0'

#个人私有仓库
source 'https://github.com/zzyhappyzzy/ZZYRepo.git'

#cocoapods官方仓库（如果source没有其它仓库，可以不写。但是，如果引用其他仓库的pod，必须显示指明官方的source）
source 'https://github.com/CocoaPods/Specs.git'

pod 'ZZYAlertView', '~>0.0.1'
```

# 目录
* ZZYAlertView
