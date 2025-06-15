# x-ui install
[3X-UI - xRay server with web GUI](https://github.com/MHSanaei/3x-ui)



```bash
adduser xray # xray-H..0
adduser xray sudo
su - xray
```

```bash
LATEST_TAG_URL=https://api.github.com/repos/mhsanaei/3x-ui/releases/latest
TAG=$(curl -sSL "$LATEST_TAG_URL" | jq -r '.tag_name')
curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/refs/tags/$TAG/install.sh | sudo bash
```

```bash
sudo x-ui
```

```bash

```


<details>
<summary>Add Inbound </summary>
  
![image](https://github.com/user-attachments/assets/5c275edd-ac2a-4cc2-ae90-f7702cac815c)

![image](https://github.com/user-attachments/assets/92b54a31-9a90-48f5-ba6d-45f2a9a182dd)

</details>

<details>
<summary>Add Client </summary>

![image](https://github.com/user-attachments/assets/108b0571-63bd-4d19-b732-37a756fd5900)

![image](https://github.com/user-attachments/assets/8b802dbd-db3a-46f2-9a95-59f12d6af2b7)

</details>

---

<details>
<summary>NekoBox For Android </summary>
  
[NekoBox For Android](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases)

![image](https://github.com/user-attachments/assets/1c797af4-8b22-4923-a839-10f718aa3ba9)
![image](https://github.com/user-attachments/assets/8b1f95bb-ea93-46ae-8dec-48766c56a5df)

Настройки / Режим VPN для приложений 
</details>

<details>
<summary>NekoBox GUI </summary>

### Ubuntu
[NekoBox For Ubuntu](https://github.com/MatsuriDayo/nekoray/releases)

```bash
sudo mv ~/nekoray.deb /tmp/
sudo apt install /tmp/nekoray.deb
```
чтобы использовать впн только на FireFox, ставим галочку “Режим системного прокси”, а в настройкх FireFox:
127.0.0.1:2081. В настройках яндекса “Не использовать прокси”.




### Windows
[necoray client](https://github.com/MatsuriDayo/nekoray) | 
[nekoray-4.0.1-2024-12-12-windows64.zip](https://github.com/MatsuriDayo/nekoray/releases/download/4.0.1/nekoray-4.0.1-2024-12-12-windows64.zip) | 
[Microsoft Visual C++](https://aka.ms/vs/17/release/vc_redist.x64.exe) | 
[Маршрутизация](https://blancvpn.online/ru/help/NekoRay-windows-split-tunneling)

настройки / настройки маршрутов / Базовые маршруты  
Напрямую: IP
```bash
geoip:ru
geoip:private
```
Напрямую: Домен
```bash
http://192.168.8.1
http://192.168.1.1
```
![image](https://github.com/user-attachments/assets/130fa909-21db-44bd-b79c-353f5fda5867) 

![image](https://github.com/user-attachments/assets/a2c9ccec-fe69-4953-824a-7e0b668ff3c8) 

![image](https://github.com/user-attachments/assets/08d2754e-90bd-4a30-a8d1-6d604a295308)


</details>
