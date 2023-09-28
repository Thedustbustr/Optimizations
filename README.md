# Optimizations
This will be a quick and simple way to optimize your Windows 11 (It probably works with 10) pc.

### Some things to note:
1. Almost all programs must be run as an administrator to run properly
2. You will most likely have to restart your computer after running any of these optimizations









# The Ultimate Windows Utility
[The Ultimate Windows Utility](https://christitus.com/windows-tool/) is easily one of the best programs for debloating windows. You can also install a wide variety of apps from this program.

### Installation 
To install it, open a powershell window as an administrator then type in the following command:<br /><sub> Note: If it askes you to install chocolatey, type `y`:</sub>
```
iwr -useb https://christitus.com/win | iex
```
### Settings
Once installed, I would recommend the following settings. I have tested these personally and only a few non-important issues occurred. I will have a section below on solutions to said issues.<br /><br />


**<ins>Tweaks<ins>:**<br />
Now I wouldn't expect you to just apply settings and not know what they do!
- **Run OO Shutup**: Disables Windows's access to private data
- **Disable Telemetry**: Disables data tracking
- **Disable Wifi-Sense**: Stops Window's from getting data about your Wifi connection and storing it on their servers
- **Disable Activty History**: Basically your browsing histroy but for all things you do on your pc
- **Delete Temporary Files**: Removes temporary files that are not necessary
- **Disable Homegroup**: Do you know what Homegroup is? Cause I didn't know until I looked it up. Useless. Eats ram. Get rid of it
- **Disable Storage Sense**: Although it *can* help with disk space, just manually run a `disk cleanup` every once in a while, and save ram and cpu usage
- **Disable Hibernation**: Disables hibernation, If you use a laptop, I'd probably leave it on
- **Disable GameDVR**: Disables the Xbox app clip recording 
- **Set Service to Manual**: Stops alot of unnecessary service from being started until they are needed
- **Show File Extensions**: Shows extensions to files in file explorer
- **Disable Notification Tray/Calendar**: If you don't use the calendar or notification tray (the thing that comes up when you click on the time), disable it
- **Remove ALL MS Store Apps**: Removes ***ALL*** Microsft Store apps. Removes a rediculus amount of bloatware but kind of a nuclear option.
- **Remove Microsfot Edge**: Uninstalls Edge
- **Remove OneDrive**: Uninstalls OneDrive, make sure you have your OneDrive backups disabled or else you may have to redownload alot of files from your OneDrive
- **Set Classic Right-Click Menu**: Restores the Windows 10 right-click menu with far more options
- **Disable Mouse Acceleration**: This removes mouse acceleration. This is extremely good for gaming as it decreases input lag and records the raw input from the mouse. However, if you are used to having it on, your mouse will feel different when it is off
  <br /><br />

![Tweaks](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Tweaks.png)

**<ins>Config<ins>:**
1. If you are having issues with games not running, installing .NET Frameworks may be helpful as alot of games rely on them.
2. If you are having issues your computer, some of the fixes may help.<br /><sub> Note: System Curruption Scans **WILL** take a while</sub>
<br />

![Config](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Config.png)

**<ins>Updates<ins>:**<br />
Make sure to set your updates to Security Only as if not on, all the bloatware will be reinstalled.<br /><br />
![Updates](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Updates.png)


### Issues
1. I've noticed that after running this tool when trying to start Minecraft the launcher will error out. I'm pretty sure it's due to the Xbox app being uninstalled. The solution is to reinstall the launcher from the official website.
2. You may have to reinstall snipping tool. Just search it on the Microsoft Store and install it.









# Registry Optimizer Utility
This utility is mainly for registry tweaks that can improve performance. You can also install a wide variety of apps from this program.

### Installation 
1. Download it from the [this github](https://github.com/Thedustbustr/Optimizations/tree/main/RegistryOptimizerUtility)
2. Run the .exe file as administrator

### Settings
Once installed, I would recommend the following settings. I have tested these personally and have not run into any issues. Thankfully the utility explains what everything does so I do not have too! Just click on the change you want more info on.

**<ins>General<ins>:**<br /><br />
![General](https://github.com/Thedustbustr/Optimizations/blob/main/.images/General.png)

**<ins>Windows 11<ins>:**<br />
<sub> Note: The "Enable Compact Mode in Explorer" is completly up to personal preference </sub><br /><br />
![Windows 11](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Windows11.png)

**<ins>Startup<ins>:**<br />
Just remove any programs that you will never have start at startup. Below is an example of mine:<br /><br />
![Startup](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Startup.png)

**<ins>Cleaner<ins>:**<br />
Clean any programs you want cleaned. I'd definitly recommend cleaning windows.<br /><br />
![Cleaner](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Cleaner.png)

**<ins>Registry<ins>:**<br />
These are just some small fixes, would definitely recommend applying them.<br /><br />
![Registry](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Registry.png)









# QuickCPU
[QuickCPU](https://coderbag.com/product/quickcpu) is a program that can help squeeze the max performance out of your CPU.

### Installation
1. Download it from [this github](https://github.com/Thedustbustr/Optimizations/tree/main/QuickCPU)
2. Run the .msi file to install
3. Once installed, run the program as administrator

**<ins>Tweaks<ins>:**<br />
The following settings are (to my knowlage) the best settings for performance. I have tested them for a while and have noticed no issues. Once applied, you can close the program.<br /><br />

![QuickCPU](https://github.com/Thedustbustr/Optimizations/blob/main/.images/QuickCPU.png)<br /><br />
![QuickCPUMAX](https://github.com/Thedustbustr/Optimizations/blob/main/.images/QuickCPUMAX.png)









# Registry Tweaks
These are registry tweaks that have to be manually applied. These can help with overall performance, input lag, and internet performance.

### Installation
1. Download it from [this github](https://github.com/Thedustbustr/Optimizations/tree/main/RegistryTweaks)
2. Extract the zip file

### Usage
To apply these tweaks, run all of the registry (.reg) files.









# Mem Reduct 
If you are having issues with high memory usage, [Mem Reduct](https://www.henrypp.org/product/memreduct) could help. It works by clearing any unused memory. The only issue is that it only clears it once, you will have to go back and continuously clear it.

### Installation
1. Download it from [this github](https://github.com/Thedustbustr/Optimizations/tree/main/MemReduct)
2. Run the .exe file to install
3. Once installed run the program as administrator

**<ins>Clear Memory<ins>:**<br /><br />
![MemReduct](https://github.com/Thedustbustr/Optimizations/blob/main/.images/MemReduct.png)










# Nvidia Drivers (Nvidia Only)
The latest graphics drivers usually maintain the highest performance and stability. To improve stability further, I installed the Nvidia Studio Drivers which update less frequently but are more stable. 

### Installation
1. The best way to download these drivers is through Nvidia GeForce Experience which you can download [here](https://www.nvidia.com/en-us/geforce/geforce-experience/)
2. Run the .exe file to install
3. Once installed run the program

**<ins>Install Studio Drivers<ins>:**<br /><br />
![Drivers](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Drivers.png)<br /><br />
![Studio](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Studio.png)









# Optimal Nvidia Control Panel Options (Nvidia Only)
Stock Nvidia Control Panel options are kinda bad. So I found (to my knowledge) the most optimal settings.

### Installation
1. Download the NvidiaProfileInspector for [this github](https://github.com/Thedustbustr/Optimizations/tree/main/NvidiaProfileInspector) (the zip file)
2. Run the .exe file
3. Download the BestPerformance profile from [this github](https://github.com/Thedustbustr/Optimizations/tree/main/NvidiaProfileInspector) (under profiles)

**<ins>Set Optimal Settings<ins>:**<br /><br />
![NvidiaInspector](https://github.com/Thedustbustr/Optimizations/blob/main/.images/NvidiaInspector.png)<br /><br />
![Profile](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Profile.png)<br /><br />
![Apply](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Apply.png)









# Overclock Nvidia GPU (Nvidia Only)
Using Nvidia GeForce Experience, you can safely overclock your GPU automatically.

### Installation
1. The best way to download these drivers is through Nvidia GeForce Experience which you can download [here](https://www.nvidia.com/en-us/geforce/geforce-experience/)
2. Run the .exe file to install
3. Once installed run the program

**<ins>Overclock GPU<ins>:**<br /><br />
![Settings](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Settings.png)<br /><br />
![Overlay](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Overlay.png)<br /><br />
Press Alt+Z by default to open the Nvidia Overlay<br /><br />
![Overlay](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Performance.png)<br /><br />
Make sure that: 
1. You have nothing graphically intensive (e.g. games, wallapaper engine, etc.) running as it may mess up the results
2. Your voltage maximum is at 100%<br /><br />

![Overclock](https://github.com/Thedustbustr/Optimizations/blob/main/.images/Overclock.png)
