# Day 1: The Sketch

8/12/2026 - 15-30 minutes (post git repo creation)

I started sketching out my project and what idea i had in mind.
![sketch](assets/sketch.jpg)

It was something that was
 * A simple usb 2.0 powered pcb
 * Light up glowing mosaic
 * Has no MCU
 * Strategic solder mask/copper placement
 * Maybe a cutout pcb stand footprint



# Day 2: Part Identification and Starting Schematic

8/13/2026 - ~1.5 hours

At first, I thought it was going to be easy to find these underside leds, but the terms for them are a little unstandardized and took a while to find.

They are "Reverse Gullwing" LEDs that can shine under itself, but some [hackaday](https://hackaday.io/page/6081-using-side-view-leds-in-place-of-reverse-mount-leds) articles (traced from another [article](https://hackaday.com/2019/04/17/the-science-of-reverse-mounted-leds/)) say that they're unfortunately expensive. 


I have been looking through a bunch of LED options, including but not limited to
 * Reverse Gullwing LEDs that need a mcu
 * Side mount LEDs (can't find one that cycles through colors)
 * Flat LEDs that can be soldered the opposite way

At this point, I will take a compromise of these [tht LEDs](https://www.sparkfun.com/led-3mm-cycling-rgb-fast.html) that cycle colors and are really small. The previous hackaday article recommended hot glue on side mount leds to help spread into the pcb, but why not just use tht leds with hot glue anyways?

![concept](assets/concept1.png)