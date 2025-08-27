# 🎬 KaraBala CLI - MTN Syria Streaming Client

> A powerful command-line interface tool for accessing streaming content through MTN Syria's network services. This tool provides a user-friendly way to browse and stream live channels, movies, and series content.

## ⚠️ Important Notice

**🔗 This tool is designed exclusively for use with MTN Syria network services. You must be connected to the MTN Syria network to use this application effectively.**

**⚠️ DISCLAIMER: This is an unofficial, educational project created for learning purposes. It is not affiliated with, endorsed by, or connected to MTN Syria in any way. MTN Syria has no knowledge of this application.**

## 💰 Free Usage

**🎉 This application allows you to watch TV channels and movies without consuming your mobile data bundles or deducting any charges from your account. It is completely free to use!**

- 📺 **Zero Data Consumption**: Watch content without using your mobile data
- 💸 **No Charges**: No deductions from your account balance
- 🆓 **Completely Free**: No hidden fees or subscription costs
- 📱 **Bundle Independent**: Works regardless of your current data plan

## ✨ Features

- **📺 Live Channel Streaming**: Access and stream live TV channels
- **🎥 Movie Library**: Browse and stream movies from the content library
- **📺 Series Streaming**: Watch TV series with episode selection
- **🔍 Search Functionality**: Search for specific movies and series
- **🔐 Automatic Authentication**: Handles user registration and verification
- **🎮 Multiple Player Support**: Compatible with MPV and VLC media players
- **💾 Persistent Credentials**: Saves authentication tokens for future use

## 📋 Prerequisites

### 🖥️ System Requirements
- 🐧 Linux operating system (tested on Ubuntu/Debian)
- 🐍 Python 3.7 or higher
- 🌐 Active MTN Syria network connection
- 📱 Valid MTN Syria phone number for registration

### 🎮 Media Players
You need at least one of the following media players installed:
- **🎬 MPV** (recommended): `sudo apt install mpv`
- **📺 VLC**: `sudo apt install vlc`

## 🚀 Installation

1. **📁 Clone or download the project files**
2. **📦 Install Python dependencies**:
   ```bash
   pip install requests rich
   ```

3. **🎮 Ensure you have a media player installed**:
   ```bash
   # For MPV (recommended)
   sudo apt install mpv
   
   # OR for VLC
   sudo apt install vlc
   ```

## 🎯 Usage

### 🆕 First Time Setup

1. **▶️ Run the application**:
   ```bash
   python3 free_mtn_streamer.py
   ```

2. **📝 Register your account**:
   - Enter your MTN Syria phone number (without country code)
   - The system will automatically add the country code (963)
   - Complete the OTP verification if prompted

3. **🔐 Authentication**:
   - The tool will automatically handle the authentication process
   - Your credentials will be saved for future use

### 🎛️ Main Menu Options

The application provides three main modes:

- **🔍 [S]earch**: Search for movies and series by keyword
- **📋 [L]ist**: Browse all available live channels
- **🚪 [Q]uit**: Exit the application

### 🧭 Navigation

- Use number keys to select content
- Press 'b' to go back to the previous menu
- Press 'q' to quit the application
- Use Ctrl+C to stop playback and return to the menu

### 📺 Content Types

1. **📺 Live Channels**: Direct streaming of live TV channels
2. **🎥 Movies**: Full-length movies with automatic path detection
3. **📺 Series**: TV series with episode selection and navigation


## 📦 Dependencies

### 🐍 Python Packages
- `requests`: HTTP client for API communication
- `rich`: Terminal formatting and UI components
- `json`: JSON data handling (built-in)
- `os`: Operating system interface (built-in)
- `shutil`: High-level file operations (built-in)
- `subprocess`: Subprocess management (built-in)
- `sys`: System-specific parameters (built-in)
- `urllib.parse`: URL parsing utilities (built-in)

### 🖥️ System Dependencies
- 🌐 Network connectivity to MTN Syria services
- 🎮 Media player (MPV or VLC)
- 🐍 Python 3.7+

## ⚙️ Configuration

The application automatically creates and manages:
- `credentials.json`: Stores your authentication tokens
- Session management for API requests
- Player preferences and settings

## 🔧 Troubleshooting

### ❗ Common Issues

1. **🔍 "No channels found"**
   - Ensure you're connected to MTN Syria network
   - Verify your phone number is registered with MTN Syria
   - Check your internet connection

2. **🎮 "Neither mpv nor cvlc found"**
   - Install MPV: `sudo apt install mpv`
   - Or install VLC: `sudo apt install vlc`

3. **🔐 Authentication failures**
   - Ensure you're using a valid MTN Syria phone number
   - Check if you're connected to the correct network
   - Try re-registering your account

4. **📺 Playback issues**
   - Verify your media player is properly installed
   - Check network connectivity
   - Ensure you have sufficient bandwidth

### 🌐 Network Requirements

- **🔗 Primary**: MTN Syria network connection
- **📊 Bandwidth**: Minimum 2 Mbps for SD content, 5+ Mbps for HD
- **⚡ Latency**: Low latency connection recommended for live streaming

## 🔒 Security Notes

- 🔐 Authentication tokens are stored locally in `credentials.json`
- 🛡️ Keep your credentials file secure and don't share it
- 🌐 The application only communicates with official MTN Syria endpoints
- 🚫 No personal data is transmitted to third-party services

## 💬 Support

For technical support, questions, or updates:

### 📱 Telegram Support
- **👤 Official Account**: [@karabala10](https://t.me/karabala10)
- **🆘 Support Contact**: Contact our Telegram account for:
  - 📢 Latest updates and releases
  - 🔧 Technical support and troubleshooting
  - 💡 Direct assistance and guidance
  - 🐛 Bug reports and feature requests

### 📋 General Support Guidelines
- ✅ Ensure you're using the latest version of the application
- 📦 Check that all dependencies are properly installed
- 🌐 Verify your MTN Syria network connection
- 🔧 Review the troubleshooting section above
- 💬 Contact us via Telegram for personalized assistance

## ⚖️ Legal Notice

**⚠️ This is an unofficial, educational project created for learning and research purposes only.**

- 🚫 This tool is not affiliated with, endorsed by, or connected to MTN Syria
- 📞 MTN Syria has no knowledge of this application
- 🎓 This project is created purely for educational purposes
- ⚖️ Users are responsible for complying with their service provider's terms of service and local regulations
- 🛡️ The developers are not responsible for any misuse of this application
- ⚠️ Use at your own risk and discretion

---

**📝 Note**: This application requires an active MTN Syria network connection and valid account credentials to function properly.
