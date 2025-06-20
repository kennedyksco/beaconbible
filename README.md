BeaconBible: A Comprehensive Cross-Platform Bible Study Application
Welcome to BeaconBible, your lightweight and fast desktop application for deep Bible study. Built with Neutralino.js, BeaconBible provides a seamless and offline experience for accessing scripture, including text and audio versions, across various operating systems. Our mission is to provide an accessible and rich resource for spiritual growth.
✨ Features
•	Offline Access: All Bible texts and included audio content are available without an internet connection after initial download.
•	Multi-Platform Compatibility: Available for Windows, Linux, and macOS.
•	Lightweight & Fast: Experience quick startup times and minimal resource usage, thanks to the efficient Neutralino.js framework.
•	Audio Bible Integration: Listen to the Word with included audio versions (e.g., Chichewa Bible).
•	Intuitive Navigation: Easily browse books, chapters, and verses.
•	Powerful Search: Quickly find specific verses or passages across the entire Bible.
•	User-Friendly Interface: A clean and modern design for an enjoyable study experience.
⬇️ Download & Installation
BeaconBible is distributed via GitHub Releases on our dedicated releases repository. We do not distribute the source code with the compiled applications.
To get started, simply visit our releases page and download the appropriate package for your operating system.
🪟 Windows (x64)
1.	Go to the BeaconBible Releases page.
2.	Download the latest BeaconBible-win_x64.zip file.
3.	Extract the contents of the zip file to a folder of your choice (e.g., C:\Program Files\BeaconBible).
4.	Locate BeaconBible-win_x64.exe inside the extracted folder and double-click to run the application.
Important Windows Prerequisites:
•	Microsoft Edge WebView2 Runtime: Most modern Windows 10/11 systems have this installed. If not, the application might prompt you to install it, or you can download it directly from Microsoft's website.
•	Microsoft Visual C++ Redistributable (x64): Required for many Windows applications. If you encounter errors about missing DLLs (e.g., VCRUNTIME140.dll), download and install the latest x64 redistributable from Microsoft's website.
🐧 Linux (AppImage)
1.	Go to the BeaconBible Releases page.
2.	Download the latest BeaconBible-x.y.z.AppImage file. (Replace x.y.z with the actual version number).
3.	Make the AppImage executable: Open your terminal, navigate to the directory where you downloaded the file, and run:
4.	chmod +x BeaconBible-x.y.z.AppImage

5.	Run the application:
6.	./BeaconBible-x.y.z.AppImage

Important Linux Prerequisites/Notes:
•	FUSE: AppImages require FUSE (Filesystem in Userspace) to run. Most modern Linux distributions have this pre-installed.
•	WebKitGTK: The AppImage bundles most necessary libraries, but relies on your system's WebKitGTK (the webview component). If you encounter rendering issues, ensure your system has webkit2gtk installed (e.g., sudo apt install libwebkit2gtk-4.0-37 on Debian/Ubuntu, or sudo dnf install webkit2gtk4 on Fedora).
🍏 macOS (x64 / ARM64 Universal)
1.	Go to the BeaconBible Releases page.
2.	Download the latest BeaconBible-mac_universal.zip (for Intel and Apple Silicon Macs) or BeaconBible-mac_arm64.zip (for Apple Silicon only).
3.	Unzip the downloaded file.
4.	Drag the BeaconBible.app bundle into your Applications folder.
5.	Double-click BeaconBible.app to launch.
Note for macOS: macOS Gatekeeper might block the application from opening initially. If you see a "BeaconBible.app cannot be opened because it is from an unidentified developer" message, right-click (or Ctrl-click) the application, select "Open," and then confirm that you want to open it.
⚙️ How to Run
After following the installation steps for your operating system, simply launch the executable:
•	Windows: Double-click BeaconBible-win_x64.exe
•	Linux: ./BeaconBible-x.y.z.AppImage from your terminal after making it executable.
•	macOS: Double-click BeaconBible.app in your Applications folder.
⚠️ Troubleshooting
•	"Permission denied" on Linux: Ensure you've made the .AppImage executable using chmod +x. If you're trying to run the direct BeaconBible-linux_x64 binary (not the AppImage) and get this error, ensure you're in a Linux filesystem (like WSL home directory, not mounted Windows drives) or configure WSL's /etc/wsl.conf with metadata option as described in WSL documentation.
•	Application does not launch (Windows): Verify that WebView2 Runtime and Visual C++ Redistributable are installed. Check your system's Event Viewer for application errors.
•	Blank window or rendering issues: Ensure your system's webview component is up-to-date. For Linux, this often means webkit2gtk.
•	Audio not playing: Check your system's audio settings and ensure volume is up for the application.
If you encounter persistent issues, please reach out to us (see "Support & Feedback" section).
🤝 Support & Feedback
We're committed to making BeaconBible the best possible Bible study tool. Your feedback is invaluable!
•	Report Bugs / Request Features: Please open an issue on our GitHub Issues page. While we don't share source code here, this is the easiest way to track issues and feature requests.
•	General Inquiries / Support:
o	Email: mhangokennedyksco@gmail.com (Replace with your actual email)
o	Website: [#]
📜 License
BeaconBible is distributed under the MIT License.
The full license text can be found in the LICENSE.rtf file included with your application download, and is also available here in plain text.
MIT License
Copyright (c) 2025 Kennedy Mhango / Beacon of hope ministries

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

🙏 Acknowledgments
BeaconBible is built with passion and relies on the excellent open-source Neutralino.js framework. We are also grateful to the contributors and projects providing the Bible text and audio resources used in this application.
•	Neutralino.js: The lightweight framework powering this application.
•	[KJV, BSB]: (Public Domain, Creative Commons Attribution).
•	[Specific Audio Bible Source]: ( Faith Comes By Hearing, Bible society Malawi).

