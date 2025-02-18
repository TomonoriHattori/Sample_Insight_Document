# Ask Questions About Document Files
By registering document files to an index, you can ask AI about information listed in the registered documents.
<br>

Look [here](IndexRegister.md) for how to register files to indexes.

## Asking About Information in Document Files
1. Select "Chat" from the app menu at the top left of the screen.<br>
![useai_07.png](/img/UseAI_02_02.png)<br>

1. Right-click the indexed document file you want to question and select "AI chat from this text (RAG)".<br>
![useai_08_02.png](/img/UseAI_08_02.png)<br>

3. Verify that the specified file or folder is displayed at the top.<br>
![useai_08_04.png](/img/UseAI_08_04.png)<br>

1. The display to the left of the chat box will show "RAG", entered your question, and send it.<br>
![useai_08.png](/img/UseAI_08.png)<br>

1. The AI will respond based on related files. (The search is conducted by the local AI)<br>
![useai_08_05.png](/img/UseAI_08_05.png)<br>

<br>

* Scroll up the generated response to see the text referenced by the AI.<br>
  Click the referenced text to confirm the reference location.<br>
![useai_08_06.png](/img/UseAI_08_06.jpg)<br>

<br>

* To return to normal chat, click "Release Refinement".<br>
![useai_08_07.png](/img/UseAI_08_07.png)<br>

## Passing the Entire Document for Questions<div id=update05></div>
In ailia DX Insight, we enhance response performance by using RAG. For more information about RAG, [please check here.](RAG.md)
However, there are cases where you may want to extract all elements of the text depending on the requirements.
In that case, right-click on the document file and select "Pass this entire sentence and ask questions (DOC)."<br>
![useai_08_07.png](/img/UseAI_08_07_01.png)<br>
In the case of DOC, information retrieval using RAG will not be performed, and the entire document will be sent to ChatGPT. While it incurs costs, it allows for greater accuracy. Please note that if the chat continues, there will be token costs for the entire document each time.

## Asking About Multiple Document Files
You can ask questions across multiple document files by putting related documents in a folder.<br>
Ensure to have the app menu at the top left set to chat mode.<br>
1. Right-click the folder containing the registered files, and select "AI chat from this folder".<br>
![useai_08_08.png](/img/UseAI_08_08.png)<br>
1. Verify the specified folder is displayed at the top.<br>The files contained within the folder will be listed at the bottom.<br>
![useai_08_09.png](/img/UseAI_08_09.png)<br>
1. The display to the left of the chat box will show "RAG", enter your question, and send it.<br>　
![useai_08_10.png](/img/UseAI_08_10.png)<br>
1. The AI will check the related files and display the response. (The search is conducted by the local AI)<br>
![useai_08_11.png](/img/UseAI_08_11.png)<br>
<br>

* Scroll up the generated response to confirm the files and text referenced by the AI.<br>
Click the referenced text to verify the reference location.<br>
![useai_08_12.png](/img/UseAI_08_12.jpg)<br>

<br>

* To return to normal chat, click "Release Refinement".<br>

## Compare multiple files and ask questions<div id=update10></div>
You can select two or more files and have the AI compare them by asking questions in DOC mode.<br>
You can quickly and easily check for changes in updated contracts or document files.<br>

1. In chat mode, select two or more files while holding Shift (or Ctrl) and right-click to choose "Give these sentences as a whole and ask (DOC)" from the menu.<br>
![useai_08_13.png](/img/UseAI_08_13.png)<br>

2. Enter your question in the chat box and send it.<br>
At this time, confirm that the display on the left side of the chat box is "DOC".<br>
![useai_08_14.png](/img/UseAI_08_14.png)<br>

3. The AI will refer to the selected files and generate an answer.<br>
![useai_08_15.png](/img/UseAI_08_15.png)<br>


## RAG
ailia DX Insight uses Retrieval-Augmented Generation (RAG) to make response rationale clear and suppress the generation of factitious information.<br>
For more details about RAG, please refer [here](RAG.md).



<br>

#### [Next&emsp;＞](AskAboutImage.md)
#### [Back to Index](UseAI.md)