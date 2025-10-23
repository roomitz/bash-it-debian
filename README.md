# 📦bash-it-debian
Debian packaging for bash-it is a project that provides an unofficial Debian package for bash-it — a popular collection of community-driven Bash scripts, aliases, and completions. The package aims to simplify the installation and management of bash-it on Debian-based systems, including SelectOS, adhering to Debian Policy standards and best practices.
# bash-it Debian Package
This repository hosts Debian packaging for [bash-it](https://github.com/Bash-it/bash-it) — a popular collection of community scripts, aliases, and completions for Bash shell.
# 📥Installation
**Download prebuilt package (recommended)**
```
wget https://github.com/roomitz/bash-it-debian/releases/latest/download/bash-it_3.0.3_linux_all.deb
sudo dpkg -i bash-it_3.0.3_linux_all.deb
sudo apt-get install -f
```
**Or build from source(currently not available)**
```
git clone https://github.com/roomitz/bash-it-debian.git
cd bash-it-debian
UPSTREAM_VERSION=2025.x.y make build
UPSTREAM_VERSION=2025.x.y make install
```
# ⚙️Usage
After installation, bash-it will enhance your shell environment with useful completions and aliases. Just start a new shell or source bash-it scripts.
# 🤝Contribute
Feel free to fork, improve packaging, and send pull requests!

# ⚖️License
Packaging is under MIT license. The [bash-it](https://github.com/Bash-it/bash-it) project is also MIT licensed.
