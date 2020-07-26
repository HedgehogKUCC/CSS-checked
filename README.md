# CSS - checked 選取器的應用

[Amos-CSS checked 選取器的應用](https://www.youtube.com/watch?v=XCyrzYp3aCY&feature=youtu.be)

<br>

## Example

https://github.com/HedgehogKUCC/CSS-checked

<br>

### 補充

`label` 標籤結構上盡量單獨使用，裡面不要包東西 ( Ex: `a` 標籤 )。

```html
<input type="radio" name="radio" id="radio1" class="panel-control" checked>
<label for="radio1">Tab1</label>
```

<br>

如果 `label` 裡面包 `input` 請記得 `label` 的屬性 `for` 就可以不用了

不然會沒有效果

```html
<label>
    <input type="radio" name="" id="">
</label>
```
