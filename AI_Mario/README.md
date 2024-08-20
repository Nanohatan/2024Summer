# AI Mario

AI（LLM）にマリオをクリアさせようnotebook
無料枠のColabのT4リソースで動かせるので，AIのお試しとしてどうぞ

## 準備

+ Google Colabolatory(無料版 T4以上？)
  + Run allすればよしなに動く，はず…

## 用語解説

+ OpenAI Gym
  + 学習アルゴリズムと環境の間で通信するための標準API、およびそのAPIに準拠した標準環境セットを提供することにより、強化学習アルゴリズムを開発および比較するためのオープンソースのPythonライブラリ．
  + gym-super-mario-bros
    + スーパーマリオブラザーズnes-pyエミュレータを使用したスーパーマリオブラザーズのOpenAI Gym環境
+ Large Language Models(LLM)
  + 大規模言語モデル．ChatGPTとかの総称．すごくサイズがでかいモデルで賢い
  + 今回のnotebookで扱ってるのは，画像入力可能なVision Large Language Models(VLLM)
    + 画像の解説とかをしてくれる

# その他生成AI

+ 画像生成AI
  + FLUX, StableDifusion，DALLE等
  + テキストを入力にしていい感じの画像を出してくれる
  + 制御を行うための技術（Controll Net等）が豊富
+ 動画生成AI
  + Gen-3，Sora等
  + テキストや画像から動画を生成できる
+ 音楽生成AI
  + Suno, Udio等
  + テキストやベースの音源から楽曲の生成が可能

この辺の話が聞きたかったら @makudara(Twitter(旧X), mattermost) までお気軽に！