# Setup Telegram push notification

In the config.ini file:
```
直播状态通知(可选微信|钉钉|tg或者都填) = tg
钉钉推送接口链接 = 
微信推送接口链接 = 
钉钉通知@对象(填手机号) = 
tgapi令牌 = xxxx
tg聊天id(个人或者群组id) = -100xxxx
只推送通知不录制（是/否） = 否
直播推送检测频率（秒） = 1800
开播推送开启（是/否）= 是
关播推送开启（是/否）= 是
```

# Ref:
- read this article to get the tgapi token: [https://help.zoho.com/portal/en/kb/desk/support-channels/instant-messaging/telegram/articles/telegram-integration-with-zoho-desk#How_to_create_a_Telegram_Bot](https://help.zoho.com/portal/en/kb/desk/support-channels/instant-messaging/telegram/articles/telegram-integration-with-zoho-desk#How_to_create_a_Telegram_Bot)
- to get the channel Id: [Read this article](https://neliosoftware.com/content/help/how-do-i-get-the-channel-id-in-telegram/) 
you can send a message in your channel or group in Telegram (through the mobile app or Telegram web, it doesn’t matter) and simply forward that message to @JsonDumpBot. The bot dumps a complete JSON of all request that he receives
