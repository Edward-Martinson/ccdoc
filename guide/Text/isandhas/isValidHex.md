# $isValidHex
checks if the given int or hex code or [color name](../../CodeReferences/ref.embed.colors.md) is valid  ,returns true,false

#### Usage: `$isValidHex[int or hexcode or color name]`
Example:
<br/>
<discord-messages>
	<discord-message :bot="false" role-color="#ffcc9a" author="Member">
		!!exec $isValidHex[#ffffff] , $isValidHex[test], $isValidHex[Red]
	</discord-message>
	<discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
		true , false, true
	</discord-message>
</discord-messages>

##### Function difficulty <Badge type="tip" text="Easy" vertical="middle" /> 
###### Tags:
<Badge type="tip" text="is" vertical="middle" /> 
<Badge type="tip" text="ValidHex" vertical="middle" /> 