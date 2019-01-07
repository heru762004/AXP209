# AXP209
Used by CHIP NTC to read Voltage and Temperature Data

# USAGE
How to use : 
1. sudo su (login superuser to your chip)
2. nano axp209.sh
3. copy paste all the script
4. chmod 777 axp209.sh (change mod / permission to allow script to be running)
5. run script to get all info with ./axp209.sh -a

# SAMPLE
```
root@chip:/home/chip/Script# ./axp209.sh -a
              ACIN: 0	Avail: 0
              VBUS: 1	Avail: 1
             VHOLD: 1 (Whether VBUS is above 4.4V before being used)
  Shutdown voltage: 2.9V
VBUS current limit: 900mA
Boot source is ACIN/VBUS
Battery connected: 1
Temperature:	47.3°C (I've seen as high as 65°C)
Battery: 0%
ACIN:	0V
VBUS:	4.9487V   276.000mA
VBAT:	2.5883 V  Discharging at 0mA
Vout:	4.8846 V
```
