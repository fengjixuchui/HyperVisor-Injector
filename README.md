# HyperVisor-Injector
- Tested on Windows 10 20h2 : OS Build 19042.1586
# 200 stars for new injection release 
# last Updated 19/02/2023


# If you are interested purchasing my private source codes or want your own developed, contact me via discord : Skeng#6969
- this is perfect if you are starting up a p2c or if you want to be Undetected without facing bans



# before using you must do this
Please enable hyper-v in "turn windows features on or off". Then run launch.bat as admin, this will mount the EFI partition and move some files around then reboot you. Voyager is designed to recover from a crash. The first thing Voyager will do when executed is restore bootmgfw on disk. If any complications occur during boot you can simply reboot.

<img src="https://imgur.com/uOpcCp7.png">


INFORMATION: The public version of this injector Supports 64bit games only

       
# active updates + changes to keep this undetected and safe to use !
# version 7.0
- Easy Anti Cheat Status : 🟢
- Battleye Status : 🟢
- Vanguard Status : 🟢
- BattleEye Status : 🟢
- Riochet Status : 🟢


## [ How To Use Injector ? ] 

make sure your dll is in the same folder 
**re-name** your dll to **test.dll** if not it wont inject
**the dll must be in the same folder as the injector**
- **have your game open when using the injector** 
-  **Open the injector -> then type out your games class name ( if this doesnt work type the window class name ) **
-  **hit enter key after you have typed it out then wait for it to inject**

[![Video Of Injection]](https://streamable.com/gyqihv)



### C++ DLL Example:
```
#include <windows.h>
#include <stdlib.h>

BOOL APIENTRY DllMain(HMODULE hModule, DWORD  ul_reason_for_call, LPVOID lpReserved) {
    if (ul_reason_for_call == DLL_PROCESS_ATTACH) {
        // RUN YOUR CODE HERE
    }

    return TRUE;
}
```


# having issues injecting on higher windows versions ?
Disable exploit protection in windows
- type this as admin in cmd
- reg add HKLM\SYSTEM\CurrentControlSet\CI\Config /v "VulnerableDriverBlocklistEnable" /t REG_DWORD /d 0 /f
- reg add HKLM\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity/v "Enabled" /t REG_DWORD /d 0 /f

To apply the changes, you will need to reboot the system.
Note: if these dont work please disable all exploit protection and TPM then try again


## How to find the class name
- head over to https://www.nirsoft.net/utils/winlister.html and download winlister x64 or x32
- open it up look for your process for my example i will use notepad
- double click on the process that you are wanting to inject into 
- then find Class: and copy that and paste it into the injector 
<img src="https://i.ibb.co/BL79h5h/tempsnip.png">




## Supports Intel + Amd Cpu's

What the private source has 
## Multiple Injection methods To Choose
- Manual Map
- load libary
- APC Injection


## Injection - > extra information
- CreateRemoteThread
- NtCreateThreadEx
- RtlCreateUserThread
- Delayed Injection ( choose how long you want to delay it for in )
- Changes Started Thread's Start Address
- Create Threads + Detours can be used within your dll
- Clears Loaded Module's PE Headers
- Changes Started Thread's Start Address



# other stuff
- Simple Display Of Imports Found From File
- Information Displayed: RVA, Original First Thunk, Name Of Module, Name Of Imported Function ( Remember that this is being parsed through file, not through running process )

# process 
- Simple Table For Processes
- Info Displayed: PID, EXE Name, Window Name, Ram Used and Full Path
- Allows You To Switch To NtQueryVirtualMemory For Checking Loaded Modules


## Requirements
- C++ Redistributables 2015, 2017, 2019, and 2022 
- download at https://www.microsoft.com/en-gb/download/details.aspx?id=48145

# Remote code execution
- Execute functions in remote process
- Assemble own code and execute it remotely
- Support for cdecl/stdcall/thiscall/fastcall conventions
- Support for arguments passed by value, pointer or reference, including structures
- FPU types are supported
- Execute code in new thread or any existing one



##  WHAT ARE THE BENIFITS THAT COME WITH BUYING THE PRIVATE SOURCE CODE?
- It is fully private source code and you will be given a complete HyperVisor with instructions + help and support needed to get everything set up and working


## Questions ?
- Q: does it work for all games | A: yes this does works for all games 
- Q: can i create threads in my dll? | A: Yes since we emulate anticheats with this injector you can create threads
- Q: Is there a risk of me using this ? | A: Of course there is as anything public can become detected 
- Q: If i purchase do i get the same source as the public version | A: No you get a completly private source code that only you will have

