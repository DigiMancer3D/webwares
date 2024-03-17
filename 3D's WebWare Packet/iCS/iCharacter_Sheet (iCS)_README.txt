---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
:'######::'##::::'##::::'###::::'########:::::'###:::::'######::'########:'########:'########::::::'######::'##::::'##:'########:'########:'########:
'##... ##: ##:::: ##:::'## ##::: ##.... ##:::'## ##:::'##... ##:... ##..:: ##.....:: ##.... ##::::'##... ##: ##:::: ##: ##.....:: ##.....::... ##..::
 ##:::..:: ##:::: ##::'##:. ##:: ##:::: ##::'##:. ##:: ##:::..::::: ##:::: ##::::::: ##:::: ##:::: ##:::..:: ##:::: ##: ##::::::: ##:::::::::: ##::::
 ##::::::: #########:'##:::. ##: ########::'##:::. ##: ##:::::::::: ##:::: ######::: ########:::::. ######:: #########: ######::: ######:::::: ##::::
 ##::::::: ##.... ##: #########: ##.. ##::: #########: ##:::::::::: ##:::: ##...:::: ##.. ##:::::::..... ##: ##.... ##: ##...:::: ##...::::::: ##::::
 ##::: ##: ##:::: ##: ##.... ##: ##::. ##:: ##.... ##: ##::: ##:::: ##:::: ##::::::: ##::. ##:::::'##::: ##: ##:::: ##: ##::::::: ##:::::::::: ##::::
. ######:: ##:::: ##: ##:::: ##: ##:::. ##: ##:::: ##:. ######::::: ##:::: ########: ##:::. ##::::. ######:: ##:::: ##: ########: ########:::: ##::::
:......:::..:::::..::..:::::..::..:::::..::..:::::..:::......::::::..:::::........::..:::::..::::::......:::..:::::..::........::........:::::..:::::
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
               
               
           
o,---.,---.
.|    `---.
||        |
``---'`---'
           
               
               
			   
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
	
	
	
The interactive Character Sheet (iCS) aka Character Builder (VRM Profile Page) are a hashed stored system for generating tabletop character sheets that are interactive with Wave-Data H-APIs and it's built in item recgonition system & custom License (the 'Unlocked License'). iCS can recgonize approximately a combined total of 1100 or so words. At any time you can click on the "Recgonized Items List" (Character-Sheet.html) and the words inside their recgonizable sections. iCS has a built in mechanic for importing & exporting items, gear, money, crypto & even metastats via the intergrated Wave-Data H-API system. All additional data is in the bottom section of the Character-Sheet.html page.


Capable Actions:
====================

Write Contracts, Journals, Deeds

Trade/sell/buy contracts, items, deeds, more

Read books to learn from them & Hold Books to obtain something from them

Exchange your Gold & Crypto in the in-house exchange (exchanging/selling/trading items with other players may effect your market and theirs)

Bank-to-Bank transfers (trade gold & crypto & move gold from player to player)

Wallet-to-Wallet transfers (move funds from player to player)

Crypto-Sweeping (sweep crypto wallets to obtain the crypto in your wallet)

Data & faux-Online Commands (this allows for accessing the bank & crypto markets for example)

API Moding (visavis Wave-Data H-APIs)

Custom Single-Player Game Pamphlets (exportable/importable)

Single-Player Multi-Player Offline-Enviroment





===========================================================================================================================================================================================================================================================================================	
 ▄  █ ████▄   ▄ ▄          ▄▄▄▄▀ ████▄       ▄      ▄▄▄▄▄   ▄███▄   
█   █ █   █  █   █      ▀▀▀ █    █   █        █    █     ▀▄ █▀   ▀  
██▀▀█ █   █ █ ▄   █         █    █   █     █   █ ▄  ▀▀▀▀▄   ██▄▄    
█   █ ▀████ █  █  █        █     ▀████     █   █  ▀▄▄▄▄▀    █▄   ▄▀ 
   █         █ █ █        ▀                █▄ ▄█            ▀███▀   
  ▀           ▀ ▀                           ▀▀▀                     
===========================================================================================================================================================================================================================================================================================




Simply fill out the sections and click on words to edit them! Play around and try clicking on the helpful learning sections at the bottom of the main page (Character-Sheet.html)!


 The interactive Character Sheet was first built up by 3Douglas 3D Pihl because of the Open Gaming License (pre OGL 2) was looking at being changed by Hasbro via Wizards of the Coast. Because of the hurt this would cause many people began very quickly changing to adapt to unforturnate events by these conglomerates. Out of that madness, 3D began showing an online usable Character Sheet. With a non-static character sheet not reliant upon OGL licensing this could help people continue to enjoy their favorite table top, RPG or larping online without worry.

============================================================================================================

   iCS takes cares of many actions for the users and considerations in a manner that is based on a custom RPG layout concept. The internal algos help make the process of keeping up with a character sheet easy for all user levels. The algorithms used are as follows:
----------------------------------------------------------------------------------------

 1) Input Maker: This algorithm inserts an input with some customized information per area
 
 2) Weight: This algorithm considers the estimated weight of items based on their item type. When a player becomes over-burdened, an orange OB will appear next to the Armor words.
 
 3) Holding: This algorithm looks at how many items are being held when equiping and unequiping weapons and books.
 
Holding Limits for single & Dual Wielding weapons:
 IF: A player that has strength that's higher then their strength combined with their phyiscal dexterity divided by their mental dexterity adjust up by 45 points can hold 2-handed items simultaneously.   "((S+PDex)/(Mdex))+45 <= strength" === Duel Wielding 2H Weapons
 
 THEN: If your character meets this criteria, equip a single handed object then equip a 2-handed weapon. Once equpied, unequip the 1-handed object then equip a second 2-handed weapon.  1H -> Hold Check (duel opened) -> 2H -> unequip 1H -> equip 2H (check not needed)

============================================================================================================

 User Details: This algorithm is a set of algorithms that keep track of various user character data.
 
 Armor Points: Points that represents the character's armor.
 
 Defense Points: Points that represents the character's attack power.
 
 Health Points: The number of points the user can take before dieing.
 
 Experience Points: The amount of total and active user experience points.
 
 Inspirations: Revalations by the character based on a random roll & other factors.
 
 Current Level: The character's level.
 
 Character Speed: How fast is the character.
 
 Moving Distance: How far can a character move (in meters).
 
 Character Wealth: The amount of wealth the character has obtained including gold, metal coins & cryptocurrency Unsued Transaction Output Hashes.
 
 Character Buy-In: The amount of cost to start a character for their attributes.
 
 Attributes & Skill Boost: The value of the attributes and the skill boost paramaters.
 
 Attribute Modifiers: Attributes Modifiers based on a unique cut-average.
 
 Spell Level: The level of a learned spell.
 
 Pages: Both a writable section of a paper object and the number of pages an object may contain.
 
 Item Hashing: The current item's state as a reversable hash.
 
 Item Rebuilding: The return API that tells how to rebuild the item via the hash.


The "iCS-giftsheet.txt" are some presaved gifts to get anyone started on their adventure!




Find more information on Github (DigiMancer3D).


Made by 3Douglas Pihl (please note Bittube Airtime no longer works || BTC:39ajMiohYWzzSH8E55vANhZAnwcrjBnTD7)