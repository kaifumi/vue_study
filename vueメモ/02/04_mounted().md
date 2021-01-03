# mounted
Vue3オブジェクトが読み込まれたあとに実行される処理

```javascript
mounted() {
  setInterval(() => {
    this.count++
    this.message = 'Count: ' + this.count
  }, 1000)
}
```