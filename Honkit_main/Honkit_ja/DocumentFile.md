# 文書ファイルについて質問する
文書ファイルをインデックスに登録すると、登録した文書に記載された情報についてAIに質問することができます。
<br>

ファイルをインデックス登録する方法については[こちら](IndexRegister.md)をご確認ください。

## 文書ファイル内の情報について質問する
1. 画面左上のアプリメニューから「チャット」を選択します。<br>
![useai_02_02.png](/img/UseAI_02_02.png)<br>

1. インデックス登録した質問したい文書ファイルを右クリックし、「この文章を対象にチャット」を選択します。<br>
![useai_08_02.png](/img/UseAI_08_02.png)<br>

3. 指定されたファイル、またはフォルダが上部に表示されていることを確認します。<br>
![useai_08_04.png](/img/UseAI_08_04.png)<br>

1. チャットボックスの左側の表示が「RAG」となるので、質問を入力し、送信します。<br>
![useai_08.png](/img/UseAI_08.png)<br>

1. AIが関連するファイルを調べた回答が表示されます。（検索はローカルAIで行われます）<br>
![useai_08_05.png](/img/UseAI_08_05.png)<br>

<br>

* 生成された回答を上にスクロールしてくと、AIが参照した文章が表示されます。<br>
  参照された文章をクリックすることで参照箇所を確認することができます。<br>
![useai_08_06.png](/img/UseAI_08_06.jpg)<br>

<br>

* 通常のチャットに戻る場合には「絞り込みを解除」をクリックします。<br>
![useai_08_07.png](/img/UseAI_08_07.jpg)<br>

### 文書全体を渡して質問（DOCモード）<div id=update05></div>
ailia DX InsightではRAGを使用することによって回答性能を向上させています。[RAGについてはこちらをご確認ください。](RAG.md)<br>
しかし、要件によってはテキストのすべての要素を洗い出したい場面があります。<br>
その場合は、文章ファイルを右クリックして、「この文章全体を渡して質問（DOC）」を選択してください。<br>
![useai_08_07_01.png](/img/UseAI_08_07_01.png)<br>
DOCの場合、RAGによる情報検索をを行わず、ドキュメント全体をLLMに投げます。コストはかかりますが、より高精度になります。なお、チャットを継続した場合も、その都度、ドキュメント全体のトークンのコストがかかります。


## 複数の文書ファイルについて質問する
関連の文書ファイルをフォルダにまとめておくことで、フォルダ内の複数文書ファイルに跨った内容の質問をすることができます。<br>
画面左上のアプリメニューはチャットの状態にしておいてください。<br>
1. インデックス登録済みのファイルが格納されたフォルダを右クリックし、「このフォルダを対象にチャット」を選択します。<br>
![useai_08_08.png](/img/UseAI_08_08.png)<br>
1. 指定されたフォルダが上部に表示されていることを確認します。<br>下部にはフォルダに含まれるファイルが一覧で表示されます。<br>
![useai_08_09.png](/img/UseAI_08_09.png)<br>
1. チャットボックスの左側の表示が「RAG」となるので、質問を入力し、送信します。<br>　
![useai_08_10.png](/img/UseAI_08_10.png)<br>
1. AIが関連するファイルを調べた回答が表示されます。（検索はローカルAIで行われます）<br>
![useai_08_11.png](/img/UseAI_08_11.png)<br>
<br>

* 生成された回答を上にスクロールしてくと、AIが参照したファイル、文章を確認することができます。<br>また、参照された文章をクリックすることで参照箇所を確認することができます。<br>
![useai_08_12.png](/img/UseAI_08_12.jpg)<br>

<br>

* 通常のチャットに戻る場合には「絞り込みを解除」をクリックします。<br>

## 複数ファイルを比較して質問する<div id=update10></div>
2つ以上のファイルを選択し、DOCモードで質問をすることでファイル同士をAIによって比較させることができます。<br>
更新された契約書の変更箇所の確認や、文書ファイルの変更箇所の確認を素早く簡単に行うことができます。<br>

1. チャットモードでShift（もしくはCtrl）押しながら２つ以上のファイルを選択した状態で右クリックメニューから「これらの文章全体を渡して質問（DOC）」を選択します。<br>
![useai_08_13.png](/img/UseAI_08_13.png)<br>

2. チャットボックスに質問を入力し、送信します。<br>
この時、チャットボックスの左側の表示が「DOC」となっていることを確認してください<br>
![useai_08_14.png](/img/UseAI_08_14.png)<br>

3. AIが選択されたファイルを参照し、回答を生成します。<br>
![useai_08_15.png](/img/UseAI_08_15.png)<br>

## RAG
ailia DX Insightは回答を生成する際、Retrieval-Augmented Generation（RAG）を使用することで出力結果の根拠を明確にし、事実に基づかない情報の生成を抑制しています。<br>
RAGに関して、詳しくは[こちら](RAG.md)をご参照ください。



<br>

#### [次のページへ&emsp;＞](AskAboutImage.md)
#### [一覧に戻る](UseAI.md)