# The Holy Grail of Layout

In this last flexbox exercise you're going to recreate an incredibly common website layout. It is so common that it is often called the [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img) layout... and with flexbox it is actually pretty easy to pull off.

As with the previous exercise, we've left a little more for you to do.

### Hints
- You will need to change the flex-direction to push the footer down.
- You will need to add some divs as containers to get things to line up correctly.
- `flex-wrap` will help get the cards aligned correctly.
-  Make sure you define how much space the cards should take up, in order for `flex-wrap` to work as intended.

## Desired outcome

![desired outcome](./desired-outcome.png)

The number of cards lined up in that section will change based on the width of your screen, so don't stress about getting _exactly_ a 2x3 or 3x2 grid.

On a smaller screen it will look like this:

![smaller](./desired-outcome-smaller.png)

Note: The emojis may instead show up as one or several text symbols (e.g. &#9734;&#9794;) if you don't have an emoji-based font family installed on your operating system. This does not affect the exercise and can be ignored.

### Self Check
- The header text is size 32px and weight 900.
- The header text is vertically centered and 16px from the edge of the screen.
- The footer is pushed to the bottom of the screen (the footer may go _below_ the bottom of the screen if the content of the 'cards' section overflows and/or if your screen is shorter).
- The footer text is centered horizontally and vertically.
- The sidebar and cards take up all available space above the footer.
- The sidebar is 300px wide (and it doesn't shrink).
- The sidebar links are size 24px, are white, and do not have the underline text decoration.
- The sidebar has 16px padding.
- There is 48px padding around the 'cards' section.
- The cards are arranged horizontally, but wrap to multiple lines when they run out of room on the page.
# 布局的圣杯

在这个最后一个Flexbox练习中，你将重新创建一个非常常见的网站布局。它如此常见，以至于经常被称为[圣杯](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img)布局……而使用Flexbox实现起来实际上相当简单。

与之前的练习一样，这次我们给你留出了更多的工作。

### 提示

- 你需要更改flex-direction以将页脚推到底部。

- 你需要添加一些div作为容器，以便正确对齐元素。

- `flex-wrap` 将帮助将卡片正确对齐。

- 确保定义卡片应该占用的空间大小，这样才能使`flex-wrap`按预期工作。

## 预期结果

![预期结果](./desired-outcome.png)

该部分中排列的卡片数量会根据屏幕宽度变化，所以不必担心恰好是2x3或3x2的网格。

在较小的屏幕上，它看起来会像这样：

![更小](./desired-outcome-smaller.png)

注意：如果你的操作系统上没有安装基于表情符号的字体，这些表情符号可能会显示为一个或多个文本符号（例如：&#9734;&#9794;）。这不会影响练习，可以忽略。

### 自我检查

- 标题文字大小为32px，粗细为900。

- 标题文字垂直居中，距离屏幕边缘16px。

- 页脚被推到屏幕底部（如果“卡片”部分的内容溢出和/或屏幕较短，页脚可能会出现在屏幕底部以下）。

- 页脚文字水平和垂直居中。

- 侧边栏和卡片占据页脚上方的所有可用空间。

- 侧边栏宽度为300px（且不会缩小）。

- 侧边栏链接的大小为24px，颜色为白色，并且没有下划线装饰。

- 侧边栏有16px的内边距。

- “卡片”区域周围有48px的内边距。

- 卡片水平排列，当页面空间不足时会换行到多行。