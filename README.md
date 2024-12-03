# manage-dataset

学習で使うデータセットを管理しているリポジトリです。

学習に使用するデータセットは[Roboflow](https://universe.roboflow.com/techcsugarcane/)というサービスを使用して作成しています。

## ダウンロード

サトウキビとパイナップルのデータがありますが、手動でダウンロードするのは面倒なので下記コマンドを実行してdatasetsをダウンロードしてください。

```bash
cd manage-dataset

# Sugarcane Version 5
$sugarcane_url="https://app.roboflow.com/ds/gethDX7bpc?key=l2lWEbZzPK"
# Pineapple Version 2
$pineapple_url="https://app.roboflow.com/ds/hfpq9ajFvM?key=5Rq1mFJi7w"

# mac向け
bash download_dataset.sh $sugarcane_url $pineapple_url

# windows向け
./download_dataset.ps1 -SugarcaneUrl $sugarcane_url -PineappleUrl $pineapple_url
```
