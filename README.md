# Pushi SOCKS Proxy

**Version:** 2026.2.14  
**Author:** Can Güngör  
**Contact:** pusheenlower@gmail.com  

Pushi is a high-performance SOCKS5 proxy server designed specifically for **Android ARM64 (Termux)**.  
It supports TCP connections, remote DNS, authentication, and JSON-formatted logging.

---

## Features

- SOCKS5 proxy (TCP) with authentication
- Remote DNS support
- JSON logging for connections and user activity
- Single binary for Android ARM64
- Closed-source, no source code disclosure
- Linux ARM64 binary coming soon
- **Windows is not supported** – running on Windows may cause kernel panic or system instability

---

## Platform Compatibility

| Platform          | Architecture | Binary Name              | Status          |
|------------------|-------------|-------------------------|----------------|
| Android Termux ✅ | ARM64       | pushi-android-arm64      | Supported      |
| Linux             | ARM64       | pushi-linux-arm64        | Coming Soon    |
| Linux             | x86_64      | pushi-linux-x86_64       | Coming Soon    |
| Linux             | ARMv7       | pushi-linux-armv7        | Not Supported  |
| Windows           | x86/x86_64  | -                        | Not Supported  |

**Note:**  
- The Android ARM64 binary is fully functional and ready to use.  
- Linux binaries are planned and will be released soon.  
- Do not attempt to run the Android binary on Linux, Windows, or 32-bit devices; it will fail or cause instability.

---

## Installation & Running

### Android (Termux)
```bash
# Give execute permission
chmod +x pushi-android-arm64

# Run the proxy
./pushi-android-arm64
