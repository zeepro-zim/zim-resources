# Zeepro-Specific G-Codes

Zeepro Forum users jpod (@jpodius) and dexx0008 looked through the controller board firmware files and collected all of the Zim-specific G-Code commands.  He posted them on [the forum] (http://zeeproforums.technobly.com/t/useful-zim-gcodes/243) but they are reproduced here.

| G-code             |  What it does on the Zeepro Zim                    |
|--------------------|----------------------------------------------------|
| M1202              | LED strips on                                      |
| M1203              | LED strips off                                     |
| M1614              | Get strip LED state (0 or 1)                       |
| M1200              | Blue LED on head on                                |
| M1201              | Blue LED off                                       |
| M1615              | Get blue LED state (0 or 1)                       |
| M106 S\<*0-255*\>  | Left fan level (print fan)\*\*                       |
| M107               | Left fan off\*\*                                     |
| M1663 R\<*0-200*\> | Right extruder multiplier percentage (100 is 100%) |
| M1663 L\<*0-200*\> | Left extruder multiplier percentage                |
| M2000              | Begin printing                                     |
| M2001              | End printing                                       |
| M1904              | End printing when head is already stopped          |
| M2002              | Shutdown Zim                                       |
| M1402              | Print the left, right and bed temperatures         |
| M1000              | Stop print                                         |
| M1400              | Get Marlin Version                                 |
| M1600              | Display if printing from SD                        |
| M1601              | Display active extruder                            |
| M1620              | Read current feed rate                             |
| M1621 V\<*value*\> | Set current feed rate                              |
| M1623              | Get acceleration                                   |
| M1624 A\<*value*\> | Set acceleration                                   |
| M1650              | Extrude 20mm from first extruder                   |
| M1651              | Extrude 20mm from second extruder                  |
| M1652              | Reverse first extruder 20mm                        |
| M1653              | Reverse second extruder 20mm                       |
| M1660              | Set offset                                         |
| M1661              | Get offset X                                       |
| M1662              | Get offset Y                                       |
| M1905              | Raise platform                                     |
| M1907              | Get filament consumption for both extruders (mm?)  |
| M9000              | "Voyage" function\*                                 |
| M9001              | Z Movement Function\*                               |
| M9002              | "Square" function\*                                 |
| M1900              | Abort printing                                     |
| M1902              | Pause printing                                     |
| M1903              | Resume printing                                    |
| M999               | Resume printing following an error condition       |
| M240               | Takes a picture\*\*                                 |
| M304 P\<*value*\> I\<*value*\> D\<*value*\>               | Tune PID controller for heated bed temp[\*\*] (http://reprap.org/wiki/G-code#M304:_Set_PID_parameters_-_Bed)       |



\* Need to explore more about what this does or what units it works in

\*\* Standard RepRap G-Codes, but still useful so included here 
