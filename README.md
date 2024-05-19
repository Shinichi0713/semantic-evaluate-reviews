# 目的
現在から今後における商品開発において、顧客のFeedBackの分析は欠かせない要素となる。
また、ユーザーからの感情を取得するためのデータは口コミや定量データなどが存在する。
今回は口コミデータにフォーカスを充てた分析手法について検討する

# 課題
アンケート


# NLPファンデーションモデル選定
使用するLLMモデルの選定を行う<br>
以下サイトに掲載されているPKSHAのモデルを採用する
採用根拠：学習に工夫が見られ、日本語埋め込み表現でより良い精度が期待できるため
参考:[https://qiita.com/skillup_ai/items/ddeaa9190c2f6447ad09](https://github.com/llm-jp/awesome-japanese-llm?tab=readme-ov-file#embeddings)
参考:https://huggingface.co/pkshatech/GLuCoSE-base-ja
