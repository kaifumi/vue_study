# v-html="対象"
ここの「対象」の中にHTMLソースをいれる

```
const list = ['One', 'Two', 'Three']
const appdata = {
  data() {
    return {
      message: `<ul>
        <li>${list[0]}</li>
        <li>${list[1]}</li>
        <li>${list[2]}</li>
      </ul>`
    }
  }
}
```

# テキストを`で囲む
「`」記号(バックティック文字)を使う。
テンプレートリテラルになる。
めりっと
・テキストを改行して記述できる
・プレースホルダー（＄{変数名など}）をはめ込むことができる
