# Open-Smartwatch
An open hardware and software smartwatch.

## Main Hardware Diagram

<img src="https://github.com/dantudose/open-smartwatch/blob/main/Images/Hacktor_Diagram.jpg" height="500"/>

This is a open-hardware wearable based on the ESP32 microcontroller. It is fully Arduino-compatible and it comes with the following features:
* ESP32-S3 Mini module (240MHz, WiFI, BLE, 512kB SRAM and 4MB Flash)
* GC9A01 1.28 inch color LCD, 240 x 240 pixels
* BMI085 6-axis inertial sensor (accelerometer and gyroscope)
* W25Q256JVEIQ 32MB external SPI Flash
* DRV2605 haptic driver
* SPI card reader
* 200mAh LiPo battery
* USB-C connector

## Repository Contents

* **/Hardware** - Eagle design files (.brd, .sch)
* **/Images** - Board images
* **/Mechanical** - Mechanical files for the case (.stl)
  
### Button Layout

<div id="cover">
 <div style='float:left'>
  <table><thead>
  <tr>
    <th>Button</th>
    <th>ESP32 Pin</th>
  </tr></thead>
<tbody>
  <tr>
    <td>UP</td>
    <td>IO11</td>
  </tr>
  <tr>
    <td>DOWN</td>
    <td>IO26</td>
  </tr>
  <tr>
    <td>BOOT</td>
    <td>IO0</td>
  </tr>
  <tr>
    <td>RESET</td>
    <td>EN</td>
  </tr>
</tbody>
</table>
 </div>
<div style='float:leftt'>
  <img src="https://github.com/dantudose/open-smartwatch/blob/main/Images/Hacktor_buttons.jpg" height="250"/> 
  </div>
  </div>




## Mechanical Dimensions

The watch has the overall dimensions of 43.5 x 48 x 18mm and supports standard 20mm straps.

<img src="https://github.com/dantudose/open-smartwatch/blob/main/Images/Hacktor_Mechanical.jpg" height="350"/>

## PCB Design

Two-layer PCB design.

<img src="https://github.com/dantudose/open-smartwatch/blob/main/Images/Hacktor_PCB.jpg" height="300"/>


