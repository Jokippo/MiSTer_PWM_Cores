These are PWM builds of the N64, PSX and Saturn cores.

If you have a 18-bit analog board for the MiSTer (MiSTer Analog IO Board v6.1 or earlier) and use the VGA port to output to a CRT then these builds will allow you to view 24-bit content. See this link for more information and discussion: [PWM on 18-bit DAC to get 24-bit Color](https://misterfpga.org/viewtopic.php?t=7565)

Add these lines to downloader.ini and run update_all, A folder 'ConsolePWM' will appear with the PWM Cores inside.

```
[Jokippo/MiSTer_PWM_Cores]
db_url = https://raw.githubusercontent.com/Jokippo/MiSTer_PWM_Cores/db/db.json.zip
```
