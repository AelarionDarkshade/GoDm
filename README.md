# Go-MassDM
coming soon star for updates!


this will release soon the code is just being uploaded here
the functions are still in development


these are working:
joiner
raider
pinger
checker
dm-spammer



# Config
_____________
Recommended Config:
```json
{
    "Modes": {
        "Discord": {
            "CfBm": false,
            "Service": "",
            "Api_Key": ""
        },

        "Net": {
            "JA3": "771,4866-4867-4865-49199-49187-52393-49191-107-158-52392-49200-103-49196-49192-159-49188-49195-255,0-11-10-35-16-22-23-13-43-45-51-21,29-23-30-25-24,0-1-2",
            "Agent": "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) discord/1.0.9006 Chrome/91.0.4472.164 Electron/13.6.6 Safari/537.36",
            "Proxy": "your.proxy.ip"
            "Redirect": false,
            "TimeOut": 0
        }
    },
    "Settings": {
        "Websocket": true,
        "Block_Usr": false,
        "Close_DM": false
    }
}

```

**Discord**
| Name | Type | Description | 
| ---  | ---  | ---         |
| `CfBm` | HEADER | Discord Clourdflare Cookie 
| `Service` | CAPTCHA | Captcha Service for Api Captcha solver
| `Api_Key` | CAPTCHA | Api Key for the Captcha Service

**Client**
| Name | Type | Description | 
| ---  | ---  | ---         |
| `JA3` | SSL/TLS | TLS Fingerprint can be left as is
| `Proxy` | HTTP | Your Proxy address Format: 'username:password@hostname:port
| `Redirect` | HTTP | specifies the policy for handling redirects
| `Agent` | HEADER | UserAgent for the http client
| `TimeOut` | HTTP | Time-[s] after request with no response, allowed

**MassDm**
| Name | Type | Description | 
| ---  | ---  | ---         |
| `WebSocket` | ADDON | Connect to discord wss before sending requests
| `Block_Usr` | ADDON | Block the User after sending them a message
| `Close_Dm` | ADDON | Close Dm after sendinf them a message
</p>

