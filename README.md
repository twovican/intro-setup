# intro-setup
Ansible Script to Install All Necessary Tools

# Pre-Requisits
Prior to running this make sure that Ansible is installed.

Install Ansible and Git

`$ sudo apt install ansible git -y`

Install Ansible Snaps Module

`$ ansible-galaxy collection install community.general`

## Checkout this Project

`$ mkdir /tmp/setup; cd /tmp/setup`

`$ git clone https://github.com/twovican/intro-setup.git`

# Running the Script

`ansible-playbook localhost.yml -i ansible_hosts -e ansible_python_interpreter=/usr/bin/python3 --ask-become-pass`

# Applications to be Installed via APT

- git
- vim
- unzip
- curl
- ffmpeg
- make
- build-essential
- libssl-dev
- zlib1g-dev
- libbz2-dev
- libreadline-dev
- libsqlite3-dev
- wget
- llvm
- libncurses5-dev
- xz-utils
- tk-dev
- libxml2-dev
- libxmlsec1-dev
- libffi-dev
- liblzma-dev
- libavcodec-extra
- ubuntu-restricted-extras
- unrar
- zip
- p7zip-full
- p7zip-rar
- rar
- wine
- winetricks
- openjdk-11-jdk
- tmux
- python3-pip
- python3-tk
- pep8
- bzr
- libgdbm-dev
- libnss3-dev
- python-dev
- wmctrl
- indicator-multiload
- virtualbox
- mussh
- multitail
- mc
- iptraf
- netcat
- links
- jmeter
- iperf
- iotop
- htop
- traceroute
- nmap
- python
- git-core
- libyaml-dev
- libxslt1-dev
- libcurl4-openssl-dev
- openssl
- pkg-config
- network-manager-openvpn-gnome
- sshuttle
- sosreport
- ubuntu-dev-tools
- sbuild
- debhelper
- piuparts
- ccache
- quilt
- autopkgtest

# Applications to be Installed via Snaps

- xsos
- cmadison
- drawio
- hotsos
- multipass
- juju
- xjs
- git-ubuntu
