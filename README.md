# sb-logger

<img width="752" height="592" src="https://media.discordapp.net/attachments/977925336882876437/1211851614458089513/image.png?ex=65efb3c4&is=65dd3ec4&hm=d7a2143881e967ec282444808178213c1378d08d81808b510bfb55669abdfaa2&=&format=webp&quality=lossless&width=822&height=671">
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

## if you want to catch lib.logger logs autometically then modify you ox_lib\imports\logger\server.lua in ox_lib

# add new service 
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


<img src="https://profile-counter.glitch.me/sblogger/count.svg" /> 
