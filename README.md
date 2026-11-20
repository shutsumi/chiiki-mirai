# 地域みらい留学 自宅から学校までの行き方

https://shutsumi.github.io/chiiki-mirai/route/

都道府県と学校を選ぶと、Googleマップのルート検索(行き先にその学校が入った状態)を開くボタンを出すページ
直下の `index.html` は `route/` へ移動するだけ

## 費用シミュレーターとの関係

`費用シミュレーター/docs/` から次のファイルをコピーして使っている、学校データや見た目を変えたら、こちらにもコピーし直す

- `data/schools.json` ← `費用シミュレーター/docs/data/schools.json`
- `style.css` ← `費用シミュレーター/docs/style.css`

CSS・JS を変えたら、`route/index.html` の `?v=…` の値を上げてから push する(GitHub Pages が最大10分ブラウザに保存させるため)
利用の記録はしていない
