# Emby.Plugin.TelegramNotification

Emby Server Plugin for sending notifications to a Telegram bot.
For Emby Server Version up and including 4.7 use Version 1.2 of the Plugin.
For Emby Server Version 4.8.20 and up use Version 1.3.1 of the Plugin.

## Install
1. Install the Plugin by downloading the DLL (or build it yourself using VS2019) and putting it into your Emby Plugin folder
2. Restart your Emby Server
3. Talk to @BotFather with your favorite Telegram Client to create your Telegram Bot
4. Start a chat with your bot (or place it in a channel) and send a message to it
5. Fire up your browser and type the following URL: `https://api.telegram.org/bot<BotTokenGoesHere>/getUpdates` 
   (without the braces) and find the ChatID 
6. Use the Settings Page of the Plugin to set Bot Token and Chat ID
7. Activate the Telegram Notifications Plugin in the desired Server notifications

Based on the raw Telegram Plugin of an unknown Author, spiced up with pieces of the Slack Notification Author and much googleling.
Please test it as much as you can. 



##安装步骤：

1.下载DLL，复制到EMBY的Plugins目录

2.重启EMBY服务器

3.使用Telegram，找@BotFather创建一个机器人（bot）

4.跟bot开始一个会话，点/start

5.打开浏览器，输入 `https://api.telegram.org/bot<BotTokenGoesHere>/getUpdates` 找到ChatID

6.打开EMBY——设置——通知——添加——Telegram，输入机器人的Token和ChatID
