# WRF-4.3-install-script-32bit

This is a script that installs all the libararies, software, programs, and geostatic data to run the Weather Research Forecast Model (WRF-4.3.3) with the option to run 3DVAR & 4DVAR observational data. Script assumes a clean directory with no other WRF configure files in the directory.

# Installation

(Make sure to download folder into your Home Directory):

> git clone https://github.com/whatheway/WRF-4.3.3-install-script-linux-32bit.git

> chmod +x WRF_ARW_INSTALL.sh

> chmod +x MET_self_install_script_Linux_32bit.sh

> chmod +x METplus_self_install_script_Linux_32bit.sh

> ./WRF_ARW_INSTALL_32bit.sh
> 
# Please make sure to read the WRF_ARW_INSTALL.sh script before installing.

I have provided comments on what the script is doing and information on configuration files.

# WRF installation with parallel process.
## Must be installed with GNU compiler, it will not work with other compilers.

Download and install required library and data files for WRF.

Tested in Ubuntu 20.04.4 LTS

Built in 32-bit system

Tested with current available libraries on 04/25/2024, execptions have been noted in script documentation. 

If newer libraries exist edit script paths for changes

# Estimated Run Time ~ 80 - 150 Minutes
### Special thanks to Youtube's meteoadriatic and GitHub user jamal919
