# My Windows Terminal -setup

<p align="center">
  <img src="https://github.com/dev-rsrimon/my-windows-terminal-setup/blob/main/teminal.PNG" width="550" title="hover text">
</p>

## How to install 

### Step- 1

Install **Windows Terminal** from Microsoft Store

### Step- 2
Install **Fira Code** font (If you don't have)

### Step- 3
Copy past `setting.json` file code to your `terminal settings.json` file 

**From Terminal Task bar to click down arrow > tape shift button and click settings option** and see the terminal settings.json file is open on your default code editor

### Step- 4
install those packags.
Let's run those command on your terminal (If you don't have git bash. You need to install it before run those command)

`Install-Module posh-git -Scope CurrentUser`

`Install-Module oh-my-posh -Scope CurrentUser -RequiredVersion 2.0.412`

`Install-Module -Name PSReadLine -Scope CurrentUser -Force -SkipPublisherCheck`

### Step- 5
Run this command on your terminal 

`notepad $PROFILE`

your can see notepad open a file. Just past those line code into this then save and close

`Import-Module posh-git`

`Import-Module oh-my-posh`

`Set-PoshPrompt -Theme paradox`

###  Done 
Run this this command And enjoy your Awesome Terminal 

`Set-Theme Agnoster`



Thank you
