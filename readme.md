Chatbot
Data sheet ( https://drive.google.com/file/d/1jjydQm_w8oTxzN6d7hJ6KqEPGQmyeH1R/view?usp=sharing)
## Intro
Chatbot learning from existing FAQs giving immediate answers found in FAQ.
Questions not found in the databse are sorted to different departments.
Answer giving by different departments are stored on database and next time some related question is asked it immediatly replies.

##Features Available now
1. Tag related searching question answering.
2. Synonym based answering.

##Features to be added further
1. Question priority setup and department sorting
2. Machine learning instant replies.

## Use Azure app service editor

1. make code change in the online editor
2. open the console window and run

```
build.cmd
```

## Use Visual Studio 

### Build and debug
1. download source code zip and extract source in local folder
2. open {PROJ_NAME}.sln in Visual Studio
3. build and run the bot
4. download and run [botframework-emulator](https://emulator.botframework.com/)
5. connect the emulator to http://localhost:3987/api/messages

#### Live Demos
1. Facebook messenger (https://www.facebook.com/AskMe-1743348222637477/) (developer mode -under review process)
2. Telegram (https://t.me/AskmeDAVS_bot) (LIVE)
