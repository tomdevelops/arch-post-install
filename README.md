# 🐧 arch-post-install

personal arch post install script for a base arch linux installation

## ✨What does it do?

The script installs yay and all the packages in the [packages.csv](packages.csv) file.

## 📦 Installation

Post arch installation execute the following command

```bash
# change to main non-root user and goto home
su tom
cd ~

# download & execute install script
curl -Lks https://raw.githubusercontent.com/tomdevelops/arch-post-install/main/install | /bin/bash
```
