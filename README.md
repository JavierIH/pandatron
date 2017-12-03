# Pandatron
Line following robot

<p align="center">
<img src=doc/pandatron.jpeg width="600" align="center">
</p>


# BOM
## PCB components

| Label                 | Package       | Value             | Comments              |
|-------------------    |-----------    |---------------    | ------------------    |
| U1                    | SIP 3T        | TR05S3V3          |                       |
| U2                    | SSOP24-P      | TB6612FNG         |                       |
| U3                    | LQFP-48       | STM32F103C8T6     | https://goo.gl/DWbec2 |
| U4-11                 | QRE1113GR     | QRE1113           | https://goo.gl/W69LTh |
| Y2                    | HC-49s        | 8MHz              |                       |
| SW1, SW4              | SKQG          | SPST              | https://goo.gl/RqLESx |
| LED / POWER           | 603           | Green / Red       |                       |
| R1, R2                | 603           | 100Ω              |                       |
| R6, R8                | 603           | 10kΩ              |                       |
| R9, R10               | 603           | 100kΩ             |                       |
| R7, R13, R14, R15     | 603           | 47Ω               |                       |
| RN1, RN3              | Array 603     | 47k               |                       |
| C1, C6                | 603           | 1uF               |                       |
| C2, C3                | 603           | 100nF             |                       |
| C4                    | 603           | 4.7uF             |                       |
| C5                    | 603           | 10nF              |                       |
| C7, C8                | 603           | 20p               |                       |
| C11, C13              | 603           | 0.1uF             |                       |
| C12, C14              | 1206          | 10uF              |                       |
| Female pin header     | 2.54          | 01x08             |                       |

## Other hardware

This parts can be modified by constructor choice.

| Component             | Brand and model               |
|-------------------    |---------------------------    |
| Motors                | Pololu 10:1                   |
| Battery               | Turnigy Nano-Tech 320mAh 2s   |
| Voltage regulator	    | XP Power TR05S3V3             |
| Wheels                | Scaleauto ProComp             |

You will need too a ST-Link V2 programmer (or compatible)

# License
Hardware: CC-BY-SA

Software: GPLv3
