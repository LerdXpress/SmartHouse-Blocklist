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
   `https://raw.githubusercontent.com/<your-username>/SmartHouse-Blocklist/main/smarthouse-blocklist.txt`).

2. **Open your AdGuard Home dashboard**  
   Go to **Filters → DNS blocklists**.

3. **Add Blocklist**  
   - Click **Add blocklist** (or similar).
   - Paste the raw GitHub URL.
   - Click **Save** or **Apply**.

4. **Update/refresh the blocklist**  
   AdGuard Home will automatically sync and apply the latest version.

## How To Load Into Other Compatible Services

- **Pi-hole:**  
  Go to *Group Management → Adlists*, paste the raw blocklist URL, and save.

- **Other DNS Filter Platforms:**  
  Any system that uses `hosts`, AdBlock/AdGuard, or domain-based DNS filtering can subscribe using the same raw URL above.

## Notes

- The blocklist is **organized by device/vendor** with comments for clarity.
- Safe for use with most smart devices and TVs, but you may need to whitelist domains if a specific feature breaks.
- The list will be updated to reflect new tracking domains and user reports.

## Contributions & Feedback

- Issues and pull requests are welcome!
- Found a domain that breaks something? Open an issue or suggest an edit.

**Protect your privacy. Keep your smart home truly smart.**
