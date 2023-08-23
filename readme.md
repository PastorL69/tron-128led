# TRON-128LED
This repository consists of a few files which I bundled together for [αDMD](https://github.com/pinballpower/alpha_dmd) installations

Only configured for a 128x32 LED DMD, using the [TRON Serum (64 colors) V2.2](https://vpuniverse.com/files/file/14216-tron-legacy-stern-2011-dmd-64-colors-serum-format-v22-final/) file

## How to install?

```
cd
cd ~/code_dmdreader
git clone https://github.com/p69172002/tron-128led
```
## Configure the files
After having cloned the repository, you must change the '/home/yourusername/' paths in `start.sh` and `tron.json`

## Enable the script
```
cd
cd ~/code_dmdreader/tron-128led
sudo chmod +x start.sh
```

## Run the script
NOTE: Running with sudo is not possible right now, but will eventually get fixed in future versions of αDMD
```
cd
cd ~/code_dmdreader/tron-128led
./start.sh
```

## Error when running the script?
It is important to make sure the pico has been programmed. To do so, use the following commands:
```
cd
cd ~/code_dmd/src/
./program-pico.sh
```
