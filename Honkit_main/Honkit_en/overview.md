# Overview
ailia DX Insight is an AI super app for corporate DX provided by ax Corporation and Axel Corporation.<br>
By simply installing it on Windows or macOS, anyone can make use of AI in their business operations. <br>
With unique AI from ailia added to text search, image search, voice recognition, corporate information search in large language models, it makes it easy to improve business efficiency using AI.<br>

![overview_01.png](/img/overview_01.png)

## Features<div id=update06></div>
Below features can be used in aillia DX insight. The models used in each feature and execution environments are as follows.

<div class="scroll_area" style="width:100%;max-width:800px;overflow-x:scroll;">
    <table style="width:800px;">
      <thead>
      <tr>
      <th>Function</th>
      <th>Operates on Cloud</th>
      <th>Operates on Device</th>
      </tr>
      </thead>
      <tbody>
      <tr>
      <td>Text Search　(RAG)</td>
      <td>ChatGPT, Azure OpenAI, Gemini, Claude(* In Preparation) (Response Generation)</td>
      <td>ailia SDK (Index Creation, Vector Search, Re-Rank Feature), Custom LLM (Response Generation)</td>
      </tr>
      <tr>
      <td>Image Generation</td>
      <td>DALLE</td>
      <td>StableDiffusion(* In Preparation)</td>
      </tr>
      <tr>
      <td>Summary / Idea Generation</td>
      <td>ChatGPT, Azure OpenAI, Gemini, Claude(* In Preparation) (Response Generation)</td>
      <td>Custom LLM</td>
      </tr>
      <tr>
      <td>Translation</td>
      <td>ChatGPT, Azure OpenAI, Gemini, Claude(* In Preparation) (Response Generation)</td>
      <td>ailia SDK, Custom LLM</td>
      </tr>
      <tr>
      <td>Image Search</td>
      <td>-</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>Voice Input</td>
      <td>-</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>Voice Recognition</td>
      <td>Whisper Large V3 Turbo</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>Meeting Minutes</td>
      <td>Whisper Large V3 Turbo</td>
      <td>ailia SDK</td>
      </tr>
      <tr>
      <td>OCR</td>
      <td>Azure AI Vision(* In Preparation)</td>
      <td>ailia SDK</td>
      </tr>
      </tbody>
    </table>
</div>

## Supported File Formats
The formats supported by ailia DX Insight are as follows.

###### Common Office Document Formats
`pdf, doc, docx, txt, md, xlsx, csv, tex, css, html`

###### Program Document Formats
`c, cpp, json, java, py, rb, php`<br>

`js, swift, .kt, rust, dart, lua` can be added from Settings ![icon_gear](img/icon_gear.png) /Index.<br>

![overview_02.png](/img/overview_02.png)


###### Image Formats
 `'png', 'jpg', 'jpeg'`

###### Audio Formats
`'wav'`

## File Saving Location
ailia DX Insight saves database and model files in the following folders. By deleting these folders, you can initialize ailia DX Insight.<br>
`Windows : c:/Users/[UserName]/Documents(*)/ailia DX Insight`<br>
`macOS : ~/Documents(*)/ailia DX Insight`<br>

<br>
(*) In Windows it may be displayed as "My Documents", and in Mac as "Documents".

<br>

#### [Next&emsp;＞](SetUp.md)