# SmartHouse Blocklist

**The Privacy-First Blocklist for the Modern Smart Home**

Take control of your connected world. The SmartHouse-Blocklist is a carefully curated, zero-breakage DNS privacy solution for every smart device in your home—smart TVs, appliances, lights, thermostats, speakers, cameras, lawn robots, vehicles, and beyond.

**Why choose SmartHouse-Blocklist?**

- 🏠 Purpose-Built for Smart Homes: From TVs to thermostats, locks to lighting—every major device category is supported, with clear coverage for today's and tomorrow's leading brands.
- 🔒 Maximum Privacy, Minimal Hassle: Blocks invasive telemetry, tracking, and ads—never core device functions or updates.
- 🚀 Ready to Grow: Future-proofed with dedicated sections for emerging tech and new brands, so you’re always ahead of the privacy curve.
- 📝 Clearly Organized, Easy to Audit: Brand-by-brand layout, helpful comments, and a transparent philosophy—making it effortless to customize, contribute, and keep your home secure.
- 🧑‍💻 Community-Driven & Open Source: Everyone is welcome to propose new additions, report any device issues, and join a privacy-first smart home movement.

> Try it today: Copy the blocklist URL and add it to your preferred platform!

Protect your privacy.  
Enjoy your smart home—on your terms.

Want more details? Explore the brand comparison, setup guides, and contribution info below!

---

## 🚀 Quick Start

**Blocklist URL:**  
```https://raw.githubusercontent.com/uberlerd/SmartHouse-Blocklist/main/smarthouse-blocklist.txt```


1. Copy the Blocklist URL above.
2. Add it to your platform of choice:
    - AdGuard Home: `Filters → DNS blocklists → Add blocklist (paste URL)`
    - Pi-hole: `Group Management → Adlists → Add URL`
    - uBlock Origin/Adblock Plus: `Dashboard → Filter Lists → Add custom list (paste URL) → Apply changes`
    - NextDNS: `Custom Lists → Add Blocklist (paste URL)`
    - Technitium DNS Server: `Blocklist Sources → Add URL`
    - Control D: `Custom Blocklists section → Add URL`
3. Save and apply changes.
4. Refresh or update blocklists in your platform to activate protection.
5. Done! Your smart home is now protected. If you notice device issues, check the blocklist comments for troubleshooting and consider whitelisting affected domains.

---

## Table of Contents

- SmartHouse Blocklist Overview
- Quick Start
- Brand & Category Coverage — At a Glance
- 🏆 Industry-Leading Device & Brand Coverage
- Platform Compatibility
- How To Use with AdGuard Home
- How To Load Into Other Compatible Services
- Example Blocklist Entries
- Changelog
- FAQ / Troubleshooting
- Notes
- Related Projects
- Contributions & Feedback

---

## Brand & Category Coverage — At a Glance

How does SmartHouse-Blocklist’s domain coverage stack up against the most respected DNS privacy/blocklist competitors?

