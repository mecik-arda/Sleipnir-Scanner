# 🐎 Sleipnir Scanner

Sleipnir Scanner is an advanced, multi-threaded Cross-Site Scripting (XSS) injection scanner and vulnerability discovery tool designed to integrate seamlessly into the **Yggdrasil Security Framework**.

## 🛡️ Features
- **Concurrent Scanning:** Utilizes multi-threading for rapid payload injection and response analysis.
- **Payload Profiles:** Supports multiple profiles including standard checks, WAF bypass payloads, and advanced polyglots.
- **Dynamic Crawling:** Includes auto-query analysis, form crawling, and manual fuzzing modes.
- **Yggdrasil Integration:** Built to work natively within the Yggdrasil framework as a dedicated Rune module.

## 🚀 Installation & Usage

*(Note: Sleipnir Scanner is typically downloaded automatically by the Yggdrasil Framework when executing a scan).*

To run standalone:
```bash
git clone https://github.com/mecik-arda/Sleipnir-Scanner
cd Sleipnir-Scanner
python sleipnir.py -u <TARGET_URL> -m auto-query -p all -t 3
```

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
