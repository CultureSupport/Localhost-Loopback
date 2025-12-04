There is no single "list of all" IPv6 addresses, as the IPv6 address space is astronomically large (containing 2^{128} possible addresses). However, you are likely looking for a list of common Public IPv6 DNS Resolver addresses, which are frequently used as an alternative to your ISP's DNS.
Here are the most popular and reliable public IPv6 DNS resolver lists, categorized by provider:
🌐 Common Public IPv6 DNS Resolvers
This list focuses on the primary and secondary IPv6 addresses for major public DNS providers.
| Provider | Service Type | Primary IPv6 Address | Secondary IPv6 Address | Key Feature |
|---|---|---|---|---|
| Cloudflare | Standard | 2606:4700:4700::1111 | 2606:4700:4700::1001 | Speed & Privacy |
| Google Public DNS | Standard | 2001:4860:4860::8888 | 2001:4860:4860::8844 | Reliability |
| Quad9 | Security (Malware Block) | 2620:fe::fe | 2620:fe::9 | Security & Malware Block |
| OpenDNS Home | Standard | 2620:119:35::35 | 2620:119:53::53 | Long-standing, customizable |
| AdGuard DNS | Ad/Tracker Block | 2a10:50c0::ad1:ff | 2a10:50c0::ad2:ff | Ad/Tracker Blocking |
| CleanBrowsing | Security Filter | 2a0d:2a00:1::1 | 2a0d:2a00:2::2 | Malware/Phishing Block |
🛡️ Different Service Tiers (Cloudflare Example)
Many providers, like Cloudflare and Quad9, offer different IPv6 addresses for different security or filtering tiers:
| Provider | Service Tier | Primary IPv6 Address | Secondary IPv6 Address |
|---|---|---|---|
| Cloudflare | Standard | 2606:4700:4700::1111 | 2606:4700:4700::1001 |
|  | Malware Blocking | 2606:4700:4700::1112 | 2606:4700:4700::1002 |
|  | Malware & Adult Content | 2606:4700:4700::1113 | 2606:4700:4700::1003 |
| Quad9 | Security (Default) | 2620:fe::fe | 2620:fe::9 |
|  | Unsecured (No Filtering) | 2620:fe::10 | 2620:fe::fe:10 |
💡 Types of IPv6 Addresses
IPv6 addresses can be broadly categorized based on their scope and purpose. They are 128 bits long, often written in compressed hexadecimal notation (which uses :: to represent consecutive blocks of zeros).
| IPv6 Address Type | Prefix Example | Description |
|---|---|---|
| Global Unicast | 2000::/3 | Publicly routable, globally unique addresses (like the ones in the table above). |
| Unique Local Unicast | fc00::/7 | Used for communication within a private network; not routable on the public internet. |
| Link-Local Unicast | fe80::/10 | Used for communication only on the local network segment (e.g., between two devices on the same Ethernet cable). |
| Loopback | ::1 | Equivalent to 127.0.0.1 in IPv4; refers to the device itself. |
| Unspecified | :: | Equivalent to 0.0.0.0 in IPv4; typically used by a device before it has an assigned address. |
| Multicast | ff00::/8 | Used for one-to-many communication (sending to a group of devices simultaneously). |

