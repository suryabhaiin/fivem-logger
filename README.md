# sb-logger
Base scripts for QB-Core Framework :building_construction:

<img width="725" height="592" src="https://media.discordapp.net/attachments/977999778535321660/1200441751589105724/image.png?ex=65c63180&is=65b3bc80&hm=9f662f0c4855ff07c8bacad0adc53d06c1d46944ed84d20e1c122092157061de&=&format=webp&quality=lossless&width=725&height=592">
This script manage your server log without database. you can search, filter log by category, filter by date and time range and search by any text features. You can create your staff account also.

Demo is here : https://log.suryabhai.in/
User : demo
Password : demo

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

# License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>
