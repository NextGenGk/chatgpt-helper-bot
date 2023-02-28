# ChatGPT Helper Bot

This app is an interface to the GPT3 API. It isn't Chatgpt nor does it use the Chatgpt api.
I made it as a second option due to the amount of errors and issues Chatgpt was having.

## Live website link 
https://chatgpt-helper.netlify.app/

## Sample Image for ChatGPT Helper Bot
![image](https://user-images.githubusercontent.com/95544839/221374571-75b3852b-0f99-4ce4-bd20-838d2365e23f.png)

## Requirements

-   Node.js (18 or newer)
-   A recent version of npm
-   An OpenAI Account

## Step-by-step Guide (Run Locally)

1. Clone this repository 
```bash
  https://github.com/NextGenGk/chatgpt-helper-bot.git
```

2. Change the directory 
```bash
  cd chatgpt-helper-bot/client
```

3. Install the node packages
```bash
  npm install
```

4. Rename `.env-example` file to `.env` file

5. Put your OpenAI API key into the `.env` file
    - You can obtain an API key [here](https://platform.openai.com/account/api-keys)
```bash
  REACT_APP_OPENAI_KEY=yourkey
```

6. Then just inside the client directory. It should automatically load the page inside of a browser.
```bash
  npm start
```
