# eventdrivenms
Using Dapr for event driven messaging

## Installations
For easy, I suggest using chocolatey for all installation on Powershell

1. Installing Chocolatey
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
2. Check chocolatey installed and well-referenced
```
choco --version
```
3. Installing Dapr using choco
```
choco install dapr
```
4. Check Dapr is installed and referenced
```
dapr
```
![image](https://github.com/NanaAgyirBrown/eventdrivenms/assets/23278430/ebdaa792-3078-4d16-a2dc-6feb983f64ba)

5. Install and run Docker Desktop
   You can follow - https://docs.docker.com/get-docker/ 
