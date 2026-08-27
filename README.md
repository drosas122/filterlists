
![uBO lists May 2024](https://github.com/yokoffing/filterlists/assets/11689349/f1925d65-963f-4bb8-aebf-d083ee5f9825)

***
# Block Twitch ads

For Twitch adblock, I use [Violentmonkey](https://violentmonkey.github.io/get-it/) with the [AdGuard Extra](https://github.com/AdguardTeam/AdGuardExtra?tab=readme-ov-file#adguard-extra) userscript. This helps uBlock Origin block server-side 
***

2. On GitHub, select `Raw` on the right-hand side of the page.
3. Copy the URL.
4. In a separate tab, go to `brave://adblock` in the URL bar.
5. Under

1. Click the **subscribe** link by one of the entries below.
2. In the new tab that opens, select **Yes, Add This Filter List**.

### AdBlock
To import custom filters into AdBlock:
1. Click the **subscribe** link by one of the entries below.
2. In the dialog box that pops up, press **OK**.


1. Click on the title of the list from the selections below.
2. In GitHub,
4. Follow your ad blocker's instructions for adding custom lists.

</details>


***

## Privacy

1) :star: [**Privacy Essentials**](https://github.com/yokoffing/filterlists/blob/main/privacy_essentials.txt) (1k rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/yokoffing/filterlists/main/privacy_essentials.txt&title=Privacy%20Essentials)

> **Privacy Essentials** may prevent you from logging into sites using Facebook, Google, or location=https://raw.githubusercontent.com/yokoffing/filterlists/main/click2load.txt&title=yokoffing's%20click2load%20filters)
<br> (**optional** if using `Privacy Essentials`) Turns many third-party audio and video players into [click-to-load](https://x.com/gorhill/status/1377613404794421258) placeholders which only load once a user clicks on it. This list speeds up page load, uses less bandwidth and browser resources, and reduces privacy exposure (by contacting fewer domains during page load). The player will load by clicking on the placeholder.

3) :star: [**Hagezi Pro mini**](https://github.com/hagezi/dns-blocklists/blob/main/adblock/pro.mini.txt) (56k domains) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.mini.txt&title=Hagezi%20Pro%20mini)
<br>
Add the functionality of [ClearURLs](https://github.com/ClearURLs/Addon#-clearurls-) to uBO. These filter lists automatically remove tracking elements from URLs to protect your privacy when browsing the Internet.

1) :star: **[Actually Legitimate URL Shortener Tool](https://github.com/DandelionSprout/adfilt/blob/master/LegitimateURLShortener.txt)** (2.8k rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/DandelionSprout/adfilt/master/LegitimateURLShortener.txt&title=Actually%20Legitimate%20URL%20Shortener%20Tool)
<br> This list also [includes](https://github.com/DandelionSprout/adfilt/discussions/163?sort=old#discussioncomment-3956776) all entries from `AdGuard's URL Tracking Protection` as of October 2022, but you can use both lists.

2) **[ClearURLs for uBO](https://github.com/DandelionSprout/adfilt/tree/master/ClearURLs%20for%20uBo)** (700 rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/DandelionSprout/adfilt/master/ClearURLs%20for%20uBo/clear_urls_uboified.txt&title=ClearURLS%20for%20URLs)
<br> This list is just the rules from the ClearURLs extension converted into a filterlist.

> [!TIP]
> If you find websites agegate.txt&title=Fanboy's%20Agegate%20List)
<br> For age-gated content.

3) **[Browse websites without logging in](https://github.com/DandelionSprout/adfilt/blob/master/BrowseWebsitesWithoutLoggingIn.txt)** (370 rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/DandelionSprout/adfilt/master/BrowseWebsitesWithoutLoggingIn.txt&title=Browse%20websites%20without%20logging%20in)
<br> This list attempts to bypass forced logins on sites.

4) [**YouTube Clear View**](https://github.com/yokoffing/filterlists/blob/main/youtube_clear_view.txt) (17 rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/yokoffing/filterlists/main/youtube_clear_view.txt&title=YouTube%20Clear%20View)
<br> Cleans up some of the clutter on YouTube.

### Paywalls
To most effectively bypass paywalls, use the **Bypass Paywalls Clean** [extension](https://gitflic.ru/user/magnolia1234). The blocklists are limited in what they can do and are therefore **optional**.

1) **[Bypass Paywalls Clean filter](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters/blob/?file=bpc-paywall-filter.txt&branch=main)** (960 rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters/blob/raw?file=bpc-paywall-filter.txt&title=Bypass%20Paywalls%20Clean%20filter)
<br> You do not need this filterlist if you use the extension.
 
2) **[Anti-paywall filters](https://github.com/liamengland1/miscfilters/blob/master/antipaywall.txt)** (2k rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/liamengland1/miscfilters/master/antipaywall.txt&title=Anti-paywall%20filters)
 <br> This list blocks additional third-party requests and annoyances that are not covered in the `Bypass Paywalls Clean` filterlist.

## Security

High-risk sites can expose your device to threats. These lists can prevent that by warning you before navigation or limiting what you can access.

1) :new: [**High-Entropy NRDs (7-day)**](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#new-newly-registered-domains-nrddga-) (509k rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dga7.txt&title=Hagezi%20High-Entropy%20NRDs%207-Day%20)
<br> Targets newly registered domains (NRDs) from the past 7 days that exhibit structural randomness. "High entropy" describes domains that look like computer-generated gibberish, such as `qj9z2x5m0l.com`. Attackers use Domain Generation Algorithms (DGAs) to produce addresses daily so that infected devices can secretly "phone home" to [command servers](https://medium.com/@laurent.mandine/c2-role-in-cyber-attack-dde4710f2037). Note that this blocklist will not catch sophisticated phishing attacks that use readable dictionary words to mimic legitimate brands, such as `verizon-wireless-login.com`. Domains are provided by [Stamus Labs]( https://www.stamus-networks.com/stamus-labs/subscribe-to-threat-intel-feed).

2) [**Most Abused TLDs**](https://github.com/hagezi/dns-blocklists/blob/main/adblock/spam-tlds-ublock.txt) (286 rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt&title=Most%20Abused%20TLDs)
<br> Displays a warning before navigating to a site with an abused [TLD](https://en.wikipedia.org/wiki/Top-level_domain). Allows exceptions for legitimate sites. Merged from my own [Enhanced website protection](https://raw.githubusercontent.com/yokoffing/filterlists/main/enhanced_site_protection.txt) list, Dandelion Sprout's `Anti-Malware List`, LennyFox's `Block non-Latin TLDs` [list](https://github.com/LennyFox/Blocklists/blob/master/Block_non_latin_TLDs.txt), and [Spamhaus](https://www.spamhaus.org/reputation-statistics/cctlds/domains/) statistics.

3) **[Dandelion Sprout's Anti-Malware List](https://github.com/DandelionSprout/adfilt/blob/master/Dandelion%20Sprout's%20Anti-Malware%20List.txt)** (88k rules) | [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Dandelion%20Sprout's%20Anti-Malware%20List.txt&title=Dandelion%20Sprout's%20Anti-Malware%20List)
<br> This list blocks domains with high abuse rates and their search results. It also blocks domains involved in malware redirects, domain parking, and Windows [PUP](https://en.wikipedia.org/wiki/Potentially_unwanted_program) ads. It has many other subcategories that distinguish it from 

A combo list bundles multiple filter lists into one. They pull updates from all the source lists and combine them.

The trade-off is that you must rely on the combo list's maintainer. You are relying on 
