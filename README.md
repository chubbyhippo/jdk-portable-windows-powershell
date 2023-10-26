# jdk-portable-windows-powershell
```
$WebClient=New-Object Net.WebClient
$Uri='https://download.bell-sw.com/java/21.0.1+12/bellsoft-jdk21.0.1+12-windows-amd64.zip'
$WebClient.DownloadFile($Uri, "jdk.zip")
Expand-Archive -Path jdk.zip
```