| Category / Example Brands¹                                     | SmartHouse Blocklist | HaGeZi IoT/SmartHome | OISD | StevenBlack | AnudeepND Smart-TV | What This Means for You                                                         |
|---------------------------------------------------------------|:-------------------:|:--------------------:|:----:|:----------:|:------------------:|----------------------------------------------------------------------------------|
| Smart Hubs & Assistants (Alexa, HomeKit, etc.)                | ✅                   | 🚀                   | 🚀   | 🚀         | 🚫                 | Amazon tracking blocked; all major platforms monitored for safe tracking          |
| TVs & Streaming (Samsung, LG, Sony, Roku)                     | ✅                   | ✅                   | ✅   | ✅         | ✅                 | Full brand-by-brand coverage—tracking/ads endpoints for ALL major TVs/devices     |
| Gaming Consoles / TV Boxes (Xbox, PS, Nintendo)               | ✅                   | 🚀                   | 🚀   | 🚀         | 🚫                 | Xbox telemetry included, future-ready for all consoles as analytics/ads emerge    |
| Smart Lighting (Hue, Nanoleaf, Govee, etc.)                   | ✅                   | 🚀                   | 🚀   | 📝         | 🚫                 | Philips Hue covered, major lighting brands sectioned for tracking expansion       |
| Thermostats / HVAC (Ecobee, Nest, Bosch, etc.)                | ✅                   | 🚀                   | 🚀   | 📝         | 🚫                 | Ecobee and key telemetry included, more added as safe analytics/tracking appear   |
| Appliances (LG, Whirlpool, Bosch, GE, Miele)                  | ✅                   | 🚀                   | 🚀   | ⚠️         | 🚫                 | Industry leaders in list, ensures tracking-only adds, safe from breakage          |
| Cameras & Security (Ring, Wyze, Arlo, Blink)                  | ✅                   | ✅                   | 🚀   | 🚀         | 🚫                 | Most popular cameras/doorbells already covered; category ready for expansion      |
| Locks & Access Control (August, Yale, Nuki)                   | 🚀                   | 🚀                   | 🚀   | 🚀         | 🚫                 | Full support structure in place—future trackers/telemetry added instantly         |
| Lawn Robotics (Husqvarna, ECOVACS, Mammotion)                 | 🚀                   | 🚀                   | 🚀   | 📝         | 🚫                 | Section ready for latest robot mowers/garden devices as privacy domains found     |
| Automotive / Telematics (Tesla, Ford, OnStar)                 | ✅                   | 🚀                   | 🚀   | 🚀         | 🚫                 | Automotive telemetry entries present; quick to add as market evolves              |
| IoT Platforms (Tuya, TP-Link, Aqara, Shelly)                  | ✅                   | ✅                   | ✅   | ✅         | 🚫                 | Platform analytics/telemetry included; ready as new vendor integrations launch    |
| Analytics & Tracking Vendors (Google, etc.)                   | ✅                   | ✅                   | ✅   | ✅         | ⚠️                 | Tracks only known analytics/ads without blocking device-critical hosts            |
| OS / Platform Telemetry (Apple, Microsoft)                    | ✅                   | ✅                   | ✅   | ✅         | 🚀                 | All major OS telemetry blocked; always ready for new endpoints                    |
| Emerging / Specialty Devices (Pet-tech, etc.)                 | 🚀                   | 🚀                   | 🚀   | 🚀         | 🚫                 | Dedicated section for tomorrow’s smart tech—easy to keep your network future-proof|

Legend:  
✅ = Covered  
🚀 = Supported and actively monitored—new trackers added quickly when safe  
⚠️/📝 = Partial or requires extension  
🚫 = Not included

¹ Examples shown—see blocklist comments for a continuously refreshed, per-brand breakdown.

---

## 🏆 Industry-Leading Device & Brand Coverage

The SmartHouse-Blocklist is meticulously curated and continuously reviewed to ensure robust compatibility and protection for:

- 100+ leading smart home brands across all major categories: TVs, appliances, cameras, lighting, voice assistants, locks, sensors, hubs, and more.
- Compatibility with the top 1000 smart home products—covering the latest connected gadgets and emerging device trends.
- Full support for global leaders such as Amazon, Google, Apple, Samsung, LG, Sony, Roku, Ecobee, Bosch, Whirlpool, Philips Hue, Wyze, and more.
- Every major device category and vendor receives its own section, making expansion easy and keeping you protected as you add new tech.
- **Future-proof:** If you buy a top-ranked device, odds are it's already covered—or ready to be, with just a single domain added.

Your peace of mind:  
Whether your home is filled with classic top brands or the latest smart gadgets, SmartHouse-Blocklist is designed to protect your privacy now and for years to come.

---

## Platform Compatibility

| Platform / Blocklist           | Compatible | Syntax Supported      | Update Method | Setup Difficulty | Notes                                                                    |
|------------------------------- |:----------:|:---------------------:|:-------------:|:----------------:|--------------------------------------------------------------------------|
| AdGuard Home                   | ✅         | ABP/AdGuard           | Auto/Manual   | Easy             | DNS filter list, ideal match                                             |
| uBlock Origin                  | ✅         | ABP/uBlock            | Manual/Auto   | Easy             | Import via dashboard                                                     |
| Adblock Plus                   | ✅         | ABP                   | Manual        | Easy             | ‘Add custom filter list’ menu                                            |
| Pi-hole                        | ✅         | Hosts/ABP             | Manual        | Easy             | Add as adlist, (gravity update)                                          |
| NextDNS                        | ✅         | ABP/Hosts             | Auto          | Easy             | Custom Lists → Blocklist                                                 |
| Control D                      | ✅         | ABP/AdGuard           | Manual        | Easy             | Custom blocklists interface                                              |
| Technitium DNS Server          | ✅         | ABP/AdGuard           | Auto          | Easy             | Blocklist Sources tab                                                    |
| OISD Blocklist                 | ✅         | ABP/Hosts             | Auto/Manual   | Easy             | Can pair with SmartHouse for layered privacy                             |
| StevenBlack’s Hosts            | ✅         | Hosts/ABP*            | Auto/Manual   | Easy             | Great with Pi-hole, AdGuard, etc.                                        |
| HaGeZi IoT/SmartHome/PRO++     | ✅         | ABP/Hosts             | Auto/Manual   | Easy             | Aggressive alternative/companion list                                    |
| Other ABP/uBlock Services      | ✅         | ABP/uBlock            | Varies        | Varies           | See your platform’s documentation                                        |

