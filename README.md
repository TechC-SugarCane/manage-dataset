# manage-dataset

学習で使うデータセットを管理しているリポジトリです。

学習に使用するデータセットは[Roboflow](https://universe.roboflow.com/techcsugarcane/)というサービスを使用して作成しています。

## ダウンロード

サトウキビとパイナップルのデータがありますが、手動でダウンロードするのは面倒なので下記コマンドを実行してdatasetsをダウンロードしてください。

```bash
cd manage-dataset

# 環境変数をセット
# Sugarcane Version 9
$sugarcane_url="https://app.roboflow.com/ds/ostMeMAiWj?key=m5xuh2Ai3D"
# Pineapple Version 3
$pineapple_url="https://app.roboflow.com/ds/NNHeCYvP9D?key=e7w99ztEfE"

# mac向け
bash download_dataset.sh $sugarcane_url $pineapple_url

# windows向け
./download_dataset.ps1 -SugarcaneUrl $sugarcane_url -PineappleUrl $pineapple_url
```
