# machi —— 住む街を数字から見る

全国 1,740 市区町村を、政府統計（e-Stat）の 16 指標で比べるサイト。

- `index.html` —— 条件を選んで全国から探すツール
- `c/<自治体コード>.html` —— 市区町村ごとの個別ページ（1,740枚）
- `sitemap.xml` / `robots.txt`

出典：政府統計の総合窓口(e-Stat) https://www.e-stat.go.jp/ を加工して作成。

生成元: `.company/tools/experiment/site/build-pages.py`（このリポジトリには含めない）
