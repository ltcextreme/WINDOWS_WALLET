# WINDOWS_WALLET:Getting started

Download the Windows wallet from Repository. Open your windows wallet and then Close your wallet then create the file named “litecoinextreme.conf” in the folder "%APPDATA%\litecoinextreme\". 
Paste the following text into litecoinextreme.conf and save the file.

addnode=nodea.ltcextreme.com
addnode=nodeb.ltcextreme.com

Open your windows wallet. Go to Help. Click Debug Window. 
This is the console where you will execute all commands.
Type this command to start mining your first block:

setgenerate true -1

If you want to use a specific number of CPU cores, instead of -1, type the number of cores.
You can type the following command to see the status of generation.

getmininginfo

It will take couple of minutes to mine your first block, depending on your computer hardware.
The message "No block source available" will disappear once you mine your first block. You are connected, when you see the icon (active connections) in the lower right corner of your wallet.

