# Gemini
ailia DX insightは、Geminiを使用して文章の生成を行うこともできます。
Geminiについての詳細は[こちら](https://ai.google.dev/gemini-api/docs/models/gemini?hl=ja)をご覧ください。

## Geminiへの接続方法
### 設定画面の呼び出し
1. ailia DX insightの初期画面にて、右上の歯車アイコンをクリックして設定ウィンドウを表示させます。<br>
![setup_03.png](/img/setup_03.png)<br>
1. 「チャットAI」の項目の中にある「Gemini」をクリックし、「+追加」を選択します
![gemini_01.png](/img/gemini_01.png)<br>

### Geminiの設定を登録
1. GeminiにデプロイしたChatGPTを登録するウィンドウが開きます。各項目を記入します。<br>
![gemini_02.png](/img/gemini_02.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: デプロイしたモデル名
  * 最大トークン長: モデルの最大トークン数

2. APIキーを登録してくださいとAPIキーのセクションに表示されているので、設定します。<br>
APIキー、モデル名については[こちら](https://ai.google.dev/gemini-api/docs/api-key?hl=ja)をご覧ください。

## Geminiの最新モデルを追加する
Geminiの最新モデルは以下のように項目を記入することで追加することができます。
現在利用できるモデルについては[GoogleAI for Developers](https://ai.google.dev/gemini-api/docs/models/gemini?hl=ja)をご確認ください。

### Gemini 2.0 Flash
![gemini_03.png](/img/gemini_03.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: gemini-2.0-Flash
  * 最大トークン長: 1048576


### Gemini 2.0 Flash-Lite プレビュー
![gemini_04.png](/img/gemini_04.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: gemini-2.0-Flash-lite-preview-02-05
  * 最大トークン長: 1048576

### Gemini 1.5 Flash
![gemini_05.png](/img/gemini_05.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: gemini-1.5-Flash
  * 最大トークン長: 1048576

### Gemini 1.5 Flash-8B
![gemini_06.png](/img/gemini_06.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: gemini-1.5-Flash-8b
  * 最大トークン長: 1048576

### Gemini 1.5 Pro
![gemini_07.png](/img/gemini_07.png)<br>
  * 名前：UI表示に使用する名称
  * 説明：必要に応じてメモとして使用
  * モデル: gemini-1.5-pro
  * 最大トークン長: 2097152

<br>

#### [次のページへ&emsp;＞](OpenAI_APIKey.md)