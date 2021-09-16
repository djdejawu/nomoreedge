# nomoreedge
Uninstall Microsoft Edge

1. Install Python3 with latest pip module
2. Run **cmd** with Sysinternals tool **PsExec**
	```psexec.exe -i -s -d cmd.exe```
3. In new window run fix.py
	```python fix.py```
4. Safely remove packages from internal database with PowerShell as Administrator
	```Get-AppxPackage | Select-String -SimpleMatch "Edge" | Remove-AppxPackage```


Big thanks to @DoubleLabyrinth

Any donations are welcome at ERC-20 0xD8cA388d7DB2b05193FF5ACC5A28804f22ad6095