## 小程序学习课程

### 细节经验总结

#### 13节
Hidden是通过opacity，visibility还是display方式，其实前两者虽然不可见但是都会占用页面布局，
这里的Hidden可以认为是该节点对象已经生成，只是未添加到父节点中。   

#### 15节
在选择使用if与hidden时，首先Hidden在初始化时消耗较高，if在有切换时消耗较高。所以在选择时如果存在经常
切换则可以选择hidden。

#### 16节
两种引用模板的方式：include和template
区别：include只会引用除template内容外的内容，
inport只会引用template内的的内容，动态的传入数据，is表示引用的模板名称，data表示传入模板的数据

