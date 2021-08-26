# **Telegram bot with calling just one function.**

### Description:
If you have some functions and you want to **bot them** use **bottem** :wink:

___
### Requirements
* Python3+
* Pyrogram

___
### Usage:
```sh
cp config.init.example config.init
vi config.init
```
```python
from . import my_module
from bottem import Bottem

Bottem(my_module)
```
___
### Config file
* `api_id` from [telegram](https://my.telegram.org/apps)
* `api_hash`
* `bot_token` from [botfather](https://t.me/botfather)
  
<br/>
PS:  
BTW I've stolen this README.md from this [repo](https://github.com/tamton-aquib).
