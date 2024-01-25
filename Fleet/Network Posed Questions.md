
# What is SCCM?

1. Configuration Manager, commonly known as SCCM, is a powerful and versatile tool created by Microsoft. It provides IT professionals with an integrated platform to manage and deploy software, hardware, and other resources across their networks.
2. SCCM, is a tool developed by Microsoft that is used to manage and deploy software, hardware, and other resources across an organization’s network. It is part of the Microsoft System Center suite of products, and is a powerful and versatile tool that allows IT professionals to streamline their operations and increase efficiency.
3. It allows IT professionals to remotely install, update, and manage software, hardware, and other resources across their networks. It also provides tools for monitoring and reporting on the health and performance of their networks. Additionally, it can be used to deploy operating systems, applications, and patches on a large scale, and to manage the security and compliance of the network.
## Components of SCCM

- **Console**, which is used to manage and configure the system; 
- **Site server**, which stores configuration data and provides access to the SCCM console;
- **Client**, which runs on each managed device; 
- **Database**, which stores information about the managed resources; 
- **Distribution points**, which are used to deploy applications and patches; 
- **Management points**, which provide access to the SCCM console; 
- **Reporting services**, which generate reports about the managed resources.

# Define Windows Deployment Services

1. Windows Deployment Services (WDS) enables you to deploy Windows operating systems over the network, which means that you do not have to install each operating system directly from a CD or DVD.

## Benefits WDS

- Allows network-based installation of Windows operating systems, which reduces the complexity and cost when compared to manual installations.
- Supports deploying images for mixed environments including Windows 7and Windows Server 2008 R2 through Windows 8.1and Windows Server 2012 R2.
- Uses standard Windows Setup technologies including Windows Preinstallation Environment (Windows PE), .wim files, and image-based setup.
- Transmits data and images by using multicast functionality.
- Allows you to create images of a reference computer using the Image Capture Wizard, which is an alternative to the ImageX tool.
- Allows you to add driver packages to the server and configure them to be deployed to client computers along with the install image.

# What is Default Gateway?

A default gateway makes it possible for devices in one [network](https://www.lifewire.com/what-is-computer-networking-816249) to communicate with devices in another network. If a computer, for example, requests a web page, the request goes through the default gateway before exiting the [local network (LAN)](https://www.lifewire.com/what-is-lan-4684071) to reach the internet.

Think of a default gateway as an intermediate device between the local network and the internet. The default gateway transfers internal data to the internet and back again.

# Define Access Control Machine

Access control is a security technique that regulates who or what can view or use resources in a computing environment. It is a fundamental concept in security that [minimizes risk](https://www.techtarget.com/searchstorage/tip/Prevent-the-storage-and-data-security-risks-of-remote-work) to the business or organization.

There are two types of access control: physical and logical. Physical access control limits access to campuses, buildings, rooms and physical IT assets. Logical access control limits connections to computer networks, system files and data.

To secure a facility, organizations use electronic access control systems that rely on user credentials, access card readers, auditing and reports to track employee access to restricted business locations and proprietary areas, such as data centers. Some of these systems incorporate access control panels to restrict entry to rooms and buildings, as well as alarms and lockdown capabilities, to prevent unauthorized access or operations.
# Define a Primary DNS

A primary [DNS server](https://www.cloudflare.com/learning/dns/dns-server-types/) is a server that hosts a website’s primary [zone file](https://www.cloudflare.com/learning/dns/glossary/dns-zone/). This is a text database file that contains all of the authoritative information for a domain, including its IP address, the identity of the domain administrator, and various resource records. Resource records list domain names alongside their corresponding IP addresses, and can take several different forms:

- **[A record](https://www.cloudflare.com/learning/dns/dns-records/dns-a-record/):** Directs a domain to an IPv4 address
- **AAAA record:** Directs a domain to an IPv6 address
- **[MX record](https://www.cloudflare.com/learning/dns/dns-records/dns-mx-record/):** Assigns a mail server to a domain
- **[NS record](https://www.cloudflare.com/learning/dns/dns-records/dns-ns-record/):** Identifies authoritative DNS servers for a domain

Primary servers are also responsible for making any necessary changes to a zone’s [DNS records](https://www.cloudflare.com/learning/dns/dns-records/). Once the primary server has completed the update, it can then pass along change requests to the secondary servers.

## Secondary DNS server

Secondary DNS servers contain zone file copies that are read-only, meaning they cannot be modified. Instead of getting their information from local files, they receive pertinent information from a primary server in a communication process known as a zone transfer.

Zone transfers become more complicated when they are completed between multiple secondary servers. If several secondary servers are in use, one may be designated as a higher-tier secondary server so that it is capable of replicating zone file copies to the remaining pool of secondary servers.


# Active Directory Tombstone
# References

[SCCM full description](https://networkinterview.com/sccm-configuration-manager/)
[Windows Deployment Services](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/hh831764(v=ws.11))
[Default Gateway](https://www.lifewire.com/what-is-a-default-gateway-817771)
[Access Control](https://www.techtarget.com/searchsecurity/definition/access-control)
[Primary vs Secondary DNS](https://www.cloudflare.com/en-gb/learning/dns/glossary/primary-secondary-dns/)
[Batch Script for Windows](https://www.howtogeek.com/263177/how-to-write-a-batch-script-on-windows/)
