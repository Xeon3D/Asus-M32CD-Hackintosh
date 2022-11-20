# Asus-M32CD-Hackintosh

Files needed to run Ventura 13.0.1 on this prebuild Asus computer.

![Asus M32CD](https://d1eh9yux7w8iql.cloudfront.net/product_images/509607_f540a862-0c1b-4994-93d3-4306f62f77a3.jpg)


### Hardware Specs:

- **Power Supply**: Delta 300w 80 Plus Bronze.
- **Motherboard**: Asus M32CD4-K
- **Processor**: Intel i7-7400 (Kaby Lake)
- **Memory**: 2 x SK Hynix 8GB DDR4 Modules
- **Storage**: 240GB PNY CS900 SATA-3 SSD
- **Graphics**: Intel HD630 Graphics
- **Sound**: Realtek HD Audio ALC 887 + Intel HDMI Audio
- **Network**: Realtek 8169 Gigabit Ethernet
- **Wi-Fi**: Apple Wireless 802.11ac card + Apple to M.2 adapter from Aliexpress
- **Optical Drive**: Disconnected. Who uses optical drives anymore? ^_^


### What's working:


Hardware | Status |
---------|--------|
Audio: Realtek ALC887 | Working |
Video: Intel HD 630 | Working |
Network: Realtek Gigabit | Working |
Wi-Fi: Apple M.2 WiFi Card | Working |
Bluetooth: Apple M.2 WiFi Card's Bluetooth | Working |
Card Reader: | Untested |
Sleep | Working |

### Notes:

I've replaced the original wireless card with the Apple one plus one adapter to make it fit the M.2 slot on the board. With this solution you don't need any kexts for bluetooth and wireless as they work OOB.

I've also removed the GeForce 1050 card that came with it as I'm not planning to run Windows, Linux or High Sierra on this machine.

Swapped the original rotating hard disk with a faster PNY CS900 SSD I had laying around.

Do note that the HD630 can't do 4K@60Hz thru the HDMI port. Maximum you will get is 4K@30

**The config.plist has got it's identifiers stripped out. You have to fill them with your own values (follow dortania's guide if you need help)**


