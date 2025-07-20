# SmartHouse Blocklist

A privacy-focused DNS blocklist for AdGuard Home (and compatible platforms) dedicated to blocking telemetry, tracking, and advertisements from smart home/IoT devices, smart TVs, and related appliances. Carefully curated to maintain device privacy **without breaking essential features**.

---

## 🚀 Quick Start

> **Blocklist URL:**  
> `https://raw.githubusercontent.com/uberlerd/SmartHouse-Blocklist/main/smarthouse-blocklist.txt`

1. **Copy the Blocklist URL** above.
2. **Add it to your platform of choice:**
   - **AdGuard Home:** *Filters → DNS blocklists → Add blocklist (paste URL)*
   - **Pi-hole:** *Group Management → Adlists → Add URL*
   - **uBlock Origin/Adblock Plus:** *Dashboard → Filter Lists → Add custom list (paste URL) → Apply changes*
   - **NextDNS:** *Custom Lists → Add Blocklist (paste URL)*
   - **Technitium DNS Server:** *Blocklist Sources → Add URL*
   - **Control D:** *Custom Blocklists section → Add URL*
3. **Save and apply changes.**
4. **Refresh or update blocklists** in your platform to activate protection.
5. **Done!** Your smart home is now protected. If you notice device issues, check the blocklist comments for troubleshooting and consider whitelisting affected domains.

---

## Table of Contents

