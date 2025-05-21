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
bash <(curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/refs/tags/$TAG/install.sh)
```

```bash
sudo x-ui
```

```bash

```


<details>
<summary>Add Inbound </summary>
  
![image](https://github.com/user-attachments/assets/1dbaf30e-ad4b-4e54-90bb-ab5ecec9990c)

</details>

<details>
<summary>Add Client </summary>

![image](https://github.com/user-attachments/assets/f947b2fd-7855-48c2-be38-2aed069ac3c1)

</details>

---

<details>
<summary>NekoBox For Android </summary>
  
[NekoBox For Android](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases)

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
[](https://github.com/MatsuriDayo/nekoray)  [Microsoft Visual C++](https://aka.ms/vs/17/release/vc_redist.x64.exe)
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
![image](https://github.com/user-attachments/assets/a2c9ccec-fe69-4953-824a-7e0b668ff3c8) 

![image](https://github.com/user-attachments/assets/08d2754e-90bd-4a30-a8d1-6d604a295308)


</details>
