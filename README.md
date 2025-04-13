# kmr1-shorten [![PyPI Downloads](https://static.pepy.tech/badge/kmr1-shorten)](https://pepy.tech/projects/kmr1-shorten)

Kmr¹ APIを使用してURLを短縮するコマンドラインツールです。  
Kmr¹API公式ドキュメント https://api.kmr1.org/v1/use  

## インストール
```bash
pip install kmr1-shorten
```
もしくは、ソースからインストールする場合は以下のコマンドを使用してください
```
git clone https://github.com/Lapius7/pip.kmr1-shorten.git
cd kmr1-shorten
pip install -r requirements.txt
```

## 使用方法（どちらでも同じ）
```
kmr1-shorten <URL> [-c <カスタム文字列>]
k1s <URL> [-c <カスタム文字列>]
```

短縮URLはクリップボードに自動コピーされます（pyperclipを使用）。