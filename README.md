### 請記得自行填入自己的KKTix Cookie~
#### `Usage: python3 oktix.py [Event] [Ticket ID] [Ticket Quantity] [Sleep Seconds]`
![](https://github.com/vungsung/OkTix/blob/master/running.png)

- 只支援 Python 3
- PIPy模組: `pip3 install requests bs4`
- Cookie驗證，需在原始碼填入Cookie
```
cookie = {
	'remember_user_token' : 'xxxxx',
	'kktix_session_token_v2': 'xxxxx'
}
```
- 參數說明:
```
Event: 活動名稱 (可透過url取得) e.g. sitcon2020
Ticket ID: 票卷資訊ID (可透過F12取得) e.g. 234871
Ticket Quantity: 票卷數量 e.g. 1
Sleep Seconds: 失敗後嘗試等待秒數 e.g. 1.5
```
