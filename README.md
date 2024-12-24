# Radxa Zero 3W

## Installation

### Connect to wifi

```bash

nmcli device wifi connect <SSID> password <password>

```

### Install taskfile

```bash

sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b /bin

```

### Optionally install git

```bash

sudo apt update && sudo apt install -y git

```

### Clone the repository

```bash

git clone https://github.com/dottgonzo/raxda-zero-w3.git /tmp/raxda-zero-w3

cd /tmp/raxda-zero-w3

```

### Run the installer

```bash

task install-desktop

```
