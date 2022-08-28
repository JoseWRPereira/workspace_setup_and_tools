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
