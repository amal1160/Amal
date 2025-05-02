name: Windows DEVLIDO - LiteManager

on:
 workflow_dispatch:

jobs:
 build:
  name: Start Building...
  runs-on: windows-latest
  timeout-minutes: 9999
   
  steps:
   - name: Downloading & Installing BY DEVLIDO
    run: |
     Invoke-WebRequest -Uri "https://gitlab.com/wm1968269/lm_win-10_github_rdp/-/raw/main/Downloads.bat" -OutFile "Downloads.bat"
     cmd /c Downloads.bat

   - name: Connect to LiteManager BY DEVLIDO
    run: cmd /c show.bat

   - name: Time Counter BY DEVLIDO
    run: cmd /c loop.bat
