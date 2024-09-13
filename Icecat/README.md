### Icecat installation from source

> ### Steps
> 
> 1. Download the installation script / source from the [Savannah Git](https://git.savannah.gnu.org/cgit/gnuzilla.git)
> 2. Extract the tar file
> 3. Install the dependencies 
> 	1. Based on the README, these are the libraries needed for the installation
> 		(libpango libpangoxft libpangoft2 libfreetype libxft libgtk2 libx11)
> 		Hence, install he libraries. 
> 		sudo apt install autoconf2.13 libgtk-3-dev libdbus-glib-1-dev libfreetype6-dev libx11-dev libxft-dev libpango1.0-dev
> 		Note: libpango1.0-dev doesn't exist in the apt repository (as default, i think)
> 	2. Install the dependencies:
> 		bzip2
> 		mercurial
> 4. Run the install script
> 	1. ./makeicecat
> 	2. This will download Firefox tar ball from Mozilla and compile the source on the system
> 	3. Language pack will take a lot of time to download at first
> 	4. Rebranding stage also took time
> 	5. Total compilation time will be 
> 		1. Starts at 0730

