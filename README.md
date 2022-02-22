# LazyMaster
<b>Because you're so lazy that you don't want to do a lot of things.</b></br>
You need a token to be able to use the module. There's two kind of token:</br>
- <b>personal token (10€)</b> that is used for a personal use of the module.</br>
- <b>guild token (150€)</b> that can be used by all members of a specific guild having the token.</br>

</br></br>
<b>Commands:</b></br>
- <b>meterkill</b> (enable / disable the kill process of the tera damage meter API)</br>
- <b>bank</b> (open the bank)</br>
- <b>broker</b> (open the broker)</br>
- <b>wardrobe</b> (open the wardrobe)</br></br>


<b>consumable @ARG</b></br>
Enable / disable auto use of wine / nostrum / noctenium / bravery / crystalbind only when in combat.</br>
By default, not using any parameters just enable / disable the auto consumable.</br>
Parameters <b>@ARG</b> being:</br>
- <b>ccb</b> (enable / disable use of auto crystalbind)</br>
- <b>nostrum</b> (enable / disable use of auto nostrum)</br>
- <b>bravery</b> (enable / disable use of auto bravery)</br>
- <b>noctenium</b> (enable / disable use of auto noctenium)</br>
- <b>wine</b> (enable / disable use of auto wine)</br></br>

<b>lazy @ARG</b></br>
You can have some usefull options with:</br>
Parameters <b>@ARG</b> being:</br>
- <b>tp</b> (enable / disable some dungeon teleportation to save time by not walking)</br>
- <b>tts</b> (enable / disable tts messages for some special skills on lancer, priest, gunner, berserker, valkyrie and warrior)</br>
- <b>brooch</b> (enable / disable auto-brooch after using a specific skill - list is in config.json -)</br>
- <b>autohp</b> (if set to true, it trigger a potion if your hp goes below the value in <b>hp @ARG1</b>)</br>
- <b>automp</b> (if set to true, it trigger a potion if your mp goes below the value in <b>mp @ARG1</b>)</br>
- <b>hp @ARG1</b> (the percentage - <b>@ARG1</b> between 0 and 100 - from when you need to trigger a potion)</br>
- <b>mp @ARG1</b> (the percentage - <b>@ARG1</b> between 0 and 100 - from when you need to trigger a potion)</br>
- <b>guildmake</b> (to make a guild, not really usefull tho)</br>
- <b>exit</b> (close the game faster than task manager)</br>
- <b>mail</b> (opening your mail box)</br>
- <b>dress</b> (to see the dresses)</br>
- <b>lobby</b> (usefull when you can't go to lobby for some reason - AFKer as example -)</br>
- <b>reset</b> (reset the dungeon)</br></br>

<b>goblin @ARG1 @ARG2</b>
You can teleport to goblin's location to get some sweet AC with this.</br>
Parameters @ARG1 being:</br>
- <b>robin</b> (<b>@ARG2</b> between 1 and 4)</br>
- <b>gibi</b> (<b>@ARG2</b> between 1 and 6)</br>
- <b>bary</b> (<b>@ARG2</b> between 1 and 3)</br></br>

<b>config.json</b> contains some usefull options:</br>
- <b>collection_effect</b> (the collection of effects you want to use on specific monster type, as a healer or in PvP - id's are from 1 to 37 -)</br>
- <b>card_preset</b> (the card preset you want to use on specific monster type, as a healer or in PvP - id's are from 1 to 10 -)</br>
- <b>ep_preset</b> (the EP preset page you will use for either PvP or PvE)
