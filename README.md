# Windows Development Environment
When starting with a fresh install of Windows, this script installs my dev tools automatically and makes it easy to keep them up to date. Just run `env-windows` from a PowerShell window with admin priveleges, go make coffee, and come back ready to work.

## to run
1. First download a zip of this repo
2. extract it somewhere on your filesystem
3. open powershell as Administrator
4. run the following from the extracted directory (you should be in the directory with the env-windows.ps1 file)\
  `powershell.exe -ExecutionPolicy Bypass ".\env-windows.ps1 | tee-object 'install.log'"`