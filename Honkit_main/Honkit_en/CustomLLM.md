# Set up Custom LLM
In ailia DX Insight, by using a custom LLM built locally, it is possible to operate in a safer offline environment.
The custom LLM can be operated on the PC running ailia DX Insight or connected to one running on another PC or server.

## About ChatGPT Compatible Server
ailia DX Insight supports ChatGPT compatible servers.<br>
There are the following methods to use local LLM.
* [Using "LM Studio"](CustomLLM_LMstudio.md)
* [Using "Ollama"](CustomLLM_Ollama.md)
* [Using Python "fastchat"](CustomLLM_FastChat.md)
* Using ailia DX Enterprise (scheduled for release at the end of July)
* Using built-in local LLM in ailia DX Insight (scheduled for release at the end of August)

## Setting Up Custom LLM Client
### Calling Settings Screen
1. On the initial screen of ailia DX Insight, click the gear icon at the top right to display the settings window.<br>
![setup_03.png](/img/setup_03.png)<br>
1. Click "Custom (OpenAI compatible server)" in the "Chat AI" section and select "+Add".<br>
![CustomLLM_01.png](/img/CustomLLM_01.png)<br>

### Registering Custom Model
The custom model registration window opens. Fill in each item.<br>
![CustomLLM_02.png](/img/CustomLLM_02.png)<br>

* Name: Name of the LLM to use (anything is fine as it is only used for UI display)
* Description: Use as needed for notes
* Model: Model name specified by the OpenAI compatible API server (e.g., gpt-3.5-turbo)
* URL(*): The IP address and port number the OpenAI compatible API server is transmitting (e.g., if the server is published as -host 192.168.1.10 -port 8000, then http://192.168.1.10:8000)
* Maximum token length: Set the maximum token number supported by the model (set to 4096 or more, this value determines the topK of RAG)
<br>

(*) If not filled in, it will result in an HTTP connection error.


<br>

#### [Next&emsp;＞](CustomLLM_LMstudio.md)