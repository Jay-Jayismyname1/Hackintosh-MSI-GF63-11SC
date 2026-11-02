Hackintosh MSI GF63 11SC

I got macOS Sequoia working on my MSI GF63 11SC and everything works except AirDrop, and Internal Mic. I’m still working on these features, I’m still new to hackintoshing and the more I do this the more I will learn this stuff, keep in mind I’m dual booting Windows 11 and macOS Sequoia. I’m proud of it but the battery isn't the best it dies quite fast but this is expected as it's a gaming laptop, here are my specs:

- [ ] Intel Core i5 11400H
- [ ] Intel UHD 730 Graphics
- [ ] NVIDIA GeForce GTX 1650
- [ ] 256GB SSD - For Windows  
- [ ] 256GB SSD - For macOS
     (These aren't two different drives I partitioned the 50/50 from my 500GB NVMe SSD).
- [ ] Intel AX-201
- [ ] Realtek ALC 897
- [ ] 8GB DDR4 RAM

What is working?
  Metal, Acceleration
  Sound
  Wifi
  Bluetooth
  CPU Power management
  Webcam
  Keyboard/Trackpad (With gestures)

What's not working
  Internal mic
  Airdrop
  Sleep
  HDMI (External monitor)

** Side Note 
   Once installed you need to head to System Prefrences --> Sound --> Output and change it to Line Out (The last One).

  Enjoy :-)

([Intel driver for Nvidia handoff](https://github.com/kitsuneislife/nmx-intel))
