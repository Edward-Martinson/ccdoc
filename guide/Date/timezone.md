# $timezone
this function set the timezone for all date functions
get tz name (here)[https://en.wikipedia.org/wiki/List_of_tz_database_time_zones]
#### Usage: `$timezone[Region/City]`

### Accepted Zones:
Standard Zones like Africa/Cairo [(list here)](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)\
Or you can use `UTC+hh:mm` or `UTC-hh:mm` to specify a certain offset like `UTC+03:00`.

### Example:
<br/>
<discord-messages>
	<discord-message :bot="false" role-color="#ffcc9a" author="Member">
		!!exec 
        UTC $hour
        after Change $timezone[Europe/Zurich]
        Europe/Zurich $hour
	</discord-message>
	<discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
		UTC 10
        after Change  Europe/Zurich 12
	</discord-message>
</discord-messages>

##### Function difficulty: <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags: <Badge type="tip" text="timezone" vertical="middle" /> 
