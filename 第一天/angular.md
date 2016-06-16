# ng-app 告诉angular启动应用
# ng-model 实现数据绑定
# {{}} 
- 可以取出对应的数据
- 进行三元表达式
- 获取计算后的值{{sum()}}
# ng-bind 防止页面闪烁
- ng-non-bindable 让{{}}正常显示出来
- ng-bind-template="{{name}} {{age}}"绑定多个变量
# ng-init 初始化数据
# ng-repeat 可以遍历对象数组 
- 如果没有unique 我们就要使用trackby 进行根据哪个遍历
# ng-click 
- angular中的点击事件
# ng-hide/ng-show/ng-if
- hide/show只是单纯的css变化
- ng-cloak 解决闪烁问题
# ng-switch/ng-switch-when/ng-switch-default
# ng-class
- {true:'样式名字',false:'样式名字'}[model上的属性]
- {'样式名字':'model上的属性'}
- ng-class="model上的属性";
# include引入页面
# 过滤器
- filter
- orderBy
- json
- number
- currency
- uppercase/lowercase
- date
