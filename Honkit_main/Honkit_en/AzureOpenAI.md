# Azure OpenAI Service
ailia DX insight conducts text generation through ChatGPT.
It is also possible to use ChatGPT via the Azure OpenAI Service in addition to the OpenAI API.
For details on Azure OpenAI Service, please refer to [here](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/overview).

## How to Connect to Azure OpenAI Service
### Calling the Settings Window
1. In the initial screen of ailia DX insight, click the gear icon in the upper right to display the settings window.<br>
![setup_03.png](/img/setup_03.png)<br>
1. Click "Azure OpenAI Service" in the "Chat AI" items and select "+ Add".
![azure_01.png](/img/azure_01.png)<br>

### Register Azure OpenAI Service Settings
A window will open to register the ChatGPT deployed in Azure. Fill in each item.<br>
![azure_02.png](/img/azure_02.png)<br>
* Name: Name used for UI display
* API Key: API key of the resource where ChatGPT is deployed
* Deployment Name: Deployment name set when ChatGPT was deployed
* API Version: The API version to use
    * The "Supported versions" on [this page](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/reference) are available.
* Resource Name: The name of the resource where ChatGPT is deployed
    * ChatGPT deployed endpoint`https://RESOURCE_NAME.openai.azure.com/`corresponds to the RESOURCE_NAME part.
* Model: Deployed model name (gpt-3.5-turbo, etc.)
* Description: Use as a memo as needed

<br>

#### [Next&emsp;＞](Gemini.md)