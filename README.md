
![Apprenda Logo](https://github.com/mammerman/acp-reference-architecture/raw/master/resources/apprenda-logo.png)

# Reference Architecture Docs for the Apprenda Cloud Platform

The documents contained in this repo describe and illustrate considerations for installing the Apprenda Cloud Platform in a production capacity in the enterprise.  Considerations include operational requirements, including networking, virtual/bare metal, OS, storage, and other requirements.  Much of the information in this document should be used as a reference point, and specific customizations can be made for your organization's needs.

* [Summary](summary/summary.md)
  * [Introduction](summary/summary.md#introduction)
  * [Who Should Read This Reference Guide?](summary/summary.md#who-should-read)
  * [Next Steps](summary/summary.md#next-steps)
* [What is the Apprenda Cloud Platform?](overview/what-is-the-apprenda-cloud-platform.md)
* [Deployment Planning](planning/deployment-planning.md)
  * Public Cloud, Private Datacenter, and Hybrid
  * Optional Infrastructure
  * A Note About Infrastructure Sizing
  * [Considerations for Availability and Redundancy](planning/considerations-for-availability.md)
* [Hardware](provisioning/hardware.md)
  * Machines
    * Bare Metal vs. Virtual Machines
  * Networking
    * Establishing a Private LAN for Apprenda Nodes
    * Inbound Traffic (Ingress)
  * Using a SAN for Storage
* [Software](provisioning/software.md)
  * Operating Systems and Software
* [Hardware & Software Recommended Specs](provisioning/recommendations.md)
* [Reference Architecture Topology](architecture/topology-single-cloud.md)
  * The Entire Architecture
  * Platform Coordinator Nodes
  * Cache Nodes
  * Worker Nodes
    * Windows Machines
    * Linux Machines
    * Docker
    * Database Servers
  * Platform Repository
  * Platform Federation Nodes - ADFS
* Apprenda Core Components and Concepts
