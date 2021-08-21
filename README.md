# Install Jetson Software with SDK Manager Instructions 

## 1. Create an NVIDIA Account 
- [X]  [New NVIDIA Account](https://developer.nvidia.com/login)
## 2. Install SDK Manager 
- [X] Click *FOR ANY JETSON DEVELOPER KIT*  in [JETPACK SDK](https://developer.nvidia.com/embedded/jetpack) 
- [X] *Download NVIDA SDK Manager*
## 3. In the terminal  

``` 
sudo apt install ./SDKmanager <your version>
sdkmanager

``` 
## 4. Setup the development environment 
- [X]  Hardware configuration >> Your Target hardware 
- [X] Target Operating System 

# *NOTE Important* 
![c2ef0d9d9039b7576b6544d9ba3b1965391c06cb_2_690x385](https://user-images.githubusercontent.com/66702376/130318701-11a2532f-2cba-455a-9387-14a3384b1f4d.jpeg)

> "No available releases for UbuntuXX.XX". This is because sdkmanager is supporting just Ubuntu 16.04 and Ubuntu 18.04. 
> You must find ```os-release``` file. You can find it in ```/etc/os-release```  and change it to 
```
NAME="Ubuntu"
VERSION="18.04.5 LTS (Bionic Beaver)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 18.04.5 LTS"
VERSION_ID="18.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=bionic
UBUNTU_CODENAME=bionic
```
> save it and open ```sdkmanager``` again.  

<img width="1036" alt="image" src="https://user-images.githubusercontent.com/66702376/130318894-9311aec7-e858-4ca8-a040-2871f80dbf47.png">

## 5. Hardware Connection 
- [X]  SD card to laptop 
- [X]  Micro USB of Jetson to laptop 
- [X] Power Jetson 

![2021-08-21 13 59 32](https://user-images.githubusercontent.com/66702376/130319664-99bab4ce-2b03-4655-b28b-bb8000a8de40.jpg)










