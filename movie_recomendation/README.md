# Movie Recommendation with GenAI

予測AI＋生成AIによる映画の推薦  
- 予測AI： 顧客造成と好みのジャンルに対応した映画の推薦
- 生成AI: 予測AIの推薦と、映画情報に対するRAGを元にした、お勧め文の作成

***

Simple Demo: [MovieRecommendation.ipynb](MovieRecommendation.ipynb)

***
#### データ
予測AI
- 学習用データ： [data/movie_rating_modelingdata.csv](data/movie_rating_modelingdata.csv)
    - 過去の映画評価履歴。ユーザー情報（user_.）、映画とタグ付けされたジャンル情報(genre_.)とユーザ評価(rating_good)
- 推論用サンプルデータ: [data/user_demographic_and_preference.csv](data/user_demographic_and_preference.csv)
    - 推薦対象の顧客データ。ユーザー情報（user_.）と顧客が入力した好みのジャンル(genre_.)
- 推薦を実施する映画のリスト: [data/movies_sample.csv](data/movies_sample.csv)

生成AI
- RAG用データ: [data/movies_sample_story.txt](data/movies_sample_story.txt)
    - 推薦対象の映画のリストの詳細内容
