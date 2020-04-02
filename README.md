# Awesome anti-censorship

> A curated list of open source tools and readings for fighting Internet censorship.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## Categories
- [Privacy and anonymity](#privacy-and-anonymity)
- [Network tunnels](#network-tunnels)
- [Firewall analysis](#firewall-analysis)
- [Decentralized systems](#decentralized-systems)
- [Steganography](#steganography)
- [Deniable encryption](#deniable-encryption)
- [Misc](#misc)
- [Related awesome lists](#related-awesome-lists)
- [Articles and research papers](#articles-and-research-papers)

### Privacy and anonymity
- [tor](https://www.torproject.org/about/overview.html.en) - The Tor network is a group of volunteer-operated servers that allows people to improve their privacy and security on the Internet. Tor's users employ this network by connecting through a series of virtual tunnels rather than making a direct connection
- [i2p](https://github.com/i2p/i2p.i2p) - I2P is an anonymizing network, offering a simple layer that identity-sensitive applications can use to securely communicate. All data is wrapped with several layers of encryption, and the network is both distributed and dynamic, with no trusted parties.
- [vuvuzela](https://github.com/vuvuzela/vuvuzela) - Vuvuzela is a messaging system that protects the privacy of message contents and message metadata. Users communicating through Vuvuzela do not reveal who they are talking to, even in the presence of powerful nation-state adversaries. 
- [whonix](https://github.com/Whonix/Whonix) - Whonix is an operating system focused on anonymity, privacy and security. It's based on the Tor anonymity network, Debian GNU/Linux and security by isolation. DNS leaks are impossible, and not even malware with root privileges can find out the user's real IP.  

### Network tunnels
- [shadowsocks](https://github.com/shadowsocks) - a fast socks5 proxy that encrypts traffic
- [v2ray](https://github.com/v2ray/v2ray-core) - A platform for building proxies to bypass network restrictions
- [obfsproxy](https://git.torproject.org/pluggable-transports/obfsproxy.git) - Tor framework for implementing pluggable transports (anti-censorship network tunnels)
- [obfsproxy with OpenVPN](https://community.openvpn.net/openvpn/wiki/TrafficObfuscation) - OpenVPN traffic obfuscation using obfsproxy 
- [flashproxy](https://crypto.stanford.edu/flashproxy/) -  miniature proxy that runs in a web browser, and reflects traffic to a Tor relay.
- [meek](https://trac.torproject.org/projects/tor/wiki/doc/meek) - Tor pluggable transport that uses HTTP for carrying bytes and TLS for obfuscation.
- [lantern](https://github.com/getlantern/lantern) - Lantern is a free desktop application that delivers fast, reliable and secure access to the open Internet for users in censored regions
- [algo](https://github.com/trailofbits/algo) - Set up a personal VPN in the cloud
- [MTProxy](https://github.com/TelegramMessenger/MTProxy) - Proxy server which helps telegram users who are inside censored areas still be able to connect to telegram
- [streisand](https://github.com/jlund/streisand) - single command set for a server running a wide variety of anti-censorship software
- [WireGuard](https://www.wireguard.com/) - WireGuard is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPSec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN.
- [tunsafe](https://tunsafe.com/about) - TunSafe is a fast and modern layer 3 VPN tunnel that implements the new and modern WireGuard protocol that is becoming increasingly popular in the VPN community due to its security, speed, reliability and ease of use. TunSafe was developed with the goal to bring the power of the WireGuard-protocol to all the Windows users around the world and in March 2018 the first version was released.
- [scramblesuit](http://www.cs.kau.se/philwint/scramblesuit/) - Tor pluggable transport that uses look-like-nothing traffic as a cover channel
- [FTE](https://github.com/kpdyer/fteproxy) - fteproxy provides transport-layer protection to resist keyword filtering, censorship and discriminatory routing policies
- [telex](https://github.com/ewust/telex) - involves placing anticensorship technology into the Internet's core network infrastructure, through cooperation from large ISPs. 
- [uproxy](https://github.com/uProxy) - uProxy is a browser extension that lets friends route their connection to their Internet through each other's computers. It can help people with restricted or insecure access to the Internet get to the content they care about safely.
- [NaïveProxy](https://github.com/klzgrad/naiveproxy) - NaïveProxy uses Chrome's network stack to camouflage traffic with stronger censorship resistence and less detectablility than custom-made network stacks (Shadowsocks and variants, V2Ray suite, handmade Golang stacks).
- [gost](https://github.com/ginuerzh/gost) - GO Simple Tunnel - a simple tunnel written in golang
- [obfs4](https://github.com/Yawning/obfs4) - the newest version of the Tor obfsproxy obfuscation proxy. implements multiple pluggable transports.
- [trojan](https://github.com/trojan-gfw/trojan) - An unidentifiable mechanism that helps you bypass GFW
- [govpn](http://git.cypherpunks.ru/cgit.cgi/govpn.git) - Simple secure VPN daemon, aimed to be reviewable, secure, DPI/censorship-resistant.
- [gohop](https://github.com/bigeagle/gohop) - A VPN implemention in golang, with crypto and obfuscation in nature.
- [Dust](https://github.com/blanu/Dust) - A Polymorphic Engine for Filtering-Resistant Transport Protocols
- [marionette](https://github.com/kpdyer/marionette/) - Marionette is a programmable client-server proxy that enables the user to control network traffic features with a lightweight domain-specific language.
- [facebook-tunnel](https://github.com/matiasinsaurralde/facebook-tunnel) Tunneling Internet traffic over FB chat.
- [chnroutes](https://github.com/fivesheep/chnroutes)- modifies the route table to route only censored ips through vpn
- [firefly-proxy](https://github.com/yinghuocho/firefly-proxy) - A proxy software to help circumventing the Great Firewall.
- [iodine](https://github.com/yarrick/iodine) - This is a piece of software that lets you tunnel IPv4 data through a DNS server. This can be usable in different situations where internet access is firewalled, but DNS queries are allowed.
- [obfuscated-openssh](https://github.com/brl/obfuscated-openssh) - Handshake obfuscation strengthens the initial SSH handshake against systems that identify or classify various network protocols by examining data in transit for static signatures.
- [infranet](http://sourceforge.net/projects/infranet/) - Infranet is a system that attempts to circumvent web censorship by allowing clients to surreptitiously request sensitive content via cooperating Web servers distributed across the global Internet.
- [fwlite](https://github.com/v3aqb/fwlite) - A powerful HTTP proxy server designed to circumvent the Great Firewall (GFW)
- [code-talker-tunnel](https://crysp.uwaterloo.ca/software/CodeTalkerTunnel.html) - Code Talker Tunnel (previously called SkypeMorph) is a protocol camouflaging tool, designed to reshape traffic output of any censorship circumvention tool to look like Skype video calls
- [stegotorus](https://sri-csl.github.io/stegotorus/) - StegoTorus, a tool that comprehensively disguises Tor from protocol analysis. To foil analysis of packet contents, Tor’s traffic is steganographed to resemble an innocuous cover protocol, such as HTTP.
- [go-packetflagon](https://github.com/BrassHornCommunications/go-packetflagon/) - A local HTTP application that serves customised Proxy Auto Configuration files for your browser to help bypass Internet censorship.

### Decentralized systems
- [ipfs](https://github.com/ipfs/ipfs) - IPFS is a global, versioned, peer-to-peer filesystem ([awesome list](https://github.com/ipfs/awesome-ipfs))
- [dat](https://github.com/datproject/dat) - a decentralized tool for distributing data ([awesome list](https://github.com/clkao/awesome-dat))
- [ZeroNet](https://github.com/HelloZeroNet/ZeroNet) - Decentralized websites using Bitcoin crypto and the BitTorrent network
- [sovereign](https://github.com/DemocracyEarth/sovereign) - Censorship resistant democracies.
- [tribler](https://github.com/Tribler/tribler) - Privacy enhanced BitTorrent client with P2P content discovery
- [AKASHA](https://akasha.world/) - next-generation social media network immune to censorship by design. It is built on top of Ethereum using Smart Contracts and IPFS
- [twister](https://github.com/miguelfreitas/twister-core) - twister is an experimental peer-to-peer microblogging software.
- [freenet](https://github.com/freenet) - Freenet is a peer-to-peer platform for censorship-resistant communication.

### Firewall analysis
- [ooni-probe](https://github.com/ooni/probe) - OONI Probe network measurement tool for detecting internet censorship https://ooni.io
- [mongol](https://github.com/mothran/mongol) - A simple python tool to pinpoint the IP addresses of machines working for the Great Firewall of China.
- [ChinaDNS](https://github.com/shadowsocks/ChinaDNS) - Protect yourself against DNS poisoning in China.
- [https://github.com/gfwlist/gfwlist](https://github.com/gfwlist/gfwlist) - Great Firewall of China ban list
- [gfw_whitelist](https://github.com/n0wa11/gfw_whitelist) - A Pac File of the Whitelisted Websites for the Great Firewall of China (GFW)
- [antizapret](https://github.com/AntiZapret/antizapret) - List of Russian government's IP addresses.
- [BlockCheck](https://github.com/ValdikSS/blockcheck) - A script that detects what kind of blocking (DNS, IP, DPI) your ISP is using (for Russia).
- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) - Passive Deep Packet Inspection blocker and Active DPI circumvention utility (for Windows)
- [DPITunnel](https://github.com/zhenyolka/DPITunnel) - DPI Tunnel is an application for Android that uses various techniques to bypass DPI (Deep Packet Inspection) systems, which are used to block some sites.

### Steganography
- [DissidentX](https://github.com/bramcohen/DissidentX) - DissidentX is encoding messages in files on the web.
- [Real Steganography with TrueCrypt](http://keyj.emphy.de/real-steganography-with-truecrypt/) (applies to VeraCrypt as well) - hiding containers inside MP4 video files.
- [PixelKnot](https://github.com/guardianproject/PixelKnot) - image steganography for Android.

### Misc 
- [cachebrowser](https://github.com/CacheBrowser/cachebrowser) - CacheBrowser is a system designed to help Internet users bypass Internet censorship. The core idea ofCacheBrowser is to grab censored content cached byContent Delivery Networks such asAkamai andCloudFlare directly from their CDN edge servers, therefore, foiling censors' DNS interference. 
- [rubberhose](https://github.com/sporkexec/rubberhose) - Julian Assange's deniable-encryption filesystem.
- [OnionShare](https://onionshare.org/) - tool that lets you securely and anonymously share a file of any size (over TOR).

### Related awesome lists
- [awesome-vpn](https://github.com/hugetiny/awesome-vpn) A curated list of awesome free VPNs and proxies.
- [awesome-privacy](https://github.com/KevinColemanInc/awesome-privacy) Limiting personal data leaks on the internet
- [personal-security-checklist](https://github.com/Lissy93/personal-security-checklist) A curated list of links and tips, to protect privacy and improve security

### Articles and research papers
- [Analyzing China's Blocking of Unpublished Tor Bridges](https://www.usenix.org/conference/foci18/presentation/dunna)
- [Learning more about the GFW's active probing system](https://blog.torproject.org/blog/learning-more-about-gfws-active-probing-system)
- [A closer look at the Great Firewall of China - Tor Blog](https://blog.torproject.org/blog/closer-look-great-firewall-china)
- [How the Great Firewall of China is Blocking Tor](https://www.usenix.org/system/files/conference/foci12/foci12-final2.pdf)
- [Towards a Censorship Analyser for Tor](http://www.cs.kau.se/philwint/pdf/foci2013.pdf)
- [stegotorus](http://freehaven.net/anonbib/cache/ccs2012-stegotorus.pdf)
- [Format-Transforming Encryption](https://kpdyer.com/publications/ccs2013-fte.pdf)
- [ScrambleSuit](http://arxiv.org/pdf/1305.3199.pdf)
- [My Experience With the Great Firewall of China - Infosec](http://blog.zorinaq.com/my-experience-with-the-great-firewall-of-china/)
- [Selected Research Papers in Internet Censorship](https://censorbib.nymity.ch/)
- [Course info - ECEN 5003: Censorship Circumvention](https://ericw.us/trow/ecen5003/)
