# Telegram_bot_chatroom

Simple web app with html and jquery, creating a chatroom in telegram using your telegram bot. All chat history **only saved in your device** and **will not transfer the chat history to your other device** even you are using the same token.

You can download and run index.html in your desktop or using it in [here](https://wingpan79.github.io/telegram_bot_chatroom/) 

# How to use

To create a chatbot on Telegram, you need to contact the BotFather.

1.Search @Botfather in Telegram and click “Start” to activate BotFather bot.

![image](https://user-images.githubusercontent.com/28686176/129160843-9d5709a6-4cea-4dfc-b362-61aa215510d7.png)

2.Send the command ```/newbot``` then send a name and username for your bot. The username must be unique and end with the word “bot.”

![image](https://user-images.githubusercontent.com/28686176/129161538-941fab74-3667-44e9-8029-a49ce6d5e9bb.png)

3.Copy the token 

![image](https://user-images.githubusercontent.com/28686176/129161993-8fa0475e-760d-45a0-bf40-096474998dd9.png)

4.Open the index.html or [here](https://wingpan79.github.io/telegram_bot_chatroom/) , Paste the token in here and submit

![2021-08-12 16_12_12-index html](https://user-images.githubusercontent.com/28686176/129162174-239c1e35-ce95-408d-8f57-804a9892ec7d.png)

5.When someone send message to your bot,you can choose the chatroom and send a reply 

![2021-08-12 16_17_04-index html](https://user-images.githubusercontent.com/28686176/129162871-2f00f68e-2690-48a3-aacc-076ef68611eb.png)


## Delete Webhook

Please **do not set any webhook service** if you want to use this web app.You can go to [https://api.telegram.org/bot<you-token>/deletewebhook](https://api.telegram.org/bot<you-token>/deletewebhook) to delete the webhook service.
  
## The group privacy mode

The newly created bot is in privacy mode by default. A bot running in privacy mode will not receive all messages that people send to the group.
  
  If you want to receive all messages in telegram group.
  
  1.Talk to BotFather

  2.Send the command ```/setprivacy``` 
  
  3.Choose your bot and Send Disable
  
  4.Now your bot can receive group messages
![2021-08-12 16_57_56-Telegram (498127)](https://user-images.githubusercontent.com/28686176/129169114-ccc74c38-d113-4055-b067-10598381d5a8.png)
