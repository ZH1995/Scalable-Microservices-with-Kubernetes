#### 1. 可扩展性

通过deployment设置replicas，可以方便的扩容/缩容。

#### 2. 滚动更新

每次先增加一个新pod，然后下掉一个旧pod。如此往复，直到所有pod都更新为最新的为止。