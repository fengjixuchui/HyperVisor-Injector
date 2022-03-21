# HyperVisor-Injector
# private source is up for sale discord : skeng#9524
- reasonable price offers for the source please
- i accept BTC | ETH | CashApp  
# be kind leave a star :)

# How to use 
- similar to my other injectors this will require you to use the window class name to inject into games  rename dll to [ rwx1.dll ]
- supported windows versions 1903 up till 20h2 

# games ive tested on so far
- Rust
- Lost ark
- Valorant
- Apex Legends
- Rainbow Six Siege
- Fortnite 
- Valorant


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


## Questions ?
- Q: does it work for all games | A: yes this does works for all games 
- Q: can i create threads in my dll? | A: Yes since we emulate anticheats with this injector you can create threads
- Q: Is there a risk of me using this ? | A: Of course there is as anything public can become detected 



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


## purpose of release ?
i dont have a lot of time since im very busy, another reason being i want to give everyone a chance to step into the internal cheating field and let people have the ability to inject into many anti-cheat protected games without worry.

future source may be released :)
