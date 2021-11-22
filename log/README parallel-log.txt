To monitor parallel process log:
1. Open get_log.ps1
1.a. Select Windows Powershell to open the file, at:
C:\Windows\System32\WindowsPowerShell\v1.0

2. If file immediately exit, need to set execution policy
Set execution policy by opening Windows powershell in admin mode, type:
Set-ExecutionPolicy RemoteSigned
Then type a

3. If still crashes, do manually in windows powershell. 
cd "C:/to the folder"
Get-Content "parallel-log.txt" -Wait