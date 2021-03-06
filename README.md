# TimedSilver
All about swift extension 😉

## Installation
```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod 'TimedSilver'
```

If your CocoaPods Version > 1.0.0, you needs add Target name like this:
```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target ‘<Your Target Name>’ do
    pod 'TimedSilver'
end
```

## Directory tree
```
├── Foundation
│   ├── NSBundle+TSExtension.swift
│   ├── NSData+TSExtension.swift
│   ├── NSDate+TSExtension.swift
│   ├── NSDictionary+TSExtension.swift
│   ├── NSFileManager+TSExtension.swift
│   ├── NSIndexPath+TSOffset.swift
│   ├── NSNotificationCenter+TSBlock.swift
│   ├── NSObject+TSExtension.swift
│   ├── NSString+TSExtension.swift
│   ├── NSTimer+TSBlock.swift
│   ├── NSURLRequest+TScURLCommand.swift
│   ├── NSUserDefault+TSArchiveData.swift
│   └── NSUserDefault+TSExtension.swift
├── Struct
│   ├── Array+TSExtension.swift
│   ├── CGSize+TSExtension.swift
│   ├── Dictionary+TSExtension.swift
│   ├── Double+TSExtension.swift
│   ├── String+TSCrypto.swift
│   └── String+TSExtension.swift
├── TimedSilverHelper.swift
└── UIKit
    ├── UIApplication+TSExtension.swift
    ├── UIButton+TSExtension.swift
    ├── UICollectionView+TSExtension.swift
    ├── UIColor+TSExtension.swift
    ├── UIControl+TSExtension.swift
    ├── UIControl+TSSound.swift
    ├── UIDevice+TSExtension.swift
    ├── UIDevice+TSType.swift
    ├── UIImage+TSExtension.swift
    ├── UIImage+TSLaunchImage.swift
    ├── UIImage+TSOrientation.swift
    ├── UIImage+TSResize.swift
    ├── UIImage+TSRoundedCorner.swift
    ├── UILabel+TSExtension.swift
    ├── UINavigationController+TSExtension.swift
    ├── UINavigationItem+TSExtension.swift
    ├── UIScreen+TSExtension.swift
    ├── UIScrollView+TSExtension.swift
    ├── UIScrollView+TSPage.swift
    ├── UISearchBar+TSExtension.swift
    ├── UITableView+TSExtension.swift
    ├── UITableView+TSiOS7SettingStyle.swift
    ├── UIView+TSExtension.swift
    ├── UIView+TSFrame.swift
    ├── UIViewController+TSExtension.swift
    ├── UIViewController+TSVisible.swift
    └── UIWindow+TSHierarchy.swift
```

## License

TimedSilver is released under the MIT license. See LICENSE for details.
