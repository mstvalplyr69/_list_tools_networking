<div class="cell small-12 thinblog wysiwyg-content">
				<p><em>Last updated July 9, 2024</em></p>
<blockquote><p><strong>Thank you</strong> to the many list contributors that added their favorite projects to <a href="https://www.linkedin.com/feed/update/urn:li:activity:7137864085341184001/" target="_blank" rel="noopener">this LinkedIn thread</a>. I had no idea how much joyful work I was creating for myself when I posted it.</p>
<p><img draggable="false" role="img" class="emoji" alt="🤔" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f914.svg"> Did we miss a project? <a href="https://packetpushers.net/fu/" target="_blank" rel="noopener">Tell us about it here</a>.</p></blockquote>
<h2>About This List</h2>
<p>This list of public, open source projects is provided as a service to the IT infrastructure community by Packet Pushers. The goal is to spread awareness of tools that might make your job easier.</p>
<p>Consider that these networking projects are all, to the best of my knowledge, open source &amp; free to use. That means three important things.</p>
<ol>
<li><strong>The project is open to you.</strong> Generally the code is found in a publicly accessible code repository such as GitHub or GitLab. If you understand the code, you can confirm that it’s safe, secure, and suitable for you to run. If you don’t understand the code, you can hope that others who do have reviewed the code and addressed flaws.</li>
<li><strong>The project is contributable by you.</strong> Open source projects tend to be started by individuals with an itch to scratch or problem to solve. When these projects become popular, they also become a time-consuming burden to their authors. Without community contributors, these projects become unsustainable and die. Seriously consider giving back. Writing documentation is as valuable a service as coding.</li>
<li><strong>The project is free for you to use, but might not be free for you to incorporate into your own for-profit projects.</strong> The licenses vary with these projects. Be careful to review the license associated with a project before re-using the code as part of your own unique project.</li>
</ol>
<h2>Not All Open Source Software Is The Same</h2>
<p>Open source networking projects exist for a variety of reasons. Those reasons could influence whether or not you want to use a given project, so it’s a good idea to know what’s going on with a project before you make it an important part of your network.</p>
<ol>
<li><strong>Vendor or business-backed projects.</strong> Some projects are backed by vendors or service providers who need the project to support their own networks or products. These folks will generally employ people to write code for the project. These projects might serve you well, but the first priority of the maintainers is meeting the needs of the businesses funding them. Probably not your needs.</li>
<li><strong>Projects as marketing tools.</strong> Other projects are marketing tools created by vendors to create awareness of a related product they want you to buy. That doesn’t mean there’s anything wrong with their project, but be aware of the project’s point of view. I have eliminated from this list vendor-driven projects of no particular use unless you’re in the vendor’s ecosystem.</li>
<li><strong>Open, community, and feature-limited projects.</strong> Yet other projects you’ll find here might be open or community editions with commercial variants that may not be free or open source. That means the author hopes to feed their families with their programming efforts using the freemium model. You have to feed your family too, which should give you pause to think. Even though the projects here won’t cost you money, nothing is free. Every line of code represented in this list cost someone something.</li>
<li><strong>Altruistic projects.</strong> Some projects exist for the betterment of the community with no strings attached. If you get a benefit from the project, you should let the maintainer know how you’re using it and express your appreciation. That would be cool of you.</li>
</ol>
<h2>How To Use This Open Source Networking List</h2>
<p>The list lacks a perfect heading for every project under a given category. Therefore, you should read category headings and the projects with an open mind, recognizing that a project might be capable of more than what the heading implies.</p>
<p>The Packet Pushers team has not personally tried all of these projects. A project’s inclusion here isn’t an endorsement or even a recommendation. Use your own discretion before using any of the software identified here.</p>
<p><em><strong>Attribution.</strong> Most project descriptions are quoted from the project’s website, code repo, documentation, or wiki, and might be edited for brevity.</em></p>
<h2 id="index">Open Source Networking Projects: Main Index</h2>
<p><a href="#daemons">BGP – Daemons</a><br>
<a href="#looking-glasses">BGP – Looking Glasses</a><br>
<a href="#rkpi">BGP – RKPI Tools</a><br>
<a href="#session">BGP – Session Monitoring &amp; Management</a><br>
<a href="#cloud">Cloud Native Networking</a><br>
<a href="#developer">Developer Tools</a><br>
<a href="#labbing">Labbing</a><br>
<a href="#automation">Management – Automation</a><br>
<a href="#configuration">Management – Configuration</a><br>
<a href="#dcim">Management – DCIM, IPAM, Network Source Of Truth</a><br>
<a href="#nms">Management – Network Management Systems</a><br>
<a href="#flow">Monitoring – Flow Collectors &amp; Generators</a><br>
<a href="#log">Monitoring – Log Management</a><br>
<a href="#observability">Monitoring – Observability</a><br>
<a href="#network-services">Network Services</a><br>
<a href="#os">Operating Systems</a><br>
<a href="#routing">Routing &amp; Overlay Platforms</a><br>
<a href="#ddos">Security – DDoS Mitigation</a><br>
<a href="#firewalls">Security – Firewalls &amp; Filtering</a><br>
<a href="#idp">Security – Intrusion Detection/Prevention</a><br>
<a href="#scanning">Security – Scanning</a><br>
<a href="#vpn">Security – VPN</a><br>
<a href="#cli">Tools – CLI Utilities</a><br>
<a href="#packet-capture">Tools – Packet Capture &amp; Analysis</a><br>
<a href="#traffic">Tools – Traffic Generators</a></p>
<hr>
<h3 id="daemons">BGP – Daemons</h3>
<p><b>ExaBGP</b><br>
<a href="https://github.com/Exa-Networks/exabgp" target="_blank" rel="noopener">https://github.com/Exa-Networks/exabgp</a><br>
ExaBGP was designed to be an easy to script BGP-based SDN application that doesn’t get in the way. Like every application, the software is not without fault but has seen large scale deployment.</p>
<p><b>GoBGP</b><br>
<a href="https://github.com/osrg/gobgp" target="_blank" rel="noopener">https://github.com/osrg/gobgp</a><br>
BGP implementation designed from scratch for modern environments and implemented in Go.</p>
<hr>
<h3 id="looking-glasses">BGP – Looking Glasses</h3>
<p><b>Alice-LG</b><br>
<a href="https://github.com/alice-lg/alice-lg" target="_blank" rel="noopener">https://github.com/alice-lg/alice-lg</a><br>
Alice-LG is a BGP looking glass which gets its data from external APIs. Currently Alice-LG supports the following APIs: birdwatcher API for BIRD and GoBGP.</p>
<p><b>Hyperglass</b><br>
<a href="https://github.com/thatmattlove/hyperglass" target="_blank" rel="noopener">https://github.com/thatmattlove/hyperglass</a><br>
Intended to make implementing a looking glass too easy not to do, with the lofty goal of improving the internet community at large by making looking glasses more common across autonomous systems of any size.</p>
<hr>
<h3 id="rkpi">BGP – RKPI Tools</h3>
<p><b>Routinator</b><br>
<a href="https://nlnetlabs.nl/projects/routing/routinator/" target="_blank" rel="noopener">https://nlnetlabs.nl/projects/routing/routinator/</a><br>
RPKI Relying Party software written in Rust. The application is designed to be secure and is greatly portable. It’s a lightweight implementation that can run effortlessly on almost any operating system using minimalist hardware.</p>
<p><b>RTRTR</b><br>
<a href="https://nlnetlabs.nl/projects/routing/rtrtr/" target="_blank" rel="noopener">https://nlnetlabs.nl/projects/routing/rtrtr/</a><br>
RPKI data proxy, designed to collect Validated ROA Payloads from one or more sources in multiple formats and dispatch it onwards. It provides the means to implement multiple distribution architectures for RPKI such as centralized RPKI validators that dispatch data to local caching RTR servers. For larger networks, RTRTR is an ideal companion to Routinator.</p>
<p><b>StayRTR</b><br>
<a href="https://github.com/bgp/stayrtr" target="_blank" rel="noopener">https://github.com/bgp/stayrtr</a><br>
RPKI-to-Router protocol (RFC 6810, RFC 8210, RFC 8210bis); based on GoRTR using Go.</p>
<hr>
<h3 id="session">BGP – Session Monitoring &amp; Management</h3>
<p><b>BGPAlerter</b><br>
<a href="https://github.com/nttgin/BGPalerter" target="_blank" rel="noopener">https://github.com/nttgin/BGPalerter</a><br>
Self-configuring BGP monitoring tool which allows you to monitor in real-time. You just run it. You don’t need to provide any data source or connect it to anything in your network since it connects to public repos. It can deliver alerts on files, email, Kafka, Slack, and more.</p>
<p><b>Peering Manager</b><br>
<a href="https://github.com/peering-manager/peering-manager" target="_blank" rel="noopener">https://github.com/peering-manager/peering-manager</a><br>
BGP session management tool. Initially conceived as a way to document Internet Exchanges points and peering sessions, its goal is now to provide a source of truth and configuration management for external BGP sessions of all kinds (transit, customers, peering, …).</p>
<hr>
<h3 id="cloud">Cloud Native Networking</h3>
<p><b>Calico</b><br>
<a href="https://www.tigera.io/tigera-products/calico/" target="_blank" rel="noopener">https://www.tigera.io/tigera-products/calico/</a><br>
Networking and security solution for containers, virtual machines, and native host-based workloads. It supports a broad range of platforms including Kubernetes, OpenShift, Docker EE, OpenStack, and bare metal services.</p>
<p><b>Cilium</b><br>
<a href="https://cilium.io/" target="_blank" rel="noopener">https://cilium.io/</a><br>
Cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary Kernel technology eBPF.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/tech-bytes/tb099-isovalent-brings-you-cilium-enterprise/" target="_blank" rel="noopener">BiB099: Isovalent Brings You Cilium Enterprise</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/full-stack-journey/full-stack-journey-061-linux-networking-and-observability-with-ebpf-and-cilium/" target="_blank" rel="noopener">FSJ061: Linux Networking And Observability With eBPF And Cilium</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c160-going-deep-into-cilium-service-mesh-with-ebpf/" target="_blank" rel="noopener">D2C160: Going Deep Into Cilium Service Mesh With eBPF</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/kubernetes-unpacked/ku022-kubernetes-networking-and-abstraction-with-cilium-and-ebpf/" target="_blank" rel="noopener">KU022: Kubernetes Networking And Abstraction With Cilium And eBPF</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/network-break/nb463-cisco-buys-ebpf-startup-for-cloud-native-networking-garter-forecasts-5-trillion-in-it-spending/" target="_blank" rel="noopener">NB463: Cisco Buys eBPF Startup For Cloud-Native Networking</a></li>
</ul>
<p><b>Envoy</b><br>
<a href="https://www.envoyproxy.io/" target="_blank" rel="noopener">https://www.envoyproxy.io/</a><br>
High performance C++ distributed proxy designed for single services and applications, as well as a communication bus and “universal data plane” designed for large microservice “service mesh” architectures.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/full-stack-journey/full-stack-journey-018-istio-envoy-service-meshes/" target="_blank" rel="noopener">FSJ018: Istio, Envoy &amp; Service Meshes</a></li>
</ul>
<p><b>Hubble</b><br>
<a href="https://github.com/cilium/hubble" target="_blank" rel="noopener">https://github.com/cilium/hubble</a><br>
Hubble is a fully distributed networking and security observability platform for cloud native workloads. It’s built on top of Cilium and eBPF to enable deep visibility into the communication and behavior of services as well as the networking infrastructure in a completely transparent manner.</p>
<p><b>Loxilb</b><br>
<a href="https://github.com/loxilb-io/loxilb" target="_blank" rel="noopener">https://github.com/loxilb-io/loxilb</a><br>
Cloud-native load-balancer based on GoLang/eBPF with the goal of achieving cross-compatibility across a wide range of on-prem, public-cloud, or hybrid K8s environments.</p>
<p><b>Metallb</b><br>
<a href="https://github.com/metallb/metallb" target="_blank" rel="noopener">https://github.com/metallb/metallb</a><br>
A load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols.</p>
<p><b>Multus-CNI</b><br>
<a href="https://github.com/k8snetworkplumbingwg/multus-cni" target="_blank" rel="noopener">https://github.com/k8snetworkplumbingwg/multus-cni</a><br>
Enables attaching multiple network interfaces to pods in Kubernetes.</p>
<hr>
<h3 id="developer">Developer Tools</h3>
<p><b>DPDK</b><br>
<a href="https://www.dpdk.org/" target="_blank" rel="noopener">https://www.dpdk.org/</a><br>
The most popular kit to accelerate packet processing on a wide variety of CPU architectures. Designed to run on x86, POWER, and ARM processors, DPDK is a set of libraries running mostly in Linux userland.</p>
<p><b>eBPF</b><br>
<a href="https://ebpf.io/" target="_blank" rel="noopener">https://ebpf.io/</a><br>
Technology with origins in the Linux kernel that can run sandboxed programs in a privileged context such as the operating system kernel. It’s used to safely and efficiently extend the capabilities of the kernel without requiring you to change kernel source code or load kernel modules.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn614-ebpf-cloud-native-networking-and-other-modern-networking-trends/" target="_blank" rel="noopener">HN614: eBPF, Cloud-Native Networking, And Other Modern Networking Trends</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c154-can-ebpf-replace-sidecar-proxies/" target="_blank" rel="noopener">D2C 154: Can eBPF Replace Sidecar Proxies?</a></li>
</ul>
<p><b>Gribi</b><br>
<a href="https://github.com/openconfig/gribi" target="_blank" rel="noopener">https://github.com/openconfig/gribi</a><br>
Defines an interface via which entries can be injected from an external client to a network element. The gRIBI interface is defined in the proto/service/gribi.proto — which defines a simple API for adding and removing routing entries. The RIB entries are described using a protobuf translated version of the OpenConfig AFT model.</p>
<p><b>gRPC</b><br>
<a href="http://www.grpc.io" target="_blank" rel="noopener">http://www.grpc.io</a><br>
Remote procedure call framework used commonly in network operating system communications. Carries messages related to programming the network device or telemetry data.</p>
<p><b>JSON</b><br>
<a href="https://www.json.org/json-en.html" target="_blank" rel="noopener">https://www.json.org/json-en.html</a><br>
Lightweight data-interchange format. It’s easy for humans to read and write. It’s easy for machines to parse and generate. JSON is built on two structures: a collection of name/value pairs and an ordered list of values.</p>
<p><b>Kne</b><br>
<a href="https://github.com/openconfig/kne" target="_blank" rel="noopener">https://github.com/openconfig/kne</a><br>
Kubernetes network emulation. Provide a standard “interface” so that vendors can produce a standard container implementation which can be used to build complex topologies. Primary use cases are test development and software development.</p>
<p><b>Libyang</b><br>
<a href="https://github.com/CESNET/libyang" target="_blank" rel="noopener">https://github.com/CESNET/libyang</a><br>
YANG data modeling language parser and toolkit written (and providing API) in C. The library is used e.g. in libnetconf2, Netopeer2, or sysrepo projects.</p>
<p><b>NETCONF</b><br>
<a href="https://www.rfc-editor.org/rfc/rfc6241" target="_blank" rel="noopener">https://www.rfc-editor.org/rfc/rfc6241</a><br>
RPC wrapped in XML for network device configuration.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/using-netconf-yang-to-configure-network-devices-and-why-it-does-not-replace-snmp/" target="_blank" rel="noopener">Using NETCONF + YANG To Configure Network Devices and Why It Does Not Replace SNMP</a></li>
</ul>
<p><b>Netmap</b><br>
<a href="https://github.com/luigirizzo/netmap" target="_blank" rel="noopener">https://github.com/luigirizzo/netmap</a><br>
Framework for very fast packet I/O from userspace. VALE is an equally fast in-kernel L2 software switch using the netmap API. Both are implemented as a single kernel module for FreeBSD and Linux. Netmap/VALE can handle tens of millions of packets per second, matching the speed of 10G and 40G ports even with minimum sized frames.</p>
<p><b>Netopeer</b><br>
<a href="https://github.com/CESNET/netopeer" target="_blank" rel="noopener">https://github.com/CESNET/netopeer</a><br>
Set of NETCONF tools built on the libnetconf library. It allows operators to connect to their NETCONF-enabled devices as well as developers to allow control of their devices via NETCONF.</p>
<p><b>Netutils</b><br>
<a href="https://github.com/networktocode/netutils" target="_blank" rel="noopener">https://github.com/networktocode/netutils</a><br>
Python library that’s a collection of functions that are used in the common network automation tasks. Tasks such as converting a BGP ASN to and from dotted format, normalizing an interface name, or “type 5” encrypting a password. The intention is to centralize these functions while keeping the library light.</p>
<p><b>OpenBCM</b><br>
<a href="https://github.com/Broadcom-Network-Switching-Software/OpenBCM" target="_blank" rel="noopener">https://github.com/Broadcom-Network-Switching-Software/OpenBCM</a><br>
Contains the source code for Broadcom network switch APIs and drivers for programming Broadcom network switch silicon based platforms. Support for XGS switch devices such as Trident (TD2, TD3, TD4), Tomahawk (TH, TH2, TH3) and DNX devices such as Ramon, Qumran (Q2A, Q2U), and Jericho (JR2, J2C).</p>
<p><b>OpenConfig</b><br>
<a href="https://www.openconfig.net/" target="_blank" rel="noopener">https://www.openconfig.net/</a><br>
Defines and implements a common, vendor-independent software layer for managing network devices. OpenConfig operates as an open source project with contributions from network operators, equipment vendors, and the wider community.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/openconfig-standardized-models-networking/" target="_blank" rel="noopener">OpenConfig: Standardized Models For Networking</a></li>
</ul>
<p><b>OpenFlow</b><br>
<a href="https://www.opennetworking.org/ja/sdn-resources-ja/onf-specifications/openflow" target="_blank" rel="noopener">https://www.opennetworking.org/ja/sdn-resources-ja/onf-specifications/openflow</a><br>
A means of programming the forwarding table of a network device over the network. While OpenFlow might still have production use cases, it’s noted here primarily as a historical artifact. OpenFlow was an important part of early software defined networking (SDN) discussions.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn076-why-openflow-has-mind-melting-potential/" target="_blank" rel="noopener">HN076: Why OpenFlow Has Mind-Melting Potential</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn231-openflows-possible-futures-with-curt-beckmann/" target="_blank" rel="noopener">HN231: OpenFlow’s Possible Futures with Curt Beckmann</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn340-openflow-fabrics-network-virtualization/" target="_blank" rel="noopener">HN340: OpenFlow, Fabrics &amp; Network Virtualization</a></li>
</ul>
<p><strong>OpenZiti</strong><br>
<a href="https://openziti.io/">https://openziti.io/</a><br>
OpenZiti is a secure networking platform that allows you to build a zero trust overlay network right into your application. Any sort of network topology is possible. SDKs are available for C, Go, Python, Swift, Android, Java, Node JS, and C# (.NET).</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c142-openziti-serves-up-zero-trust-for-applications-sponsored/">Day Two Cloud 142: OpenZiti Serves Up Zero Trust For Applications (Sponsored)</a></li>
</ul>
<p><strong>QUIC Implementations List<br>
</strong><a href="https://github.com/quicwg/base-drafts/wiki/Implementations">https://github.com/quicwg/base-drafts/wiki/Implementations</a><br>
Maintained by the IETF QUIC working group co-chair Lucas Pardue, this list documents several implementations of the QUIC protocol as well as HTTP/3. The list might not be completely current. Not all implementations listed are open source.</p>
<p><b>Vagrant</b><br>
<a href="https://www.vagrantup.com/" target="_blank" rel="noopener">https://www.vagrantup.com/</a><br>
Enables the creation and configuration of lightweight, reproducible, and portable development environments.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/ansible-development-vagrant/" target="_blank" rel="noopener">Ansible Rapid Development Environment using Vagrant</a></li>
</ul>
<p><b>VPP</b><br>
<a href="https://github.com/FDio/vpp" target="_blank" rel="noopener">https://github.com/FDio/vpp</a><br>
Vector Packet Processing platform is an extensible framework that provides out-of-the-box production quality switch/router functionality. It’s the open source version of Cisco’s VPP technology: a high performance, packet-processing stack that can run on commodity CPUs.</p>
<p><strong>vSSH</strong><br>
<a href="https://github.com/yahoo/vssh">https://github.com/yahoo/vssh</a><br>
Go library to handle tens of thousands SSH connections and execute the command(s) with higher-level API for building network device / server automation. Documentation and examples are available via <a href="https://godoc.org/github.com/yahoo/vssh">godoc</a>.</p>
<p><b>XDP</b><br>
<a href="https://www.iovisor.org/technology/xdp" target="_blank" rel="noopener">https://www.iovisor.org/technology/xdp</a><br>
eXpress Data Path provides a high performance, programmable network data path in the Linux kernel as part of the IO Visor Project. XDP provides bare metal packet processing at the lowest point in the software stack which makes it ideal for speed without compromising programmability.</p>
<hr>
<h3 id="labbing">Labbing</h3>
<p><b>BGPLabs</b><br>
<a href="https://bgplabs.net" target="_blank" rel="noopener">https://bgplabs.net</a><br>
This series of BGP hands-on labs by Ivan Pepelnjak will help you master numerous aspects of EBGP, IBGP, and BGP routing policy configuration on a platform of your choice. More than a dozen labs are already waiting for you.</p>
<p><strong>Clabernetes<br>
</strong><a href="https://containerlab.dev/manual/clabernetes/">https://containerlab.dev/manual/clabernetes/</a><br>
A companion tool for Containerlab. Clabernetes deploys Containerlab topologies into a kubernetes cluster. The goal of Clabernetes is to scale Containerlab beyond a single node while keeping the user experience you love. If all goes to plan, Clabernetes is going to be one of the solutions to enable multi-node labs and allow its users to create large topologies powered by a k8s cluster.</p>
<p><b>Containerlab</b><br>
<a href="https://containerlab.dev/" target="_blank" rel="noopener">https://containerlab.dev/</a><br>
Provides a CLI for orchestrating and managing container-based networking labs. It starts the containers, builds a virtual wiring between them to create lab topologies of users choice and manages labs lifecycle.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/tech-bytes/tb-containerlab-makes-container-and-vm-networking-labs-easy-sponsored/" target="_blank" rel="noopener">Tech Bytes: Containerlab Makes Container And VM Networking Labs Easy</a></li>
</ul>
<p><b>EVE-NG Community Edition</b><br>
<a href="https://www.eve-ng.net/index.php/download/#DL-COMM" target="_blank" rel="noopener">https://www.eve-ng.net/index.php/download/#DL-COMM</a><br>
First clientless multi-vendor network emulation software that empowers network and security professionals with huge opportunities in the networking world.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn661-home-labbing-with-eve-ng-and-juniper/" target="_blank" rel="noopener">HN661: Home Labbing With EVE-NG And Juniper</a></li>
</ul>
<p><b>GNS3</b><br>
<a href="https://www.gns3.com/" target="_blank" rel="noopener">https://www.gns3.com/</a><br>
Build, design, and test your network in a risk-free virtual environment and access the largest networking community to help. Whether you’re studying for your first networking exam or building out a state-wide telecommunications network, GNS3 offers an easy way to design and build networks of any size without the need for hardware.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn556-the-state-of-gns3-for-network-labs/" target="_blank" rel="noopener">HN556: The State Of GNS3 For Network Labs</a></li>
</ul>
<p><b>Mininet</b><br>
<a href="https://mininet.org/" target="_blank" rel="noopener">https://mininet.org/</a><br>
Creates a realistic virtual network, running real kernel, switch, and application code, on a single machine (VM, cloud or native), in seconds, with a single command. Because you can easily interact with your network using the Mininet CLI (and API), customize it, share it with others, or deploy it on real hardware, Mininet is useful for development, teaching, and research. Mininet is also a great way to develop, share, and experiment with SDN systems using OpenFlow and P4.</p>
<p><b>Netlab</b><br>
<a href="https://netlab.tools" target="_blank" rel="noopener">https://netlab.tools</a><br>
Ivan Pepelnjak’s network lab orchestrator for people who are weary of clicky-clicky. Use YAML to define a lab environment including device links, routing protocols, IP addressing, and more and then say “netlab up”.</p>
<p><b>NRX</b><br>
<a href="https://github.com/netreplica/nrx" target="_blank" rel="noopener">https://github.com/netreplica/nrx</a><br>
Reads a network topology graph from NetBox DCIM system and exports as Containerlab, Cisco Modeling Labs, Graphite, D2, Cytoscape CYJS, or other format defined by a Jinja2 template.</p>
<hr>
<h3 id="automation">Management – Automation</h3>
<p><b>Ansible</b><br>
<a href="https://www.ansible.com/" target="_blank" rel="noopener">https://www.ansible.com/</a><br>
IT automation system. It handles configuration management, application deployment, cloud provisioning, ad-hoc task execution, network automation, and multi-node orchestration.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn198-kirk-byers-network-automation-python-ansible/" target="_blank" rel="noopener">HN198: Kirk Byers on Network Automation with Python &amp; Ansible</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c064-bringing-ansible-into-a-windows-shop/" target="_blank" rel="noopener">D2C064: Bringing Ansible Into A Windows Shop</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn537-ansible-vs-terraform-for-network-automation/" target="_blank" rel="noopener">HN537: Ansible Vs. Terraform For Network Automation</a></li>
<li><img draggable="false" role="img" class="emoji" alt="📺" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f4fa.svg">️ <a href="https://www.youtube.com/watch?v=99j9UbNP7LY&amp;list=PLtO_OYBiEo6lW_LO-ucRuz7Z8_DJ62NAM" target="_blank" rel="noopener">Ansible For Network Automation Video Tutorial Series</a></li>
</ul>
<p><strong>Arista AVD<br>
</strong><a href="https://avd.arista.com/stable/index.html">https://avd.arista.com/stable/index.html</a><br>
The Arista team pointed out that the Arista Validated Designs would be a good fit for this list. They stated that the while the AVD project focuses on automating Arista-based networks, the project structure allows the framework to be extended to support other vendors. How? Arista builds network configurations based on open standards and their network wide models (eos_designs) generates a machine-readable structured configuration. This allows eos_cli_config_gen to be replaced with some_other_vendor_config_gen role to generate other vendor configurations. What’s more, this has been done in real life. Lots of documentation explaining how to use AVD with Python and Ansible.</p>
<p><b>Awesome Network Automation list</b><br>
<a href="https://github.com/networktocode/awesome-network-automation" target="_blank" rel="noopener">https://github.com/networktocode/awesome-network-automation</a><br>
Network automation is a cross between the discipline of network infrastructure and the discipline of programming. This list was created to serve as a one-stop shop for information related to network automation.</p>
<p><b>AWX</b><br>
<a href="https://github.com/ansible/awx" target="_blank" rel="noopener">https://github.com/ansible/awx</a><br>
Provides a web-based user interface, REST API, and task engine built on top of Ansible. It’s one of the upstream projects for Red Hat Ansible Automation Platform.</p>
<p><strong>eNMS</strong><br>
<a href="https://www.enms.io/">https://www.enms.io/</a><br>
A vendor-agnostic Network Management System (NMS) designed for building workflow-based network automation solutions. eNMS simplifies interaction with a wide variety of network device types for automating complex operations like network audits or upgrades without worrying about the details of communication with each device. eNMS developers focus on the data not the communication.</p>
<p><b>Jinja</b><br>
<a href="https://jinja.palletsprojects.com/en/3.1.x/" target="_blank" rel="noopener">https://jinja.palletsprojects.com/en/3.1.x/</a><br>
Fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.</p>
<p><strong>Kubenet<br>
</strong><a href="https://learn.kubenet.dev/">https://learn.kubenet.dev/</a><br>
A Nokia-backed project. The Kubenet community has been created with the goal to help network engineers understand the potential of kubernetes for network automation. While we discuss networking, we are NOT talking about CNI(s) here, but about using kubernetes as an automation/orchestration engine to manage physical, virtual or containerized NOS(s). The question to ask here is why is the networking industry not leveraging kubernetes for network automation. The Kubenet community is setup with to goal to help understand networking engineers the potential of kubernetes for network automation.</p>
<p><b>Netmiko</b><br>
<a href="https://github.com/ktbyers/netmiko" target="_blank" rel="noopener">https://github.com/ktbyers/netmiko</a><br>
Network automation to screen-scraping devices is primarily concerned with gathering output from show commands and with making configuration changes. Netmiko aims to accomplish both of these operations and to do it across a very broad set of platforms. It seeks to do this while abstracting away low-level state control (i.e., eliminate low-level regex pattern matching to the extent practical).</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn270-design-build-9-automation-python-netmiko/" target="_blank" rel="noopener">HN270: Design &amp; Build 9: Automation With Python And Netmiko</a></li>
</ul>
<p><strong>Net Schema</strong><br>
<a href="https://github.com/packetcoders/net-schema">https://github.com/packetcoders/net-schema</a><br>
Net Schema is a library that validates JSON and YAML documents against a defined schema, utilizing JSON Schema. This ensures that data adheres to specified formats and rules. Additionally, this project is designed for schema validation of network-specific data, providing a range of network-related custom validators.</p>
<p><strong>Network Unit Testing System (NUTS)<br>
</strong><a href="https://github.com/network-unit-testing-system/nuts">https://github.com/network-unit-testing-system/nuts</a><br>
The Network Unit Testing System or “nuts” in short draws on the concept of unit tests, known from the domain of programming, and applies it to the domain of networking. In the network testing domain, tests are less about edge cases, but more about testing existing network states with pre-defined test cases. Such a single test case might be “can host A reach neighbors X, Y, Z?” on many different devices. This is what nuts tries to achieve: Apply test cases based on your pre-defined network topology to your actual network and have the tests confirm the correct state.</p>
<p><b>Nornir</b><br>
<a href="https://github.com/nornir-automation/nornir" target="_blank" rel="noopener">https://github.com/nornir-automation/nornir</a><br>
A pure Python automation framework intended to be used directly from Python. While most automation frameworks use their own Domain Specific Language (DSL) which you use to describe what you want to have done, Nornir lets you control everything from Python. See also <a href="https://github.com/nornir-automation/gornir">Gornir</a>.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn445-an-introduction-to-the-nornir-automation-framework/" target="_blank" rel="noopener">HN445: An Introduction To The Nornir Automation Framework</a></li>
<li><img draggable="false" role="img" class="emoji" alt="📺" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f4fa.svg">️ <a href="https://youtu.be/yWG8DuXrG1M" target="_blank" rel="noopener">Practical Python For Networking: 3.1 – Detection With Nornir</a></li>
</ul>
<p><strong>Orchestrator-Core</strong><br>
<a href="https://workfloworchestrator.org/orchestrator-core/">https://workfloworchestrator.org/orchestrator-core/</a><br>
Provides a framework through which you can manage service orchestration for your end users. It enables you to define products to which users can subscribe, and helps you intelligently manage the lifecycle of Creation, Modification, Termination and Validation of a customer subscription.</p>
<p><b>Pydantic</b><br>
<a href="https://docs.pydantic.dev/latest/" target="_blank" rel="noopener">https://docs.pydantic.dev/latest/</a><br>
The most widely used data validation library for Python. Fast and extensible, Pydantic plays nicely with your linters/IDE/brain. Define how data should be in pure, canonical Python 3.8+; validate it with Pydantic.</p>
<p><b>Scrapli</b><br>
<a href="https://carlmontanari.github.io/scrapli/" target="_blank" rel="noopener">https://carlmontanari.github.io/scrapli/</a><br>
Python library focused on connecting to devices, specifically network devices (routers, switches, firewalls, etc.) via SSH or Telnet. The name scrapli is just “scrape cli” (as in screen scrape) squished together! See also <a href="https://github.com/scrapli/scrapligo">scapligo</a>.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn532-scrapli-is-a-netmiko-alternative/" target="_blank" rel="noopener">HN532: Scrapli Is A Netmiko Alternative</a></li>
</ul>
<p><b>Terraform</b><br>
<a href="https://www.terraform.io/use-cases/manage-network-infrastructure" target="_blank" rel="noopener">https://www.terraform.io/use-cases/manage-network-infrastructure</a><br>
<a href="https://github.com/hashicorp/terraform" target="_blank" rel="noopener">https://github.com/hashicorp/terraform</a><br>
IT automation system. Build, change, and version infrastructure safely and efficiently. It’s notable that Hashicorp, the company behind Terraform, changed Terraform’s licensing in mid-2023 such that another project can’t use Terraform source code to make a competing product. This caused outrage for some in the TF community, with purists insisting that Terraform is no longer truly open source. The main result of this outrage was <a href="https://opentofu.org/">the OpenTofu project</a>, a fork of Terraform that’s part of the Linux Foundation and backed by many commercial interests. If open source licensing distinctions are important to you or your company, pay careful attention to Terraform’s licensing.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/full-stack-journey/full-stack-journey-027-understanding-infrastructure-as-code-and-terraform-with-curt-micol/" target="_blank" rel="noopener">FSJ027: Understanding Infrastructure As Code And Terraform With Curt Micol</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn537-ansible-vs-terraform-for-network-automation/" target="_blank" rel="noopener">HN537: Ansible Vs. Terraform For Network Automation</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/kubernetes-unpacked/ku004-pros-and-cons-of-using-terraform-with-kubernetes/" target="_blank" rel="noopener">KU004: Pros And Cons Of Using Terraform With Kubernetes</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c155-terraform-stinks/" target="_blank" rel="noopener">D2C 155: Terraform Stinks</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c202-how-azure-embraces-terraform-for-infrastructure-as-code/" target="_blank" rel="noopener">D2C202: How Azure Embraces Terraform For Infrastructure As Code</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn711-get-cloud-like-operation-of-your-data-center-with-juniper-apstra-and-terraform-sponsored/" target="_blank" rel="noopener">HN711: Get Cloud-Like Operation Of Your Data Center With Juniper Apstra And Terraform</a></li>
</ul>
<hr>
<h3 id="configuration">Management – Configuration</h3>
<p><b>Aerleon</b><br>
<a href="https://github.com/aerleon/aerleon" target="_blank" rel="noopener">https://github.com/aerleon/aerleon</a><br>
Generate firewall configs for multiple firewall platforms from a single platform-agnostic configuration language through a command line tool and Python API. Aerleon is a fork of Capirca.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/startup-radar-invariant-combines-batfish-aerleon-to-model-and-test-network-changes/" target="_blank" rel="noopener">Startup Radar: Invariant Combines Batfish, Aerleon To Model And Test Network Changes</a></li>
</ul>
<p><b>Batfish</b><br>
<a href="https://www.batfish.org/" target="_blank" rel="noopener">https://www.batfish.org/</a><br>
Network configuration analysis tool. Batfish finds errors and guarantees the correctness of planned or current network configurations. It enables safe and rapid network evolution, without the fear of outages or security breaches.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn658-using-batfish-to-model-and-test-your-network/" target="_blank" rel="noopener">HN658: Using Batfish To Model And Test Your Network</a></li>
</ul>
<p><b>Netshot</b><br>
<a href="https://www.netfishers.onl/netshot" target="_blank" rel="noopener">https://www.netfishers.onl/netshot</a><br>
Netshot is a network device manager for configuration and compliance management. Many of the most used network devices in the world are supported out-of-the-box and you can easily add your own drivers — this is a simple script file to write. Netshot is available through a web application GUI.</p>
<p><strong>Network Configuration Backup</strong><br>
<a href="https://github.com/jeremyschulman/netcfgbu">https://github.com/jeremyschulman/netcfgbu</a><br>
As a network engineer I need to backup my network configuration files into a version control system, and I need a tool to automate this process. My primary means of accessing the devices is SSH. The netcfgbu tool was built specifically to backup network operating system (NOS) configurations that are monolithic in nature. That is to say the entire configuration can be captured using a command such as “show running-config”. Any NOS that provides a monolithic configuration should be supported by netcfgbu.</p>
<p><strong>Open-AudIT</strong><br>
<a href="https://github.com/Opmantek/open-audit">https://github.com/Opmantek/open-audit</a><br>
Open-AudIT is an application to tell you exactly what is on your network, how it is configured and when it changes. Open-AudIT will run on Windows and Linux systems. Open-AudIT is a database of information, that can be queried via a web interface and JSON API. Data about the network is inserted using audit scripts (shell, vbscript) as well as Nmap and SNMP results.</p>
<p><b>Oxidized</b><br>
<a href="https://github.com/ytti/oxidized" target="_blank" rel="noopener">https://github.com/ytti/oxidized</a><br>
Oxidized is a network device configuration backup tool. It’s a RANCID replacement! It’s light and extensible and supports over 130 operating system types.</p>
<p><b>rConfig Community Edition</b><br>
<a href="https://github.com/rconfig" target="_blank" rel="noopener">https://github.com/rconfig</a><br>
An enterprise grade network configuration management (NCM) software package with superior NCM features and capabilities to help you easily manage configurations on large and small heterogenous networks.</p>
<hr>
<h3 id="dcim">Management – DCIM, IPAM, Network Source Of Truth</h3>
<p><strong>Infrahub<br>
</strong><a href="https://github.com/opsmill/infrahub">https://github.com/opsmill/infrahub</a><strong><br>
</strong>Infrahub by OpsMill is a source of truth combined with version control and several other features important to people automating their infrastructure. In their own words, “Infrahub offers a central hub to manage the data, templates and playbooks that powers your infrastructure by combining the version control and branch management capabilities of Git with the flexible data model and UI of a graph database.” Infrahub documentation lives <a href="https://docs.infrahub.app/">here</a>.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://www.linkedin.com/posts/ethanbanks_autocon1-autocon1-activity-7202267980011876353-Vem8">OpsMill Infrahub launch announcement coverage from AutoCon1 (LinkedIn)</a></li>
</ul>
<p><b>Nautobot</b><br>
<a href="https://networktocode.com/nautobot/" target="_blank" rel="noopener">https://networktocode.com/nautobot/</a><br>
A network source of truth that’s the foundation required for successful enterprise network automation. A fork of NetBox.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn610-network-automation-with-nautobot/" target="_blank" rel="noopener">HN610: Network Automation With Nautobot</a></li>
</ul>
<p><b>NetBox</b><br>
<a href="https://netboxlabs.com/open-source-netbox/" target="_blank" rel="noopener">https://netboxlabs.com/open-source-netbox/</a><br>
The source of truth for everything on your network, from physical components like power systems and cabling to virtual assets like IP addresses and VLANs. Network automation and observability tools depend on NetBox’s authoritative data to roll out configurations, monitor changes, and accelerate operations across the enterprise.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn452-using-netbox-as-a-source-of-networking-truth/" target="_blank" rel="noopener">HN452: Using NetBox As A Source Of Networking Truth</a></li>
</ul>
<p><b>phpIPAM</b><br>
<a href="https://phpipam.net/" target="_blank" rel="noopener">https://phpipam.net/</a><br>
Web IP address management application (IPAM). Its goal is to provide light, modern, and useful IP address management. It’s a PHP-based application with MySQL database backend, using jQuery libraries, ajax, and HTML5/CSS3 features.</p>
<hr>
<h3 id="nms">Management – Network Management Systems</h3>
<p><b>LibreNMS</b><br>
<a href="https://www.librenms.org/" target="_blank" rel="noopener">https://www.librenms.org/</a><br>
Fully featured network monitoring system that provides a wealth of features and device support. A fork of the Observium project.</p>
<p><strong>NeDi<br>
</strong><a href="https://www.nedi.ch/">https://www.nedi.ch/</a><strong><br>
</strong>NeDi discovers your network devices and tracks connected end-nodes. It contains many additional features for managing enterprise networks including intelligent topology awareness, MAC address mapping/tracking, traffic, error, discard and broadcast graphing with threshold based alerting, uptime, BGP peer and interface status monitoring, correlate syslog messages and traps with discovery events, network maps for documentation and monitoring dashboards, detecting rouge access points and finding missing devices, and extensive reporting ranging from devices, modules, interfaces all the way to assets and nodes.</p>
<p><b>Netdisco</b><br>
<a href="https://netdisco.org" target="_blank" rel="noopener">https://netdisco.org</a><br>
Web-based network management tool suitable for small to very large networks. IP and MAC address data is collected into a PostgreSQL database using SNMP, CLI, or device APIs.</p>
<p><strong>NMISv9<br>
</strong><a href="https://github.com/Opmantek/nmis9">https://github.com/Opmantek/nmis9</a></p>
<p dir="auto">NMIS is an Open Source Network Management System which performs multiple functions from the OSI Network Management Functional Areas. NMIS has evolved rapidly to meet the demands of highly available production environments and user demands. The distributed polling engine uses SNMP to collect availability and performance data for any SNMP capable device. A highly configurable and extensible GUI displays health and performance data focused on technical information, as well as high level reporting for executive reports. NMIS has been developed continually since 1998 and remains open source. Version 9 represents the most recent major generational upgrade.</p>
<p><b>Observium Community</b><br>
<a href="https://www.observium.org/" target="_blank" rel="noopener">https://www.observium.org/</a><br>
Network monitoring and management platform that provides real-time insight into network health and performance. It can automatically discover network devices and services, collect performance metrics, and generate alerts when problems are detected. Observium includes a web UI.</p>
<p><b>OpenWisp</b><br>
<a href="https://openwisp.org/" target="_blank" rel="noopener">https://openwisp.org/</a><br>
Modular network management system built on top of OpenWRT (but designed to allow supporting multiple embedded operating systems) that allows managing and automating several aspects of IT network deployment, monitoring, and management.</p>
<p><strong>Zabbix</strong><br>
<a href="https://www.zabbix.com/network_monitoring">https://www.zabbix.com/network_monitoring</a><br>
Keep track of your network’s health and performance. Collect SNMP metrics or deploy a Zabbix agent to monitor a variety of network metrics. Apply the appropriate template on your network monitoring endpoint and start collecting network metrics, including incoming and outgoing traffic, total bandwidth usage, packet loss and interface error rates, number of TCP connections, link status, and interface speed and status. Supports SNMP versions v1, v2c, and v3 and SNMP trap collection, enabling compatibility with legacy and modern devices.</p>
<hr>
<h3 id="flow">Monitoring – Flow Collectors &amp; Generators</h3>
<p><b>Akvorado</b><br>
<a href="https://github.com/akvorado/akvorado" target="_blank" rel="noopener">https://github.com/akvorado/akvorado</a><br>
Receives flows (currently Netflow/IPFIX and sFlow), enriches them with interface names (using SNMP), geo information (using IPinfo.io), and exports them to Kafka, then ClickHouse. It also exposes a web interface to browse the collected data.</p>
<p><b>GoFlow2</b><br>
<a href="https://github.com/netsampler/goflow2" target="_blank" rel="noopener">https://github.com/netsampler/goflow2</a><br>
NetFlow, IPFIX, sFlow collector in Go. It gathers network information (IP, interfaces, routers) from different flow protocols, serializes it in a common format. This software is the entry point of a pipeline. The storage, transport, enrichment, graphing, alerting are not provided. A fork of CloudFlare’s GoFlow project.</p>
<p><b>Host sFlow</b><br>
<a href="https://sflow.net/" target="_blank" rel="noopener">https://sflow.net/</a><br>
Exports physical and virtual server performance metrics using the sFlow protocol. The agent provides scalable, multi-vendor, multi-OS performance monitoring with minimal impact on the systems being monitored.</p>
<p><b>Pmacct</b><br>
<a href="https://github.com/pmacct/pmacct" target="_blank" rel="noopener">https://github.com/pmacct/pmacct</a><br>
Collect, replicate, and export network information. On the data plane it can cache in memory tables, store persistently to RDBMS, noSQL databases and flat-files, publish to AMQP and Kafka brokers. Export sFlowv5, NetFlow v5/v9 and IPFIX. Perform data aggregation. It can also filter, sample, renormalize, tag, and classify at L7. On the control and infrastructure planes it can collect and publish to AMQP and Kafka brokers BGP, BMP, RPKI, and streaming telemetry data both standalone and as correlation/enrichment of data plane information.</p>
<hr>
<h3 id="log">Monitoring – Log Management</h3>
<p><b>Fluentd</b><br>
<a href="https://www.fluentd.org/" target="_blank" rel="noopener">https://www.fluentd.org/</a><br>
Data collector that lets you unify the data collection and consumption for a better use and understanding of data. Normalize and filter inbound logs and ship them out.</p>
<p><b>Graylog Open</b><br>
<a href="https://graylog.org/products/source-available/" target="_blank" rel="noopener">https://graylog.org/products/source-available/</a><br>
Provides the core centralized log management functionality you need to collect, enhance, store, and analyze data. Support is through Graylog’s online resources, community, and other Open groups.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn192-logging-design-best-practices/" target="_blank" rel="noopener">HN192: Logging Design &amp; Best Practices</a></li>
</ul>
<hr>
<h3 id="observability">Monitoring – Observability</h3>
<p><b><strong>Checkmk Raw Edition</strong><br>
</b><a href="https://checkmk.com/product/raw-edition">https://checkmk.com/product/raw-edition</a><br>
Monitoring for enterprises and power-users, offering extensibility, flexibility and adaptability without hassle or cumbersome configuration. The Checkmk team recommends Checkmk Raw Edition for small enterprises or hobbyists running a home lab.<b></b></p>
<p><strong>Grafana</strong><br>
<a href="https://grafana.com/oss/grafana/" target="_blank" rel="noopener">https://grafana.com/oss/grafana/</a><br>
Easily collect, correlate, and visualize data with beautiful dashboards. Data visualization and monitoring solution that drives informed decisions, enhances system performance, and streamlines troubleshooting.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/day-two-cloud/d2c057-see-your-data-with-grafana/" target="_blank" rel="noopener">D2C057: See Your Data With Grafana</a></li>
</ul>
<p><strong>ntopng Community Edition</strong><br>
<a href="https://github.com/ntop/ntopng">https://github.com/ntop/ntopng</a><br>
ntopng® is a web-based network traffic monitoring application released under GPLv3. It is the new incarnation of the original ntop written in 1998, and now revamped in terms of performance, usability, and features.</p>
<p><b>SuzieQ</b><br>
<a href="https://github.com/netenglabs/suzieq" target="_blank" rel="noopener">https://github.com/netenglabs/suzieq</a><br>
The first open source, multi-vendor network observability platform application. It’s both a framework and an application using that framework that’s focused on improving your understanding of your network.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn719-meet-suzieq-the-network-observability-application/" target="_blank" rel="noopener">HN719: Meet SuzieQ, The Network Observability Application</a></li>
</ul>
<hr>
<h3 id="network-services">Network Services</h3>
<p><b>Bind (DNS)</b><br>
<a href="https://www.isc.org/bind/" target="_blank" rel="noopener">https://www.isc.org/bind/</a><br>
Very flexible, full-featured DNS system. Whatever your application is, BIND 9 probably has the required features. As the first, oldest, and most commonly deployed solution, there are more network engineers who are already familiar with BIND 9 than with any other system.</p>
<p><b>Kea (DHCP)</b><br>
<a href="https://www.isc.org/kea/" target="_blank" rel="noopener">https://www.isc.org/kea/</a><br>
ISC distributes TWO full-featured, open source, standards-based DHCP server distributions: Kea DHCP and ISC DHCP. Kea includes all the most-requested features, is far newer, and is designed for a more modern network environment.</p>
<p><strong>LibreQoS</strong><br>
<a href="https://libreqos.io/">https://libreqos.io/</a><br>
Quality of Experience (QoE) platform that helps Internet Service Providers (ISPs) enhance their customers’ internet connections. It leverages state of the art Flow Queueing (FQ) and Active Queue Management (AQM) algorithms to manage latency and bufferbloat over existing infrastructure. It also monitors performance by measuring end-to-end TCP round trip time for each subscriber, Access Point, and Site on a network. LibreQoS ensures fair allocation of bandwidth, prioritizes critical real-time applications, and promotes connection quality, equity and access.</p>
<p><b>Mosh</b><br>
<a href="https://mosh.org/" target="_blank" rel="noopener">https://mosh.org/</a><br>
Remote terminal application that allows roaming, supports intermittent connectivity, and provides intelligent local echo and line editing of user keystrokes. Mosh is a replacement for interactive SSH terminals. It’s more robust and responsive, especially over Wi-Fi, cellular, and long-distance links.</p>
<p><b>OpenNTPD</b><br>
<a href="https://www.openntpd.org/" target="_blank" rel="noopener">https://www.openntpd.org/</a><br>
Easy-to-use implementation of the Network Time Protocol. It provides the ability to sync the local clock to remote NTP servers and can act as NTP server itself, redistributing the local clock.</p>
<p><b>PTPd</b><br>
<a href="https://github.com/ptpd/ptpd" target="_blank" rel="noopener">https://github.com/ptpd/ptpd</a><br>
Implementation of the Precision Time Protocol (PTP) version 2 as defined by IEEE Std 1588-2008. PTP provides precise time coordination of Ethernet LAN connected computers. It was designed primarily for instrumentation and control systems.</p>
<p><b>Squid</b><br>
<a href="https://www.squid-cache.org/" target="_blank" rel="noopener">https://www.squid-cache.org/</a><br>
Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently requested web pages. Squid has extensive access controls and makes a great server accelerator.</p>
<p><strong>Zrok</strong><br>
<a href="https://zrok.io/">https://zrok.io/</a><br>
An open source sharing solution built on OpenZiti, the zero trust networking platform. Available as SaaS or self-hosted. Provides Private or Public, instant, secure tunneling of applications from anywhere. Secured effortlessly by using a zero trust overlay network provided by OpenZiti.</p>
<hr>
<h3 id="os">Operating Systems</h3>
<p><b>Dent</b><br>
<a href="https://dent.dev/" target="_blank" rel="noopener">https://dent.dev/</a><br>
Uses the Linux kernel, Switchdev, and other Linux-based projects as the basis for building a new standardized network operating system without abstractions or overhead. All underlying infrastructure — including ASIC and silicon for networking and datapath — is treated equally, while existing abstractions, APIs, drivers, low-level overhead, and other open software are simplified. DENT unites silicon vendors, ODMs, SIs, OEMs, and end users across all verticals to enable the transition to disaggregated networks.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/network-break/nb373-google-buys-mandiant-to-bolster-security-ops-network-os-dent-2-0-released/" target="_blank" rel="noopener">NB373: Network OS DENT 2.0 Released</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/putting-a-dent-in-open-source-switches-nos-device-driver-combo-gains-traction/" target="_blank" rel="noopener">Putting A Dent In Open-Source Switches: NOS/Device-Driver Combo Gains Traction</a></li>
</ul>
<p><b>Open Network Install Environment</b><br>
<a href="https://opencomputeproject.github.io/onie/" target="_blank" rel="noopener">https://opencomputeproject.github.io/onie/</a><br>
Creates an installation environment for bare-metal switches. ONIE is the tool that enables bare metal switches to have different network operating systems installed on a switch by providing a simple execution environment with basic network connectivity.</p>
<p><b>Open Network Linux</b><br>
<a href="https://github.com/opencomputeproject/OpenNetworkLinux" target="_blank" rel="noopener">https://github.com/opencomputeproject/OpenNetworkLinux</a><br>
Linux distribution for bare metal switches. ONL builds an ONIE-compatible installer and a switch image which contains a complete Debian distribution with added drivers and configuration for running on bare metal switches. Has been moved to maintenance mode, pending archival.</p>
<p><b>OpenSwitch</b><br>
<a href="https://www.openswitch.net/" target="_blank" rel="noopener">https://www.openswitch.net/</a><br>
The OPX project creates an operating system abstracting a variety of switching chips and providing a programmable interface. <a href="https://www.openswitch.net/news-and-events/2020/08/10/2835/" target="_blank" rel="noopener">The project was deemed mature as of August 2020</a>.</p>
<p><b>Open vSwitch</b><br>
<a href="https://openvswitch.org/" target="_blank" rel="noopener">https://openvswitch.org/</a><br>
A virtual switch akin to Broadcom VMware’s vSwitch or Cisco’s Nexus 1000V. OVS can also sit on a hypervisor or a network switch. OVS can run across servers as a distributed virtual switch. The feature focus is on L2 functions such as VLANs, LACP, spanning tree, and L2 QoS.</p>
<p><b>OpenWRT</b><br>
<a href="https://openwrt.org/" target="_blank" rel="noopener">https://openwrt.org/</a><br>
Open Wireless RouTer. Linux operating system targeting embedded devices. Instead of trying to create a single, static firmware, OpenWRT provides a fully writable filesystem with package management. This frees you from the application selection and configuration provided by the vendor and allows you to customize the device through the use of packages to suit any application.</p>
<p><b>SoNiC</b><br>
<a href="https://github.com/sonic-net/SONiC" target="_blank" rel="noopener">https://github.com/sonic-net/SONiC</a><br>
Network operating system based on Linux that runs on switches from multiple vendors and ASICs. SONiC offers a full-suite of network functionality, like BGP and RDMA, that has been production-hardened in the data centers of some of the largest cloud-service providers. It offers teams the flexibility to create the network solutions they need while leveraging the collective strength of a large ecosystem and community.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn521-diving-into-dell-technologies-sonic-network-os-for-the-enterprise-sponsored/" target="_blank" rel="noopener">HN521: Diving Into Dell Technologies’ SONiC Network OS For The Enterprise</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn551-an-insiders-guide-to-the-sonic-network-os/" target="_blank" rel="noopener">HN551: An Insider’s Guide To The SONiC Network OS</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn570-dell-brings-the-sonic-nos-to-smartnics-and-dpus-sponsored/" target="_blank" rel="noopener">HN570: Dell Brings The SONiC NOS To SmartNICs And DPUs</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/people-getting-sonic-wrong/" target="_blank" rel="noopener">What People Get Wrong About Microsoft SONiC</a></li>
</ul>
<p><b>VyOS</b><br>
<a href="https://vyos.io/" target="_blank" rel="noopener">https://vyos.io/</a><br>
Network operating system based on Debian GNU/Linux. VyOS provides a free routing platform that competes directly with other commercially available solutions from well known network providers. Because VyOS runs on standard amd64, i586, and ARM systems, it’s able to be used as a router and firewall platform for cloud deployments.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn450-getting-to-know-the-open-source-vyos-network-os/" target="_blank" rel="noopener">HN450: Getting To Know The Open-Source VyOS Network OS</a></li>
</ul>
</li>
</ul>
<hr>
<h3 id="routing">Routing &amp; Overlay Platforms</h3>
<p><strong>Bio-Routing</strong><br>
<a href="https://github.com/bio-routing/bio-rd">https://github.com/bio-routing/bio-rd</a><br>
A versatile, fast and reliable routing daemon in Golang. bio = BGP + IS-IS + OSPF.&nbsp; We value respect and robustness!</p>
<p><b>Bird</b><br>
<a href="https://bird.network.cz/" target="_blank" rel="noopener">https://bird.network.cz/</a><br>
Aims to develop a fully functional dynamic IP routing daemon. Supports IPv4 and IPv6, multiple routing tables, BGP, RIP, OSPF, BFD, Babel, static routes, IPv6 RA, and inter-table protocol, and offers a CLI using the `birdc’ client and a powerful language for route filtering.</p>
<p><b>freeRtr</b><br>
<a href="http://www.freertr.org/" target="_blank" rel="noopener">http://www.freertr.org/</a><br>
Control plane meant to be paired with a programmable dataplane. P4, DPDK, XDP, and TCPDUMP/libpcap are cited as dataplane possibilities. Think of freeRtr as a learning tool that allows for several router instances to be stood up on the same device and connected to each other using UDP encapsulation.</p>
<p><b>Free Range Routing</b><br>
<a href="https://frrouting.org/" target="_blank" rel="noopener">https://frrouting.org/</a><br>
Internet routing protocol suite for Linux and Unix platforms. It implements BGP, OSPF, RIP, IS-IS, PIM, LDP, BFD, Babel, PBR, OpenFabric, and VRRP, with alpha support for EIGRP and NHRP. FRR’s seamless integration with native Linux/Unix IP networking stacks makes it a general purpose routing stack applicable to a wide variety of use cases including connecting hosts/VMs/containers to the network, advertising network services, LAN switching and routing, internet access routers, and internet peering.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn401-deeper-understanding-free-range-routing-frr/" target="_blank" rel="noopener">HN401: A Deeper Understanding Of Free Range Routing (FRR)</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn541-an-update-on-free-range-routing/" target="_blank" rel="noopener">HN541: An Update On Free Range Routing</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/free-range-routing-project-forks-quagga/" target="_blank" rel="noopener">Free Range Routing Project Forks Quagga</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<p><b>Holo</b><br>
<a href="https://github.com/holo-routing/holo" target="_blank" rel="noopener">https://github.com/holo-routing/holo</a><br>
Suite of routing protocols designed to support high-scale and automation-driven networks. Holo’s main goal is to create a reliable, easy-to-maintain, and extensible codebase. With the ever increasing complexity of routing protocols and their extensions, it’s crucial to have routing protocol implementations built on a robust foundation. Supports BFD, MPLS LDP, OSPF, and RIP, with BGP and IS-IS on the roadmap.</p>
<p><strong>Pathvector</strong><br>
<a href="https://pathvector.io/">https://pathvector.io/</a><br>
Declarative edge routing platform that automates route optimization and control plane configuration with secure and repeatable routing policy. Features include automatic configuration from PeeringDB, automatic route optimization by enriching the standard set of BGP attributes with latency and packet loss metrics, declarative configuration model, data-plane agnosticism, BFD and VRRP support, and an extensible Go plugin API.</p>
<p><strong>SCION<br>
</strong><a href="https://github.com/netsec-ethz/scion">https://github.com/netsec-ethz/scion</a><br>
Scalability, Control and Isolation On next-generation Networks, a future Internet architecture. SCION is the first clean-slate Internet architecture designed to provide route control, failure isolation, and explicit trust information for end-to-end communication. To find out more about the project, please visit our <a href="https://scion.docs.anapaya.net/en/latest/">documentation site</a>.</p>
<p><strong>ZeroTier<br>
</strong><a href="https://zerotier.com/community/">https://zerotier.com/community/</a><br>
An overlay networking tool that extends L2 over L3. ZeroTier is a smart programmable Ethernet switch for planet Earth. It allows all networked devices, VMs, containers, and applications to communicate as if they all reside in the same physical data center or cloud region. All ZeroTier traffic is encrypted end-to-end using secret keys that only you control. Most traffic flows peer to peer, though we offer free (but slow) relaying for users who cannot establish peer to peer connections.</p>
<hr>
<h3 id="ddos">Security – DDoS Mitigation</h3>
<p><b>FastNetMon Community Edition<br>
</b><a href="https://github.com/pavel-odintsov/fastnetmon">https://github.com/pavel-odintsov/fastnetmon</a><br>
High-performance DDoS detector/sensor built on top of multiple packet capture engines: NetFlow, IPFIX, sFlow, AF_PACKET (port mirror). Detects hosts in the deployed network sending or receiving large volumes of traffic, packets/bytes/flows per second and perform a configurable action to handle that event. These configurable actions include notifying you, calling script or making BGP announcements.</p>
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn375-design-build-14-ddos-mitigation/" target="_blank" rel="noopener">HN375: Design &amp; Build 14: DDoS Mitigation</a></li>
</ul>
<hr>
<h3 id="firewalls">Security – Firewalls &amp; Filtering</h3>
<p><b>Iptables</b><br>
<a href="https://www.netfilter.org/projects/iptables/index.html" target="_blank" rel="noopener">https://www.netfilter.org/projects/iptables/index.html</a><br>
Userspace command line program used to configure the Linux 2.4.x and later packet filtering ruleset. It’s targeted towards system administrators. Since NAT is also configured from the packet filter ruleset, iptables is used for this too. The iptables package also includes ip6tables. ip6tables is used for configuring the IPv6 packet filter.</p>
<p><b>Nftables</b><br>
<a href="https://netfilter.org/projects/nftables/" target="_blank" rel="noopener">https://netfilter.org/projects/nftables/</a><br>
Replaces the popular {ip,ip6,arp,eb} tables. This software provides a new in-kernel packet classification framework that’s based on a network-specific virtual machine and a new nft userspace command line tool. nftables reuses the existing Netfilter subsystems such as the existing hook infrastructure, the connection tracking system, NAT, userspace queueing, and logging subsystem.</p>
<p><b>Opnsense</b><br>
<a href="https://opnsense.org/" target="_blank" rel="noopener">https://opnsense.org/</a><br>
Easy-to-use and easy-to-build FreeBSD based firewall and routing platform. OPNsense includes most of the features available in expensive commercial firewalls, and more in many cases. It brings the rich feature set of commercial offerings with the benefits of open and verifiable sources.</p>
<p><strong>pfSense<br>
</strong><a href="https://github.com/pfsense/pfsense">https://github.com/pfsense/pfsense</a><strong><br>
</strong>The pfSense project is a free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. pfSense software, with the help of the package system, is able to provide the same functionality or more of common commercial firewalls, without any of the artificial limitations.</p>
<hr>
<h3 id="idp">Security – Intrusion Detection &amp; Prevention</h3>
<p><strong>CrowdSec Free Edition<br>
</strong><a href="https://github.com/crowdsecurity/crowdsec">https://github.com/crowdsecurity/crowdsec</a><br>
<a href="https://www.crowdsec.net/pricing">CrowdSec</a> is a free, modern, and collaborative behavior detection engine, coupled with a global IP reputation network. It stacks on fail2ban’s philosophy but is IPV6 compatible and 60x faster (Go vs Python), it uses Grok patterns to parse logs, and YAML scenarios to identify behaviors. CrowdSec is engineered for modern cloud / containers / VM-based infrastructures (by decoupling detection and remediation). Once detected you can remedy threats with various bouncers (firewall block, nginx http 403, captchas, etc.) while the aggressive IP can be sent to CrowdSec for curation before being shared among all users to further improve everyone’s security.</p>
<p><b>Snort</b><br>
<a href="https://www.snort.org/" target="_blank" rel="noopener">https://www.snort.org/</a><br>
Snort has three primary uses: As a packet sniffer like tcpdump, as a packet logger — which is useful for network traffic debugging, or it can be used as a full-blown network intrusion prevention system. Snort can be downloaded and configured for personal and business use alike.</p>
<p><b>Suricata</b><br>
<a href="https://suricata.io/" target="_blank" rel="noopener">https://suricata.io/</a><br>
High performance, open source network analysis and threat detection software used by most private and public organizations, and embedded by major vendors to protect their assets. Not only IDS/IPS, but also transaction logging, packet capture, and more.</p>
<p><b>Zeek (formerly Bro)</b><br>
<a href="https://zeek.org/" target="_blank" rel="noopener">https://zeek.org/</a><br>
Sits on a “sensor,” a hardware, software, virtual, or cloud platform that quietly and unobtrusively observes network traffic. Zeek interprets what it sees and creates compact, high-fidelity transaction logs, file content, and fully customized output, suitable for manual review on disk or in a more analyst-friendly tool like a security and information event management (SIEM) system.</p>
<hr>
<h3 id="scanning">Security – Scanning &amp; Reconnaissance</h3>
<p><strong>Bettercap</strong><br>
<a href="https://github.com/bettercap/bettercap">https://github.com/bettercap/bettercap</a><br>
Powerful, easily extensible and portable framework written in Go which aims to offer to security researchers, red teamers and reverse engineers an easy to use, all-in-one solution with all the features they might possibly need for performing reconnaissance and attacking WiFi networks, Bluetooth Low Energy devices, wireless HID devices and Ethernet networks.</p>
<p><strong>Furious IP/Port Scanner</strong><br>
<a href="https://github.com/liamg/furious">https://github.com/liamg/furious</a><br>
Furious is a fast, lightweight, portable network scanner. A SYN scan of a single host, including all known ports (~6000) will typically take in the region of 4 seconds. On the same machine, nmap took 98 seconds and produced exactly the same results.</p>
<p><b>Ivre</b><br>
<a href="https://github.com/ivre/ivre" target="_blank" rel="noopener">https://github.com/ivre/ivre</a><br>
Network recon framework, including tools for passive and active recon. IVRE can use data from Zeek, Argus, Nfdump, p0f, airodump-ng, Nmap, Masscan, ZGrab2, ZDNS, Nuclei, httpx, dnsx, tlsx, and Dismap.</p>
<p><b>Nmap</b><br>
<a href="https://nmap.org/" target="_blank" rel="noopener">https://nmap.org/</a><br>
Tool for network exploration and security auditing. It was designed to rapidly scan large networks, although it works fine against single hosts. Nmap uses raw IP packets in novel ways to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics. While Nmap is commonly used for security audits, many systems and network administrators find it useful for routine tasks such as network inventory, managing service upgrade schedules, and monitoring host or service uptime.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn096-hack-the-hackers-fyodor-on-nmap-the-security-industry/" target="_blank" rel="noopener">HN096: Hack the Hackers: Fyodor On Nmap &amp; The Security Industry</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<hr>
<h3 id="vpn">Security – VPN</h3>
<p><b>strongSwan</b><br>
<a href="https://www.strongswan.org/" target="_blank" rel="noopener">https://www.strongswan.org/</a><br>
Comprehensive implementation of the Internet Key Exchange (IKE) protocols that allows securing IP traffic in policy- and route-based IPsec scenarios from simple to very complex.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/strongswan-an-inexpensive-aws-vpn-alternative/" target="_blank" rel="noopener">StrongSwan: An Inexpensive AWS VPN Alternative</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<p><b>Wireguard</b><br>
<a href="https://www.wireguard.com/" target="_blank" rel="noopener">https://www.wireguard.com/</a><br>
Extremely simple yet fast and modern VPN that uses state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN.</p>
<hr>
<h3 id="cli">Tools – CLI Utilities</h3>
<p><b>BNG Blaster</b><br>
<a href="https://github.com/rtbrick/bngblaster" target="_blank" rel="noopener">https://github.com/rtbrick/bngblaster</a><br>
Network tester for access and routing protocols. Originally developed as an access protocol tester, the BNG Blaster has undergone a significant evolution, transforming into a comprehensive network testing tool that now encompasses both access and routing functionalities. Its scope has expanded beyond the assessment of access protocols and now encompasses a broader spectrum, involving the evaluation of network functionalities at large. BNG Blaster isn’t restricted only to BNG (Broadband Network Gateway) testing. It simulates a massive number of PPPoE and IPoE (DHCP) subscribers, encompassing IPTV and L2TP (LNS). Additionally it supports all common routing protocols such as IS-IS, OSPF, LDP, and BGP.</p>
<p><strong>Commando</strong><br>
<a href="https://github.com/hellt/cmdo">https://github.com/hellt/cmdo</a><br>
Commando is a tiny tool that enables users to collect command outputs from a single or a multiple networking devices defined in an inventory file and send file-based or string-based configs towards the devices defined in the inventory file. All that with zero dependencies and a 1-click installation.</p>
<p><b>Ethtool</b><br>
<a href="https://mirrors.edge.kernel.org/pub/software/network/ethtool/" target="_blank" rel="noopener">https://mirrors.edge.kernel.org/pub/software/network/ethtool/</a><br>
Standard Linux utility for controlling network drivers and hardware, particularly for wired Ethernet devices.</p>
<p><b>gNMIc</b><br>
<a href="https://gnmic.openconfig.net" target="_blank" rel="noopener">https://gnmic.openconfig.net</a><br>
A gNMI CLI client that provides full support for Capabilities, Get, Set and Subscribe RPCs with collector capabilities.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/tech-bytes/tech-bytes-configure-devices-stream-telemetry-with-nokias-free-open-source-gnmic-sponsored/" target="_blank" rel="noopener">Tech Bytes: Configure Devices, Stream Telemetry With Nokia’s Free, Open-Source gNMIc</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<p><b>gNOIc</b><br>
<a href="https://gnoic.kmrd.dev" target="_blank" rel="noopener">https://gnoic.kmrd.dev</a><br>
gNOI CLI client that provides support for select gNOI Services: Certificate Management, File, System, and OS.</p>
<p><b>Iproute2</b><br>
<a href="https://wiki.linuxfoundation.org/networking/iproute2" target="_blank" rel="noopener">https://wiki.linuxfoundation.org/networking/iproute2</a><br>
Collection of utilities for controlling TCP / IP networking and traffic control in Linux. Most network configuration manuals still refer to ifconfig and route as the primary network configuration tools, but ifconfig is known to behave inadequately in modern network environments. They should be deprecated, but most distros still include them.</p>
<p><strong>lswifi</strong><br>
<a href="https://github.com/joshschmelzle/lswifi">https://github.com/joshschmelzle/lswifi</a><br>
CLI-centric Wi-Fi scanning tool for Windows that provides more information about nearby Wi-Fi networks than built-in tools (e.g. netsh show wlan networks). Examples include Received Signal Strength Indicator (RSSI), showing security AKMs and ciphers, parsing 802.11 feature set, looking at 6 GHz Reduced Neighbor Reports, and more. With capable Wi-Fi adapters, lswifi can detect and show networks in 2.4 GHz, 5 GHz, and 6 GHz bands.</p>
<p><b>Mtr</b><br>
<a href="https://bitwizard.nl/mtr/" target="_blank" rel="noopener">https://bitwizard.nl/mtr/</a><br>
Combines the functionality of the ‘traceroute’ and ‘ping’ programs in a single network diagnostic tool. As mtr starts, it investigates the network connection between the host mtr runs on and a user-specified destination host. After it determines the address of each network hop between the machines, it sends a sequence ICMP ECHO requests to each one to determine the quality of the link to each machine. As it does this, it prints running statistics about each machine.</p>
<p><b>Netcat</b><br>
<a href="https://nc110.sourceforge.io/" target="_blank" rel="noopener">https://nc110.sourceforge.io/</a><br>
Aka “nc”. Simple Unix utility which reads and writes data across network connections, using TCP or UDP protocol. It’s designed to be a reliable “back-end” tool that can be used directly or easily driven by other programs and scripts. At the same time, it’s a feature-rich network debugging and exploration tool, since it can create almost any kind of connection you would need and has several interesting built-in capabilities.</p>
<p><b>Scapy</b><br>
<a href="https://github.com/secdev/scapy" target="_blank" rel="noopener">https://github.com/secdev/scapy</a><br>
Powerful Python-based interactive packet manipulation program and library. It’s able to forge or decode packets of a wide number of protocols, send them on the wire, capture them, store or read them using pcap files, match requests and replies, and much more. It’s designed to allow fast packet prototyping by using default values that work.</p>
<p><b>Sipcalc</b><br>
<a href="https://github.com/sii/sipcalc" target="_blank" rel="noopener">https://github.com/sii/sipcalc</a><br>
Console-based IP subnet calculator with IPv4 and IPv6 support.</p>
<p><b>Speedtest CLI</b><br>
<a href="https://www.speedtest.net/apps/cli" target="_blank" rel="noopener">https://www.speedtest.net/apps/cli</a><br>
CLI-based up/down bandwidth test.</p>
<p><b>Switchmap</b><br>
<a href="https://switchmap.sourceforge.net/" target="_blank" rel="noopener">https://switchmap.sourceforge.net/</a><br>
Perl program that creates HTML pages that show information about a set of Cisco Ethernet switches. The program uses SNMP to gather data from the switches.</p>
<hr>
<h3 id="packet-capture">Tools – Packet Capture &amp; Analysis</h3>
<p><b>TCPdump &amp; libpcap</b><br>
<a href="https://www.tcpdump.org/" target="_blank" rel="noopener">https://www.tcpdump.org/</a><br>
Tcpdump, a powerful command-line packet analyzer, and libpcap, a portable C/C++ library for network traffic capture.</p>
<p><b>Wireshark</b><br>
<a href="https://www.wireshark.org/" target="_blank" rel="noopener">https://www.wireshark.org/</a><br>
The world’s most popular network protocol analyzer. It lets you see what’s happening on your network at a microscopic level. It’s the de facto (and often de jure) standard across many industries and educational institutions.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn108-wireshark-with-gerald-combs/" target="_blank" rel="noopener">HN108: Wireshark with Gerald Combs</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn277-riverbeds-role-wireshark-security-sponsored/" target="_blank" rel="noopener">HN277: Riverbed’s Role In Wireshark, Security &amp; More</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn323-making-most-of-wireshark/" target="_blank" rel="noopener">HN323: Making The Most Of Wireshark</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/ipv6-buzz/ipb010-understanding-and-troubleshooting-ipv6-with-wireshark/" target="_blank" rel="noopener">IPB010: Understanding And Troubleshooting IPv6 With Wireshark</a></li>
<li><img draggable="false" role="img" class="emoji" alt="🗒️" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f5d2.svg"> <a href="https://packetpushers.net/blog/understanding-wireshark-capture-filters/" target="_blank" rel="noopener">Understanding Wireshark Capture Filters</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<hr>
<h3 id="traffic">Tools – Traffic Generators</h3>
<p><strong>Arachne</strong><br>
<a href="https://github.com/uber/arachne">https://github.com/uber/arachne</a><br>
Arachne is a packet loss detection system and an underperforming path detection system. It provides fast and easy active end-to-end functional testing of all the components in Data Center and Cloud infrastructures. Arachne is able to detect intra-DC, inter-DC, DC-to-Cloud, and DC-to-External-Services issues by generating minimal traffic.</p>
<p><strong>Ethr</strong><br>
<a href="https://github.com/microsoft/ethr">https://github.com/microsoft/ethr</a><br>
Ethr is a cross platform network performance measurement tool written in golang. The goal of this project is to provide a native tool for comprehensive network performance measurements of bandwidth, connections/s, packets/s, latency, loss &amp; jitter, across multiple protocols such as TCP, UDP, HTTP, HTTPS, and across multiple platforms such as Windows, Linux and other Unix systems. Ethr takes inspiration from existing open source network performance tools and builds upon those ideas.</p>
<p><b>Iperf</b><br>
<a href="https://github.com/esnet/iperf" target="_blank" rel="noopener">https://github.com/esnet/iperf</a><br>
Tool for active measurements of the maximum achievable bandwidth on IP networks. It supports tuning of various parameters related to timing, protocols, and buffers. For each test it reports the measured throughput / bitrate, loss, and other parameters.</p>
<p><b>Magna</b><br>
<a href="https://github.com/openconfig/magna" target="_blank" rel="noopener">https://github.com/openconfig/magna</a><br>
Open Traffic Generator implementation from OpenConfig project.</p>
<p><b>Ostinato</b><br>
<a href="https://github.com/pstavirs/ostinato/" target="_blank" rel="noopener">https://github.com/pstavirs/ostinato/</a><br>
Network packet crafter and traffic generator. Source available to DIY build. Purchasing the binaries and add-ons supports the creator and maintainer.</p>
<p><strong>perfSONAR<br>
</strong><a href="https://github.com/perfsonar">https://github.com/perfsonar</a><br>
perfSONAR is the performance Service-Oriented Network monitoring ARchitecture, a network measurement toolkit designed to provide federated coverage of paths and help to establish end-to-end usage expectations. There are thousands of perfSONAR instances deployed worldwide, many of which are available for open testing of key measures of network performance. This global infrastructure helps to identify and isolate problems as they happen, making the role of supporting network users easier for engineering teams and increasing productivity when utilizing network resources.</p>
<p><b>Pktgen</b><br>
<a href="https://github.com/pktgen/Pktgen-DPDK" target="_blank" rel="noopener">https://github.com/pktgen/Pktgen-DPDK</a><br>
Traffic generator powered by DPDK at wire rate traffic with 64 byte frames.</p>
<p><b>T-rex</b><br>
<a href="https://trex-tgn.cisco.com/" target="_blank" rel="noopener">https://trex-tgn.cisco.com/</a><br>
Low cost, stateful, and stateless traffic generator fuelled by DPDK. It generates L3-7 traffic and provides in one tool capabilities provided by commercial tools.</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li style="list-style-type: none;">
<ul>
<li><img draggable="false" role="img" class="emoji" alt="🎧" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f3a7.svg">️ <a href="https://packetpushers.net/podcasts/heavy-networking/hn482-test-your-limits-with-the-trex-oss-traffic-generator/" target="_blank" rel="noopener">HN482: Test Your Limits With The TRex OSS Traffic Generator</a></li>
</ul>
</li>
</ul>
</li>
</ul>
<p><b>Warp17</b><br>
<a href="https://github.com/Juniper/warp17" target="_blank" rel="noopener">https://github.com/Juniper/warp17</a><br>
Lightweight solution for generating high volumes of session based traffic with very high setup rates. WARP17 currently focuses on L5-L7 application traffic (e.g., HTTP) running on top of TCP as this kind of traffic requires a complete TCP implementation. Nevertheless, WARP17 also supports application traffic running on top of UDP.</p>
<hr>
<p><img draggable="false" role="img" class="emoji" alt="🤔" src="https://s.w.org/images/core/emoji/15.0.3/svg/1f914.svg"> Did we miss a project? <a href="https://packetpushers.net/fu/" target="_blank" rel="noopener">Tell us about it here</a>.</p>

									<div class="author-bio bg-lblue">
																			<img alt="" src="https://secure.gravatar.com/avatar/2713ce8f9b3998a74cf3dee9b86ce7e5?s=96&amp;d=blank&amp;r=g" srcset="https://secure.gravatar.com/avatar/2713ce8f9b3998a74cf3dee9b86ce7e5?s=192&amp;d=blank&amp;r=g 2x" class="avatar avatar-96 photo" height="96" width="96" decoding="async">												<div class="author-content">
							<!--<a href="https://packetpushers.net/author/ethan-banks/"></a>-->
							<p>
								<strong> About Ethan Banks:</strong>
								Founder &amp; CEO of Packet Pushers, a podcast network for IT people. (NH)NUG organizer. Recovering CCIE #20655. Co-host of the Heavy Networking, Tech Bytes &amp; N Is For Networking pods. Your network is not a democracy. Rig every election.							</p>
															<h6 class="biolinks">
																														<a href="https://www.linkedin.com/in/ethanbanks/" target="_blank">LinkedIn</a><span>|</span>								</h6>
													</div>
					</div>
				
			</div>
