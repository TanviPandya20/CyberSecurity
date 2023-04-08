# 1. Create anIPsec-basedVPN with the help of the Strongswan tool.
## Setting up IPSec VPN Tunnel in left socket
### sudo apt install strongswan strongswan-pki libcharon-extra-plugins libcharon-extauth-plugins libstrongswan-extra-plugins libtss2-tcti-tabrmd0 -y

`sudo apt install strongswan strongswan-pki libcharon-extra-plugins libcharon-extauth-plugins libstrongswan-extra-plugins libtss2-tcti-tabrmd0 -y`

![image](https://user-images.githubusercontent.com/68326118/229407567-ec666ac2-b3dc-49f4-978f-bae82ee6133e.png)

### loading the new settings for left socket
`sudo sysctl -p`

![image](https://user-images.githubusercontent.com/68326118/229409132-c9732d1e-5f4b-4a9a-b471-8a3f8d54d025.png)

### Enabling the Strongswan tool for left socket

![image](https://user-images.githubusercontent.com/68326118/230721511-55bab938-09be-4f17-981c-0dfd18d13b76.png)

### Getting the RSA private key for both the sockets

![image](https://user-images.githubusercontent.com/68326118/230721859-79f08289-e417-4ae6-89d4-ef6c7fe2ae1a.png)

![image](https://user-images.githubusercontent.com/68326118/230722045-06e2ff0a-2282-4087-9ee6-1920a7125596.png)

## Setting up IPSec VPN Tunnel in Right socket
### loading the new settings for right socket

![image](https://user-images.githubusercontent.com/68326118/230722185-fd6d9d90-7c94-4026-9ca0-080eba888e6c.png)

### Setting up UFW for right socket

![image](https://user-images.githubusercontent.com/68326118/230722305-f75560ef-fc82-4bc9-bcdd-b491df366164.png)

![image](https://user-images.githubusercontent.com/68326118/230722578-d5a81893-e100-48b6-88f5-d839aabd735f.png)

### Enabling the Strongswan tool for right socket

![image](https://user-images.githubusercontent.com/68326118/230722623-b610cb2f-74b7-4b0f-a228-333ed59d079f.png)

![image](https://user-images.githubusercontent.com/68326118/230722823-518796eb-b744-4391-bc96-11ff027d068f.png)

![image](https://user-images.githubusercontent.com/68326118/230723117-26becce3-1694-4a34-a3db-cf0a29865443.png)

