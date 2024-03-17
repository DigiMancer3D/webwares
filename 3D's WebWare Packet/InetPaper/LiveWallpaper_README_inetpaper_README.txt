---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
'####:'##::: ##:'########:'########::::'##:::::::'####:'##::::'##:'########::::'##:::::'##::::'###::::'##:::::::'##:::::::'########:::::'###::::'########::'########:'########::
. ##:: ###:: ##: ##.....::... ##..::::: ##:::::::. ##:: ##:::: ##: ##.....::::: ##:'##: ##:::'## ##::: ##::::::: ##::::::: ##.... ##:::'## ##::: ##.... ##: ##.....:: ##.... ##:
: ##:: ####: ##: ##:::::::::: ##::::::: ##:::::::: ##:: ##:::: ##: ##:::::::::: ##: ##: ##::'##:. ##:: ##::::::: ##::::::: ##:::: ##::'##:. ##:: ##:::: ##: ##::::::: ##:::: ##:
: ##:: ## ## ##: ######:::::: ##::::::: ##:::::::: ##:: ##:::: ##: ######:::::: ##: ##: ##:'##:::. ##: ##::::::: ##::::::: ########::'##:::. ##: ########:: ######::: ########::
: ##:: ##. ####: ##...::::::: ##::::::: ##:::::::: ##::. ##:: ##:: ##...::::::: ##: ##: ##: #########: ##::::::: ##::::::: ##.....::: #########: ##.....::: ##...:::: ##.. ##:::
: ##:: ##:. ###: ##:::::::::: ##::::::: ##:::::::: ##:::. ## ##::: ##:::::::::: ##: ##: ##: ##.... ##: ##::::::: ##::::::: ##:::::::: ##.... ##: ##:::::::: ##::::::: ##::. ##::
'####: ##::. ##: ########:::: ##::::::: ########:'####:::. ###:::: ########::::. ###. ###:: ##:::: ##: ########: ########: ##:::::::: ##:::: ##: ##:::::::: ########: ##:::. ##:
....::..::::..::........:::::..::::::::........::....:::::...:::::........::::::...::...:::..:::::..::........::........::..:::::::::..:::::..::..:::::::::........::..:::::..::
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
               
               
           
                                                                
--.--|             . . .     |    |                             
  |  |---.,---.    | | |,---.|    |    ,---.,---.,---.,---.,---.
  |  |   ||---'    | | |,---||    |    |   |,---||   ||---'|    
  `  `   '`---'    `-'-'`---^`---'`---'|---'`---^|---'`---'`    
                                       |         |              
           
               
               
			   
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
	
	
	
The Live Wallpaper AKA Internet Live Wallpaper is a simple raid capable webpage cycling background from IPFS CIDs with 4 virtual configurable memory arrays. You can adjust, clear, add and remove CID files to make your own. On screen there are only 3 points to focus on: the main image & background color (main & center of screen), the information output (center-bottom of screen), the input bar (bottom-right corner of screen). Clicking on the information output will toggle the input bar, so if you don't see the input bar or do not want to see the input bar simply click the hashed data. Because the Internet Wallpaper has 4 virtual congfigurable memory arrays, actions in the input field that are not CIDs to pull in from IPFS/IPNS you will need to end with "\" which will tell the system you are inserting a command.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PLEASE NOTE:
**There's a input loop for CID pulls. Every so many seconds, the system will grab any text in the input field and if it's a CID it will auto add that CID into it's main memory array. If it's not a CID, that will become a locked text. Don't lock yourself out of commands. This is an anti-bot feature just like it is ran on a local device.**
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



Command Inputs:
====================

**Clicking "[DONE]" after many commands will return the wallpaper to it's normal cycle upon the start of the next cycle. The cycle timer is used for rendering timers and to prevent overloading actions, this doesn't always work as intended**

====================
[user-input] Command\ ::Action Expected (notes)
====================

arcdump\ ::Dump Memory Array Archive into text 
arcdrip\ ::Display vmArray Archive Index Length (There's a chance the information doubles every time it's checked. Use Dump to Check Contents of Array [ie: length check].)
help\ ::Scrolls helpfull information in the informational display section (use help off\ to remove)
help list\ ::Scrolls all input capable commands as a list (use help off\ to remove)
list help\ ::Scrolls all input capable commands as a list (use help off\ to remove)
[almost anything] scroller\ ::Adds text before " scroller\" to the scroller bar's databox array (used to create custom scrollbars for your live wallpaper. use "scroller off\" to remove)
   **scroller\, scrollbar\ & marquee\ are all useable, all 3 should share the same memory array, I could be wrong about that thou**
  ***all scrollbars will return to their last known location if they are unchanged when called for again (stop marque\ removes marque data)***
credits\ ::Displays Credit Details
credit\ ::Displays Credit Details
whom made this\ ::Displays Credit Details
builder is\ ::Displays Credit Details
what are the numbers on the page for\ :: Displays detailed information about the infomration output hash
Q # ::Displays detailed information about the infomration output hash (This is a rare instance where the "pound sign" or "hash symbol" is used instead of "\")
blur\ ::Fuzzies the screen (use sharpen\ to correct)
   **blur\, fuzzy\ or glass\ can be used as the same but each has their own blur amount**
  ***sharpen\ or correct\ can be used to fix blurs and most screen adjustments***
