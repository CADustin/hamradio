# Baofeng UV-5R Cheatsheet

## Valid for
* UV-5R
* UV-5R+
* BF-8HP
* ...Probably others?...

## Useful Accessories

### Antenna's
* [NA-771 15.6-Inch Whip VHF/UHF (144/430Mhz) Antenna](https://www.amazon.com/Authentic-NA-771-15-6-Inch-SMA-Female-BTECH/dp/B00KC4PWQQ/ref=sr_1_3?dchild=1&keywords=NA-771&qid=1599754810&s=electronics&sr=1-3) -- If I'm going to use a long antenna on my radio and I don't care about the storage space, this is what I'll use. I carried one for a very long time, using it in the car, and hiking through the Sierra's. I was never disappointed with this antenna's capabilities.
* [NA-771R 16-Inch Retractable VHF/UHF (144/430Mhz) Dual Band Antenna](https://www.amazon.com/gp/product/B075XS66YC/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) -- This is a newer antenna to me, still an NA-771, but it's retractable making it an interesting choice for situations where the constraints prevent me from using a regular NA-771. 

### Batterys, Power, and Charging
* [BL-5 3800mAh Extended Battery](https://www.amazon.com/Baofeng-Batteries-Compatible-Rechargeable-Mirkit/dp/B07MNTFD4P/) -- If I am worried about the space / weight and I dont need runtime, the standard battery is fine... However, if I need runtime and I plan to recharge using the USB Cable, these batterys are an amazing accessory to have.
* [Mirkit 2.5mm USB Charger Cable](https://www.amazon.com/Mirkit-Charger-Indicator-Capacity-Batteries/dp/B084ZXTSHT) -- This charger can be used to recharge the **3800mAh Extended Batterys** via USB. This is extremely appealing if you think you may need to recharge your battery via a USB Battery Pack or in the car in some other emergency. Yes, there are other charging options like a DC Charger, AC Adapter, etc... but, when you consider the space used and the near universal capabilities, I have decided to only carry these cables.

### USB Programming Cables
* [Mirkit USB FTDI Programming Cable Model 3](https://www.amazon.com/gp/product/B07MQVJLZ4/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) -- I've tried quite a few programming cables for the Baofeng radios and this seems to be the most robustly designed, and easiest to use cable. Some of the other FTDI cables seem to take some fiddling with to get them to work and can take 20+ minutes to get working for the first time. This cable from Mirkit really was plug and play.

## List of UV-5R Menus
| Commonly Used | Menu Item | Menu Name | Description |
|---------------|-----------|-----------|-------------|
| Y 			| 0 		| SQL 		| squelch level: 0-9
|   			| 1 		| STEP 		| frequency step: 0 2.5, 1 5, 2 6.25, 3 10, 4 12.5, 5 25
| Y 			| 2  		| TXP 		| transmit power: 0 high, 1 low
|   			| 3  		| SAVE 		| battery save: 0 off, 1 1:1, 2 1:2, 3 1:3, 4 1:4
|   			| 4  		| VOX 		| 0 off, 1-10
|   			| 5  		| WN 		| wideband/narrowband: 0 wide, 1 narrow
|   			| 6  		| ABR 		| display illumination: 0 off, 1, 2, 3, 4, 5 seconds
|   			| 7  		| TDR 		| dual watch reception: 0 off, 1 on
|   			| 8  		| BEEP 		| keypad beep: 0 off, 1 on
|   			| 9  		| TOT 		| transmission timer: 0 15, 1 30, 2 45, 3 60, … 585 and 600 seconds in 15-second increments
|   			| 10  		| R-DCS 	| reception digital coded squelch
| Y 			| 11 		| R-CTCS 	| reception continuous tone coded squelch
|   			| 12  		| T-DCS 	| transmission digital coded squelch
| Y 			| 13 		| T-CTCS 	| transmission continuous tone coded squelch
|   			| 14  		| VOICE 	| voice prompt: 0 off, 1 on (older versions), 0 off, 1 English, 2 Chinese (Newer versions)
|   			| 15  		| ANI-ID 	| automatic number identification of the radio: can only be set by pc software
|   			| 16  		| DTMFST 	| dtmf tone of transmitting code: 0 off, 1 dt-st, 2 ani-st, 3 dt+ani
|   			| 17  		| S-CODE 	| signal code: only could be set by pc software
|   			| 18  		| SC-REV 	| scan resume method: 0 TO, 1 CO, 2 SE
|   			| 19  		| PTT-ID 	| push to talk id: 0 off, 1 bot, 2 eot, 3 both
|   			| 20  		| PTT-LT 	| delay the signal code sending, 0-30 ms
|   			| 21  		| MDF-A 	| (under channel mode the channel displays): 0 frequency, 1 channel number, 2 name (name is only programmable via programming software)
|   			| 22  		| MDF-B 	| same as menu 21, for b band
|   			| 23  		| BCL 		| busy channel lockout: 0 off, 1 on. [Note: This doesn’t lock out a channel from memory scan. It prevents transmitting on a busy channel and is programmed on a per channel basis.]
|   			| 24  		| AUTOLK 	| keypad locked automatically: 0 off, 1 on
| Y 			| 25  		| SFT-D 	| direction of frequency shift: 0 off, 1 plus, 2 minus
| Y 			| 26  		| OFFSET 	| frequency shift: 0-69.990 mhz
| Y 			| 27  		| MEM-CH 	| store memory channels: 000-127
| Y 			| 28  		| DEL-CH 	| delete memory channel: 000-127
|   			| 29  		| WT-LED 	| illumination display color of stand by: 0 off, 1 blue, 2 orange, 3 purple
|   			| 30  		| RX-LED 	| illumination display color of reception: 0 off, 1 blue, 2 orange, 3 purple
|   			| 31  		| TX-LED 	| illumination display color of transmission: 0 off, 1 blue, 2 orange, 3 purple
|   			| 32  		| AL-MOD 	| alarm mode: 0 site, 1 tone, 2 code
|   			| 33  		| BAND 		| band selection: 0 vhf, 1 uhf
|   			| 34  		| TDR-AB 	| transmitt+ selection while in dual watch/reception: 0 off,  1 a, 2 b
|   			| 35  		| STE 		| tail tone elimination: 0 off; 1 on
|   			| 36  		| RP-STE 	| tail tone elimination in communication through repeater: 0 off; 1-10
|   			| 37  		| RPT-RL 	| delay of tail tone of repeater: 0 off; 1-10
|   			| 38  		| PONMSG 	| boot display: 0 full; 1 mgs
|   			| 39  		| ROGER 	| tone end of transmission: 0 off; 1 on
|   			| 40  		| RESET 	| restore to default setting: 0 VFO; 1 all

## Programming the Radio

### How to manually program a simplex channel
1. Press **VFO/MR** and enter Frequency Mode.
2. Press **A/B** and choose the A Side (upper display).
The A side must be used to program channels into the radio. Programming data entered on the B Side (lower display) will not be saved.
3. Press **BAND** for the frequency band.
Toggle **BAND** to choose 136 MHz (VHF) or 470 MHz (UHF).
If the incorrect band is chosen for the frequency entered in Step 5, the radio will cancel the operation.
4. Disable TDR (Dual Watch/Dual Standby).
Press **MENU** 7 **MENU** **press up/down arrow keys** OFF **MENU** **EXIT**
It is highly advised to turn TDR off when programming directly from the radio.
5. Enter the frequency.
Use the keypad to enter the frequency into the radio.
6. optional - Enter the transmit CTCSS/DCS code.

** CTCSS - **MENU** 13 **MENU** **enter/choose code XXXX** **MENU** **EXIT**
** DCS - **MENU** 12 **MENU** **choose code XXXXX** **MENU** **EXIT**
7. Assign the frequency to a channel.
**MENU** 27 **MENU** **enter channel number XXX** **MENU** **EXIT**
[Source](https://www.buytwowayradios.com/blog/2016/08/how_to_manually_program_the_baofeng_uv-5r_from_the_keypad.html)

### How to manually program a repeater channel
1. Press **VFO/MR** and enter Frequency Mode.
2. Press **A/B** and choose the A Side (upper display).
the simplex channels, the A side must be used to program the repeater channels into the radio. Programming data entered on the B Side (lower display) will not be saved.
3. Press **BAND** for the frequency band
Toggle **BAND** to choose 136 MHz (VHF) or 470 MHz (UHF).
If the incorrect band is chosen for the frequency entered in Step 6, the radio will cancel the operation.
4. optional - Clear any CTCSS/DCS codes previously assigned to the channel.
If no previous codes exist or when setting up the channel for the first time and no codes are needed, set the menu items listed below to OFF.
* RX DCS - **MENU** 10 **MENU** **enter 0 (OFF)** **MENU** **EXIT**
* RX CTCSS - **MENU** 11 **MENU** **enter 0 (OFF)** **MENU** **EXIT**
* TX DCS - **MENU** 12 **MENU** **enter 0 (OFF)** **MENU** **EXIT**
* TX CTCSS - **MENU** 13 **MENU** **enter 0 (OFF)** **MENU** **EXIT**
5. Disable TDR (DualWatch/Dual Standby).
Press **MENU** 7 **MENU** **press up/down arrow keys** OFF **MENU** **EXIT**
It is highly advised to turn TDR off when programming directly from the radio.
6. optional - Delete any existing data on the channel to program.
Skip this step when setting up the channel for the first time.
Press **MENU** 28 **press up/down arrow keys to choose channel number** **MENU** **EXIT**
It is highly advised to turn TDR off when programming directly from the radio.
7. Enter the repeater output (your receiving) frequency.
Use the keypad to enter the frequency into the radio.
8. Input the repeater frequency offset.
Press **MENU** 26 **MENU** **enter the offset for 2 meter or 70 cm repeater** **MENU** **EXIT**
9. Enter the Transmit Frequency Shift.
Press **MENU** 25 **MENU** **enter 1 for positive shift or 2 for negative shift** **MENU** **EXIT**
10. optional - Enter the transmit CTCSS/DCS code.
* CTCSS - **MENU** 13 **MENU** **enter/choose code XXXX** **MENU** **EXIT**
* DCS - **MENU** 12 **MENU** **choose code XXXXX** **MENU** **EXIT**
11. Assign the receive frequency entered in Step 7 to the channel.
**MENU** 27 **MENU** **enter channel number XXX** **MENU** **EXIT**
12. Press the ***\*Scan*** button to activate Reverse Mode and display the transmit frequency.
13. Assign the transmit frequency to the channel.
Press **MENU** 27 **MENU** **enter the same memory channel entered in step 12** **MENU** **EXIT**
14. Press the \**Scan** button to exit Reverse Mode.
[Source](https://www.buytwowayradios.com/blog/2016/08/how_to_manually_program_the_baofeng_uv-5r_from_the_keypad.html)

## Programming Examples

### Listen to an FM Radio Station
Living in California, one of the really useful things about having a Ham Radio has been being able to listen to whats going on with CalFire. A useful resource for CalFire frequencies is ['Scan CalFire'](http://www.scancal.org/calfire/index.html) -- which has a listing of frequencies being used by CalFire, how the organizational structure works, etc..

### Listen to a CalFire Frequency

### How to manually program a simplex channel

## Useful Guides
** https://miro.cmivolunteers.org/wp-content/uploads/2018/07/BaoFeng-UV5R-F8HP.pdf
