# Setup

[If you haven't updated from ailia DX Insight 1.0 to 1.1 yet, please check here.](v1_1update.md)

[Please check here for the update details of ailia DX Insight 1.2.](v1_2update.md)

## Download
<a href="https://ailia.ai/dx/" target="_blank">Download</a> ailia DX Insight and unzip the zip file.

## Start Installer
For Windows, open ailia_dx_insight.msix and install "aillia_dx_insight.msix".<br>
For macOS, open "ailia_dx_insight.dmg" and install ailia_dx_insight.app into the Application folder.<br>
![setup_00.png](/img/setup_00.png)<br>
## Select License or Config File
When you start the program for the first time, a window will appear saying "Please select a license or configuration file." Select the license file from the folder.<br>

The license file required for startup will be stored in `[HOME]/Library/SHALO` for macOS, and `[ROOT]/ProgramData/SHALO` for windows. By selecting a config file, you can customize the application.<br>
![setup_001](/img/setup_001.jpg)<br>
 By selecting a [config file](ConfigFile.md), you can customize the application.

## Acquiring OpenAI API Key
Register an account on the OpenAI WEB page and obtain the OpenAI API key. Even without inputting the OpenAI API key, you can use ailia DX Insight, but with limited functionality.
## Setup
After selecting the license or config file, the tutorial screen will be displayed. <br>
![setup_01.png](/img/setup_01.png)<br>
You can set the OpenAI API key on the final screen of the tutorial.
### Setting OpenAI API Key
#### If setting from the tutorial
1. Proceed to "Setting API Key" at the end of the tutorial.
1. Enter the OpenAI API key starting with "sk-" into the text box below "OpenAI API Key".<br>
![setup_02.png](/img/setup_02.jpg)<br>
1. Press the "Done" button.
#### If setting from the normal screen
1. Press the gear icon in the top right corner of the screen.<br>
![setup_03.png](/img/setup_03.png)<br>
1. Enter the OpenAI API key starting with "sk-" into the text box in the displayed dialog.<br>
![setup_04.png](/img/setup_04.png)<br>
1. Click "OpenAI", select the version of chatGPT to use, and press the "Close" button.
### Downloading AI Models
After completing the tutorial on the first run, the AI model download will start. You can check the progress at the lower part of the left sidebar.<br>
![download_model.png](/img/download_model.png)<br>
Once the download is complete, ailia DX Insight will be available for use.

## Selecting an OpenAI Model
1. On the ailia DX insight screen, click the gear icon in the upper right corner to display the settings window.
1. Click "OpenAI" in the "Chat AI" section and select a model.

#### How to Add GPTo3-mini
1. Click "OpenAI" in the "Chat AI" section and select "+Add."<br>
![setup_06.png](/img/setup_06.png)<br>
1. You can use ChatGPT o3-mini by entering as follows in the window that appears.<br>
![setup_07.png](/img/setup_07.png)<br>
  * Model: o3-mini
  * Maximum Token Length: 200000
  * Description: Use as a note if needed

<br>
If it is a model that OpenAI has made accessible via API, it can be added to chat AI in the same way for use.

<br>

#### [Next&emsp;＞](v1_2update.md)