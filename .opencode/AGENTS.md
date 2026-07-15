
## Build Workflow
When the user asks to compile:
1. `cpp.exe` → `2ccts.nml`
2. Delete `D:\Games\OpenTTD\content_download\newgrf\2ccts.grf` and `OpenTGVnml.grf` if they exist
3. `nmlc --grf "D:\Games\OpenTTD\content_download\newgrf\OpenTGVnml.grf" 2ccts.nml`
