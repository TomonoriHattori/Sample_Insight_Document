# version 1.2.0 release note

## Additional features

### AI chat
* [Supported local LLM](LocalLLM.md)
* [Markdown display support](AskToAI.md#update00)
* [Added a button to copy code](AskToAI.md#update01)
* [Added a feature to select the model upon sending](AskToAI.md#update02)

### File viewer
* [Added a quick access button for file view](FileView.md#update03)
* [Supported initial directory settings](FileView.md#update04)

### RAG
* [Added a mode for chatting with the entire text](DocumentFile.md#update05)

### Create minutes
* [Supported Whisper Large V3 Turbo](overview.md#update06)

### Others
* [Added benchmark functionality for the AI execution environment](Benchmark.md)

### OpenAI model changes
* Removed GPT-3.5
* Supported GPT-4o mini

### UI
* [Displayed the expiration date of the license file in the config file settings on the settings screen](ConfigFile.md#update07)
* [Displayed before and after changes in proofreading and translation](Translation.md#update08)
* [Added a button to select the entire image in image editing](GenerateImage.md#update09)

## improvement
* Accelerated document registration when using GPU
* Removed trailing whitespace during Excel import
* Improved translation accuracy for PDFs with text split within a single line

## Bug fixes
* Fixed the issue where editing the translation command prompt displayed it as the proofreading prompt
* Fixed the problem of overflow when entering a large amount of text in the chat window
* Fixed the difficulty in widening the left and right margins of the chat history
* Fixed the issue where the system prompt is not applied in Gemini
* Fixed the problem that libllama.dylib cannot start on macOS 13 because it is built for macOS 14
<br>

#### [Next&emsp;＞](v1_1update.md)