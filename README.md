[![★](https://img.shields.io/github/stars/sammygrey/Torpedo?label=❤)](https://github.com/sammygrey/Torpedo/stargazers)
[![License](https://img.shields.io/github/license/sammygrey/Torpedo.svg)](https://github.com/sammygrey/Torpedo/LICENSE)

# Torpedo

A minimal Windows installer for Tor protocol for easy setup and configuration of relays.

## Download and Installation:

### Easiest Installation

Simply download and run Torpedo.msi

### Building the Files from Scratch:

To build the installer run make_installer.bat after making any desired changes to Torpedo.wxs. The files within the tor-win32 folder are required to build the installer.

Feel free to replace the tor-win32 folder with the same folder directly from Tor. The folder used is the Windows Expert Bundle from Tor and **NOT** the Tor Browser. The respective files can be found [here](https://www.torproject.org/download/tor/) as a zip archive.

It is important to note that for Windows servers before 2008 and Windows editions before Windows 7 are not guaranteed to be able to run tor.exe and support for those systems is currently unable to be provided.

## Usage and Credit

### Modification and Redistribution

Torpedo is fully open source and you may change and distribute it however you like. We only ask that you follow Tor's license for modification and distribution and give credit when applicable. You can find a copy of Tor's license here

### Third-Party Disclaimer

Torpedo is not registered as a subsidiary under The Tor Project nor do we claim ownership of any of the files we have created an installer for. We are following Tor's open source license for modification and distribution. For questions surrounding the Tor protocol and browser please view our license file [here](https://github.com/sammygrey/Torpedo/blob/main/LICENSE).
