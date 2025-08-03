# A common 'modal' style
This one is another very common pattern on the web. The solution to this one is _simple_... but it might not be immediately obvious to you. You'll need to edit the HTML a bit to get everything where it needs to be.

### A hint
Depending on how you approach this one, you might need to revisit the `flex-shrink` property to keep a flex item from getting smashed. In addition, pay attention to the structure of the html, specifically look into adding an additional container surrounding the header, button, main text, cancel, and continue divs; and look into moving the header div to encompass the button as well.

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- The blue icon is aligned to the left.
- There is equal space on either side of the icon (the gaps between the icon and the edge of the card, and the icon and the text, are the same).
- There is padding around the edge of the modal.
- The header, text, and buttons are aligned with each other.
- The header is bold and a slightly larger text-size than the text.
- The close button is vertically aligned with the header, and aligned in the top-right of the card.


# 一种常见的“模态框”样式

这是一种在网页上非常常见的模式。解决这个问题的方法是_简单_的……但可能一开始对你来说并不明显。你需要对HTML进行一些修改，以确保所有元素都放置在正确的位置。

### 一个提示

根据你处理这个问题的方式，你可能需要重新回顾`flex-shrink`属性，以防止弹性项目被挤压。此外，请注意HTML的结构，特别是考虑在标题、按钮、主要内容、取消和继续的div周围添加一个额外的容器；并考虑将标题div扩展以包含按钮。

## 预期效果

![预期效果](./desired-outcome.png)

### 自我检查

- 蓝色图标与左侧对齐。

- 图标两侧有相等的间距（图标与卡片边缘之间的间隙，以及图标与文本之间的间隙相同）。

- 模态框的边缘有内边距。

- 标题、文本和按钮相互对齐。

- 标题是加粗的，并且比文本稍大一些。

- 关闭按钮与标题垂直对齐，并位于卡片的右上角。