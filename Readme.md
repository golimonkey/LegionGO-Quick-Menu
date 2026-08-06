# LegionGo Quick Menu
A lightweight native quick settings overlay for the Lenovo Legion Go. Default Lenovo programs use 250MB+, this one uses ~60MB and around 40MB while in background.

It supports touch, mouse, keyboard, and the built-in controller, and can open directly from the physical Quick Menu button.

<img width="2241" height="1400" alt="Untitled" src="https://github.com/user-attachments/assets/10510c78-433f-4526-8377-017c644c8fd1" />


[!WARNING]<br />
This project is experimental and uses undocumented Lenovo interfaces.<br />
Back up your drive before using it.<br />
Use it entirely at your own risk. I am not responsible for data loss, hardware damage, software problems, overheating, controller issues, or any other damage.


https://github.com/user-attachments/assets/95581a2b-8ecc-4257-9ae8-3978100d53d6



# Compatibility

Tested only with: Lenovo Legion Space 1.3.4.9<br />
Other versions may not work.

# Installation

Open services.msc<br />
Stop DAService<br />
Set DAService startup type to Disabled<br />
Open Task Manager and Kill Task: LegionSettingMenu.exe<br />
Place LegionQuickMenu.exe inside: C:\Program Files\Lenovo\LegionSpace\1.3.4.9\<br />
Run the program<br />
Open Settings and enable Start with Windows<br />
The program must remain running in the background for the Legion buttons to work<br />


# Features

Thermal Profile Selection<br />
Controller Profile Selection<br />
Brightness and Volume sliders<br />
Resolution and Refresh Rate switcher<br />
Fan Mode<br />
Shortcuts<br />
and more...<br />


#Important
Do not move or rename Lenovo DLL files.
Lenovo DLLs are not included in this repository.
The application must currently run from the Legion Space folder.
Only Legion Space 1.3.4.9 has been tested.
Other Legion Space versions may fail or behave differently.

#Download
https://github.com/golimonkey/LegionGO-Quick-Menu/releases

Disclaimer
This is an unofficial community project and is not affiliated with Lenovo.
Lenovo, Legion, Legion Go, and Legion Space are trademarks of Lenovo.
