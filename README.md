# WebDKP
Originally Created by ZeddZorandor of Stormscale
Modified version of https://github.com/DuduSandsten/WebDKP/

Description:
The webdkp addon is used together with the site
www.webdkp.com to help guild leaders manage their
dkp. 

Information recorded by the addon is stored into a log file
which can then be uploaded by the guild master to the
website using the SyncTool. 


# HOW TO USE:

type /webdkp

For help with the addon, check out the tutorial at:
http://www.webdkp.com/index.php?view=tutorial


Type into chat:

?startbid [Item Link]

or shift+click an item with the bidding window open

To start dkp bidding

# MODIFICATIONS

  - Addon has been modified to accommodate fixed DKP costs. Any item specified in the WebDKP loot table will auto-fill when bidding starts.
  - To be elegible for loot, members will whisper ?main or ?off for mainspec or offspec respectively. Mainspec bid will be the price specified in WebDKP loto table. Offspec item is free.
  - Auto-award for bosskills has also been reduced to 2.
  - Use "?" prefix instead of "!", which is reserved for server commands on Elysium.
  - DKP listing has been disabled due to the spam-filter on Elysium.

# OLD FEATURES

- Sync tool that uploads syncs your dkp addon with the website
  Requires .Net 2.0 Framework:
  http://www.microsoft.com/downloads/details.aspx?FamilyID=0856EACB-4362-4B0D-8EDD-AAB15C5E04F5&displaylang=en

- Whisper DKP!
  Other members can now whisper you to have you automattically whisper them back with information
  (Whispers are hidden from you, so you dont' get bogged down in info)

  Commands that you can be whispered:
  
  ?help - sends them a list of commands
  ?dkp  - sends the person who whispered you their current dkp