#Nova.BotConnector

*Nova.BotConnector is a JavaScript connector to connect messagers and unification of work with them*

##Features
###Channel Capabilities
####Legend

|:material-close:                   |:material-check:                       |-                                              |
| :---:                             |     :---:                             |          :---:                                |
|Feature is not supported by channel|Feature is implemented in the component|Feature is not yet implemented in the component|

***

####Channels
| **Channel**                                                                                                                                                                          |**Text**         |**Image **       |**File **        |**Emoji**        |**Typing**       |**Quick Replies**|**Card**         |**Button List**  |**Button Grid**  |**Carousel**     |
| :---                                                                                                                                                                                 |:---:            |:---:            |:---:            |:---:            |:---:            |:---:            |:---:            |:---:            |:---:            |:---:            |
|<figure> <a href="botconnector/telegramconnector.html"> <img src="/novadocs/components/assets/telegram.svg" title="Telegram" width="100" height"100"> </a> </figure>                  |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/viberconnector.html"> <img src="/novadocs/components/assets/viber.svg" title="Viber" width="100" height"100"> </a> </figure>                           |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/fbconnector.html"> <img src="/novadocs/components/assets/fbmesseger.svg" title="Facebook Messeger" width="100" height"100"> </a> </figure>             |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/twitterconnector.html"> <img src="/novadocs/components/assets/twitter.svg" title="Twitter" width="100" height"100"> </a> </figure>                     |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/lineconnector.html"> <img src="/novadocs/components/assets/line.svg" title="Line" width="100" height"100"> </a> </figure>                              |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/slackconnector.html"> <img src="/novadocs/components/assets/slack.png" title="Slack" width="100" height"100"> </a> </figure>                           |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/abcconnector.html"> <img src="/novadocs/components/assets/abc.svg" title="Apple Business Chat" width="100" height"100"> </a> </figure>                 |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-close: |:material-close: |:material-check: |:material-check: |:material-close: |
|<figure> <a href="botconnector/whatsappconnector.html"> <img src="/novadocs/components/assets/whatsapp.svg" title="WhatsApp" width="100" height"100"> </a> </figure>                  |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |
|<figure> <a href="botconnector/kikconnector.html"> <img src="/novadocs/components/assets/kik.svg" title="Kik" width="100" height"100"> </a> </figure>                                 |-                |-                |-                |-                |-                |-                |-                |-                |-                |-                |
|<figure> <a href="botconnector/smoochconnector.html"> <img src="/novadocs/components/assets/smooch.jfif" title="Smooch" width="100" height"100"> </a> </figure>                       |:material-check: |:material-check: |:material-check: |:material-check: |-                |-                |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/vkconnector.html"> <img src="/novadocs/components/assets/vk.svg" title="Vkontakte" width="100" height"100"> </a> </figure>                             |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/okconnector.html"> <img src="/novadocs/components/assets/ok.svg" title="Odnoklassniki" width="100" height"100"> </a> </figure>                         |:material-check: |:material-check: |:material-check: |:material-check: |-                |:material-check: |:material-check: |:material-check: |:material-check: |:material-check: |
|<figure> <a href="botconnector/webchatconnector.html"> <img src="/novadocs/components/assets/webchat.jpg" title="WebChat" width="100" height"100"> </a> </figure>                     |:material-check: |-                |-                |-                |-                |:material-check: |:material-check: |-                |-                |:material-check: |
|<figure> <a href="botconnector/novachatsconnector.html"> <img src="/novadocs/components/assets/novachats.svg" title="NovaChats" width="100" height"200"> </a> </figure>               |:material-check: |-                |-                |-                |-                |:material-check: |-                |:material-close: |:material-close: |-                |
|<figure> <a href="botconnector/infobipconnector.html"> <img src="/novadocs/components/assets/infobip.png" title="Infobip" width="100" height"100"> </a> </figure>                     |:material-check: |:material-check: |:material-check: |:material-check: |-                |-                |:material-close: |:material-close: |:material-close: |:material-close: |
|<figure> <a href="botconnector/fbwpconnector.html"> <img src="/novadocs/components/assets/fbwallpost.png" title="Facebook Wallposts" width="100" height"100"> </a> </figure>          |:material-check: |:material-check: |:material-check: |:material-check: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |
|<figure> <a href="botconnector/twitterwpconnector.html"> <img src="/novadocs/components/assets/twitterwallpost.png" title="Twitter Wallposts" width="100" height"100"> </a> </figure> |:material-check: |:material-check: |:material-check: |:material-check: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |
|<figure> <a href="botconnector/vkwpconnector.html"> <img src="/novadocs/components/assets/vkwallpost.jpg" title="Vkontakte Wallposts" width="100" height"100"> </a> </figure>         |:material-check: |:material-check: |:material-check: |:material-check: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |
|<figure> <a href="botconnector/okwpconnector.html"> <img src="/novadocs/components/assets/okwallpost.png" title="Odnoklassniki Wallposts" width="100" height"100"> </a> </figure>     |:material-check: |:material-check: |:material-check: |:material-check: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |:material-close: |