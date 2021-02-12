# QuickEOS
v1.1

A little script to quickly log into the GVSU EOS servers using Pulse VPN

### Usage:
`./QuickEOS.ps1 [-n <int>] [-arch]`
Use `-n` to specify the number of the server you want to connect to (eos01, eos02, etc.)
Use `-arch` to connect to arch servers instead of eos

### Suggested Installation:
- Put it in `~/Documents/WindowsPowerShell/Scripts`
- Add an import to your `$PROFILE` like `Import-Module ~/Documents/WindowsPowerShell/Scripts/QuickEOS.ps1`

Or however you like, don't let me tell you what to do.
If you don't like my very mediocre PowerShell scripting, send me a PR.
Enjoy :)

### !!! Disclaimer !!!
This will store your GVSU credentials to your device. Use at your own risk.
