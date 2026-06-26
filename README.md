# links

論文用永久連結重導向站，託管於 GitHub Pages。

## 使用方式

URL 格式：`williamlu1218and0630.github.io/links/<名稱>`

### 新增連結

1. 建資料夾：`mkdir <名稱>`
2. 在資料夾內建 `index.html`，把 `url=` 改成目標網址
3. 在根目錄 `index.html` 的 `<ul>` 加一行索引
4. commit & push

### 改連結目標

改對應資料夾的 `index.html` 裡 `url=` 後面的網址，push 即生效。

## 結構

```
links/
  index.html          ← 索引頁（列出所有連結）
  paper1/
    index.html        ← meta refresh 重導向
  paper2/
    index.html
  ...
```
