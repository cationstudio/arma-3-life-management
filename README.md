# arma-3-life-management

This is a management script for ArmA 3 RPG Life.

<a href="https://www.buymeacoffee.com/julianbauer" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## Installation

A working installation of ArmA Life RPG Framework is required for a successful installation. Modifying the ArmA Life RPG Framework could cause errors – feel free to connect to our discord if you have a problem.

### Step 1

Download the newest release and extract the archive. Copy the folder "perm" in your “cation” folder that can be found in the  root folder (subsequently called \<mission\>) of your mission.

### Step 2

Open \<mission\>/cation/cation_functions.cpp and insert

`#include "perm\functions.cpp"`

and save the file.

### Step 3

Open \<mission\>/cation/cation_master.cpp and insert

`#include "perm\config.cpp"`

and save the file.

### Step 4

Open \<mission\>/cation/cation_remoteExec.cpp and insert

`#include "perm\remoteExec.cpp"`

and save the file.

### Step 5

Open  \<mission\>/core/init.sqf and insert at the bottom

`[] spawn cat_perm_fnc_initPerm;`

and save the file.

**That’s it!**

You have installed the cationstudio management system successfully!

## Configuration

You can adjust settings in  \<mission\>/cation/perm/config.cpp.

In the settings it is important to set ArmA Life version to your used version.

Texts and translations can be edited in  \<mission\>/cation/perm/language.cpp.

The management system is opened by default by looking at the desired unit and pressing the key “H”. This key can be edited in  \<mission\>/cation/perm/config.cpp.
