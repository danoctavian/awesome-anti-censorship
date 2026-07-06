# Awesome anti-censorship

A curated list of open source tools and readings for fighting Internet censorship.

Inspired by the [awesome list](https://github.com/sindresorhus/awesome).

## Categories

- [Censorship bypass tools](#censorship-bypass-tools)
- [Privacy and anonymity](#privacy-and-anonymity)
- [Network tunnels](#network-tunnels)
- [Firewall analysis](#firewall-analysis)
- [Decentralized systems](#decentralized-systems)
- [Steganography](#steganography)
- [Deniable encryption](#deniable-encryption)
- [Misc](#misc)
- [Related awesome lists](#related-awesome-lists)
- [Articles and research papers](#articles-and-research-papers)

## Censorship bypass tools

- [Zerodrop](https://github.com/Vinum-Security/zerodrop) - Open-source stealth URL toolkit optimized for bypassing censorship filters.

## Privacy and anonymity

- [tor](https://www.torproject.org/) - The Tor network is a group of volunteer-operated servers that allows people to improve their privacy and security on the Internet. Tor's users employ this network by connecting through a series of virtual tunnels rather than making a direct connection
- [i2p](https://geti2p.net/en/) - I2P is an anonymizing network, offering a simple layer that identity-sensitive applications can use to securely communicate. All data is wrapped with several layers of encryption, and the network is both distributed and dynamic, with no trusted parties.
- [vuvuzela](https://github.com/vuvuzela/vuvuzela) - Vuvuzela is a messaging system that protects the privacy of message contents and message metadata. Users communicating through Vuvuzela do not reveal who they are talking to, even in the presence of powerful nation-state adversaries.
- [whonix](https://www.whonix.org/) - Whonix is an operating system focused on anonymity, privacy and security. It's based on the Tor anonymity network, Debian GNU/Linux and security by isolation. DNS leaks are impossible, and not even malware with root privileges can find out the user's real IP.
- [tails](https://tails.boum.org/) - Tails is a portable operating system that protects against surveillance and censorship.

## Network tunnels

- [shadowsocks](https://github.com/shadowsocks/shadowsocks) - a fast socks5 proxy that encrypts traffic
- [v2ray](https://github.com/v2ray/v2ray-core) - A platform for building proxies to bypass network restrictions
- [obfsproxy](https://github.com/Yawning/obfs4) - Tor framework for implementing pluggable transports (anti-censorship network tunnels)
- [obfsproxy with OpenVPN](https://github.com/NOISPICA/obfsproxy-openvpn) - OpenVPN traffic obfuscation using obfsproxy
- [flashproxy](https://crypto.stanford.edu/flashproxy/) - miniature proxy that runs in a web browser, and reflects traffic to a Tor relay.
- [meek](https://trac.torproject.org/projects/tor/wiki/doc/meek) - Tor pluggable transport that uses HTTP for carrying bytes and TLS for obfuscation.
- [lantern](https://getlantern.org/) - Lantern is a free desktop application that delivers fast, reliable and secure access to the open Internet for users in censored regions
- [algo](https://github.com/trailofbits/algo) - Set up a personal VPN in the cloud
- [MTProxy](https://github.com/TelegramMessenger/MTProxy) - Proxy server which helps telegram users who are inside censored areas still be able to connect to telegram
- [streisand](https://github.com/StreisandEffect/streisand) - single command set for a server running a wide variety of anti-censorship software
- [WireGuard](https://www.wireguard.com/) - WireGuard is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography.
- [tunsafe](https://tunsafe.com/) - TunSafe is a fast and modern layer 3 VPN tunnel that implements the WireGuard protocol.
- [scramblesuit](https://github.com/NullHypothesis/scramblesuit) - Tor pluggable transport that uses look-like-nothing traffic as a cover channel
- [FTE](https://kpdyer.com/fte/) - fteproxy provides transport-layer protection to resist keyword filtering, censorship and discriminatory routing policies
- [telex](https://github.com/jmwample/telex) - involves placing anticensorship technology into the Internet's core network infrastructure, through cooperation from large ISPs.
- [uproxy](https://www.uproxy.org/) - uProxy is a browser extension that lets friends route their connection to their Internet through each other's computers.
- [NaïveProxy](https://github.com/klzgrad/naiveproxy) - NaïveProxy uses Chrome's network stack to camouflage traffic with stronger censorship resistance.
- [gost](https://github.com/ginuerzh/gost) - GO Simple Tunnel - a simple tunnel written in golang
- [obfs4](https://github.com/Yawning/obfs4) - the newest version of the Tor obfsproxy obfuscation proxy.
- [trojan](https://github.com/trojan-gfw/trojan) - An unidentifiable mechanism that helps you bypass GFW
- [govpn](https://github.com/govpn/govpn) - Simple secure VPN daemon, aimed to be reviewable, secure, DPI/censorship-resistant.
- [gohop](https://github.com/bigeagle/gohop) - A VPN implementation in golang, with crypto and obfuscation in nature.
- [Dust](https://github.com/blanu/Dust) - A Polymorphic Engine for Filtering-Resistant Transport Protocols
- [marionette](https://github.com/kpdyer/marionette) - Marionette is a programmable client-server proxy that enables the user to control network traffic features with a lightweight domain-specific language.
- [facebook-tunnel](https://github.com/wanderview/facebook-tunnel) - Tunneling Internet traffic over FB chat.
- [chnroutes](https://github.com/fivesheep/chnroutes) - modifies the route table to route only censored ips through vpn
- [firefly-proxy](https://github.com/fireflyproxy/fireflyproxy) - A proxy software to help circumventing the Great Firewall.
- [iodine](https://github.com/yarrick/iodine) - This is a piece of software that lets you tunnel IPv4 data through a DNS server.
- [obfuscated-openssh](https://github.com/brl/obfuscated-openssh) - Handshake obfuscation strengthens the initial SSH handshake against systems that identify or classify network protocols.
- [infranet](https://css.csail.mit.edu/infranet/) - Infranet is a system that attempts to circumvent web censorship by allowing clients to surreptitiously request sensitive content via cooperating Web servers.
- [fwlite](https://github.com/v3aqb/fwlite) - A powerful HTTP proxy server designed to circumvent the Great Firewall (GFW)
- [code-talker-tunnel](https://github.com/SkypeMorph/SkypeMorph) - Code Talker Tunnel is a protocol camouflaging tool, designed to reshape traffic output of any censorship circumvention tool to look like Skype video calls
- [stegotorus](https://github.com/hardenedlinux/stegotorus) - StegoTorus, a tool that comprehensively disguises Tor from protocol analysis.
- [go-packetflagon](https://github.com/PacketFlagon/go-packetflagon) - A local HTTP application that serves customised Proxy Auto Configuration files for your browser to help bypass Internet censorship.
- [Firezone](https://github.com/firezone/firezone) - Self-hosted VPN server using WireGuard. Supports MFA, SSO, and has easy deployment options.
- [proxy-dns-leak-check](https://github.com/SotaProxy/proxy-dns-leak-check) - CLI tool to detect DNS leaks when routing traffic through proxies (residential, mobile, datacenter). Companion to a [DNS troubleshooting guide](https://sotaproxy.com/en/blog/dns-resolution-problems?utm_source=github&utm_medium=readme&utm_campaign=anti_censorship_list) for proxy-based infrastructure.

## Firewall analysis

- [ooni-probe](https://ooni.org/install/) - OONI Probe network measurement tool for detecting internet censorship
- [mongol](https://github.com/nkrusch/mongol) - A simple python tool to pinpoint the IP addresses of machines working for the Great Firewall of China.
- [ChinaDNS](https://github.com/shadowsocks/ChinaDNS) - Protect yourself against DNS poisoning in China.
- [gfwlist](https://github.com/gfwlist/gfwlist) - Great Firewall of China ban list
- [gfw_whitelist](https://github.com/Leask/gfw_whitelist) - A Pac File of the Whitelisted Websites for the Great Firewall of China (GFW)
- [antizapret](https://antizapret.prostovpn.org/) - List of Russian government's IP addresses.
- [BlockCheck](https://github.com/net4people/bbs) - A script that detects what kind of blocking (DNS, IP, DPI) your ISP is using (for Russia).
- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) - Passive Deep Packet Inspection blocker and Active DPI circumvention utility (for Windows)
- [DPITunnel](https://github.com/nomoresat/DPITunnel-android) - DPI Tunnel is an application for Android that uses various techniques to bypass DPI systems.
- [Geneva](https://github.com/Kkevsterrr/geneva) - Novel experimental genetic algorithm that evolves packet-manipulation-based censorship evasion strategies.

## Decentralized systems

- [ipfs](https://ipfs.tech/) - IPFS is a global, versioned, peer-to-peer filesystem
- [dat](https://dat-ecosystem.org/) - a decentralized tool for distributing data
- [ZeroNet](https://zeronet.dev/) - Decentralized websites using Bitcoin crypto and the BitTorrent network
- [sovereign](https://github.com/sovereign/sovereign) - Censorship resistant democracies.
- [tribler](https://www.tribler.org/) - Privacy enhanced BitTorrent client with P2P content discovery
- [AKASHA](https://akasha.world/) - next-generation social media network immune to censorship by design.
- [twister](https://github.com/miguelfreitas/twister-core) - twister is an experimental peer-to-peer microblogging software.
- [freenet](https://freenetproject.org/) - Freenet is a peer-to-peer platform for censorship-resistant communication.
- [Disroot](https://disroot.org/) - Disroot is a platform providing online services based on principles of freedom, privacy, federation and decentralization.

## Steganography

- [DissidentX](https://github.com/moxie0/DissidentX) - DissidentX is encoding messages in files on the web.
- Real Steganography with TrueCrypt (applies to VeraCrypt as well) - hiding containers inside MP4 video files.
- [PixelKnot](https://guardianproject.info/apps/org.mrpdog.pixelknot/) - image steganography for Android.

## Misc

- [cachebrowser](https://github.com/CacheBrowser/cachebrowser) - CacheBrowser is a system designed to help Internet users bypass Internet censorship by grabbing censored content cached by CDNs.
- [rubberhose](https://en.wikipedia.org/wiki/Rubberhose_(file_system)) - Julian Assange's deniable-encryption filesystem.
- [OnionShare](https://onionshare.org/) - tool that lets you securely and anonymously share a file of any size (over TOR).

## Related awesome lists

- [awesome-vpn](https://github.com/dutchakdev/awesome-vpn) - A curated list of awesome free VPNs and proxies.
- [awesome-privacy](https://github.com/anondotli/awesome-privacy-tools) - Limiting personal data leaks on the internet
- [personal-security-checklist](https://github.com/Lissy93/personal-security-checklist) - A curated list of links and tips, to protect privacy and improve security

## Articles and research papers

- Analyzing China's Blocking of Unpublished Tor Bridges
- Learning more about the GFW's active probing system
- A closer look at the Great Firewall of China - Tor Blog
- How the Great Firewall of China is Blocking Tor
- Towards a Censorship Analyser for Tor
- stegotorus
- Format-Transforming Encryption
- ScrambleSuit
- My Experience With the Great Firewall of China - Infosec
- Selected Research Papers in Internet Censorship
- Course info - ECEN 5003: Censorship Circumvention
