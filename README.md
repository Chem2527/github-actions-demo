# github-actions-demo


Created a sample dotnet application using 

dotnet new webapp -n DummyDotNetApp

created an instance with windows OS - attched volume of gp3 100gb

open powershell as admin and run:  Install-WindowsFeature -name Web-Server -IncludeManagementTools

by default disk is offline make it online by right-clicking on disk and again right-click and initialize the disk and create a partition with name convention as per comfort.


http://localhost---> we will be able to see IIS home page on browser. download https://dotnet.microsoft.com/en-us/download/dotnet in windows ec2 and install it. open epowershell and verify the version by entering dotnet --version

mkdir -p .github/workflows in git

install openssh on windows ec2 --> 

Add-WindowsCapability -Online -Name OpenSSH.Server~~~~0.0.1.0

Start-Service sshd

Set-Service -Name sshd -StartupType 'Automatic'


