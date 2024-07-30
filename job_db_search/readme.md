# Job matching with GenAI

予測AI＋生成AIによるジョブマッチング  
- 生成AI: 職務経歴書から、書かれているスキル（専門技術、マネジメント、経験等）を抽出する
- 予測AI： 抽出したスキル一覧とマッチする仕事をリストアップする


***

Demo: [JobDb_Search.ipynb](JobDb_Search.ipynb)

***
#### データ

生成AI
- RAG用データ: [data/resume_0106.docx](data/resume_0106.docx)
    - 職務経歴書

予測AI
- 学習用データ： [data/job_database_wCategory.csv](data/job_database_wCategory.csv)
    - XXXXX
- 検索対象の仕事リスト: [data/job_database.csv](data/job_database.csv)
    - XXXXX
- 検索対象の仕事リストのEmbedding Table: [data/job_embeddings.csv](data/job_embeddings.csv)
　　　 　　　- XXXXX

