# Handy_Utils
Scripts to do certain actions in the game "AssaultCube"
## Description
First of all, you should have all in your autoexec.cfg. And of course, you can change the binds.
-	In autoexec, there are some misc settings, as toggleconsole on F, demo viewing binds (arrows) or inter menu (bind with “M”). But most important is to have well associated all scripts, as I show (i.e. with execdir for folders or exec for cfg).
-	Auto-sorry is just a modification of the old simple script to work with this version of the game. I have just changed some features and added a better menu. It will display a random sorry message at a random momment between 1 and 5 seconds. In the menu binded with “O”, you can set if you enable it, you can set the nick you want to work with (others will not auto sorry) and you can enable always.
-	Teamkillers menu is another modification of the script made by Thrawn, just adapted and colored. Really useful to hatch an eye to teamkillers. I binded it in letter “C”.
Now the most interesting to me and done by me:
-	Info scripts are a modification of geoip script combined with teamkillers menu and with some modifications to execute it on player connect and show his teamkills as well in a menu.
  -	When you enter a server, all players will be shown with their names, cn, IP, nationallity and Tks.
    -	When a player connects to the server you are in, it will show the same.
  -	Bind “Q” to show a menu with all players and their information. 
  -	Useful commands:
     - info CN -> It displays the information of a player of our election on console.
     - Infoall -> It displays all players information on console.
-	Admin tools are some scripts to make easier and faster to be admin. I’ve done it from the beginning since lack of compability between versions. And added some extra very interesting features.
  -	With letter “P”, or with every admin tools command, you can take/release admin. When you are in other nick, you will change the nick to the name you had put in admin_name, when you press again (or vote has made), you will turn back to your old nick (useful for hosts or reports to know who was it).
  -	If you perform admin tools commands with a weak reason, it will transform to a valid generic one (to make it faster to ban if needed).
  -	First of all, we need to set up the servers in which we are admin.
      With letter “X”, when we are in a server, we can display a menu to put the password of it and save. That way, if we add various servers, we can just take admin with the letter “P”.
      -	You can change the admin name to change when having admin, even if you are on other name (to make easier for hosts to know who was it). 
  -	admin_name = "ADMIN_NAME"
      With letter “U”, you can prevent trollers or ban evaders (or VPN) to appear. Just set the name with “I” and everytime you press “U”, you will make an admin ban vote to the player NAME you had set. I think it is really usefull in those cases.
  -	Commands
    - /goadmin (to take admin if you have it)
    - /akick (kick with admin)
    - /aban (ban with admin)
    - /abanss (aban with remember for info and screenshot)
    - /abanname (aban by the name)
    - /abannamess (abanname with remember for info and screenshot)
    - /set_abanname (to fastly ban trollers) with the bind in “U”.
