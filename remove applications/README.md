# 🗑️app-cleaner

## Setup guide

### Step 1: create `/usr/local/bin` directory

```shell
sudo mkdir -p /usr/local/bin
```
```shell
sudo chown ${USER} /usr/local/bin
```

### Step 2: download [uninstall.sh](./uninstall.sh) script

```shell
cd /usr/local/bin
```
download [uninstall.sh](./uninstall.sh)
```shell
chmod +x /usr/local/bin/uninstall.sh
```

### Step 3: Go

```shell
uninstall.sh /path/to/app.app
```

👍

---
