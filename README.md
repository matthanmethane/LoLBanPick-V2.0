# LoLBanPick-V2.0
Simulate League of Legend Ban Pick using FastApi and WebSocket
## Main  Feature
* **Real-time** update using **Websocket**
* Allow **multiple** independent ban picks running distinguished by a token
* **Retrieval** of current banPick information when any new WebSocket connection is made during a banPick
* Champions they selected but not locked-in is viewed to everyone
* All BanPick Basic Rules
  * Blue can't perform any actions when its Red turn
  * Spectate can only spectate
  * Champions selected cannot be reselected
## Running
1. Install requirements.txt 
2. Run python main.py
3. Open https://localhost:8080/create
 Then, you should see links generated for each side and for spectator
## Implementation
Backend: FastApi & Websocket <br/>
Frontend: Simple HTML, CSS, JavaScript <br/>
Template Engine: Jinja2 <br/>
![lol_ban_pick drawio](https://user-images.githubusercontent.com/10554125/178157555-a69eb301-cb6b-4cd5-b143-6e59783b7789.png)
## Demo
https://user-images.githubusercontent.com/10554125/178156919-246e3ca3-6bea-4d18-bcbb-de20b550d1f6.mp4
