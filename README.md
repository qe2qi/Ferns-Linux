# Ferns Client (Linux)

A modifed Roblox client for infinite condos with an unlimited runtime and no security risks. Use responsibly — this project is not affiliated with or endorsed by Roblox Corporation.

> NOTE: Using this client with an active RobloxPlayerBeta.exe in your system that is logged into a roblox account could cause an enforcement ban. This is because the client used for Roblox is modified to fit with Fern's servers. Please use the client at your own risk.

---

Table of Contents
- [About](#about)
- [Safety Checks](#safety-checks)
- [Supported Platforms](#supported-platforms)
- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Deletion Process](#deletion-process)
- [Contributing](#contributing)
- [Security & Legal](#security--legal)
- [Contact](#contact)

---

## About

Fern's is a modified Roblox client focused on safe, unbannable condos that run 24/7, using seperate servers than roblox. THe best alternative if you want always active roblox condos. This repository is for users who want to run the windows client on Linux desktops and development containers.

This repository contains:
- Source code and build scripts (where applicable)
- Linux-compatible binaries (when provided in Releases)
- Configuration templates and documentation

---

## Safety Checks

The Ferns Client (Ferns.exe) has a 3/71 score on virus total (False Positives) with a large community to back it. Ferns is open source and free for anyone to use and inspect,but shall not be copied by anyone.

VirusTotal results listed here > [VirusTotal Results](https://www.virustotal.com/gui/file/a36eb126dc3833b60f6e7fbce480f1d39b6922cead71c5e407f66186ff5b474e/detection)

## Supported Platforms

- Primary: Linux (Any Distro that can run Wine. Tested on Ubuntu, Debian — details below)


If you need support for a different distro, please open an issue with details about your environment.

---

## Requirements

Exact dependencies vary depending on whether you are running a prebuilt binary or building from source. Common requirements:

- Wine (Newest, Stable version)
- A modern Linux distribution (Ubuntu, Debian, Fedora, Arch, etc.)
- glibc and standard runtime libraries

---

## Quick Start

1. Visit https://www.ferns.club/

2. Create an account and download the Windows installer at https://www.ferns.club/download

3.1 ( Software Manager ) Open your Software Manager, then search install the most recent/running version of Wine (wine-stable)

3.2 ( Terminal ) Open your terminal (Startup menu or Control + T) and run the command `sudo apt install wine`

4. After installing both Wine and the Ferns Client, open your Home directory (Super/Windows + E), then navigate to the directory that the Ferns_Instaler.exe was put into.

5. Right click Ferns_Installer.exe, click Open With > Other Application, and then enter the custom command `wine` or `wine start` This should open the installer. Go through the installation process, then refer to Step 6 and 7 to run the Client.

6. Go back to your Home directory and view hidden files, (Control + H) Then make your way to the .wine directory. Then, follow the next directories in order.

`*/.wine/drive_c/users/user/AppData/Local/Ferns/Client`
 
 `(drive_c > users> usr (Your username) > AppData > Local > Ferns > Client)`

7. Locate Ferns.exe in the Client directory, right click it, and run with the custom `wine`/`wine start` you created beforehand. The website should open, and you can then join a server by going to the ferns site, Clicking Games, then Public Games, and joining an active server.

---

## Deletion Process

1. Locate the Ferns_Installer.exe and delete it from your system.

2. Go to your Home directory, locate the .wine, and follow the directory list below.

`*/.wine/drive_c/users/user/AppData/Local/`
 
 `(drive_c > users> usr (Your username) > AppData > Local)`

3. Delete the "Ferns" Directory. All of its files and data will follow.
4. Check the .var directory for any lingering data you do not want from the client.

   To have your data removed from the Ferns DB, please make a ticket in the Discord server. (Contact Tab, line 122)

## Contributing

Contributions are welcome. Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Describe your change"`
4. Push to your fork and open a Pull Request

Please include:
- Clear description of the change
- How to test it
- Any new dependencies

Code of Conduct:
Be respectful and constructive. Any abusive behavior will not be tolerated.

---

## Security & Legal

- This project is not affiliated with Roblox Corporation.
- This project does not run on Roblox's servers and cannot be accessed publically
- If you discover a security vulnerability, please open a private issue or contact the repository owner rather than posting details publicly.

---

## Contact

[Ferns Discord server](https://www.discord.com/invite/ferncondos)

Repo Maintainer: [V.Ally](https://github.com/qe2qi) | Discord : vzhlslb

For questions, issues, or feature requests, please use the GitHub Issues tab.

---
