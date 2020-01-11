1. 在组件中传入 props 时，如果属性为非必传，在组件中直接使用`props.object.a`时，vscode 会提示报错。解决方法有两种：

- 使用\_!操作符显式地告诉编译器这个变量不会是 undefined。`<button onClick={click!}></button>`
- 使用三目运算符 `<buttton onClick={click ? click : () => {}}></button>`

2.
