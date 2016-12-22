| /do/camp/LICENSE   |                        |
|:-------------------|:-----------------------|
| Info               | [alpha] [undocumented] |

| /do/camp/changeport            |                                                                                                                  |
|:-------------------------------|:-----------------------------------------------------------------------------------------------------------------|
| Info                           | [alpha] [undocumented]                                                                                           |
| Arguments                      | 1:port,                                                                                                          |
| Variables                      | port=$1,                                                                                                         |
| Modules                        | /do/supervisor/create camera "/usr/bin/python "/do/camp/www/server.py" --require-login  --use-usb --port $port", |
| 1. [CAMP] Change port to $port |                                                                                                                  |

| /do/camp/install                                                 |                                                                                                                                                                        |
|:-----------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Info                                                             | [alpha] [undocumented]                                                                                                                                                 |
| Softwares                                                        | python-dev, python-pip, python-opencv, libjpeg-dev,                                                                                                                    |
| Modules                                                          | /system/gitcloner patrickfuller/camp /do/camp/www, /do/supervisor/create camera "/usr/bin/python "/do/camp/www/server.py" --require-login  --use-usb --port 8000",     |
| System                                                           | /system/install python-dev, /system/install python-pip, /system/install python-opencv, /system/install libjpeg-dev, /system/gitcloner patrickfuller/camp /do/camp/www, |
| 1. Install camp Websocket camera webserver                       |                                                                                                                                                                        |
| 5. Type /do/camp/start and go to http://$(/show/name).local:8000 |                                                                                                                                                                        |

| /do/camp/readme.md   |                        |
|:---------------------|:-----------------------|
| Info                 | [alpha] [undocumented] |

| /do/camp/restart   |                                |
|:-------------------|:-------------------------------|
| Info               | [alpha] [undocumented]         |
| Modules            | /do/supervisor/restart camera, |

| /do/camp/start   |                              |
|:-----------------|:-----------------------------|
| Info             | [alpha] [undocumented]       |
| Modules          | /do/supervisor/start camera, |

| /do/camp/stop   |                             |
|:----------------|:----------------------------|
| Info            | [alpha] [undocumented]      |
| Modules         | /do/supervisor/stop camera, |

