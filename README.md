# Workspace: Setup and Tools


# Git

## Install 
```bash
sudo apt install git
```

## SSH keygen
```bash
ls -al ~/.ssh

ssh-keygen -t ed25519 -C "usuario@email.com"

# Enter a file name
# Enter and confirm passphrase

# Copy public key to SSH and GPG keys on GitHub
cat ~/.ssh/id_ed25519.pub
```




# Terminal
 
```bash
sudo apt install terminator
```


# i3 Window Manager

```bash
cp i3_config_mate ~/.config/i3/config
```


# Peek: Simple Screen recorder
```bash
sudo apt install peek
```

# Visual Studio Code
```bash
sudo dpkg -i codexxxxxxx.deb
```


# USB

Editar o arquivo a seguir ou equivalente:

```bash
user@host:~$ sudo nano /etc/udev/rules.d/z010_mchp_tools.rules
```

incluir a seguinte linha para o reconhecimento do PICkit2

```bash
ATTR{idVendor}=="04d8", ATTR{idProduct}=="0033", MODE="666"
```
