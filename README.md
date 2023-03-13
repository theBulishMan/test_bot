# test_bot
确保python版本高于3.7

    python3 -v

安装依赖
werobot
    pip3 install werobot
openai
    pip3 install --upgrade openai


编辑config.json文件
"channel": {
    "type": "wechat_mp",
        
    "wechat_mp": {
      "token": "YOUR TOKEN",          
      "port": "80"                 
    }
微信个人订阅号会只会访问80
更改key
  "model": {
    "type" : "chatgpt",
    "openai": {
      "api_key": "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",
      "proxy": "",
      "conversation_max_tokens": 1000,
      "character_desc": "你是ChatGPT, 一个由OpenAI训练的大型语言模型, 你旨在回答并解决人们的任何问题，并且可以使用多种语言与人交流。"
    }
