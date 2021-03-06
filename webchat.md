---
layout: default
title: Webchat
permalink: /webchat/
---

# Webchat

## Checking the Webchat dashboard
The dashboard is in [https://clirack.pepperloop.com/dashboard/webchat](https://clirack.pepperloop.com/dashboard/webchat). Here you can check all webchat, edit and get information about it.

![Dashboard](/assets/img/webchat/wb_dashboard.png)

## Creating a webchat
First to go [webchat](https://clirack.pepperloop.com/dashboard/webchat) and upper of the table click +

![Add](/assets/img/webchat/wb_add.png)

Add information of your bot and save
![Save](/assets/img/webchat/wb_save.png)

## Editing a webchat
In your dashboard click in the pencil of the webchat that you want to edit:
![Add](/assets/img/webchat/wb_edit.png)

Change the information of your bot and save
![Save](/assets/img/webchat/wb_save.png)

## Deleting a webchat
In your dashboard click in the trash can of the webchat that you want to delete and confrim.
![Delte](/assets/img/webchat/wb_delete.png)

## Adding to website site the webchat
In the list of your webchat click in the code icon
![Add to site](/assets/img/webchat/wb_add_html.png)

Then copy the code and paste it before the body tag is closed
![Copy Code](/assets/img/webchat/wb_add_html_1.png)

## Adding to telegram the webchat
In the dashboard click in the chat icon
![Add to telegram](/assets/img/webchat/wb_add_telegram.png)

The easy way to add your webchat to telegram is using the links in the dialog, but if you want to do manually you can copy the code and write to the bot:
![copy telegram code](/assets/img/webchat/wb_add_telegram_1.png)

### Getting telegram app
You can download telegram app for:
- Desktop [https://desktop.telegram.org/](https://desktop.telegram.org/)
- Android [https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en](https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en)
- iOs [https://itunes.apple.com/us/app/telegram-messenger/id686449807?mt=8](https://itunes.apple.com/us/app/telegram-messenger/id686449807?mt=8)

### Adding webchat to telegram manually
You can do this from Telegram desktop app (left) or Telegram mobile app (right).
Open Telegram
![Telegram](/assets/img/webchat/wb_add_telegram_2.png)
Open Telegram and sarch ClirackBot
![Search ClriackBot](/assets/img/webchat/wb_add_telegram_2.png)
Start chat with ClirackBot
![Start chat with ClriackBot](/assets/img/webchat/wb_add_telegram_3.png)
Send the secret key to Clirack
![Send the secrey key ClriackBot](/assets/img/webchat/wb_add_telegram_4.png)
Send the secret key to Clirack
![Send the secrey key ClriackBot](/assets/img/webchat/wb_add_telegram_4.png)

### Adding webchat to telegram group manually
![Add ClriackBot to a group](/assets/img/webchat/wb_add_telegram_5.png)

## Customization the webchat
![Customization of the Webchat](/assets/img/webchat/wb_customization.jpg)
```
<html>

<body>

    <script id="ClirackWebchat" 
    webchat-identification-key="USE_YOUR_IDENTIFICATION_KEY-####"
    webchat-tittle="THE_NAME_OF_THE_WEBCHAT"
    webchat-theme-color="#009de7"
    webchat-font-color="#ffffff"
    webchat-background-color="#ffffff"
    webchat-font-color-names="#50565d"
    webchat-font-color-reciber="#ffffff"
    webchat-font-color-sender="#50565d"
    webchat-background-reciber="#009de7"
    webchat-background-sender="#e6ecf0"
    webchat-open-chat='from {bottom: -450px;} to {bottom: 0px;}'
    webchat-close-chat='from {bottom: 0px;} to {bottom: -450px;}'
    webchat-open-toggle='from {right: -75px;} to {right: 0px;}'
    webchat-close-toggle='from {right: 0px;} to {right: -75px;}'
    webchat-animation-velocity="1s"
    webchat-ask-name="What is your name?"
    webchat-ask-name-error="You can help me with your name?"
    webchat-ask-email="What is your mail?"
    webchat-ask-email-error="You can help me with your mail?"

    src="https://clirack.pepperloop.com/plugin/webchat-1/index.js"
    ></script>

</body>
</html>
```

