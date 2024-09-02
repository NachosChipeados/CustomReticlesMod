### V1.3.9
- rpak materials update
### V1.3.81
- CHANGELOG/README fixes
### V1.3.8
- rpak materials update
### V1.3.7
- fixed "test" crash
### V1.3.6
- updated dependencies
### V1.3.5
- updated to the current modsetting format (I did it as soon as it launched but I forgor... sry )
### V1.3.4
- seperated temporarily into two mod files
- reworked ui for hcog2/redline_sight/holo_r2
- added support for mozambique/wingman/wingman_elite/RE45
- added uv clamp to wingman/mastiff reticles to avoid it going oob
### V1.3.3
- cleaned up rpaks due to issues with installation
### V1.3.2
- fixed hcog_r1 windage [didn't source global_scalar properly]
- updated proto_viewmodel_test sight selection
- Improved hcog_r5 vmt file [general tidying up]
- added hcog_r5 to latest .blend build of `r201_full_compile.blend`
- added vmt templates for custom color ammo counters
- added Hcog x1 classic from R5 to the rpak list





### V1.3.1
- fixed typo in r97 reticle vmt
### V1.3.0
- reorganised majority of materials
- Added option to customise windage [rear reticle] style
- Added option to resize windage [rear reticle] (by default size will be kept the same as reticle)
- Moved from individual scalars to a singular global one (First menu)
  [Automatic scaling will come soon™ w/ ### V1.4.0]
- added various options for ammo counters
Update info for mdlshitters:
temp update (file/name/scripting reorganization +more on the way), contact me if you plan on making new models ;)
### V1.2.0
- fixed ammo_counter_meter (broke when put on multiple bodygroups)
- added aog_r1 to proto_viewmodel_test selection
- adjusted default color/style values for most of the scopes
- proto_viewmodel_test now supports all reticles/ammo_counters/field_emitters
- updated gallery
### V1.1.0
- readme.md updates
- added proto_viewmodel_test replacement for testing offsets
- added ui for r201/hemlok iron sights
- added cqh sight support
- added hcog_r1 support [titanfall 1 version]
### V1.0.1
- minor fixes
### V1.0.0
- added global killswitch for reticle offset
- added option to prioritize custom color over colorblind setting
- changed how Holo_scale works - now it'll adjust offset_scalar automatically
- added presets for most common fov values [enable by typing ie 'exec crf_fov96']
### v0.0.2
- added proper aog_r1 correction
- changed acgs_sight windage to accomodate for sway correction

## TODO for ### V1.4
```
- Add support for NegativBuilt
- Add an option to force ptpov camera and force ads when option is highlighted(+user has the specific scope equipped)
- Add wrappers to minimize ammount of space in modsettings
- Add global color setting +colorblind options
- Replace 3 convar setup for colors to 2 convar (vector3 + multiplier)
- Replace 2 convar setup for scaling/offset scalar to vector2' and push values through vscript
- Add support for colorpickers
- Add automatic calibration based on lagrange' interpolation (no support for viewmodel_fov/zoom_fov_viewmodel) w/ a multiplier based on sway attachment
- Add Proper setup for sniper rifles (same setup as regular but reticle atlas will be x256 and windage x1024 to keep resolution krisp "enough")
- Update acgs sight to accomodate for new scanlines setup
- Replace current per weapon .blend setup with a global setup bound to 'ja_ads_attachment' bone
- Fix 'Oracle sight' lack of front vertices
- Add proper 2 texture setup for sniper rifles
- Update the base reticle atlas to feature ~20 reticles as opposed to 11
- Update/Reorganize atlases and mod.json to keep vanilla reticles in beginning of the .vtf
- Add new material proxies to recreate 'uiX_draw_cloaked' option used for rui
```