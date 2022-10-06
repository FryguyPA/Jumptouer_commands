# Audit file via jump router<br>

The purpose of this script is to allow you to use a router as a "jumphost" for running commands.<br>
This script will ssh to the device listed in *jumphost.txt* and then iterate over the *routers.txt* and *commands.txt* file. <br>
<br>
Output is saved in the *output* directory with an individual file based on the device name in *routers.txt*.


### Command:
*python main.py jumphost.txt routers.txt commands.txt*

Where: <br>

>main.py
>> The script!<br>

>jumphost.txt
>>ip<br>
>>port<br>

>routers.txt
>>router1<br>
>>router2<br>
>>router3<br>
>>etc. . .<br>

>commands.txt
>>command1<br>
>>command2<br>
>>command3<br>
>>etc. . .<br>

<br>
---
Example:

>jumphost.txt<br>
>>192.168.0.117<br>
>>22<br>

>routers.txt<br>
>>10.2.2.2<br>
>>10.3.3.3<br>
>>10.4.4.4<br>

>commands.txt<br>
>>show ip int br<br>
>>show ip ospf interface<br>
>>show ver<br>


Jeff Fry
Fryguy.net


  