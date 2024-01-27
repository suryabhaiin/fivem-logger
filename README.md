# sb-logger
Base scripts for QB-Core Framework :building_construction:

<img width="725" height="592" src="https://media.discordapp.net/attachments/977999778535321660/1200441751589105724/image.png?ex=65c63180&is=65b3bc80&hm=9f662f0c4855ff07c8bacad0adc53d06c1d46944ed84d20e1c122092157061de&=&format=webp&quality=lossless&width=725&height=592">
This script manage your server log without database. you can search, filter log by category, filter by date and time range and search by any text features. You can create your staff account also.

Demo is here : https://log.suryabhai.in/
- User : demo
- Password : demo

## Features
- Advance fivem logger
- Search easyly logs


## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg


```Lua
exports['sb-logger']:createLog('log_category', 'log_message')
```

```Lua
TriggerEvent('sblogger:createLog', 'log_category', 'log_message')
TriggerClientEvent('sblogger:createLog', 'log_category', 'log_message')
```

## default login info (Make sure to change on first login)
Default URL : http://localhost:3000
```Lua
User : admin
Password : admin
```

# Buy here : https://surya.tebex.io/package/6093091
