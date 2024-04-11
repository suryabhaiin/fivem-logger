# sb-logger

[![Show Case](https://img.youtube.com/vi/DYD8PZn4y-g/maxresdefault.jpg)](https://www.youtube.com/watch?v=DYD8PZn4y-g)
This script manage your server log without database. you can search, filter log by category, filter by date and time range and search by any text features. You can create your staff account also.
<br>

# Preview : https://youtu.be/DYD8PZn4y-g <br>
# Demo is here : https://log.suryabhai.in/
```Lua
User : demo
Password : demo
```

## Features
- Advance fivem logger
- Search logs
- auto catch all existing qb-logs
- support ox.logger (Checkout ox.logger config bellow)


## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg


```Lua
exports['sb-logger']:createLog('log_category', 'log_message')               -- from client and server
```
# For ox_lib logger catch
## if you want to catch lib.logger logs autometically then modify your ox_lib\imports\logger\server.lua in ox_lib

## add new service 
```Lua
if service == 'sblogger' then
    function lib.logger(source, event, message, ...)
        exports['sb-logger']:createLog(event, message) 
    end
end

```
# and add server.cfg 

```Lua
set ox:logger "sblogger"
```

# Buy here : https://surya.tebex.io/package/6093091

## Note : Make sure you have 1 extra port available on your host


<img src="https://profile-counter.glitch.me/sblogger/count.svg" /> 
