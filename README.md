# Accenture PR デモページ

## ブラウザで開く方法

### 1) ファイルを直接開く（最速）
- Finder / Explorer で `index.html` をダブルクリック
- もしくはターミナルで実行:

```bash
xdg-open index.html   # Linux
open index.html       # macOS
start index.html      # Windows (cmd)
```

### 2) ローカルサーバーで開く（推奨）
同じフォルダで以下を実行し、表示されたURLをブラウザで開きます。

```bash
python3 -m http.server 8000
```

その後ブラウザで:
- `http://localhost:8000/index.html`

> `Ctrl + C` でサーバー停止。
