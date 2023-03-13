# test_bot
确保python版本高于3.7

“python3 -v”

安装依赖

“pip3 install werobot”

“pip3 install --upgrade openai”


编辑config.json文件
"channel": {
    "type": "wechat_mp",
        
    "wechat_mp": {
      "token": "YOUR TOKEN",          
      "port": "80"                 
    }
}
微信个人订阅号会只会访问80
