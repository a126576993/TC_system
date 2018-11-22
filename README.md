# TC_system
v2.3

# TC_system installation

TC_system is a local system that collects data from ASE DCS and insert into Mysql database with outputing in dashboards.

Caution : It's a script for whole installation, if it fails, please read "Ubuntu安裝教學 N2 V1.01.pdf" for step-by-step installation details.

## Installation

Extract TC_system.tar into Desktop

Open terminal run script

```bash
./Desktop/TC_N2_v3/installation.sh
```

If first time installing crontab, it will ask for choosing editor.

Choose your favorte one and exit the editor to continue the install.

And y for reboot.

##Caution : script has second part that will be auto running after reboot, please wait for 5 mins and it will reboot again itself.

## Usage

After second reboot, you can login with user: admin/ pw: 123 in 127.0.0.1

And login mysql with user: root/ pw: 123 in 127.0.0.1:1234

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

