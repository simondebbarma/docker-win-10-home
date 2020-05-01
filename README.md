# How To  Install Docker on Windows 10 Home
Use the instructions below to get Docker on your Windows 10 Home.


## Steps: 
1. Install Hyper-V using the [Hyper-V](scripts/hyperv.bat) script as Admin that will install the Hyper-V components. A reboot is required and make sure you run as Administrator.

2. Use the [Continers](scripts/hyperv.bat) script to get the Containers feature for Docker.

3. Download the latest installer for [Docker](https://www.docker.com/products/docker-desktop).

4. Temporarily modify the windows registry to validate the prerequisites for Docker installation.

Changes in \HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion :
```
EditionID: Core --> Professional
ProductName: Windows 10 Home --> Windows 10 Pro
```
