
# OpenScan – 3D Photogrammetry Scanner Build

My build of the [OpenScan](https://openscan-org.github.io/OpenScan-Doc/) open-source project: a 3D scanner based on photogrammetry.

OpenScan is a modular concept for building your own photogrammetry-based 3D scanner. Its individual modules (firmware, 3D-printable design, PCB, cloud photogrammetry processing) can be used and adapted as needed. The core is a Raspberry Pi–based camera and motor controller that drives the scanning hardware.

## What I built

- **Electronics design:** designed the controller PCB based on the reference circuits and photos from the official documentation.
- **Hardware modifications:** made targeted changes to the original design, including replacing the voltage regulator and reworking the board layout.
- **Mechanical assembly:** 3D printed and assembled the scanner structure.
- **Integration:** assembled the electronics, then installed and configured the firmware on the Raspberry Pi.
- **Testing:** ran scanning tests with different capture parameters to evaluate results.

## Tech stack

Raspberry Pi · Embedded Linux · Stepper motors · PCB design · 3D printing · Photogrammetry

## Photos

<img width="1599" height="899" alt="OpenScan build – view 1" src="https://github.com/user-attachments/assets/42baff6a-224f-45ad-8a0d-994af7ca6b8c" />
<img width="1599" height="899" alt="OpenScan build – view 2" src="https://github.com/user-attachments/assets/16081eb4-a972-46da-a141-85a3687cc76d" />
<img width="899" height="1599" alt="OpenScan build – view 3" src="https://github.com/user-attachments/assets/76253446-f8b1-41cc-897f-c886f65b67ca" />

## Credits

This build is based on the OpenScan project and on the work of many open-minded contributors who shared tutorials on YouTube, discussions on Reddit, code on GitHub and much more. This project would not be possible without them.

- Official documentation: https://openscan-org.github.io/OpenScan-Doc/
