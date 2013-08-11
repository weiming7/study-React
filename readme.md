#  React
###  数据驱动
###  函数式编程
###  状态机
###  自动DOM
###  组件化

###  JSX  JavaScriptXML
###  类XML语法容易接受 增强JS语义 结构清晰 抽象程度高 代码模块化

###  htmlFor className

### 注释、CSS样式以及嵌套
### 条件判断的四种方法
### 万能的函数表达式


###  非DOM标准属性
###  dangerouslySetInnerHTML  ref  key
###  直接插入   父组件引用子组件  提高渲染性能
###  React diff


### JSX解释器架构
### 执行顺序入手
### 忽略忽略细节
### 笔记
### 反复阅读

### 入口函数 载入模块  解析JSX 执行JS


### React组件生命周期  属性---状态----事件
### 组件  ----  状态机  F(x)
### 初始化  运行中  销毁

### getDefaultProps     共享引用  
### getInitialState     特有状态
### componentWillMount  最后一次修改
### render              this.props   this.state
### componentDidMount   完成后可以修改DOM

### componentWillReceiveProps
### shouldComponentUpdate

### componentWillUnmount





//类         //构造器
var Hello  = React.createClass({
    render:func  
              {this.props.name}
});

React.render(,document.body);