![Banner](banner.png)

# chaudit-UnattendedUpdatesChecker
A simple script to check if unattended upgrades are enabled and configured correctly on Debian and Ubuntu systems, reporting on the status and any misconfigurations. It runs one dpkg -s check for the unattended-upgrades package and reads the two apt configuration files /etc/apt/apt.conf.d/50unattended-upgrades and /etc/apt/apt.conf.d/20auto-upgrades. It can also validate a YAML or JSON configuration file against a JSON schema supplied by the user. No predefined schema or rule set ships with this tool.

## Install
`git clone https://github.com/ShadowStrikeHQ/chaudit-unattendedupdateschecker`

## Usage
`./chaudit-unattendedupdateschecker [params]`

## Parameters
- `-h`: Show help message and exit
- `--check-upgrades`: Check unattended upgrades status.
- `--config-file`: No description provided
- `--schema-file`: Path to the JSON schema file.

## License
Copyright (c) ShadowStrikeHQ
