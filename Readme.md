# PCB TUNNER

This is a Printed Circuit Board guitar tunner.

## Overview

Select the target note using the OLED display and the push buttons. PCB Tuner listens to the guitar signal through a digital MEMS microphone, detects pitch on an ESP32-S3, and shows the result through a row of LEDs, arranged from the lowest to the highest pitch, left to right. The middle LED turns green when the string is correctly tuned. The board runs off a small LiPo battery and charges over USB-C.

The device is not intended to be used while charging (no power-path/load-sharing circuitry).