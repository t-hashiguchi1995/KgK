# KgK
社内の初学者コンペに使ったコード群

コードのコメント等は全くしていない

## 対象コンペ
https://signate.jp/competitions/264/submissions

CV：9872, 17460

LB：13897.3998533

## 各種コードのやってる内容
- add_category_feature.ipynb：元データにある「バス・トイレ」などのカラムをすべて数値特徴に変換する
- model.ipynb：ベースラインから学習の部分を切り取ったもの。高額物件(50万以上)は除いたモデルを追加で作成
- parameter_tune.ipynb：Optunaを使ったパラメータチューニング。
- postprocessing.ipynb：高額物件への補正や高額物件の閾値を使った最終サブミットへの微調整。
- geocoder.ipynb：Google Map APIを使ったジオコーディング+pyprojで各種主要施設への距離などを追加
- nlp_feature.ipynb：TF-IDFを使った似ている物件の検索。犯罪データが所在地で追加するものだったので、結合のための粒度合わせ
- adversarial-validation-on-ieee-fe-with-some-eda.ipynb：ネットで調べて見つけたKaggleのコード
