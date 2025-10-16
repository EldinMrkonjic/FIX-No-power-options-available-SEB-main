# [FIX]: No power options available/Win+L shortcut disabled 
Note, this will only work if your issue is related to SEB (Safe Exam Browser).
This can occur if you once installed it/were required to install it.

## Instructions

Find the reset Folder of your SEB-Installation. The default path is:

`C:\Program Files\SafeExamBrowser\Reset`

In this Folder Find the reset Tool. The Tool is called

`SafeExamBrowser.ResetUtility.exe`

Start the Tool and allow admin access

![image](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/02e7be9d-1a37-46c9-b36c-bd11d74bd577)

Use the arrow keys to select `Reset system configuration to default values` like this:
![image](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/123bc8f8-2f6a-42d1-a011-1e601f80c2fa)

Then press Enter and enter the name of your Account, it is VERY IMPORTANT that you don't enter your name but the system name of your account. Otherwise it won't work.
If you dont know your current username you click [here](#How-to-see-your-username).
![image](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/73563773-a6e3-46e8-b664-2420c5751323)

Press Enter and wait.
![Screenshot 2024-04-03 130330](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/45099696-b44d-4e02-ab20-703c98d132cb)

If everything worked you should end up back here:
![image](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/d78cb6d7-13ce-4b09-95e2-fb69aad9ed2b)

You can exit and the options might be back already, if not you should restart your PC. You can shut down you PC by either holding the power Button until the screen goes black or by entering `shutdown /s` into the console. (`shutdown /f` works too and is faster but might cause loss of unsaved data)


## How to see your username

Start your Console, you don't need admin access for this.

![image](https://github.com/Becausnt/FIX-No-power-options-awailable-SEB/assets/142886938/3e5d3456-62dc-49ea-9c02-99ff40b88115)

Enter the command:

`net user`

This command lists all available users. You can ignore the users `DefaultAccount` and `WDAGUtilityAccount` as you probably aren't using those. Find your account and enter the name into the reset tool of the SEB. If you don't know which one is yours, you can just try all of them.
