# SmartHouse Blocklist

A privacy-focused DNS blocklist for AdGuard Home (and compatible platforms) dedicated to blocking telemetry, tracking, and advertisements from smart home/IoT devices, smart TVs, and related appliances. Carefully curated to maintain device privacy **without breaking essential features**.

## What Is the SmartHouse Blocklist?

- **Purpose:**  
  Blocks domains used for telemetry, analytics, and tracking by popular smart home products and appliances (Amazon Echo, Google Home, smart TVs, cameras, etc.).
- **Focus:**  
  Stops excessive data collection and advertising while preserving device operation and functionality wherever possible.
- **Compatibility:**  
  Works with [AdGuard Home](https://adguard.com/en/adguard-home/overview.html), [Pi-hole](https://pi-hole.net/), and other DNS-based filtering systems that support blocklists.

## How To Use with AdGuard Home

1. **Copy the raw URL** for the blocklist file in this repository (e.g.  
   `https://raw.githubusercontent.com/uberlerd/SmartHouse-Blocklist/main/smarthouse-blocklist.txt`).

2. **Open your [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) dashboard**  
   Go to **Filters → DNS blocklists**.

3. **Add Blocklist**  
   - Click **Add blocklist** (or similar).
   - Paste the raw GitHub URL.
   - **When prompted to name the list, enter:**  
     **UberLerd’s SmartHouse Blocklist**
   - Click **Save** or **Apply**.

4. **Update/refresh the blocklist**  
   AdGuard Home will automatically sync and apply the latest version.

## Suggested Name

We recommend naming the list:

**UberLerd’s SmartHouse Blocklist**

This makes it easy to identify among multiple blocklists and supports branding consistency.

## How To Load Into Other Compatible Services

- **[Pi-hole](https://pi-hole.net/):**  
  Go to *Group Management → Adlists*, paste the raw blocklist URL, and save.

- **[NextDNS](https://nextdns.io/):**  
  Add the URL under *Denylist* or *Blocklist* in the [Custom Lists](https://my.nextdns.io/) section.

- **[Control D](https://controld.com/):**  
  Use the *Custom Blocklists* section and paste the raw list URL.

- **[Technitium DNS Server](https://technitium.com/dns/):**  
  Add the list via *Blocklist Sources* (supports AdBlock/AdGuard syntax).

- **Other DNS Filter Platforms:**  
  Any system that uses `hosts`, AdBlock/AdGuard, or domain-based DNS filtering can subscribe using the same raw URL above.

> **Note:**  
> These platforms support the AdGuard/AdBlock syntax (e.g., `||domain.com^`), and your list avoids complex rules or modifiers that would cause incompatibility.

## Notes

- The blocklist is **organized by device/vendor** with comments for clarity.
- Safe for use with most smart devices and TVs, but you may need to whitelist domains if a specific feature breaks.
- The list will be updated to reflect new tracking domains and user reports.

## Related Projects

For complementary or broader coverage, check out these widely trusted community blocklists:

- [StevenBlack’s Hosts](https://github.com/StevenBlack/hosts) — Composite ad/tracker/malware hosts file
- [HaGeZi Multi PRO++ Blocklist](https://github.com/hagezi/dns-blocklists) — Highly granular levels for various privacy needs
- [Dandelion Sprout’s Smart-TV Blocklist](https://github.com/DandelionSprout/adfilt/blob/master/Smart-TV-Blocklist.txt)
- [OISD Blocklist](https://oisd.nl/) — Wide and regularly updated ad/tracker blocklist
- [Firebog’s Recommended Lists](https://firebog.net/) — Curated best-of-lists for privacy and ad filtering

## Contributions & Feedback

- Issues and pull requests are welcome!
- Found a domain that breaks something? Open an issue or suggest an edit.

**Protect your privacy. Keep your smart home truly smart.**