frost\ ::Glazes the screen (use correct\ to sharpen)
   **frost\ or glaze\ can be used as the same but each has their own frost amount**
  ***sharpen\ or correct\ can be used to fix glazing and most screen adjustments***
crinkle\ ::Sprinkles haze over the screen (use correct\ to sharpen)
   **crinkle\ or sprinkle\ can be used as the same but each has their own haze amount**
  ***sharpen\ or correct\ can be used to fix hazing and most screen adjustments***
fix\ ::Breaks, adjusts then fixes the screen
breaker\ ::Breaks output to voided-screen (should return after about 30 seconds or so with a refurbished startup)
flashboot\ ::Wipes output to de-voided-screen (should return after 30 seconds or so with a refreshed startup)
[linked data] slidein-A\ ::Adds remote data into vmArray(A)
[linked data] slidein-B\ ::Adds remote data into vmArray(B)
[linked data] slidein-C\ ::Adds remote data into vmArray(C)
[linked data] slidein-D\ ::Adds remote data into vmArray(D)
[linked data] slidein_A-D ::Adds remote data into vmArrays(A,B,C,D)
   **slidein_#-# can use any combination of A-D as long as the starter# is lower than the ending# [with A=1 & D=4]**
  ***A-B, A-C, A-D, B-C, B-D, C-D are all the known combinations for multi-slidein setups***
reorg_raid0\ ::Sets Storage to Raid0 (A is load)
reorg_A-backup ::Syncs Disks to A
   **reorg_#-backup can use any combination of these array slots A,B,C,D as long as only using 1 array slot at a time**
  ***reorg_#-backup will sync to that disk chosen at #***
reorg_raid1\ ::Sets storage to Raid1 (1 backup)
   **reorg_raid# can use any combination of these identifiers 1,2,z0,z1,z2,g0,g1 as long as only using 1 identifier at a time**
  ***reorg_raid# will sync to that number of disks chosen at # (z & g represent a different category of syncing)***
reorg_1-backup\ ::Syncs disks to Backup drive
   **reorg_raid#-backup can use any combination of these identifiers 1,2,z0,z1,z2,g0,g1 as long as only using 1 identifier at a time**
  ***reorg_raid#-backup will sync that number of disks chosen at the 1st # (z & g represent a different category of syncing #)*** 
 ****reorg_raid#-backup-# will backup to that disk chosen at the second # (only 1 or 2 can be choosen for the second # and this cannot be used for raid1-backup because it ony has 1-array for dumping)****
dump_1\ ::Dumps D into raid load
   **dump_# can use any combination of these identifiers 1,2,z0,z1,z2,g0,g1 as long as only using 1 identifier at a time**
  ***dump_# will dump for the raid setup given at # (so pick your dump based on your array setup)***
reorg_raidz0-fullbackup\ ::Syncs disks to backup drive (fullbackup for raid type z0)
   **reorg_raid#-fullbackup can use any combination of these identifiers z0,z1,z2,g0,g1 as long as only using 1 identifier at a time**
  ***reorg_raid#-fullbackup will backup for the raid setup given at # (so pick your backup based on your array setup)***
clear A\ ::Clears Drive A
   **clear # can use any combination of these array slots A,B,C,D as long as only using 1 identifier at a time (Clears the vmArray for that selected Drive Series)**
clear no A\ ::Clears all drives except for Drive Series A
   **clear no # can use array slots A or D as long as only using 1 identifier at a time (Clears all except the vmArray selected)**
clear most\ ::Clears Drives B & C
clear other\ ::Clears Drives A & D
phresh\ ::Clears all images form the archive (arc)
fresh\ ::Clears all images form the archive (arc)
start\ ::Clears the archive (arc) & prepares for more inputs to start over 
lnkme\ ::Allows temparary use of links in the input field (most image links starting with "https://" should work without this)
clear\ ::Clears excess text
reboot\ ::Reboots to factory
data\ ::Displays Data Map
   **data\ dubug\ dubugger\ should all give this data**
  ***Clicking any [DONE] in the Data Map will drop the entire map***


   
   





===========================================================================================================================================================================================================================================================================================	
 ▄  █ ████▄   ▄ ▄          ▄▄▄▄▀ ████▄       ▄      ▄▄▄▄▄   ▄███▄   
█   █ █   █  █   █      ▀▀▀ █    █   █        █    █     ▀▄ █▀   ▀  
██▀▀█ █   █ █ ▄   █         █    █   █     █   █ ▄  ▀▀▀▀▄   ██▄▄    
█   █ ▀████ █  █  █        █     ▀████     █   █  ▀▄▄▄▄▀    █▄   ▄▀ 
   █         █ █ █        ▀                █▄ ▄█            ▀███▀   
  ▀           ▀ ▀                           ▀▀▀                     
===========================================================================================================================================================================================================================================================================================




Activate and let it run, as it finds the ipfs files it'll ad the images in automatically. If anything, add more CIDs and let it do it's thing. Hover over anything to learn more.




Find more information on Github (DigiMancer3D).


Made by 3Douglas Pihl (please note Bittube Airtime no longer works || BTC:39ajMiohYWzzSH8E55vANhZAnwcrjBnTD7)