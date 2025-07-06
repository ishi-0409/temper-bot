# temper-bot
slackでbotにメンションすると気温と湿度をこたえてくれる  
外出先でもraspberry pi 本体がwifiに接続されていればスマホのslackからメンションすればこたえてくれる

## デモ動画
[![Watch the demo](https://img.youtube.com/vi/wiVyNvclrGE/0.jpg)](https://www.youtube.com/watch?v=wiVyNvclrGE)

raspberry pi とパソコンがおなじwifiに接続されている場合






[![Watch the demo](https://img.youtube.com/vi/SRJZh7yryRo/0.jpg)](https://www.youtube.com/shorts/SRJZh7yryRo)

raspberry piが自宅のwifiに接続されているときにスマホのslackから外出先で部屋の温度と確認する場合  
このときスマホはraspberry piとおなじwifiに接続されていなくても可能


## メモ
トークンが必要（SLACK_BOT_TOKEN、SLACK_SIGNING_SECRET、SLACK_APP_TOKEN)  
temperIot.envファイルのなかに保存   
仮想環境が必要
