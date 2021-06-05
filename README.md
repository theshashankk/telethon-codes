# telethon-codes by shashankxD 

# #1 telethon code:

```python
from telethon import TelegramClient

#ploxx___use___your___own___apiid and hash 
api_id = "your api id here" #remove "" from api id 
api_hash = "your api hash" #dont remove "" from api hash 

from TelegramClient('anons', api_id, api_hash) as client:
  client.loop.run_until_complete(client.send_message('me', 'your code us correctly running'))
#You can run this code in termux or pydroid
#first install telethon "pip install telethon"
#$cd locate your file location
#$python3 filename.py
```

# #2 telethon code

```python
from telethom.sync import TelegramClient

api_id = your api id 
api_hash = "your api hash"
bot_token = "your bot token"

bot = TelegramClient('bot_token', api_id, api_hash).start(bot_token=bot_token)
with bot:
    ...
```
