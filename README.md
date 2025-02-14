# Dolphin-AI
This is an AI assistant app for MacOS. You can chat with OpenAI GPT-4o with your API Key. Please see the demo video below. 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4uMNRiWfJYo/0.jpg)](https://www.youtube.com/watch?v=4uMNRiWfJYo)


## Used tech
- Figma, Xcode, Visual Studio Code
- Swift and SwiftUI on the front end
- Python(Flask) on the back end
- Vercel for building API servers
  
## How to install
1. Go to green "<> Code" button, then click "Download ZIP".
2. Unzip the zip file and double-click the Dolphin AI.dmg file to open it.
3. You will see volume named Dolphin AI on your desktop. Open it.
4. Drag and drop Dolphin AI.app to Applications folder.
5. Go to Applications folder and double-click Dolphin AI.app to open it.
    - If you see a warning window, click "OK", then right click Dolphin AI.app, select "Open". You will see a different warming window, then click "Open".


## How to set up
1. You need OpenAI API key because this app uses GPT-4o. If you don't have API key, you can get it from [here](https://openai.com/index/openai-api/).
2. Open the app, click a gear mark in the upper left corner of the window.
3. Paste your API key to the text field then click "Done".


## How to chat
1. Click "+ New Chat" button in in the upper left corner of the window.
2. Before starting a chat, I strongly recommend setting a system role for the assistant. This will make the assistant much smarter.
   1. Click "Chat setting" in the upper right corner of the window.
   2. Enter the role you would like your assistant to play in the text box. For example, if you want your assistant to teach you about programming, type “You are a very good programmer” and so on.
   3. Click "Done" to complete.
4. You can enter your prompt in the prompt box in the bottom of the window. You can also use images to chat with the assistant.


## Upcoming features
- Chat with a PDF

## Currently identified problems (09/17/2024)
- System role cannot be changed once it's set up.
- Sometimes the app crashes when it tries to generate a title of a chat.
- Cannot answer based on Youtube video. (This problem is most likely due to the fact that Youtube now blocks access from AWS-based servers.)

