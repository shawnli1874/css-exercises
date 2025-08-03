# Descendant Combinator
Understanding how combinators work can become a lot easier when you start playing around with them and see what exactly is affected by them versus what isn't.

The goal of this exercise is to apply styles to elements that are descendants of another element, while leaving elements that *aren't* descendants of that element unstyled.

You can use either type or class selectors for this exercise; use whichever you may feel you want to practice with more. The HTML file is set up (so no need to edit anything in it) such that any combination of selectors will work, so if you're feeling adventurous you can even try combining a type *and* class selector for the descendant combinator.

The properties you need to add are:

* Only the `p` elements that are descendants of the `div` element should have a yellow background, red text, a font size of 20px, and center aligned.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the elements that contain the text "This should be styled" have the correct styles applied?
- Do the elements that contain the text "This should be unstyled" have no styles applied?

# 后代选择器

当你开始尝试使用这些选择器并观察它们具体影响哪些元素而不是哪些元素时，理解选择器的工作原理会变得容易得多。

本练习的目标是为另一个元素的后代元素应用样式，同时保持那些**不是**该元素后代的元素不受样式影响。

你可以使用类型选择器或类选择器进行此练习；使用你想要练习的任意一种即可。HTML 文件已经设置好（无需编辑），因此任何选择器组合都可以正常工作。如果你愿意冒险，甚至可以尝试将类型选择器和类选择器结合起来用于后代选择器。

你需要添加的属性是：

* 只有 `div` 元素的后代 `p` 元素应该具有黄色背景、红色文字、20 像素字体大小，并且居中对齐。

## 预期结果

![预期结果](./desired-outcome.png)

### 自我检查

- 包含文本 "This should be styled" 的元素是否应用了正确的样式？

- 包含文本 "This should be unstyled" 的元素是否没有应用任何样式？