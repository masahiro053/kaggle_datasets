# Customer Analytics Practice Dataset
![image](https://github.com/kaneda05/kaggle_datasets/blob/main/png/01_Customer%20Analysis.png)

このデータセットは、一般的なMall Customersデータセットを拡張したもので元のデータに年齢、性別、年収、購買スコアといった基本的な情報に加え、以下のようなより現実的な特徴が追加されている。

追加データ
- 年齢層
- 推定貯蓄額
- 信用スコア
- ロイヤルティ年数
- 好みのカテゴリー

利用目的
- 教師なし学習: 顧客セグメンテーションなど
- 教師あり学習: 信用スコアや貯蓄額などの予測
- 特徴量エンジニアリングと可視化

[分析コード](https://github.com/kaneda05/kaggle_datasets/blob/main/01_Customer%20Analytics%20Practice%20Dataset/cluster-analysis.ipynb)

[kaggleページ](https://www.kaggle.com/datasets/vikasjigupta786/customer-analytics-practice-dataset)

---
# 20250831
EDAの作成と顧客のセグメンテーションをエルボー法で最適なセグメント数を求め、K-means法にてクラスタリングを実施した後に、セグメント結果からどのようの顧客層がいるかを纏めた。