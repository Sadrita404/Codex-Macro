<div align="center">
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td align="center" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/194be1c6-877e-42bb-aa48-439963e3918d" width="100%" max-width="800px" alt="Rough Layout For The PCB" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 500;">
      </td>
    </tr>
  </table>
</div>

|Title | Codex Macro |
|:-- |:--|
|Author | Sadrita Neogi|

## Overview
This is a fully open source Codex Macro , which is basically the clone of Codex Micro which is made by Open AI.

## Why I chose this project?
Actually, behind choosing this project when I saw the post of open AI that they are introducing and codex micro for their codex app then it kind of strike me that I can also make something like that. This is basically an micro pad, but with special feature such as like audio input custom keys with Rotary encoder and joystick.
##  How to use this project

So for using this project, we can do it directly connected to our desktop or laptop. Then we can use it as an Micropath as well as it will also works with the codex app to toggle the different features of the app.

## Features 
* Programmable Mechanical Switches
* Rotary Encoders (Knobs)
* Multi-Directional Joysticks & Switches
* Integrated Microcontrolle (Waveshare RP2040-Zero)
* Microphones (for voice commands)


<div align="center">
## Schematic

<img width="701" height="471" alt="Screenshot 2026-08-11 at 6 11 34 AM" src="https://github.com/user-attachments/assets/89a10cda-1df2-4c87-9c26-6c28e05c63b4" />

<div align="center">
  <h2> PCB </h2>
<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Screenshot 2026-08-11 at 6 18 02 AM" src="https://github.com/user-attachments/assets/035dfa20-2815-4903-8761-97bd56f2645c" />
    </td>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Screenshot 2026-08-11 at 6 18 13 AM" src="https://github.com/user-attachments/assets/ed869a9b-aa2e-4a07-81e9-dd922a01b6eb" />
    </td>
  </tr>
</table>

  <table border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
    <tr>
      <!-- FRONT SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/20e5e214-0bc4-4125-b104-b5d4cad95de6" width="100%" alt="Front Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Front Side View
        </div>
      </td>
      <!-- SPACER FOR GITHUB MOBILE DEGRADATION -->
      <td width="2%">&nbsp;</td>
      <!-- BACK SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/17b86777-be87-46dd-8ca0-88fb5278ba6e" width="100%" alt="Back Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Back Side View
        </div>
      </td>
    </tr>
  </table>
</div>
</div>



<h2> Fusion Renders</h2>
<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Render 1" src="https://github.com/user-attachments/assets/3c470710-c104-4e2b-99b0-e2e6ba521711" />
    </td>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Render 2" src="https://github.com/user-attachments/assets/168dafcc-b01d-4e9b-a13a-d071164fafbe" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Render 4" src="https://github.com/user-attachments/assets/5264d3da-bbc4-4189-b40d-d9331300fa25" />
    </td>
    <td width="50%" align="center">
      <img width="100%" height="auto" alt="Render 6" src="https://github.com/user-attachments/assets/76aabe04-c144-4d28-9f9b-cde688dda559" />
    </td>
  </tr>
</table>





<div align="center">
  <h2> Bill of Materials</h2>
</div>

| Component Name | Purpose | Qty | Total Price | Source Link | Distributor |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **PCB(moq5)** | The Main Board | 5 | $4.00 | [JLC PCB](https://jlcpcb.com/) | JLC PCB |
| **Waveshare RP2040-Zero** | The Controller Board | 1 | $4.50 | [Robu](https://robu.in/product/waveshare-rp2040-zero-without-header/) | Robu |
| **SMD LED** | For the board | 20 | $0.20 | [Robu](https://robu.in/product/xl-1608ubc-04-xinglight-20ma-240mcd-colorless-transparent-lens-20%e2%84%8385%e2%84%83-positive-stick-455nm475nm-blue-120-70mw-3-3v-0603-led-indication-discrete-rohs/) | Robu |
| **Microphone Module** | For the audio input | 1 | $1.60 | [Robu](https://robu.in/product/inmp441-mems-high-precision-omnidirectional-microphone-module-i2s/) | Robu |
| **Joystick Switches** | For the Control | 1 | $0.35 | [Robu](https://robu.in/product/10109-6p-wx-shou-han-smd-6p10x10mm-multi-directional-switches-rohs/) | Robu |
| **47 Ohm 0.25W Metal Film Resistor** | For the led | 40 | $0.12 | [Robu](https://robu.in/product/47-ohm-0-25w-metal-film-resistor-pack-of-100/) | Robu |
| **Rotary Encoder** | For the Control | 1 | $0.40 | [Robu](https://robu.in/product/hongyan-rs11-threadless-insert/) | Robu |
| **1N4148 1W Zener Diode** | For the keys | 20 | $0.30 | [Robu](https://robu.in/product/1n4148-1w-zener-diode-pack-of-50/) | Robu |
| **Keycaps(set)** | For the keys | 1 | $7.50 | [Neomacro](https://neomacro.in/products/mahjong-mx-style-keycaps?variant=50665429369110) | Neomacro |
| **Low Profile Switches** | For the Board | 1 | $13.00 | [Neomacro](https://neomacro.in/products/kailh-choc-v2-low-profile-switches?variant=51316563312918) | Neomacro |
| **PLA Filament** | For 3d Print ( I have 3d Printer) | 1 | $6.00 | [Numakers](https://india.numakers.com/products/pla?variant=45708299305129) | Numakers |
| **Shipping** | incl. PCB | - | $16.00 | - | - |
| **Tax** | - | - | $2.20 | - | - |
| **Total (Rounded Off)** | - | - | **$60.00** | - | - |

</div>



## Copyright and License
Copyright (c) 2026 Sadrita Neogi. All rights reserved.

All files are licensed under the MIT license. For more information, see the [LICENSE](LICENSE).

Project Under Hack Club
