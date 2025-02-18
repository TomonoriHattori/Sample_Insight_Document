# Take Meeting Minutes
With voice recognition AI, you can take meeting minutes without moving your hands.

1. Click "Create Minutes" from the app menu at the top left of the screen to open the meeting minutes screen.<br>
![useai_18.png](/img/UseAI_18.png)<br> 
1. Enter the meeting place into "Meeting place" at the top right of the screen. You can also change the meeting name.<br>
![useai_19.png](/img/UseAI_19.png)<br>
1. Click the “Start Recording” button at the bottom of the screen to start taking the minutes.<br>
![useai_20.png](/img/UseAI_20.png)<br>
- If the AI model necessary for voice recognition has not been downloaded, the download will start. It will be available for use once the download is complete.

  [Downloading AI models required for speech recognition](VoiceInput.md)

4. When you wish to end the recording, click the "Stop Recording" button at the bottom to save the minutes.<br>
![useai_21.png](/img/UseAI_21.png)<br>
<br>

## Viewing Recorded Minutes
Click on the recorded minutes lined up on the left side of the meeting minutes screen to view the recorded minutes.<br>
![useai_22.png](/img/UseAI_22.png)<br>
You can correct the text by clicking the button on the right side of the recorded text.<br>
![useai_23.png](/img/UseAI_23.png)<br>
You can start recording minutes again by clicking the “Start Recording” button at the bottom of the screen.

## Creating Minutes from Audio Files
You can create minutes from an audio file by clicking on the "Microphone" in the query bar, changing it to "File," and then selecting "Start Recording." <br>
![useai_21_01.png](/img/UseAI_21_01.png)<br>

### Supported Formats
The minutes feature can only read wav files by default.<br>
By installing ffmpeg separately, you can also read mp3 and mp4 files.<br>

For Windows, please place ffmpeg.exe in a location where the PATH environment variable is set, or in the following folder:<br> <code>/Users/[UserName]/Documents()/ailia DX Insight/ffmpeg/</code><br>

For macOS, place ffmpeg in a location where the PATH environment variable is set, or in one of the following folders:<br>
<code>~/Documents()/ailia DX Insight/ffmpeg/</code><br>
<code>/usr/local/bin/</code><br>
<code>/opt/homebrew/bin/</code><br>
<code>/opt/local/bin/</code><br>

## Export minutes to a text file
You can export the minutes as a txt file by right-clicking on the minutes on the left side of the recording screen and selecting "Export the contents."<br>
![useai_24.png](/img/UseAI_24.png)<br>

<br>

#### [Next&emsp;＞](VoiceInput.md)
#### [Back to Index](UseAI.md)