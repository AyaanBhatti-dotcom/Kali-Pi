# Kali-Pi
A Raspberry Pi Zero 2 W configured with Kali Linux for portable pentesting and network-analysis training. Headless setup with SSH access, Wi-Fi configuration, and automation for tools like nmap and tcpdump — a complete Kali environment that fits in your pocket.




**Do you wish you could carry your Kali VM in your pocket and run nmap scans anywhere?**

Now you can—introducing the **Kali Pi**.

This project turns a **Raspberry Pi Zero 2 W** into a fully portable, battery-friendly Kali Linux environment. Once configured, you can **SSH** into it from any device (laptop, tablet, or phone) and use it just like your desktop Kali VM, all from a device that literally fits in your hand.



---
<br>

## Features

* **Headless Access:** Seamless **SSH** access from any host OS (macOS, Windows, or Linux).
* **Built-in Connectivity:** Integrated Wi-Fi and Bluetooth means **no external dongles** are required.
* **Essential Toolkit:** Pre-configured and ready to run core tools like nmap, tcpdump, neofetch, and aircrack-ng.
* **Perfectly Portable:** Great for **on-the-go pentesting**, mobile reconnaissance, and CTF practice.

---

## Setup Summary (Get Running in 7 Steps)

Follow these simple steps to flash and configure your Kali Pi for headless use.

1.  **Flash Kali Linux ARM:** Flash the appropriate **Kali Linux ARM image** onto a microSD card (a 32 GB card is recommended).
2.  **Configure Advanced Options:** Open **Raspberry Pi Imager**. Before writing the image, open **Advanced Options** (`Ctrl + Shift + X`) and configure the following:
    * Enable **SSH**.
    * Set your preferred **username** and **password**.
    * Configure the **wireless LAN** (SSID, password, and country).
3.  **Initial Boot:** Insert the microSD card and boot the Pi. (You can optionally connect an HDMI cable to watch the initial install process).
4.  **Verify/Connect Wi-Fi:** If the Wi-Fi doesn't connect automatically, SSH in using a temporary connection (or use the HDMI output) and run:
    ```bash
    sudo nmtui
    ```
    Select and activate your preferred network.
5.  **Find the IP Address:** Once online, find your Pi's IP address:
    ```bash
    hostname -I
    ```
6.  **SSH In:** Connect from any device on the same network using the hostname:
    ```bash
    ssh yourusername@raspberrypi.local
    ```
7.  **BOOM:** You now have a fully working, pocket-sized Kali Linux installation!

---

## Demo 

(Coming soon)

* 

---

## Notes

Remember, this isn't a high-performance rig; it's a **pocket-sized learning environment**.

Use the Kali Pi for:

* **Network Diagnostics**
* **Training Labs**
* **Mobile Reconnaissance**

**BOOM. A fully working Kali Linux box that fits in your pocket.**
