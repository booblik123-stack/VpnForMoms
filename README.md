# VpnForMoms 🐱

> A simple, mom-friendly VPN solution for Russians to access the unrestricted internet.

## What is VpnForMoms?

VpnForMoms is an easy-to-use VPN service designed specifically for moms in Russia who want to access the open internet safely and securely. No technical knowledge required!

## Features

✨ **Mom-Friendly**
- Simplified instructions written for non-technical users
- Just scan a QR code and click activate
- No complicated setup or configuration

🔐 **Secure**
- Military-grade WireGuard encryption
- Your IP is protected and hidden
- Safe browsing from anywhere

🚀 **Fast**
- Optimized for Russian users
- Dual-path routing through Russian IP bridge
- Minimal latency and excellent speeds

📱 **Works Everywhere**
- Windows, Mac, Linux
- iOS, Android
- Laptop, phone, tablet

## How It Works

1. **Visit the Website**: Open https://n8n.dglocean.com/vpn
2. **Choose Your Connection**: Select the appropriate QR code based on your needs
3. **Scan & Install**: Use WireGuard app to scan the QR code
4. **Name Your VPN**: Give it a simple name like "AstraVPN"
5. **Grant Permission**: Allow the app to connect to the internet
6. **Activate**: Turn on the VPN with one click
7. **Done!** You now have secure internet access

## Available Configurations

### For Mom (Basic Setup)
- Full protection for all traffic
- Simplest option for everyday use
- **Scan**: QR code on main page

### For Remote Work
- Optimized for work-related apps
- Telegram, Instagram, ID services via VPN
- Russian services for speed
- **Scan**: Available at `/vpn/work.html`

### For Russian Users (Recommended)
- Routes through Russian IP bridge (optional premium server)
- Bypasses geo-blocks effectively
- Works with restricted sites
- **Scan**: Available at `/vpn` - "Russian IP" option

## System Requirements

- **Windows**: Windows 10 or later
- **Mac**: macOS 10.15 or later
- **Linux**: Ubuntu 18.04 or later
- **Mobile**: iOS 12+ or Android 6.0+
- **Internet**: Any connection (broadband recommended)

## Installation Steps

### Step 1: Download WireGuard
Visit [wireguard.com](https://www.wireguard.com/install/) and download for your device:
- 🪟 Windows
- 🍎 macOS
- 🐧 Linux
- 📱 iOS (App Store)
- 🤖 Android (Google Play)

### Step 2: Open WireGuard

### Step 3: Add New Tunnel
Click the "+" (plus) button to add a new tunnel

### Step 4: Scan QR Code
Choose "Scan from QR code" or "Import from file"

### Step 5: Give It a Name
Name your VPN (for example, "AstraVPN")

### Step 6: Grant Permission
Allow WireGuard to connect to the internet when asked

### Step 7: Activate
Click "Activate" to turn on your VPN

### Done! 🎉
Your IP is now protected and you have access to the open internet!

## Troubleshooting

**Q: VPN connects but doesn't work?**
A: Try restarting WireGuard or your device. Make sure you granted internet permission.

**Q: Too slow?**
A: Check your internet connection. Try the Russian IP configuration for better speeds.

**Q: Still blocked?**
A: Contact support - there may be network-specific issues we need to address.

## Security & Privacy

- We use WireGuard, the most secure VPN protocol
- Your data is encrypted end-to-end
- No logs are kept of your activity
- Your real IP is completely hidden

## Configurations Provided

| Config | Purpose | Best For |
|--------|---------|----------|
| Basic (AstraVPN) | All traffic protected | Everyday use |
| Work | Selective routing | Remote work |
| Russia | Through Russian IP | Bypassing blocks |

## Support

If your mom needs help:
1. Check the instructions on the website
2. Review the troubleshooting section
3. Try restarting WireGuard
4. Contact support if issues persist

## Technical Details

- **Protocol**: WireGuard
- **Encryption**: ChaCha20-Poly1305 + Curve25519
- **Servers**: DigitalOcean (USA) + Russian Bridge
- **DNS**: Cloudflare (1.1.1.1)
- **No logs**: Activity never recorded

## For Developers

If you want to host your own instance:
1. Set up WireGuard on your server
2. Configure the website files
3. Generate QR codes for each configuration
4. Deploy with nginx
5. Use HTTPS with Let's Encrypt

## License

This project is provided as-is for educational and personal use.

## Made With ❤️

VpnForMoms is created with love to help Russian families stay connected to the open internet safely and securely.

**For the best moms out there!** 🐱

---

**Version**: 1.0.0  
**Last Updated**: May 2026  
**Status**: Active & Maintained
