# Windows 98 UTM Image
<img width="2272" height="1836" alt="utm_w98" src="https://github.com/user-attachments/assets/7a8dfb90-63c7-49e8-9323-77b421a360c3" />
A UTM image to run Windows 98 on macOS. Has working internet and patched Firefox 2.0 for HTTPS access.

## What's Included
- Windows 98 
- Working internet connection
- Patched Firefox 2.0 for HTTPS sites
- Pre-installed FTP server for file transfers

## Getting Started

### 1. Download UTM
Get UTM for free from GitHub: [https://github.com/utmapp/UTM/releases](https://github.com/utmapp/UTM/releases)

### 2. Download the Windows 98 Image  
Download `Win98.utm.zip` from the [Releases page](https://github.com/ducbao414/utm-windows-98/releases).

### 3. Import & Run
- Unzip the downloaded file
- Open UTM → File → Open
- Select the `Win98.utm` file to import it
- Click the play button to start

## File Transfer Between Windows 98 and macOS

### On Windows 98:
1. **Get your local IP**: Double-click "FTP Server" on the desktop → Configure Settings → Click the dropdown in IP address section → Note down the local IP (looks like `192.168.x.x`)
2. **Start the server**: Click "Start" to begin the FTP server

### On macOS:
1. Use an FTP client like [Cyberduck](https://cyberduck.io/)
2. Connect to `192.168.x.x:21` using anonymous login
3. Transfer files between your Mac and Windows 98
4. Files transferred via FTP will appear in the "Shared" folder on the Windows 98 desktop
<img height="500" alt="cyberduck" src="https://github.com/user-attachments/assets/44e0a5f9-2e23-4ec3-8c6c-b1692a16dd84" />

## Finding Old Software

- **WinWorld PC**: https://winworldpc.com/home
- **OldVersion**: http://www.oldversion.com/