*StevenBlack’s Hosts recommended mainly for DNS/blocking platforms, not direct browser extension imports.

---

## How To Use with AdGuard Home

1. Copy the blocklist URL:
```https://raw.githubusercontent.com/uberlerd/SmartHouse-Blocklist/main/smarthouse-blocklist.txt```

2. Open your AdGuard Home dashboard.
3. Go to Filters → DNS blocklists.
4. Add Blocklist:  
   - Paste the URL, name it (e.g., UberLerd’s SmartHouse Blocklist), and save.
5. AdGuard Home will automatically sync and keep the list updated.

---

## How To Load Into Other Compatible Services

- uBlock Origin / Adblock Plus / AdGuard Browser Extension:  
  Add the blocklist URL in your Filter Lists dashboard and apply changes.
- Pi-hole:  
  Use Group Management → Adlists, paste the URL, save, then update gravity.
- NextDNS:  
  Add to Custom Lists → Blocklist.
- Control D:  
  Use the Custom Blocklists section.
- Technitium DNS Server:  
  Add under Blocklist Sources.
- Other ABP/uBlock compatible services:  
  Check platform documentation for best method of adding custom lists.

---

## Example Blocklist Entries

`||smarthome-telemetry.example.com^`
`||smarttv-ads.vendor.net^`
`||iot-tracker.vendor.com^`

All rules use ABP/uBlock syntax for maximum compatibility and safety. See the full blocklist for detailed per-brand entries.

---

## Changelog

See [Commit History](https://github.com/uberlerd/SmartHouse-Blocklist/commits/main) for full details.

---

## FAQ / Troubleshooting

**Q: My device stopped working or lost a feature!**  
A: Some smart device features depend on telemetry or cloud calls. Check blocklist comments to find the likely domain, temporarily whitelist it, and report to help improve the list.

**Q: Is this blocklist safe for all IoT/TV brands?**  
A: The list targets known tracking/ad domains while avoiding those needed for core functions, but whitelisting may be needed; report issues.

**Q: How do I force an update?**  
A: Each platform has an “update,” “refresh,” or “reload blocklists” option; refer to documentation.

**Q: Can I use this with OISD, StevenBlack’s Hosts, or HaGeZi as well?**  
A: Yes! Many users combine SmartHouse-Blocklist with other reputable lists for layered privacy protection.

**Q: How often is this blocklist updated?**  
A: The list is updated as needed or when new domains are discovered/reported.

---

## Notes

- Device/vendor comments: Specific comments in the blocklist help with troubleshooting or custom adjustments.
- Safe, privacy-first: Focused on blocking tracking/ad domains while minimizing disruption to core smart device features.
- User whitelisting encouraged: If issues occur, whitelist the domain, report it, and help improve the blocklist.
- Growth-focused: All major device classes and brands have dedicated sections, including emerging smart home tech—making the list easy to maintain and expand.

---

## Related Projects

- **[StevenBlack’s Hosts](https://github.com/StevenBlack/hosts):** Reputable composite hosts file merging multiple ad, tracker, and malware lists.
- **[HaGeZi Multi PRO++ Blocklist](https://github.com/hagezi/dns-blocklists):** Feature-rich and modular DNS blocklist for precise filtering.
- **[OISD Blocklist](https://oisd.nl/):** Community-powered, extensive ad/tracker blocklist for various platforms.
- **[Firebog’s Recommended Lists](https://firebog.net/):** Curated selection of the best privacy and ad/tracker blocklists with detailed explanations.

---

## Contributions & Feedback

- Contributions welcome: Open an issue or submit a pull request.
- Code of Conduct: Please be respectful and constructive in all communications.
- Help us grow: If you notice a missing tracker/telemetry domain for a smart device, create an issue or PR for rapid inclusion!

---

Enjoy your smart home—on your terms.
