# 6/26
Time spent: 1h

Played around with one of my rpi picos and figured out how to detect touch on just a wire. (Capacitive touch)
You can do this by measuring the capacitance of the wire and then using a threshold to determine if it is being touched.

# 6/27
Time spent: 7h
Created the schematic and PCB that integrates the RP2350A and a capacitive touch pad in the formfactor of a Yubikey.

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3a73c7d7a489c2296834e4e9849e602b0f07d2f8_image.png)
---
Time spent: 2h
Sourced parts and created BOM
---
Time spent: 3h
I decided to add a keyring hole, and that took FOREVER because I wanted a triangle in the corner, that's plated on the inside, which meant I needed to get creative with pads.
I did finally get it to work, though.
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e44f58c1845eb2a1792c929860ba9e7d3f9d6492_kicad_t2iim3xxzf.png)

I then decided to swap out the led for something that would shine thru the pcb, so I spent forever finding the perfect led that has the right dimensions, and was in a gullwing package. I finally found the AAA3528RBGS, which is also in stock at LCSC! I then spent a LOT of time redesigning the button footprint (KICAD'S FOOTPRINT EDITOR SUCKS) to include a hole with no copper and only fiberglass, and then redesigning the clock section of the PCB to accommodate the new led footprint.

**TOTAL TIME:** 12h (I literally spent the whole day and night on this, it's 4am now)
