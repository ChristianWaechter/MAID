# MAID
Mass Analogue Image Digitizer - A fully custom made and open platform for mass digitizing of images like Super8, negative/slide photos etc

Currently work in progress and more of a brainstorming platform

# Benchmark negative photo digitizer

Braun FS-120

Nikon Coolscan V ED

Super Coolscan 5000 ED

Super Coolscan 9000 ED

# Cameras that might be useful
Raspberry Pi HQ Kamera (12 MP) mit CS-Mount

https://www.arducam.com/product/64mp-af-for-raspberry-pi/

https://rbts.co/solutions/c50m-camera-module-for-raspberry-pi-nvidia-jetson-and-rockchip-rk3588/

# Lightsource
first planned with a single, high light quality (CRI 97) white LED. But as camera sensors only detect red, green and blue, a set of a red, green and blue LED might be sufficient. This would also allow the live adjustment of the histogram during scanning, as each color channel can be dimmed individualy.

Additionally, a IR-LED can be used to take an image for scratch detection. In this case, a camera module without IR filter has to be used!

For this, see Cine2Digits, e.g.

http://www.cine2digits.co.uk/

http://www.cine2digits.co.uk/Downloads/C2Dbrochure2.pdf

# BOM (so far, not complete, work in process)

Seoul Semiconductor Inc. S4SM-1566509736-0C500H3S-00001, SunLike, 5000K, 97 CRI, 2655 lm @ 720 mA, 35.2 V

Adafruit Industries LLC, 2442, SERVOMOTOR RC 130 RPM 5V

Sunon MF50151VX-B00U-A99, radial fan, 12 VDC, 2 W

Photoelectric Sensor Infrared Correlation Counting Sensor Module ME074, 5 V, LM393

# This project is inspired by these projects
https://www.sabulo.com/sb/3d-printing-2/8mm-film-scanner-final-version-with-canon-1000d/

https://hackaday.io/project/185040-8mm-film-scanner-v2

https://hackaday.io/project/189773-program-with-a-gui-for-the-anton-8mm-film-scanner

http://www.nightshade-arts.co.uk/telecine/

DIY Cleaner: https://www.super-8.com/film-reiniger.html

DIY Wetgate: https://www.youtube.com/watch?v=Nsk4Eb1Lzq4

Filmtransfer Tutorial (part 3), in depth information about wet gate and cleaning: https://www.youtube.com/watch?v=irbZewfz-SA

DIY Super8 digitizer in old projector https://www.youtube.com/watch?v=eZniFhJR17M

https://www.movie-college.de/filmschule/kamera/film-analog/filmformate/super-8/super-8-abtastung



# Usefull software for postproduction
"The power of Avisynth: restoring old 8mm films", a video cleaning package for AviSynth for cleaning 8mm films: https://forum.doom9.org/showthread.php?t=144271
