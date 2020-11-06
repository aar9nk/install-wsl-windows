# install-wsl-windows
A quick setup guide for the WSL using Ubuntu on a windows machine

## Before You Start

Update windows by opening the start menu and searching `Windows Update` 

Click **Check for updates**

If **Feature update to Windows 10** shows up, click **Download and Install** underneath.

![Extra Updates](./wslupdate.png) 

 

## Recording

* Start here: [Video 1](https://generationinitiative.zoom.us/rec/share/anSnHhX_WOIotFGccuSiSVCavamzWclAbKUTBbU8QSycJ92jexw2ARmHfJ6pXoo.qTaAeXvMN9mt654B?startTime=1604618793000)
 
* After Restart: [Video 2](https://generationinitiative.zoom.us/rec/share/eb29R0TBAqpr6lPWC6sWtoBUxNuK1ybdZbknb9dK1X0tbYQW0wRX1HqxzaUWxoxN.G5PBRBcy6-X3Y1kz?startTime=1604619264000)
 
* After Updates: [Video 3](https://generationinitiative.zoom.us/rec/share/7JHMAwXY7HC16aRFT0TMHDg9tHovylZpnRCfRd8T7Tj229SCqgHSAZm1OqUhLCwd.tG6CZclu-O3y-Log?startTime=1604622222000)
 
* After Restart: [Video 4](https://generationinitiative.zoom.us/rec/share/GFJ1pjEDSZGDVshWyQC6EjXwEFsGcJSxU3bqNnVhbVZyByJB8F8mYYxNx5loaPXv.Sj23RmWHzh-XE8dT?startTime=1604622554000)

* After Restart/After Errors: [Video 5](https://generationinitiative.zoom.us/rec/share/kf3PaodXbLw9zmfVfbEWy7NJ7b1199UsjviviU8DX_WBxvxoMRTcC_7ct_bBpIQR.g0biI3M23lrjweUo?startTime=1604623236000)

* Final Video: [Video 6](https://generationinitiative.zoom.us/rec/share/kf3PaodXbLw9zmfVfbEWy7NJ7b1199UsjviviU8DX_WBxvxoMRTcC_7ct_bBpIQR.g0biI3M23lrjweUo?startTime=1604624336000)
 
### After All Videos:
Open Ubuntu from the start menu:

* Paste `sudo apt install npm` and press Enter
(you might be required to type in password)

* Wait for it to complete


## Links and References

1. Chrome:
https://www.google.com.au/chrome/ 
 
2. `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`


3. `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`


4. `wsl --set-default-version 2`

4 b: 
 https://docs.microsoft.com/en-gb/windows/wsl/wsl2-kernel

5. Ubuntu:
 https://www.microsoft.com/store/apps/9n6svws3rx71
 
6. `sudo apt-get update`

7. `sudo apt-get install nodejs`

8. `sudo apt install npm `

9. Visual Studio Code: 
https://code.visualstudio.com/ 

10. Visual Studio Code Extension: 
https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

11. Postman:  https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop

12. This is all one command: 
` curl "https://raw.githubusercontent.com/aar9nk/terminal-files/master/{.bashrc,.git-completion.bash,.git-prompt.sh,.profile}" -o ~/#1 && rm -f ~/.bash_profile`

13. `mkdir jwd && cd jwd`

14. `code .`

## Errors

* Press start and type: `winver`

Make sure you come with the screenshot of the build number to make sure your computer is up to date! 

Reach out on slack! But the most likely case is not updating your Windows and you will be sent back to the start so make sure to follow all the steps!!

