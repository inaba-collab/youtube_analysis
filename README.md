# YouTube分析アプリ

[アプリを使ってみる](https://gafavisuaize-bgxwobjhgwkrtxessdxy5p.streamlit.app/)
※初回起動に数秒かかる場合があります。

## アプリの概要
このアプリではクエリと登録者数を指定してYouTube上の動画を検索することでその動画・チャンネルの情報を取得します。
アプリ内でAPIを利用してYouTube検索することを目的としています。

## デモ画面
https://carhyparjyg4viuzp5he63.streamlit.app/

## 使用技術
- Python
- streamlit

## 機能
- クエリ入力
- 登録者で閾値指定
- 動画・チャンネル情報取得
- 動画出力

## 前提条件
Python 3.7以上

## 使用方法
'''bash<br>
cd youtube_analysis<br>
streamlit run app.py
