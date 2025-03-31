# Awesome-LOTL-Resources
<p align="center">A collections of verity of Living Off The Land Binaries, Scripts and Libraries.</p>

<p align="center">
	<img src="https://awesome.re/badge.svg" alt="Awesome">
</p>

A curated list of resources related to "Living Off the Land" (LOTL) techniques and similar security concepts. LOTL refers to attack methods that leverage legitimate system tools and processes to conduct malicious activities, making detection more challenging. This repository aims to provide a comprehensive collection of catalogs, tools, and techniques that cybersecurity professionals—such as researchers, red teamers, and defenders—can use to understand and mitigate LOTL-based attacks.


---

## Table of Contents

- [Operating System Binaries and Scripts](#operating-system-binaries-and-scripts)
- [Drivers and Low-Level Components](#drivers-and-low-level-components)
- [Applications and Tools](#applications-and-tools)
- [Hardware and Firmware](#hardware-and-firmware)
- [Evasion and Exploitation Techniques](#evasion-and-exploitation-techniques)
- [Persistence Mechanisms](#persistence-mechanisms)
- [Certificates and Trust](#certificates-and-trust)
- [Command and Control](#command-and-control)
- [Active Directory and Windows-Specific](#active-directory-and-windows-specific)
- [APIs and Malware Analysis](#apis-and-malware-analysis)
- [Miscellaneous](#miscellaneous)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Operating System Binaries and Scripts

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **GTFOArgs**      | A collection of Unix binaries exploitable via argument injection.          | [https://gtfoargs.github.io/](https://gtfoargs.github.io/) |
| **GTFOBins**      | Curated list of Unix binaries to bypass local security restrictions.       | [https://gtfobins.github.io/](https://gtfobins.github.io/) |
| **LOLBAS**        | Living Off The Land Binaries, Scripts, and Libraries for Windows.          | [https://lolbas-project.github.io/](https://lolbas-project.github.io/) |
| **LOOBins**       | Living Off The Orchard Binaries - macOS binaries that can be abused.       | [https://www.loobins.io/](https://www.loobins.io/)         |
| **LOLESXi**       | Living Off the Land ESXi - Binaries/scripts in VMware ESXi used by adversaries. | [https://lolesxi-project.github.io/LOLESXi/](https://lolesxi-project.github.io/LOLESXi/) |
| **WTFBins**       | Repository of suspicious Windows binaries and their behaviors.             | [https://wtfbins.wtf/](https://wtfbins.wtf/)              |

---

## Drivers and Low-Level Components

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **Bootloaders**   | Curated list of known malicious bootloaders for various operating systems. | [https://www.bootloaders.io/](https://www.bootloaders.io/) |
| **LOLDrivers**    | A collection of vulnerable and malicious Windows drivers.                  | [https://www.loldrivers.io/](https://www.loldrivers.io/)   |

---

## Applications and Tools

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **LOLAPPS**       | Documents built-in and third-party apps abused for malicious purposes.     | [https://lolapps-project.github.io/](https://lolapps-project.github.io/) |
| **LOLRMM**        | Curated list of Remote Monitoring and Management tools potentially abused. | [https://lolrmm.io/](https://lolrmm.io/)                  |

---

## Hardware and Firmware

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **LOTH**          | Guidance on identifying and utilizing malicious hardware/devices.          | [https://lothardware.com.tr/](https://lothardware.com.tr/)|

---

## Evasion and Exploitation Techniques

| Project Name            | Description                                                                 | URL                                                        |
|-------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **Argument Injection Vectors** | A curated list of exploitable options for argument injection bugs.   | [https://sonarsource.github.io/argument-injection-vectors/](https://sonarsource.github.io/argument-injection-vectors/) |
| **Evasions**            | Resource for understanding and implementing various evasion techniques.    | [https://evasions.checkpoint.com/](https://evasions.checkpoint.com/) |
| **HijackLibs**          | Collection of DLL hijacking techniques and vulnerable libraries.           | [https://hijacklibs.net/](https://hijacklibs.net/)         |
| **LOFL**                | Cmdlets and binaries for remote system activities and unconventional persistence. | [https://lofl-project.github.io/](https://lofl-project.github.io/) |
| **LOTD**                | Inventories development tools in CI/CD pipelines with RCE features.        | [https://boostsecurityio.github.io/lotp/](https://boostsecurityio.github.io/lotp/) |
| **LOTS Project**        | Living Off Trusted Sites - Legitimate domains abusable by attackers.       | [https://lots-project.com/](https://lots-project.com/)     |
| **LOTTunnels**          | Documents digital tunnels abused for data exfiltration, persistence, etc. | [https://lottunnels.github.io/](https://lottunnels.github.io/) |
| **LOTWebhooks**         | Documents webhooks exploited for data exfiltration and C2 communications. | [https://lotwebhooks.github.io/](https://lotwebhooks.github.io/) |
| **Sploitify**           | Database of exploits and vulnerabilities for systems and applications.    | [https://sploitify.haxx.it/](https://sploitify.haxx.it/)   |

---

## Persistence Mechanisms

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **Persistence Info** | Compiles Windows persistence techniques for detection and mitigation. | [https://persistence-info.github.io/](https://persistence-info.github.io/) |

---

## Certificates and Trust

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **LOLCerts**      | Collects details of code signing certificates abused by malicious actors.  | [https://github.com/WithSecureLabs/lolcerts](https://github.com/WithSecureLabs/lolcerts) |

---

## Command and Control

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **LOLC2**         | Collection of C2 frameworks leveraging legitimate services to evade detection. | [https://lolc2.github.io/](https://lolc2.github.io/)   |

---

## Active Directory and Windows-Specific

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **LOLAD**         | Comprehensive collection of Active Directory techniques for offensive ops. | [https://lolad-project.github.io/](https://lolad-project.github.io/) |
| **WADComs**       | Collection of one-liners and commands for Windows AD environments.         | [https://wadcoms.github.io/](https://wadcoms.github.io/)   |

---

## APIs and Malware Analysis

| Project Name      | Description                                                                 | URL                                                        |
|-------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **MalAPI**        | Comprehensive Windows API reference for malware analysis and red teaming.  | [https://malapi.io/](https://malapi.io/)                  |

---

## Miscellaneous

| Project Name          | Description                                                                 | URL                                                        |
|-----------------------|-----------------------------------------------------------------------------|------------------------------------------------------------|
| **FileSec**           | Comprehensive database of file extensions and associated security risks.   | [https://filesec.io/](https://filesec.io/)                |
| **LOLBins CTI Driven**| Helps understand LOLBin usage by threat actors in a graphical format.      | [https://lolbins-ctidriven.vercel.app/](https://lolbins-ctidriven.vercel.app/) |
| **Project Lost**      | Lesser-known techniques and tools for red teaming and penetration testing. | [https://0xanalyst.github.io/Project-Lost/](https://0xanalyst.github.io/Project-Lost/) |

---

## How to Contribute

We welcome contributions to make this list even more comprehensive! If you know of a resource that fits and isn’t already included, please:

1. Open an issue or submit a pull request.
2. Provide the following details:
   - **Project Name**
   - **Description**
   - **URL**
   - **Suggested Category**

### Guidelines
- Resources must be publicly accessible.
- They should relate to LOTL techniques or similar security concepts.
- They should offer unique value not already covered by existing entries.

Contributions to improve descriptions or correct errors are also appreciated!

---

## License

This work is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.en). Feel free to share and adapt, provided you give appropriate credit.

---

## Acknowledgments

This list draws inspiration from various "Awesome" lists in the security community and consolidates resources related to LOTL techniques. A special thanks to the maintainers of the projects listed here for their invaluable contributions to cybersecurity.
