# 变更1
```
package.json
	"version": "2.3" --> "version": "2.4.0"
	"mobile": "1.8" --> "mobile": "1.8.0"
```

解决npm install报错的问题。

nodejs版本：v4.4.7

npm版本：2.14.15

```
9 error node v4.4.7
10 error npm  v2.14.15
11 error Invalid version: "2.4"
12 error If you need help, you may report this error at:
12 error     <https://github.com/npm/npm/issues>
13 verbose exit [ 1, true ]
```

# 变更2

原有的版本不能在FIS3框架中作为第三方组件使用，报id.replace is not function错误。查看分析认为是代码结构封装问题，于是以underscore代码结构为范本进行了重构，完美解决以上问题。

# 构建步骤

```
npm install
grunt
```


## 简要
layer是一款近年来口碑非常不错的web弹层组件，她具备全方位的解决方案，致力于服务各个水平段的开发人员，您的页面会轻松地拥有丰富友好的操作体验。

在与同类组件的比较中，layer总是能轻易获胜。她尽可能地在以更少的代码展现更强健的功能，且格外注重性能的提升、易用和实用性，正因如此，越来越多的开发者将媚眼投上了layer。layer兼容了包括IE6在内的所有主流浏览器。 她数量可观的接口，使得您可以自定义太多您需要的风格，每一种弹层模式各具特色，皆广受欢迎。当然，这种“王婆卖瓜”的陈述听起来总是有点难受，因此你需要进一步了解她是否真的如你所愿。

[文档与演示](http://layer.layui.com/) 

## 愿景
致力于打造国内最盛行的弹层组件，为web开发提供强劲动力。

## 现状
从两年前初出茅庐，到后来成为小众组件，再发展到今天，已为数以万计的人所熟知。
据不完全统计，截至到2015年09月01号，layer已服务于10万余家web平台。


## 备注
[官网](http://layer.layui.com/)、[更新日志](https://github.com/sentsin/layer/blob/2.x/CHANGELOG.md)、[社区交流](http://fly.layui.com)