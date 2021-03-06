These instructions seem to cause a lot of errors with many users, especially on OSX 10.12. It is recomended that you [build Malmo yourself](build_macosx.md). 

## Installing dependencies for MacOSX ##

1. Install Homebrew: https://coolestguidesontheplanet.com/installing-homebrew-on-os-x-el-capitan-10-11-package-manager-for-unix-apps/
    
2. Install dependencies:
    1. `brew install boost --with-python`
    2. `brew install boost-python ffmpeg xerces-c mono`
    3. `brew cask install java`

3. If you have not already done so, unzip the Malmo zip to some location (e.g. your home folder).
4. Add `export MALMO_XSD_PATH=~/MalmoPlatform/Schemas` (or your Schemas location) to your `~/.bashrc` and do `source ~/.bashrc`
5. When you update Malmo you will need to update the MALMO_XSD_PATH too.

## Notes: ##

These instructions were tested on MacOSX 10.11. 

On MacOSX we currently only support the system python, so please use `/usr/bin/python` for running agents, if it is not already the default. 

