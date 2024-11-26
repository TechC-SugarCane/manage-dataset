# manage-dataset

学習で使うデータセットを管理しているリポジトリです。

学習に使用するデータセットは[Roboflow](https://universe.roboflow.com/techcsugarcane/)というサービスを使用して作成しています。

## ダウンロード

サトウキビとパイナップルのデータがありますが、手動でダウンロードするのは面倒なので下記コマンドを実行してdatasetsをダウンロードしてください。

```bash
# Sugarcane Version 4
$sugarcane_url="https://app.roboflow.com/ds/T2zV0t9XVG?key=VldKEnvBjY"
# Pineapple Version 2
$pineapple_url="https://app.roboflow.com/ds/hfpq9ajFvM?key=5Rq1mFJi7w"

# mac向け
bash download_dataset.sh $sugarcane_url $pineapple_url

# windows向け
./download_dataset.ps1 -SugarcaneUrl $sugarcane_url -PineappleUrl $pineapple_url
```
