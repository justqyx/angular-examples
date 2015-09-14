# AngularJS 学习笔记

## 基础概念

AngularJS 通过 ng-directives 扩展了 HTML

- ng-app 指令，指定了一个应用程序的 scope
- ng-module 用于定义一个 ng-app（AngularJS 应用程序）
- ng-controller 用于控制 ng-app
- ng-model 指令把元素值（比如输入域的值）绑定到了应用程序
- ng-bind 指令把应用程序数据绑定到 HTML 视图


## Directives（指令）

AngularJS 通过 directives 扩展了 HTML， AngularJS 需要对 HTML 进行编译，
即拥有了所谓的 context，而 directives 就是接口，通过它可以在 context 中
实现你想要的逻辑。之所以这么命名，我想是借鉴了 CPU 指令的理念。

- ng-app 初始化一个 AngularJS 应用程序
- ng-init 指令初始化应用程序数据
- ng-model 指令，把元素值（比如输入域的值）绑定到应用程序

其他

- ng-disabled
- ng-show
- ng-hide
- ng-click

## Services

- value
- constant
- factory
- service
- provider
