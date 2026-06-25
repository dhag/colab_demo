# colab_demo　デジタル通信用



## UDP
画像データを送受信する。自分自身で送受信。

***UDP_image_demo.ipynb***


テキストデータを受信する。pinggyでブリッジ。

***UDP_text_reciever.ipynb***

テキストデータを送信する。

***UDP_text_sender.ipynb***

## TCP
画像データを受信するサーバ。ngrokでブリッジ

***TCP_server_receiver_ngrok.ipynb***

画像データを送信するクライアント。ngrokでブリッジ

***Tcp_client_sender.ipynb***


## HTTP
ごく簡単なHTTPサーバ。ngrokでブリッジ

***Flask+ngrokの例.ipynb***

画像をアップロードして処理したものを受け取る簡単なHTTPサーバ。ngrokでブリッジ

***HTTP_flask_browser_ngrok.ipynb***

## API
GeminiのAPIを使うサンプル。サンプル以前。
***クイックAI.ipynb***

GeminiのAPIを使うサンプル。他社もほぼ同等（だが無料枠がないものが多い）

***gemini_colab_quickstart.ipynb***


## Web sock
ごく簡単なエコーサーバ
***WS_echo_server_colab_ngrok.ipynb***
チャット
***websocket_chat_colab.ipynb***

## Web hook
ラインのWeb hook

***line_webhook_colab.ipynb***

ラインのWeb hook。画像を扱える(ただしデモではごく簡単な処理だけ)

***line_dummy_image_colab.ipynb***

ラインのWeb hook。geminiによる画像生成（有償版じゃないとダメかもね）。

***line_gemini_image_colab.ipynb***


---
# colab_demo　ロボティクス用

## DQN A
倒立紳士のパラメータをDQNで学習する。

***強化学習による倒立振子_改良版.ipynb***

## DQN B
レーシングゲーム風の操作を学習する。基本編。レースというより虫の歩き。

***強化学習でS字コースを走る。基本動作なのでちょっとかっこわるい.ipynb***

レーシングゲーム風の操作を学習する。応用編。カーブで横滑りしない程度の高速走行するように。

***強化学習でS字コースを走る。発展版.ipynb***



## CNN
HaGRIDのデータでじゃんけんを学習してCNNの中身を見る。

***HaGRID_CNN_feature_map_kyozai.ipynb***

