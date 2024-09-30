# 家計簿システムに明細一覧を新規追加する。
## 【要件(開発内容)】
### ■要件
　既存の家計簿システム(仮)に、明細一覧を出力する機能を設けたい。
　リリース日：**2024/1/30(土)**

### ■現在の家計簿システム(仮)
　運用中の家計簿システムにおいて、入力したデータを一覧表示する機能が存在しない。
　そのため、全体を俯瞰して明細を把握することが困難である。

### ■具体的な機能要件
　[大前提]
　　明細一覧表示ができる画面の新規追加。
　　　⇒入力した明細が全データ分一覧表示されること。
  [オプション]
　　期間別(月別・年別)での明細一覧を表示可能であること。
  　　⇒期間を入力するのではなく、月別と年別の一覧を選択式で出力可能であること。
    ※オプションに関しては、段階リリースという形で対応し、可能であれば2025/02までにリリース予定。

## 【技術スタック】
### ■OS
　WindowsOS

### ■フロントエンド
　開発言語：React

### ■バックエンド
　開発言語：Java
　Framework：Spring Boot
　Database：Firebase

### ■開発環境
　フロントエンド：VSCode
　バックエンド：Eclipse
