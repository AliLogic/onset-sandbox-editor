# onset-sandbox-editor
Authors: Digital, Logic_

#### Features
* Camera.
* Spawn objects, weapons, vehicles, doors & clothing.
* Precise editing.
* World saving and loads on server start.
* World auto saves every 15 minutes.
* Clothing fully synced.
* Copy pasting objects (rotation & scale).
* Select multiple objects.
* Delete object(s).
* Move, scale, rotate and copy object(s).
* Schematics (Save & load custom builds).

#### Installation
Create a folder inside your servers package folder called sandbox, download all files from this repository and place them inside the sandbox folder.
Edit your server_config.json to install sandbox as a package.
Weapons will not work unless you enable the "default" package.<br/>
![Config](https://cdn.felfire.app/55c69ef1e5eadca4c5101bb4195160b5.png)

#### Media
[Objects](https://cdn.felfire.app/c56de900778947bd42cae2deb246ab96.png)<br/>
[Weapons](https://cdn.felfire.app/04fb7fc70b9a83ba2c4fe8f835d1e2c3.png)<br/>
[Clothing](https://cdn.felfire.app/b9d66ca4a4633510de6918dd508f24f5.png)<br/>
[Vehicles](https://cdn.felfire.app/e68f2ed093420786f742d612ffffa8a8.png)

#### Updates
* Rewrote the duplication logic.  Now it duplicates the object and spawns it at the same position and selects it so you can move it.
* Added new vehicle ID 26 (Buzzard) support.
* Added all game doors until the update 1.1.0 (Released 8th of March, 2020)

#### Modification
* To add more vehicles, refer to VEHICLE_CONFIG and TOTAL_VEHICLES.
* To add more doors, refer to TOTAL_DOORS.
* To add more weapons, refer to TOTAL_WEAPONS.
* To add more clothing presets, refer to TOTAL_CLOTHING.