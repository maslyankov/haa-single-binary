# haa-single-binary
The awesome HomeKit Accessory Architect (aka HAA and RavenCore v2) firmware for ESP8266 with a single file binary for using with some flashing tools.

# How to use

This repo was created for my article on the [Easiest way to flash your Sonoff, Shelly, Wemos or any ESP8266 and add HomeKit support](https://smarty.one/posts/easiest-way-to-flash-your-sonoff-shelly-wemos-or-any-esp8266)

The three files (rboot.bin, blank_config.bin, haaboot.bin) were combined into **haa-single.bin** using the cat command on MacOS.

Simply flash **haa-single.bin** on ESP device.

I generate this file to make your life easier. I try to update it as often as I can (usually within a day or two) and I DO NOT modify any of the files. I simply generate haa-single.bin using the command "cat" as shown in my video. 

If you're having problems, make sure to go through the FAQ page - https://smarty.one/en/homekit-accessory-architect-faq
If you're still having trouble with the firmware and you think it is because of my file, you're free to use the official repo files. :)

# Credits and more info

### Want to report a bug? -> https://github.com/RavenSystem/esp-homekit-devices/issues

### All files archived from https://github.com/RavenSystem/esp-homekit-devices haaboot from https://github.com/RavenSystem/haa_ota/releases


### Firmware wiki: https://github.com/RavenSystem/esp-homekit-devices/wiki

### All credits for this firmware go to the creator of HAA.

### I will no longer update this repo, as the firmware creator started pushing a pre-concatenated file (a single file binary), which was the purpose of this. I hope it was useful to someone.
### You can find the latest version of the firmware here: https://github.com/RavenSystem/haa/releases ( you need fullhaaboot.bin )
