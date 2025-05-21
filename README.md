# vpn
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
