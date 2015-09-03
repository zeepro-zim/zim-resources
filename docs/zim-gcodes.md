# Zeepro-Specific G-Codes

Zeepro Forum users jpod (@jpodius) and dexx0008 looked through the controller board firmware files and collected all of the Zim-specific G-Code commands.  He posted them on [the forum] (http://zeeproforums.technobly.com/t/useful-zim-gcodes/243) but they are reproduced here.

| G-code             |  What it does on the Zeepro Zim                    |
|--------------------|----------------------------------------------------|
| M1202              | LED strips on                                      |
| M1203              | LED strips off                                     |
| M1614              | Get strip LED state (0 or 1)                       |
| M1200              | Blue LED on head on                                |
| M1201              | Blue LED off                                       |
| M1615              | Get blue LED state (0 or 1)                        |
| M106 S\<*0-255*\>  | Left fan level (print fan)                         |
| M107               | Left fan off                                       |
| M1663 R\<*0-200*\> | Right extruder multiplier percentage (100 is 100%) |
| M1663 L\<*0-200*\> | Left extruder multiplier percentage                |
| M2002              | Shutdown Zim                                       |
| M1402              | Print the left, right and bed temperatures         |
| M1000              | Stop print                                         |
| M1400              | Get Marlin Version                                 |
| M1600              | check state                                        |
| M1601              | Get extrud                                         |
| M1620              | get speed                                          |
| M1623              | get acceleration                                   |
| M1660              | Set offset                                         |
| M1661              | Get offset X                                       |
| M1662              | Get offset Y                                       |
| M1905              | Raise platform                                     |
| M1907              | get consumption                                    |
