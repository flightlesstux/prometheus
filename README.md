## PRometheus Automation
I need to install Prometheus latest version with automatically. I decided to turn the installation steps into bash script. 

# Information
- arm64 based support
- x86_64 based support
- Tested on Amazon Linux 2, ubuntu, Debian, CentOS7, CentOS8

# Requirements
- Freshly installed server or doesn't contains a user with name `prometheus`
- sudo privileges

## Usage
Run the command with under `sudo` privilege in your linux server directly via SSH. \
`sh <(curl https://raw.githubusercontent.com/flightlesstux/prometheus/master/installer.sh)`