# Hackintosh 4790K Z97X GTX 960

I have managed to succesfully run High Sierra 10.13.6 on my i7-4790k, Gigabyte Z97X Gaming 5 and GTX 960 with OpenCore 0.5.9.

![opencore](https://github.com/acidanthera/OpenCorePkg/raw/master/Docs/Logos/OpenCore_with_text_Small.png)

## Resources:

* [r/Hackintosh](https://www.reddit.com/r/hackintosh/) - A subreddit to learn about Hackintosh-ing
* [OpenCore](https://github.com/acidanthera/OpenCorePkg/) - You can get the Custom Bootloader here
* [dortania OpenCore Guide](https://dortania.github.io/OpenCore-Desktop-Guide/) - Best guide available on the planet

## Kexts that I have used:

0. SMC: `VirtualSMC.kext`
1. Ethernet: `AtherosE2200Ethernet.kext`
2. USB: `USBInjectAll.kext` and `FakePCIID.kext + FakePCIID_XHCIMux.kext`
3. Audio: `AppleALC.kext` with `Lilu.kext` companion
4. Graphics: `WhateverGreen.kext` with `Lilu.kext` companion

![desktop](https://github.com/amogh-w/Hackintosh-4790K-Z97X-GTX-960/blob/master/screenshots/desktop.png?raw=true)

## Disclaimer

I have not created any of the above kexts. I have just picked the kexts which were needed for my system and made the necessary changes to the `config.plist` to ensure that my system runs perfectly. Thank you, the wonderful Hackintosh Community! ❤️
