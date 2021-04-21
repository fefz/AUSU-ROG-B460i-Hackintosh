# AUSU-ROG-B460i-Hackintosh


### Instructions for use
Use following command to build the EFI.


```bash
git clone https://github.com/TokiharaSay/ASRock-B460M-ITX-ac-Hackintosh
cd AUSU-ROG-B460i-Hackintosh
chmod +x **/*.sh
./build.sh
```
Find generated EFI under `Output` folder. Find OpenCore config at `Output/EFI/OC/config_sample.plist` and fill in your own SMBIOS (Follow [the guide](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html), use  `model you need`) then rename `config_sample.plist` to `config.plist`.

Thanks for the help of the following friends

- [SukkaW](https://github.com/SukkaW)
