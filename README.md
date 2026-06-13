# Setup
<br>

- ** Enable "Http Enabled" in the game settings. **
- ** Enable "Loadstring" in serverscriptservice
- ** Put a script in ServerscriptServie

<br>

### Soure


```Lua

local HttpService = game:GetService("HttpService")
local rawLink = "DEIN_RAW_LINK_HIER"


 loadstring(HttpService:GetAsync(rawLink))


```
