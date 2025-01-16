![image](https://github.com/user-attachments/assets/69114066-08b1-4945-a3d0-569070172824)

`openupm search be.elab`


My aim in taking the time to publish packages on PyPi, Crates, OpenUPM, NPM, and NuGet is to enable IID Multiplayer game servers and IoT. I won't be putting all of my packages on OpenUPM, only those that contribute to this goal.

I need to have:
- IID: Tool defining what is a IID
- WowInt: Abstraction of what is keyboard and xbox controller
- WsMetaMaskCoaster: Tools that allows websocket authentification to server with ETH(RSA) as main or coaster key
  - See Pi Pythno PushIID 
- pBit4096B58Pkcs1SHA256 : Allows to make sign and verify RSA compatible in Python and Unity3D.


## Unity3D
- **IID, Index Integer Date Utility**:
  - [https://github.com/EloiStree/OpenUPM_IID](https://github.com/EloiStree/OpenUPM_IID)
- **Key Mapping of keyboard and Xbox as integers for playing games with a remote controller**:
  - [https://github.com/EloiStree/OpenUPM_WowInt](https://github.com/EloiStree/OpenUPM_WowInt)
- **Unity PushIID Connection**:
  - [https://github.com/EloiStree/2025_01_01_UnityToServerTunnelingMetaMaskWS](https://github.com/EloiStree/2025_01_01_UnityToServerTunnelingMetaMaskWS)
    - [https://github.com/EloiStree/pypi_pBit4096B58Pkcs1SHA256](https://github.com/EloiStree/pypi_pBit4096B58Pkcs1SHA256) for Python
    - [https://github.com/EloiStree/OpenUPM_pBit4096B58Pkcs1SHA256](https://github.com/EloiStree/OpenUPM_pBit4096B58Pkcs1SHA256) for Unity3D
    - [https://github.com/EloiStree/2025_01_01_ClipboardableAssymentricMetaCoasterUnity3D.git](https://github.com/EloiStree/2025_01_01_ClipboardableAssymentricMetaCoasterUnity3D.git)
  - [https://github.com/EloiStree/2024_08_06_PathTypeReadWrite](https://github.com/EloiStree/2024_08_06_PathTypeReadWrite)
  - [https://github.com/EloiStree/2024_04_04_GenereteRsaKeyInUnity](https://github.com/EloiStree/2024_04_04_GenereteRsaKeyInUnity)

 -----------
 
# OpenUPM
How to publish package on Open UPM

# Pi Python Server: 
- Server PushIID:
  - https://github.com/EloiStree/2025_01_01_HelloMetaMaskPushToIID.git
---------------- 

https://openupm.com/
https://openupm.com/packages/?sort=downloads&q=eloistree

[![image](https://github.com/user-attachments/assets/88ac53de-d863-475b-9532-3b850c762d69)](https://youtu.be/lZrL0YZ7vAo)   
https://youtu.be/lZrL0YZ7vAo  



# Use 
1. Download https://nodejs.org/en/download/  
![image](https://github.com/user-attachments/assets/2fa30c01-b7c8-45f2-b9ba-58aab6084fe2)

2. `npm install -g openupm-cli`   
3. Go to your project Unity3D   
4. `openupm search string`  
5. `openupm search eloistree`   
6. `openupm add be.eloistree.jimmyscreamfps`  
6.B. `openupm remove be.eloistree.jimmyscreamfps`  
It will add in `package.json`:  
```
 "scopedRegistries": [
    {
      "name": "package.openupm.com",
      "url": "https://package.openupm.com",
      "scopes": [
        "be.eloistree.jimmyscreamfps"
      ]
    }
```
![image](https://github.com/user-attachments/assets/e65f26b0-4bc5-4572-ba8e-9e4fa9d7c35c)

Unity Installer install app:  
`C:\Users\elois\AppData\Roaming\Unity\Asset Store-5.x`  

# Publish

Publish a package on GitHub compatible with Unity3D.   
Read about it:     
- [https://github.com/EloiStree/HelloUnityPackage/wiki](https://github.com/EloiStree/HelloUnityPackage/wiki)
- Create a version tag release.   

Notify your package here:   
- [https://openupm.com/packages/add/](https://openupm.com/packages/add/)  


# Package manual:  
- https://docs.unity3d.com/6000.1/Documentation/Manual/upm-manifestPkg.html  