- [What Is the SmartHouse Blocklist?](#what-is-the-smarthouse-blocklist)
- [Platform Compatibility](#platform-compatibility)
- [How To Use with AdGuard Home](#how-to-use-with-adguard-home)
- [How To Load Into Other Compatible Services](#how-to-load-into-other-compatible-services)
- [Example Blocklist Entries](#example-blocklist-entries)
- [Changelog](#changelog)
- [FAQ / Troubleshooting](#faq--troubleshooting)
- [Notes](#notes)
- [Related Projects](#related-projects)
- [Contributions & Feedback](#contributions--feedback)

---

## What Is the SmartHouse Blocklist?

- **Purpose:**  
  Blocks domains used for telemetry, analytics, and tracking by smart home products and appliances (Amazon Echo, Google Home, smart TVs, cameras, etc.).

- **Focus:**  
  Stops excessive data collection and advertising while preserving device operation and functionality wherever possible.

- **Compatibility:**  
  Designed for [AdGuard Home](https://adguard.com/en/adguard-home/overview.html), [Pi-hole](https://pi-hole.net/), and any DNS-based filtering system that supports ABP/uBlock/AdGuard blocklists, including **uBlock Origin**, **Adblock Plus**, **AdGuard Browser Extension**, **NextDNS**, **Technitium DNS Server**, and **Control D**.

> **ABP/uBlock syntax used:** All rules use `||domain.com^` for maximum compatibility and avoid cosmetic or advanced scriptlet filtering.

---

## Platform Compatibility

| Platform                      | Compatible | Syntax Supported      | Update Method | Setup Difficulty | Notes                                               |
|-------------------------------|:----------:|:---------------------:|:-------------:|:----------------:|-----------------------------------------------------|
| AdGuard Home                  | ✅         | ABP/AdGuard           | Auto/Manual   | Easy             | Uses DNS filter list format                         |
| uBlock Origin                 | ✅         | ABP/uBlock            | Manual/Auto   | Easy             | Import via Dashboard                                |
| Adblock Plus                  | ✅         | ABP                   | Manual        | Easy             | “Add custom filter list”                            |
| Pi-hole                       | ✅         | Hosts/ABP             | Manual        | Easy             | Go to Group Management → Adlists                    |
| NextDNS                       | ✅         | ABP/Hosts             | Auto          | Easy             | Add to Custom Lists → Blocklist                     |
| Control D                     | ✅         | ABP/AdGuard           | Manual        | Easy             | Custom Blocklists section                           |
| Technitium DNS Server         | ✅         | ABP/AdGuard           | Auto          | Easy             | Blocklist Sources in web UI                         |
| CleanBrowsing DNS             | ❌         | Hosts/Domain only     | N/A           | N/A              | **Not compatible with ABP/uBlock/AdGuard syntax**   |
| Ghostery (browser extension) | ❌         | Ghostery-specific     | N/A           | N/A              | **Does not support ABP/uBlock/AdGuard list imports**|
| Other ABP/uBlock services     | ✅         | ABP/uBlock            | Varies        | Varies           | Check platform documentation for compatibility      |

---

## How To Use with AdGuard Home

1. **Copy the blocklist URL:**
   ```
   https://raw.githubusercontent.com/uberlerd/SmartHouse-Blocklist/main/smarthouse-blocklist.txt
   ```
2. **Open** your [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) dashboard.
3. Go to **Filters → DNS blocklists**.
4. **Add Blocklist:**  
   - Paste the URL, name it (e.g., **UberLerd’s SmartHouse Blocklist**), and save.
5. AdGuard Home will automatically sync and keep the list updated.

---

## How To Load Into Other Compatible Services

- **uBlock Origin / Adblock Plus / AdGuard Browser Extension:**  
  Add the blocklist URL in your Filter Lists dashboard and apply changes.

- **Pi-hole:**  
  Use *Group Management → Adlists*, paste the URL, save, then update gravity.

- **NextDNS:**  
  Add to *Custom Lists → Blocklist*.

- **Control D:**  
  Use the *Custom Blocklists* section.

- **Technitium DNS Server:**  
  Add under *Blocklist Sources*.

- **Other ABP/uBlock compatible services:**  
  Check platform documentation for best method of adding custom lists.

---

## Example Blocklist Entries

```
||smarthome-telemetry.example.com^
||smarttv-ads.vendor.net^
||iot-tracker.vendor.com^
```

*All rules use ABP/uBlock syntax for compatibility.*

---

## Changelog

- **2025-07-19:** Enhanced quick start section, improved clarity.
- **2025-07-19:** Broader usability and troubleshooting improvements.
- **2025-07-13:** Syntax and compatibility clarified; example entries added.

See [Commit History](https://github.com/uberlerd/SmartHouse-Blocklist/commits/main) for full details.

---

## FAQ / Troubleshooting

**Q: My device stopped working or lost a feature!**  
A: Some smart device features depend on telemetry or cloud calls. Check blocklist comments to find the likely domain, temporarily whitelist it, and report to help improve the list.

**Q: Is this blocklist safe for all IoT/TV brands?**  
A: The list targets known tracking/ad domains while avoiding those needed for core functions, but whitelisting may be needed; report issues.

**Q: How do I force an update?**  
A: Each platform has an “update,” “refresh,” or “reload blocklists” option; refer to documentation.

**Q: Can I use this with CleanBrowsing DNS or Ghostery?**  
A: No, they do not support ABP/uBlock/AdGuard list formats.

**Q: How often is this blocklist updated?**  
A: The list is updated **as needed or when new domains are discovered/reported**.

---

## Notes

- **Device/vendor comments:** Specific comments in the blocklist help with troubleshooting or custom adjustments.
- **Safe, privacy-first:** Focused on blocking tracking/ad domains while minimizing disruption to core smart device features.
- **User whitelisting encouraged:** If issues occur, whitelist the domain, report it, and help improve the blocklist.

---

## Related Projects

- **[StevenBlack’s Hosts](https://github.com/StevenBlack/hosts):** Reputable composite hosts file merging multiple ad, tracker, and malware lists.
- **[HaGeZi Multi PRO++ Blocklist](https://github.com/hagezi/dns-blocklists):** Feature-rich and modular DNS blocklist for precise filtering.
- **[OISD Blocklist](https://oisd.nl/):** Community-powered, extensive ad/tracker blocklist for various platforms.
- **[Firebog’s Recommended Lists](https://firebog.net/):** Curated selection of the best privacy and ad/tracker blocklists with detailed explanations.

---

## Contributions & Feedback

- **Contributions welcome:** Open an issue or submit a pull request.
- **Code of Conduct:** Please be respectful and constructive in all communications.

---

**Protect your privacy. Keep your smart home truly smart.**
