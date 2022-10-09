# HyperVisor-Injector
# how does it recieve updates ? >> we communicate through a server to release updates to the injectors loader 
# Please read the full description!
# if you are interested in the private source you can purchase source via discord : skeng#9524

# before using make sure Hypervisor suport is on in bios
depending on your motherboard it may be called something different in your bios



<details>
<summary>update 28/09/2022</summary>
<br>
   # added VT support for EAC 
   # added supports SSDT hooks
   # added support R3 Hook
   # added hidden injection
   # supports hidden injections 
   # software: runs stable without issues
<br><br>
</details>


#changes 
- - 21/09/2022
  - fixed threading issues ( causing crashes )
  - added faster loading times 
  - added Operation spoofing
  - added custom shell code execution
  - added custom target process hijacking ( injects via another process )

  
- - 26/08/2022
    - faster loading loading times 
    - fixed crashing when injected into EFT, Valorant
    - added ue5 support
    - added imports support ( ex: minhook )
    - added payload manager 
    - added external changes ( works via config.ini )
    - added configuration system 
    - added dll streaming for p2c support 
    - fixed windows 11 issues with loading HV / drivers 
    - fixed Windows 20H2 issues with stuck on integrity checks 
    - fixed pc booting slower after restart
    - added auto spoof Hardware + Clear cache + traces
    
    
    
- - 23/06/2022
    - updated injection method for games
    - fixed eac blocking windows hook
    - fixed bsod issues
    - added automatically enable HV in bios
    - added auto spoof registry
    - added auto spoof HWID traces 
    - added clean traces for most games


 -  - 20/04/2022
       - WindowsHook -> added ( how to use ? | enter your dll filepath + the name of the dll | then simply write what you want the output name to be ( example "cheat" )
         what does it do ? | it converts your dll into bytes allowing the injector to read the dll bytes and inject them into your targeted game.

 -  - 14/04/2022
       - fixed call dll method 
       - fixed random bsod issues
       - added que dll injection
       - fixed detections for eac + be
       - imports fixed
       
# active updates + changes to keep this undetected and safe to use !
# version 2.0
- EAC Status : 🟢
- Vangaurd Status : 🟢
- BattleEye Status : 🟢
- Riochet Status : 🟢


## [ How To Use Injector ? ] 

# make sure you enable Hyper-V support in bios
some motherboards will name it differently so please look up before using

make sure your dll is in the same folder 
**re-name** your dll to **rwx1.dll** if not it wont inject
**the dll must be in the same folder**
-  **Open the injector -> then type out your game**
-  **hit enter key after you have typed it out**
- wait around 10-20 seconds for it to initalize


## Supports Intel + Amd Cpu's

## Injection methods 
- Manual Map
- load libary
- x86 / x64 support
- APC Injection
- SetWindowsHook ( uses window class name to inject )


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

# Remote code execution
- Execute functions in remote process
- Assemble own code and execute it remotely
- Support for cdecl/stdcall/thiscall/fastcall conventions
- Support for arguments passed by value, pointer or reference, including structures
- FPU types are supported
- Execute code in new thread or any existing one



## what are the benifits with buying the source?
- the source code is not public version it will be a completely undetected injector + driver along with a custom mapper allowing you to bypass vangaurd + faceit blocking methods 

- UI Mode ( imgui mode of the injector )
- dump games + the game pdb ( some games dont work )
- you can use detours + minhook
- decrypt warzone offsets
- decrypt rainbow 6
- dump offsets for all titles + auto sig maker
- choose what injection format you want x86 / x64
- IAT dumper
- Dump EAC + BE Drivers
- Anti-Cheat Emulator ( allowing you to do anything you want practically )


## Questions ?
- Q: does it work for all games | A: yes this does works for all games 
- Q: can i create threads in my dll? | A: Yes since we emulate anticheats with this injector you can create threads
- Q: Is there a risk of me using this ? | A: Of course there is as anything public can become detected 

