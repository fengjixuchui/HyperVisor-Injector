# Windows Hyper-Visor Injector
- Tested on Windows 10 20h2 : OS Build 19042.1586



# If you are interested in buying my Private source codes or would like your own project to be developed, contact me via discord at: Skeng#6969
- I have multiple sources for sale
- Private Source Is perfect if you are starting up a p2c or if you want to be Undetected without facing bans
- I will only respond to serious Enquiries/Offers, Time wasters will not be tolerated.
- The private source code is fully undetected and has a lot more features and security than the public TEST version, it also supports all games + engines with much more flexabilty.

Vouches + Proof can be shown.
 
# before using do this
Please enable hyper-v in "turn windows features on or off". Then run launch.bat as admin, this will mount the EFI partition and move some files around then reboot you. Voyager is designed to recover from a crash. The first thing Voyager will do when executed is restore bootmgfw on disk. If any complications occur during boot you can simply reboot.

<img src="https://imgur.com/uOpcCp7.png">


INFORMATION: The public version of this injector Supports 64bit games only

       
# active updates + changes to keep this undetected and safe to use !
# version 8.0
- Easy Anti Cheat Status : 🟢
- Battleye Status : 🟢
- (Private) Vanguard Status : 🟢
- (Private) Riochet Status : 🟢


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
You must Disable exploit protection in windows
Disable Secure Boot/fast boot in Bios settings

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

What Does the private source includes: 

- all windows versions 


- In-Built hardware spoofer 
- EPT Hooks

## Multiple Injection methods To Choose
- Manual Map
- Load libary
- APC Injection
- Windows Hook


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


## Requirements before use
- C++ Redistributables 
- download at https://www.microsoft.com/en-gb/download/details.aspx?id=48145

# Remote code execution
- Execute functions in remote process
- Assemble own code and execute it remotely
- Support for cdecl/stdcall/thiscall/fastcall conventions
- Support for arguments passed by value, pointer or reference, including structures
- FPU types are supported
- Execute code in new thread or any existing one





## Questions ?
- Q: does it work for all games | A: yes this does works for all games that are 64bit
- Q: can i create threads in my dll? | A: Yes since we emulate anticheats with this injector you can create threads
- Q: Is there a risk of me using this ? | A: Of course there is as anything public can become detected 
- Q: If i purchase do i get the same source as the public version | A: No you get a completly private source code that only you will have

