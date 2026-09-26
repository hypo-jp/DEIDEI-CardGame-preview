# DEIDEI プロトタイプ UIモック（daisyUI + Tailwind）

仮デザイン確認用の**静的クリックモック**です。アプリ本体ではありません。

## 公開URL（GitHub Pages）

| ページ | URL |
|--------|-----|
| ランディング | https://hypo-jp.github.io/DEIDEI-CardGame-preview/ |
| UIモック | https://hypo-jp.github.io/DEIDEI-CardGame-preview/ui-mock/ |
| ワイヤーフレーム | https://hypo-jp.github.io/DEIDEI-CardGame-preview/wireframes/ |
| 画面遷移ボード | https://hypo-jp.github.io/DEIDEI-CardGame-preview/wireframes/screen-flow.html |

要求定義（プロトタイプ／アプリ／ルール）は private リポジトリ `hypo-jp/DEIDEI-CardGame` 側です。

## 操作

- 枠外上部のセレクト・前後ボタン・デモリンクは **モック操作用**（本アプリUIではない）
- 枠内が参加者／admin 想定の画面
- 初回ロードで **P-01 TOP** が必ず表示されます
- P-06 給与は「確認」で同一画面内の確認待ち状態へ切替
- P-11 ソリューション詳細は「決定」で同一画面内の効果反映状態へ切替（旧 P-12 廃止）

## 対応画面

ワイヤーフレーム更新後の ID（P-01〜P-24、給与待ち／ソリューション効果は同一画面の状態）に揃えています。  
パンくずは `給与＞退職＞ソリューション＞採用`。  
admin 手番順（P-24）は参加者リストの上下入れ替えです。
