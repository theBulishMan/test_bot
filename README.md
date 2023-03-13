# test_bot
确保python版本高于3.7
```bash
python3 -v
```
安装依赖

werobot:
```bash
pip3 install werobot
```
openai:
```bash
pip3 install --upgrade openai
```
编辑config.json文件
```bash
"channel": {
        "type": "wechat_mp",

        "wechat_mp": {
          "token": "YOUR TOKEN",          
          "port": "80"                 
        }
       }
 ``` 
微信个人订阅号
http 访问的是80 https访问的是443 
记得设置好端口

填入key：
```bash
   "model": {
        "type" : "chatgpt",
        "openai": {
          "api_key": "",
          "proxy": "",
          "conversation_max_tokens": 1000,
          "character_desc": "你是ChatGPT, 一个由OpenAI训练的大型语言模型, 你旨在回答并解决人们的任何问题，并且可以使用多种语言与人交流。"
            }
        }
```
然后就可以试着运行app.py文件了
        python3 app.py
出现
```bash
[wechat_mp_channel.py:25] - [WX_Public] Wechat Public account service start!
Bottle v0.12.23 server starting up (using AutoServer())...
Listening on http://127.0.0.1:8088/
Hit Ctrl-C to quit.
```
就基本上成功了
