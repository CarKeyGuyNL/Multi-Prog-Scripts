# Multi Prog Scrips

Here you can download the X-Horse Multi-Prog scripts i made.

## Installation
Download the desired script, open Xhorse Multi-PROG, \
Go to 'Scripts' -> 'Released features' -> 'Import' and \
select the .mjs file you just downloaded.
Under 'Released features' Select the script you imported
and click on Run. The script functions will now be visible in the menu.

## Script available
### 1. EWS Code Calculator
To program remotes for Land Rover / Mini / Rover, you need 3 sets of code which can be calculated by the barcode on the lable, or the sticker on the PCB of the remote (Original remotes. After-market remotes usual don't have a sticker on the PCB).

#### To calculate from barcode label, 
 Click on 'EWS Barcode', Enter the 35 characters, including the * symbols \
For example: *NAD644DAD644CFFN**FFFFFFFF529BB2V*.


```bash
Here are the codes for Barcode *NAD644DAD644CFFN**FFFFFFFF529BB2V*
-----------------------------------
Basic Code----------| AD 64 4D
Random Code---------| AD 64 4C
Encryption Code-----| FF FF FF FF FF 52 9B B2
-----------------------------------
```

#### To calculate from sticker,
 Click on 'EWS Sticker', Enter the 6 digits of the top row of the sticker.
 For example: "AD644D".


```bash
Here are the codes for Sticker AD 64 4D
-----------------------------------
Basic Code----------| AD 64 4D
Random Code---------| AD 64 4C
Encryption Code-----| FF FF FF FF FF 52 9B B2
