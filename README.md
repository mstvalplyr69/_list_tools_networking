# _list_tools_networking
A comprehensive list of links and descriptions for networking tools

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
<li>
