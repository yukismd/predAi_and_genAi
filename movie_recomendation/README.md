# Movie Recommendation with GenAI

予測AIが顧客の映画の評価予測を実施し、生成AIがお勧め映画の推薦文を作成  
  
予測AI: 顧客属性と好みのジャンルに基づく映画の推薦  
生成AI: 予測AIの推薦結果と、映画情報を知識DBとしてRAGを実施し、推薦文を作成

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
