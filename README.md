# Kubernetes-intro

Setup
Install Powershell Core
Open Windows Powershell

Run

winget install Microsoft.PowerShell
Close Windows Powershell

Open Terminal

Arrow Down / Settings
Under Default Profile Select PowerShell NOT Windows PowerShell
Click Save
Restart Terminal

Back to top

Install WSL (Windows Subsystem for Linux)
In Powershell
wsl --install
wsl --update

wsl --install Ubuntu-24.04
Restart the Terminal again
Expand the Arrow Down and verify that you now have Ubuntu-24.04
Open an instance of Ubuntu
Back to top

Install docker desktop
In Ubuntu
sudo apt update
sudo apt upgrade -y

sudo apt install docker.io -y
sudo usermod -aG docker $USER
newgrp docker

.


