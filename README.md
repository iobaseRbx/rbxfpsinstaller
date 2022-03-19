# rbxfpsinstaller
Auto installs a roblox fps unlocker and updates it!


I do not own any rights to the origial package and I am not going to steal the code even if it is publically avaliable.


## How to install?

Simple either run the following code in a command prompt or download the code [here](https://pages.github.com/).


*install git*

open up a new command prompt and run the following below

```
powershell -command "Install-Module posh-git -Scope CurrentUser -Force"
```

*install files*

open up a new command prompt and run the following below after you did above.

```
git clone https://github.com/iobaseRbx/rbxfpsinstaller.git
```


**OR**

open up a new command prompt and run the following below

```
powershell -command "$souce = \"https://github.com/iobaseRbx/rbxfpsinstaller/archive/refs/heads/main.zip\"; $aPath = \"C:\temp\"; $newDestination = \"$aPath\rbxfps.zip\"; Invoke-RestMethod -Uri $souce -OutFile $newDestination -UseDefaultCredentials"
cd "C:\temp"
%SystemRoot%\explorer.exe "C:\temp"
```


## Aditional Notes

The x64 or 64 bit installer doesn't require admin permissions but may flag your default microsoft windows defender and same with the other one simply add them to an exclusion. (Reason being batch to exe not exactly greatest conversion thing) Just allow the file and you will be fine. We do not have a virus in here.
