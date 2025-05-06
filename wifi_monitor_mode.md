# WiFi Adapter Monitor Mode

## Introduction

Monitor mode (sometimes called RFMON mode) is a feature that allows a computer with a wireless network interface controller (WNIC) to monitor all traffic received on a wireless channel. Monitor mode allows packet capturing without having to associate with an access point or ad hoc network first.

## Compatible WiFi Adapters

Not all WiFi adapters support monitor mode. Here are some popular adapters known for their monitor mode capabilities:

- Alfa AWUS036NH
- Alfa AWUS036ACH
- TP-Link TL-WN722N (V1 only)
- Panda PAU09 N600

## Enabling Monitor Mode

### Linux

```bash
# Check your wireless interface name
iwconfig

# Disable the interface
sudo ifconfig wlan0 down

# Kill interfering processes
sudo airmon-ng check kill

# Enable monitor mode
sudo airmon-ng start wlan0

# Verify monitor mode is enabled
iwconfig
```

### macOS

```bash
# List available wireless interfaces
system_profiler SPNetworkDataType

# Enable monitor mode
sudo airport en0 sniff 6
```

### Windows (with appropriate drivers)

Windows doesn't natively support monitor mode. You can use tools like:

- Aircrack-ng suite with compatible drivers
- Acrylic WiFi Professional
- CommView for WiFi

## Common Tools That Use Monitor Mode

- **Aircrack-ng**: Wireless network security auditing
- **Wireshark**: Network protocol analyzer
- **Kismet**: Wireless network detector and sniffer
- **Wifite**: Automated wireless attack tool

## Ethical and Legal Considerations

Monitor mode can be used for legitimate purposes like:
- Network troubleshooting
- Wireless security testing (with proper authorization)
- Educational purposes

However, using these techniques without authorization on networks you don't own can be illegal in many jurisdictions. Always:
- Only analyze networks you own or have explicit permission to test
- Check local laws regarding network monitoring
- Use these tools responsibly and ethically

## Additional Resources

- [Aircrack-ng Documentation](https://www.aircrack-ng.org/documentation.html)
- [Wireshark Documentation](https://www.wireshark.org/docs/)
- [Kali Linux Wireless Penetration Testing](https://www.kali.org/docs/usb/kali-linux-live-usb-persistence/)
