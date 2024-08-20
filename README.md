# Business_Card
This business card is more than just a way to share contact information—it's a fully functional gaming device, built around a custom-designed PCB. The core is an ATTiny85 microcontroller. The software is based on the open-source Tiny Joypad repository, with some modifications to fit this specific design. The display is a 128x64 UG-2864KSWLG01 OLED. There’s room for a larger screen, but the smaller one hits the sweet spot for price and functionality.

The design is very much cost-focused. You won’t find a USB port or a rechargeable battery here; everything is optimized for simplicity and affordability. This card requires an external programmer, which connects via an unpopulated AVR pin header.

The software comes from Tiny Joypad’s collection of games and tools, with some tweaks to integrate a graphics library and ensure compatibility with this setup.

I relied on Spencer Konde’s ATTinyCore for adding microcontroller support to the Arduino IDE. Keep in mind that software compilation can vary depending on your IDE version and libraries—sometimes minor tweaks are needed.
