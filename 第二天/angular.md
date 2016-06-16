## 安装bower
- 第一步
```
    npm install bower -g
```
- 第二步
```
    bower install angular
```
## 使用angular
- 引入angularjs
- 增加ng-app 让angular启动整个应用
## ng-model 
- 带ng的都是angular中的指令
## 表达式
- {{}}可以进行值的运算
- ng-bind ng-bind-template ng-cloak
- ng-non-bindable
## ng-init初始化数据
## ng-repeat track by $index
- $index $middle $even...
## ng-click在angular中的事件
## ng-show/ng-hide/ng-if
## ng-switch ng-switch-when ng-switch-default
## ng-class
- {true:'样式名',false:'样式名'}[isActive]
- {'red':red,'green':green}
## include 
- 加''
## 过滤器
- currency:'指定的符号'，默认'$'
- uppercase/lowercase
- limitTo:5
- number:2
- orderBy:'name'/angular中的变量对应的值:true/false
- filter
    - 一般和input同时使用进行筛选
    - 可以指定筛选的区域filter:{name:query}
- date:'yyyy-MM-dd hh:mm:ss'
- json 
```
<pre>{name | json}</pre>
```
## 方法
- angular.forEach(function(){});
- angular.equals({},{});
- angular.extend();
- angular.copy();
```
console.log(angular);
```
## 创建模块
- 自带一个angular对象可以通过angular去创建模块
```
    angular.module('模块的名字',['模块1','模块2'])
```
- 通过返回值来获取这个模块
## 控制器
- 通过模块创建出来的
```
app.controller()
```
- 一个页面上可以使用多个控制器
- 而且控制器可以嵌套
- 防止代码压缩采用是数组的方式
- 用run方法设置rootScope初始值
## $apply
- 告诉angular刷新视图
- $timeout $interval angular中的内置服务
- 取消定时器 $timeout.cancel()/$interval.cancel()
> 已经有apply功能的 就不要在调用apply了
## $watch
- 可以监听模型数据的变化
```
$scope.$watch('模型的名字',function(){})
```