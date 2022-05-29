# 插件[Edit on GitHub](https://github.com/facebook/react/tree/master/docs/docs/10-addons.zh-CN.md)

React插件是一系列的用来构建 React app的有用模块。 **这些应该被认为是实验性的** 并趋向于比core变动更频繁。

- [`TransitionGroup` 和 `CSSTransitionGroup`](http://react-cn.github.io/react/docs/animation.html), 用来处理通常不能简单实现的动画和转换，比如在组件移除之前。
- [`LinkedStateMixin`](http://react-cn.github.io/react/docs/two-way-binding-helpers.html), 简化用户的表单输入数据与组件状态的协调。
- [`cloneWithProps`](http://react-cn.github.io/react/docs/clone-with-props.html), 创建React组件的浅拷贝并改变它们的props。
- [`createFragment`](http://react-cn.github.io/react/docs/create-fragment.html), 创建一组外键的子级。
- [`update`](http://react-cn.github.io/react/docs/update.html), 一个使不可变数据在JavaScript里更易处理的辅助函数。
- [`PureRenderMixin`](http://react-cn.github.io/react/docs/pure-render-mixin.html), 一个特定情况下的性能优化器。
- [`shallowCompare`](http://react-cn.github.io/react/docs/shallow-compare.html), 一个辅助函数，用来对 props 和 state在组件里 执行浅比较 以决定一个组件是否应该更新。

下面的插件只存在开发版(未压缩)React中：

- [`TestUtils`](http://react-cn.github.io/react/docs/test-utils.html), 用于写测试用例的简单的辅助工具（仅存在于未压缩版本）。
- [`Perf`](http://react-cn.github.io/react/docs/perf.html), 用于测量性能并给你提示哪里可以优化。

要获取插件，单独从npm安装他们(例如 `npm install react-addons-pure-render-mixin`).我们不支持使用插件如果你没有用npm.


 