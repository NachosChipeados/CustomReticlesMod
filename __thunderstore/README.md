## _Customisable reticles framework_
### `Version v1.3.9` `/` ` internal mod version v1.3.9`
## 📲*Contact info:*
```
Discord id: Creamy#5877
NS Discord Server:
 For Crashes - Please refer #modding_chat and @ me, before creating a ticket for the support team
 For Skins   - Please refer to #skin_chat and make sure to @ me
```
## ℹ️Info 
This mod adds vmts/vtfs for customisable reticles as well as convars for modsettings to use.

All transformations to reticles can be done via console, all convars start with 'CRM.'

This mod reqiures a modder to implement vmts into their model, this mod does not work on vanilla weapons.

## `Avaible Reticle Styles`

![reticle](https://i.imgur.com/CLGvoyP.png)

## `Avaible Windage Styles`

![windage](https://i.imgur.com/0V7hhWP.png)

In order to use presets you need to input ie 'exec crf_fov96', if your fov is not on a list fear not, just play around with one of the scopes and create your own custom scalar based on theese values then simply save the your .cfg 
 file in [ns mod folder]/CustomReticlesFramework/mod/cfg

### Table for all FOV/cl_fovscale values


| FOV         | 70    | 76     | 80     | 86    | 90    | 96     | 100    | 106   | 110   | ~115 | 120   |
|-------------|-------|--------|--------|-------|-------|--------|--------|-------|-------|------|-------|
| cl_fovscale | 1.0   | 1.0825 | 1.1375 | 1.22  | 1.275 | 1.3575 | 1.4125 | 1.495 | 1.55  | 1.6  | 1.7   |
| SCALAR      | 2.065 | 1.88   | 1.75   | 1.608 | 1.5   | 1.361  | 1.268  | 1.141 | 1.062 | 1.0  | 0.877 |


### *Example cfg used for fov_scale "1.7"*
```
CRM.hcog2_offset_scalar 0.875
CRM.acgs_offset_scalar 0.875 
CRM.aog_r1_offset_scalar 0.875 
CRM.aog_r2_offset_scalar 0.875
CRM.cro_offset_scalar 0.875
CRM.r201_front_offset_scalar  0.875
CRM.vinson_front_offset_scalar 0.875
```

### How to check all offset presets using `proto_viewmodel_test`
To test all of the avaible sights you need to launch private match whith `sv_cheats 1` enabled.

![ass text](https://i.imgur.com/HRT1etq.jpg)

After you load into your map type in console `give proto_viewmodel_test` - this will show all avaible mods that can be equipped. Lastly equip the sight you'd like to preview.

![ass text](https://imgur.com/ENQ2B4q.jpg)

list of avaible scopes:
```
give proto_viewmodel_test hcog
give proto_viewmodel_test redline_sight
give proto_viewmodel_test threat_scope
give proto_viewmodel_test holosight
give proto_viewmodel_test aog
give proto_viewmodel_test aog_r1
give proto_viewmodel_test cqh
give proto_viewmodel_test hcog_r1
give proto_viewmodel_test hcog_r5
```

*To use this framework in your custom models download the .blend containing r201 with all base scopes or individual smd files from github link*

## ⚠️***Warning***

Unfortunetely settings such as cl_fov_scale;viewmodel_fov;zoom_fov (or any other settings that modify your fov), will 100% break the default scaling, in order to adjust it use [...]offset_scalar convar to fit your preference or use one of the presets mentioned above :p

Some .qc files need additionall $attachments like aog_r1 which you can copy from here:
```
$attachment "AOG_R1_FRONT" "def_c_scope_aog_r1" 0 1.685 -1.55 rotate -90 -90 0
$attachment "AOG_R1_REAR" "def_c_scope_aog_r1" 0 1.685 -1.56 rotate -90 -90 0
```

This is just a preview that was set up for 1.6 fov_scale, which is slightly  [fov_scale 1 = 70fov; fov_scale 1.55 = 110fov] 

## 📑Features 
## 8 styles of front reticles to choose from
![styles](https://user-images.githubusercontent.com/88903493/212467779-d36999b8-cd9e-4a9c-b98c-58db5b04a5b2.gif)
## ability to scale reticle
![scale](https://user-images.githubusercontent.com/88903493/212468200-88c8dfbb-b9bd-4f74-ac5c-a120ed2aec63.gif)
## customisable base colour
![colors](https://user-images.githubusercontent.com/88903493/212468009-3b495903-6dbc-4d11-bcbd-6e5b63c6a235.gif)
## reticle will be in sync with the crosshair/ center of the screen
 ![center](https://user-images.githubusercontent.com/88903493/212468636-0b807f09-9a61-46a6-b37c-d89558c5bc20.gif)
## RGB mode [can be assigned to toggle]
![hcog_rgb_gif](https://user-images.githubusercontent.com/88903493/210629404-69eb1338-420f-49bd-9be4-a579f4abc06c.gif)
## support for default colourblind modes `[enabled by default]`

### ⏬Installation
Install via thundersore/VTOL is preffered, but if you are installing this mod manually, install this skin as a **MOD** !!

# 📷 _Gallery_ [all available types]
## IRON SIGHTS
![ass text](https://i.imgur.com/WQiDs7K.jpg)
## HCOG R2
![alt text](https://i.imgur.com/6kTeHxU.jpg)
## ACGS SIGHT
![ass text](https://i.imgur.com/ROPtH7Q.jpg)
## HOLOSIGHT
![ass text](https://i.imgur.com/7ieaL4r.jpg)
## THREAT SCOPE
![alt text](https://i.imgur.com/PcLyf10.jpg)
## AOG
![ass text](https://i.imgur.com/FsMLQxM.jpg)
## AOG R1
![ass text](https://i.imgur.com/uyazOwr.jpg)
## CQH SIGHT
![ass text](https://i.imgur.com/64JEFCn.jpg)
## HCOG R1
![ass text](https://i.imgur.com/XFHZzbU.jpg)
Have fun <3