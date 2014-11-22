# tabnav, pillnav, linenav

导航

* 有 `<jie-tabnav>`、`<jie-pillnav>`、`<jie-linenav>` 3 种内置样式
* 可以结合 horizontal layout flex 等特性达到类似 justified 的效果

## Example

```
<jie-tabnav>
  <li name="item1" active>ITEM 1</li>
  <li name="item2">ITEM 2</li>
  <li name="item3">ITEM 3</li>
</jie-tabnav>

<jie-pillnav selected="1">
  <li name="item1">ITEM 1</li>
  <li name="item2">ITEM 2</li>
  <li name="item3">ITEM 3</li>
</jie-pillnav>

<jie-linenav>
  <li name="item1">ITEM 1</li>
  <li name="item2">ITEM 2</li>
  <li name="item3" active>ITEM 3</li>
</jie-linenav>
```
