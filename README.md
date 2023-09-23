# ThinkPad Yoga X1 Gen 3 Hackintosh
My EFI for a Ventura 13.5.2 ThinkPad X1 Yoga Hackintosh

## Specs
- CPU: i5-8350U @ 1.7Ghz
- GPU: Intel UHD 620
- RAM: 8GB LPDDR3
- Audio: ALC285 (branded as ALC3286)
- Ethernet: Intel I219-LM (port through extension so untested)
- WiFi/BT: Intel AC 8265 802.11ac + Bluetooth 4.2
- BIOS: Newest Official (16. September 2023)

### Currently Working
- iGPU acceleration
- WiFi and Bluetooth
- Audio (w/mic)
- Keyboard
- Touchscreen (no pen), Touchpad, Mousenipple
- SMC
- USB (fully USB mapped)


### Currently non working
- Touchscreen Pen
- Backlight
- HDMI Out (Flickers screen with no output)

### Basic Usage

>## Disclaimer: I do **NOT** recommend using this EFI as is. Read the [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/), know your hardware and Proceed with caution.

#### Option 1: as is
1. Check Compatibility
2. [Generate an SMBios](https://github.com/corpnewt/GenSMBIOS) and add it to PlatformInfo (MacBookPro14,1 recommended)
3. Format your USB and follow Dortania install instructions

#### Option 2: grab what you'll use
1. Read the Dortania guide and make an EFI
2. Download the EFI
3. Use whatever you want to or think will work (Download newer versions of kexts if available)

 
## Disclaimer
I cannot help you with installation or similar, there are many other places like r/Hackintosh or similar that can help you. 
<br>I will try to keep this repo up to date as long as I'm using my X1 and am actively trying to find fixes for the missing features. If you have suggestions open an issue and I'll respond.
