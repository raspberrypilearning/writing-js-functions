函数是执行特定任务的可重复使用的代码块。

函数将代码分解为特定的任务，以便于理解。

当你有需要多次完成的任务时，它们特别有用。 它们就像你可以在代码的不同部分反复使用的工具。

### 编写函数：

- 以 `function` 关键字开头，表示创建一个函数。
- 给你的函数起一个名字（例如 `addNumbers`）。
- 在函数名称后包含括号 `()`。 这些可以包含你的函数所需的参数（输入）。
- 使用打开的花括号 `{` 来定义函数将执行的代码块。
- 关闭花括号 `}` 以表示函数的结束。

下面是一个示例：

## --- code ---

language: js
filename:
line_numbers:
line_number_start:
line_highlights:
-----------------------------------------------------

function addNumbers(a, b) {
return a + b;
}

\--- /code ---

这里，`addNumbers` 是一个函数，它接受两个输入 `a` 和 `b` 并返回它们的和。

### 使用函数：

您可以通过**调用**来使用函数。

这里，函数 `addNumbers()` 被调用，参数为值 5 和 8。

它返回数字的总和，然后你可以使用它。 在这个例子中，5 加 8 的和被赋值给变量 `result`，然后在控制台中显示  `result`。

## --- code ---

language: js
filename:
line_numbers:
line_number_start:
line_highlights:
-----------------------------------------------------

let result = addNumbers(5, 8);
console.log(result); // 输出: 13

\--- /code ---
