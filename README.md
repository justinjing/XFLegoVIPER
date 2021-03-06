<p align="center">
    <img src="./ScreenShot/logo.png" alt="logo" width="499"/>
</p>
<p align="center">
  <a href="http://cocoadocs.org/docsets/XFLegoVIPER">
  	<img src="https://img.shields.io/badge/cocoapods-v2.6.0-brightgreen.svg" alt="cocoapods" />
  </a>
  <img src="https://img.shields.io/badge/language-ObjC-orange.svg" alt="language" />
  <img src="https://img.shields.io/npm/l/express.svg" alt="LICENSE" />
  <img src="https://img.shields.io/badge/platform-ios6%2B-green.svg" alt="version" />
</p>

## Note
🚀 A lightweight framework base on VIPER architecture for iOS, to build robust and maintained large scale project.
* Assemble a module as fast so far, only need one line code.
* Build-In powerful component event communication.
* Real-Time track Component link💫.
* Can combine popular `ReactiveCocoa` library work together seamless.
* Consider module and controller as component, using the same transition and event API.
* Compatible with old project that build of MVx pattern, and help transition to VIPER pattern.
* Make project more clearly, testable, maintainable, reconfigurable.

🍺Thanks VIPER!

![VIPER Design Pattern](https://www.objc.io/images/issue-13/2014-06-07-viper-intro-0a53d9f8.jpg)

## Component Architecture
![Component Architecture](./ScreenShot/construct.png)

## Example
### Demo
![Demo](./ScreenShot/usage.gif)

### Complete project
see [BDJProjectExample](https://github.com/yizzuide/BDJProjectExample)

## Video
- [XFLegoVIPER Framework Introduce](https://pan.baidu.com/s/1mhZHRQC)
- [How to code with XFLegoVIPER](https://pan.baidu.com/s/1o8yeyN4)


## Requirements
* Xcode 7.0+
* IOS 6.0+

## 2.x Release
XFLegoVIPER `2.x` is now available (December 2016). Read up on [what's new](https://github.com/yizzuide/XFLegoVIPER/wiki/1.-Getting-Started-(%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B)) in the docs.

Migration info from `1.x` can be found in the [2.x release notes](./RELEASE.md)

## Installation
### CocoaPods
```ruby
pod 'XFLegoVIPER', '~> 2.0'
```

### Manual
Copy all files under `~/XFLegoVIPER` folder  to your project.

## ❤Using Template❤
Now you can use template file to create a module which make of stuff class as fast as possible.
### 1.Find Template file 
find Template file  `~/Template/Architecture/XFLegoVIPER.xctemplate`

### 2.Copy to Xcode path
1. open path `/Applications/Xcode.app/Contents/Developer/Library/Xcode/Templates/File Templates`
2. create new folder named `Architecture`
3. drag the template file to `Architecture` folder

### 3.Using xcode create module files
1. Quit Xcode and open again
2. Right click a group, select `New File...`
3. Scrolling to Architecture Section, double click `XFLegoVIPER` item
4. Input module name (you need add class prefix), and next, final click `create` action

### 4.Fix blue folder ref
we have blue folder under select group, what's wrong? Let's fix it:

1. Right click blue folder, select `Show in Finder`
2. Back to Xcode, right click blue folder again, select `Delete`->`Remove References`
3. Back to opened Finder, drag new-folder to Xcode under a group

OK! It Work!

## VIPER Module
![XFLegoVIPER Module Layer](./ScreenShot/framework.png)

## Documentation
[1.x(Chinese)](./README1_5_x.md) | [2.x(Chinese)](https://github.com/yizzuide/XFLegoVIPER/wiki/1.-Getting-Started-(%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B))

## Change log
see [change log](./RELEASE.md)

## Reference
iOS Architecture Patterns [English](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.6tpii2lax) | [Chinese](http://www.cocoachina.com/ios/20160108/14916.html?utm_source=tuicool&utm_medium=referral)

Architecting iOS Apps with VIPER [English](https://www.objc.io/issues/13-architecture/viper/) | [Chinese](https://objccn.io/issue-13-5/)

## Author
yizzuide, fu837014586@163.com

## License
XFLegoVIPER is available under the MIT license. See the LICENSE file for more info.

