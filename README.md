<h1 align="center">こんにちは、Cherie です 👋</h1>

<p align="center">
  <b>データアナリスト・データエンジニア → データサイエンティスト / 機械学習エンジニア</b><br>
  機械学習・生成AIを業務データに適用し、検証を組み込んで現場で使われる形にすることを目指しています。
</p>

---

## 🧭 About

- 💼 **これまで**: データアナリスト・データエンジニアとして約2年半、SQL・Python・Snowflake によるデータ分析とパイプライン構築、機械学習（XGBoost・Amazon SageMaker）、生成AI・業務アプリ開発（Streamlit in Snowflake）を担当。それ以前は Java・Kotlin でのシステム開発
- 🎯 **目指す方向**: データサイエンティスト / 機械学習エンジニア（モデル構築・分析）、LLM を組み込む AI エンジニア
- 🏅 **Kaggle**: [Competitions Expert](https://www.kaggle.com/cherie01)（銀メダル1・銅メダル1）
- 🧩 **大切にしていること**: 動くだけで終わらせず、評価指標で確かめ、限界も README に書くこと
- 🤖 **開発の進め方**: 設計と評価の方針は自分で決め、実装には AI エージェントを活用。テストと CI で品質を確かめています

## 📌 Projects

| プロジェクト | 解く課題 | 手法 | 評価 |
|---|---|---|---|
| [🔍 defect-detection](https://github.com/Cherie01234/defect-detection) | 正常品の画像だけで、外観検査の欠陥を検出し位置を示す | PatchCore 方式を PyTorch で実装（学習済み ResNet のパッチ特徴＋最近傍距離）。オートエンコーダ方式とも比較 | 画像単位・ピクセル単位の AUROC。MVTec AD（screw）でバックボーンを比較 |
| [🗄️ text2sql-bi](https://github.com/Cherie01234/text2sql-bi) | 自然言語から SQL を生成して DuckDB で実行し、結果をグラフ化 | スキーマ検索、sqlglot による構文検証と SELECT 以外の拒否、エラー時の自己修正 | 実行結果の一致率（Execution Accuracy）で複数の LLM を比較。不一致の原因を評価指標の性質と切り分け、評価データを修正 |
| [📄 rag-doc-qa](https://github.com/Cherie01234/rag-doc-qa) | PDF・テキストへの質問に、根拠の箇所を示して回答 | Sentence-Transformers＋FAISS で検索し、LangChain 経由の LLM（切替可）で回答 | 定量評価は今後の課題 |
| [🖼️ clip_search](https://github.com/Cherie01234/clip_search) | 日本語・英語のキーワードや手持ちの画像から、意味の近い画像を検索 | 多言語 CLIP（open-clip-torch）＋FAISS | 約4.4万枚の画像で検索 |

> 4本とも pytest と GitHub Actions の CI を整備しています。各 README の冒頭に、課題・手法・評価・使い方をまとめています。

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?logo=snowflake&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-005571)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?logo=duckdb&logoColor=black)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

- **実務**: SQL / Python / Snowflake（Streams・Tasks、Snowpark、Cortex）/ pandas・scikit-learn・XGBoost / Amazon SageMaker・S3 / Streamlit in Snowflake / Tableau・Power BI / Java・Kotlin
- **個人開発**: PyTorch / scikit-learn / pandas・NumPy / LangChain / FAISS / Sentence-Transformers / CLIP（open-clip-torch）/ DuckDB / sqlglot / Streamlit / Plotly / GitHub Actions
