# NEW NOTICE! New private version 5.X

The new private version have:

-Weapon paint attached to his corresponding weapon.

-Multilanguage support for all the paints.

-Always updated with the new paints.

-Methods for prevent bans in your server and you can use it always.

-Full support.

-Soon much more.


Interested people contact with http://steamcommunity.com/id/franug (negotiable price). 

You can see all my servers with it here http://bans.cola-team.com/index.php?p=servers

# End of notice.


You want to support this plugin? you can with donations using Paypal to my account -> franug13@gmail.com
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=LWD5V2WBKDQPQ



Installation:
 
 
Upload .cfg file to addons/sourcemod/configs

Upload .smx file from the zip to addons/sourcemod/plugins

Upload .phrases.txt file to addons/sourcemod/translations

Add a entry called "weaponpaints" to addons/sourcemod/configs/databases.cfg


You dont need to upload the .sp file


If you already use a old version. Remove your database content and start since 0


A example of a basic databases.cfg is http://pastebin.com/XqsEjPhS


Cvar (put in server.cfg):

sm_weaponpaints_c4 "1" // Enable or disable that people can apply paints to the C4. 1 = enabled, 0 = disabled

sm_weaponpaints_saytimer "10" // Time in seconds for block that show the plugin commands in chat when someone type a command. -1 = never show the commands in chat

sm_weaponpaints_roundtimer "20" // Time in seconds roundstart for can use the commands for change the paints. -1.0 = always can use the command

sm_weaponpaints_rmenu "1" // Re-open the menu when you select a option. 1 = enabled, 0 = disabled.

sm_weaponpaints_onlyadmin "1" // This feature is only for admins. 1 = enabled, 0 = disabled. (Use the value 1 and try to keep this plugin secret for the normal users because they can report it)

sm_weaponpaints_zombiesv "1" // Enable this for prevent crashes in zombie and 1v1 servers for knifes. 1 = enabled, 0 = disabled. (Use the value 1 if you use my knife plugin)




Recommendations: dont advertise the plugin in sv_tags and use it only for admins
