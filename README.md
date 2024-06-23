Place the NativeUI files in a folder named NativeUI inside your resources folder.
Add to Server Config:

Open your server.cfg file and add the following lines to start your vehicle spawner resource and NativeUI:
cfg

**start NativeUI**
**start vehicle_spawner**

**Explanation**
NativeUI: A library that simplifies the creation of UI elements in FiveM.
MenuPool: A pool that manages all the menus.
SpawnVehicle Function: Spawns the specified vehicle at the player's location.
AddVehicles Function: Adds vehicle options to the menu.
OpenVehSpawnerMenu Function: Toggles the visibility of the vehicle spawner menu.
Key Control: Opens the vehicle spawner menu when the "E" key is pressed.

**Customization**
Vehicles: You can add more vehicles to the vehicles table in the AddVehicles function.
Key Binding: Change the key binding by modifying the key code in the IsControlJustPressed function.
This script sets up a basic vehicle spawner menu using NativeUI in FiveM. You can expand and customize it further to fit your needs.
