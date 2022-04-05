# HyperVisor-Injector
# Please read the full description!
# if you are interested in the source you can purchase source via discord : skeng#9524

# version 1.2
- current status : undetected 


## [ How To Use ? ] 

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


## [ Why would i release this? ]
i am releasing this as an executable due to me not wanting people selling my source code.
the reason i released this is because i have just started college and have not enough time to keep working on my Pay to cheat as i have already made a lot of money from my cheat and development in other projects and still make an income from certain projects of mine that have been sold on to other branches and i just don't have the time to spend 12 hours coding everyday constantly like i use to but i will keep updating the driver and the injector for everyone that wants to play on anticheat games with there own software :)

