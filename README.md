Welcome to my Git repo. Below you can find a list of projects I am working on, sorted chronologically by date of last 'commit':

* [AudioPot+](https://github.com/valinet/audiopot-plus) - AudioPot+ is the second attempt at producing a volume knob for a computer using an Arduino. It is an evolution of the original [AudioPot](https://github.com/valinet/audiopot) project. This version is entirely based around microcontroller code, in the end obtaining a plug and play device that works on any operating system. Also, the mechanical construction is much improved, by switching to a rotary encoder instead of a potentiometer.

* [ThunderbirdToasts](https://github.com/valinet/ThunderbirdToasts) - Thunderbird Toasts is a simple framework that allows Thunderbird to send Windows 10 toasts as notifications instead of the current custom popup notifications that are not native.
  
  * Check this out for an example of calling Windows Runtime APIs from pure C code.

* [IMAP Notes](https://github.com/valinet/IMAPNotes) - Simple Thunderbird extension (compatible with Thunderbird 78+ as of January 2021) that allows editing notes created, edited and synced from the iPhone Notes app. 

* [WinCenterTitle](https://github.com/valinet/WinCenterTitle) - a library that is injected into DWM and centers the title bar text in Windows 10

  This example presents the following concepts:

  * Injecting a DLL into a remote process using the classic LoadLibrary/CreateRemoteThread technique
  * Setting up a trampoline using a specialized library

* [EtherCard-MDNS](https://github.com/valinet/EtherCard-MDNS) - Simple multicast DNS name resolution and service discovery library for EtherCard library that works with the ENC28J60 module.

* [homepi+](https://github.com/valinet/homepi-plus) - homepi+ is an Arduino based implementation of a home control system. . It interfaces and communicates with various hardware devices in order to provide a single point of control for all of them. It is used to control all the electric and electronic equipment in my study room, from light fixtures to computers and laptops. The user interacts with the service using a simple web application which is accessible from any device which has a browser, so pretty much any modern smart device, and can control it not only from the local network, but also from the larger Internet using a robust and secure security mechanism.

* [homepi-android-client](https://github.com/valinet/homepi-android-client) - A simple Android web wrapper for the interface of homepi or homepi+.

* [libvalinet](https://github.com/valinet/libvalinet) - libvalinet is a header-only collection of generic implementations shared between multiple projects. In order to avoid duplicating code between various projects I have, I will reference this library into all of them, and maintaing this single shared instance instead.

* [ThinkPad Keyboard Backlight Manager](https://github.com/valinet/kb_light) - ThinkPad Keyboard Backlight Manager is a simple Windows service that maintains keyboard backlight across reboots and temporarily shuts it off when a full screen application is in use

* [Get dark command windows all the time in Windows](https://gist.github.com/valinet/6afb524426635df9dbe2a9035701fcf4) - This short write-up provides information on how to combine a series of techniques in order to correctly patch an executable. It provides an overview of a couple of operating systems concepts, and how to approach analyzing a similar problem. Although showcased on Windows, the principles mentioned here apply to any modern operating system.

* [Fix Task Manager blurriness on different DPI monitors in Windows 10](https://gist.github.com/valinet/d66733e5f1398856bb21bda466a267cf) - Task Manager on Windows 10 is blurry on secondary monitors if they have a different DPI from the primary monitor. Let's fix that!

* [WinOverview2](https://github.com/valinet/WinOverview2) - reimplements the classic Task View from earlier builds of Windows 10 that showed the windows around the center of the screen, without a timeline, and most importantly, lag free.

* [ShutdownDaemon](https://github.com/valinet/ShutdownDaemon) - implements a mechanism to find whether the system is shutting down or rebooting in Windows

  This example presents the following concepts:

  - Creating a Windows service
  - Exploring UIs of other applications using UI Automation
  - Using named pipes as a basic IPC mechanism
  - Making web requests (e.g. POST) using WinINet

* [AudioPot](https://github.com/valinet/AudioPot) - Provides Arduino code for reporting potentiometer values and a Windows service for interpreting and acting on the received data

  This example presents the following concepts:

  * Reading potentiometer values from an analog pin on Arduino and reporting on serial port
  * Creating a Windows service that reads the data and changes the system volume

* [Get browser forward gesture on Android 10 Pixel Experience Plus ROM for Poco F1](https://gist.github.com/valinet/260d246136a36ca31eee5361e006a455)

  This example shows opcode patching on compiled Android binaries

* [RunPE for x64](https://gist.github.com/valinet/e27e64927db330b808c3a714c5165b0a) - a classic implementation of RunPE, for Windows running on amd64 based systems

* [Convert files to PDF using Puppeteer (Chromium).js](https://gist.github.com/valinet/8e9d3ca463003c8486b08856a0bc03fc#file-convert-files-to-pdf-using-puppeteer-chromium-js)

* [homepi](https://github.com/valinet/homepi) - a set of configuration data and front end files for the Raspberry Pi that automates my home office setup

  This example presents the following concepts:

  * Server-side basic coding using PHP
  * Setting up systemd services (like nginx, cups, lircd etc)
  * Creating an asynchronous mechanism for applying settings from the frontend to a (sometimes slow) backend
  * Implementing a high performance server-client solution, using epoll on Linux, and overlapped I/O (CompletionPorts) on Windows

* [WinOverview](https://github.com/valinet/WinOverview) - a port of the GNOME Activities overview to Windows 10

  This example presents the following concepts:

  * Capturing and presenting live window data
  * Creating windows in bands reserved for the operating system
  * Spawning a process with a lowered token by CreateRemoteThread of WinExec in remote process with lower token

* [Trivial Network Load Balancer](https://github.com/valinet/network-load-balancer) - a user-space daemon for balancing traffic across multiple routes which lead to the Internet for Windows 10

  This example presents the following concepts:

  * Using Windows Management Instrumentation to monitor for events:
    * Process creation
    * Performance data, specifically network adapters load information
  * Injecting a DLL into a remote process using classic LoadLibrary/CreateRemoteThread technique; besides injecting an amd64 DLL into an amd64 process from an amd64 process, this shows how to inject an IA-32 DLL into an IA-32 process running under WoW64 (Window on Windows) from an amd64 process - includes parsing the PE header of the DLL and identifying the addresses of relevant functions
  * Setting up a trampoline manually, by statically analyzing the injected function ahead of time

* [ThinkPad LED Control](https://github.com/valinet/ThinkPadLEDControl) - a Microsoft Windows application that allows controlling the various LEDs present on ThinkPad laptops and linking them to various system events (disk activity, key presses etc.).
