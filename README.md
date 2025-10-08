# Intro to VPNs Overview Guide

**TODO:** A brief introductory guide to what VPNs are and how they operate.

#### Table of Contents

1. [What Are VPNs?](#definition)
2. [Palo Alto GlobalProtect](#palo)
3. [Fortinet FortiClient VPN and EMS](#fortinet)
4. [SonicWall SMA VPNs](#sonicwall)
5. [Comparing Three Vendors: Palo Alto, Fortinet, SonicWall](#comparison)
6. [Supplemental Resources](#supplemental)

<hr />

## <a name="definition">1. What Are VPNs?</a>

<hr />

## <a name="palo">2. Palo Alto GlobalProtect</a>

<hr />

## <a name="fortinet">3. Fortinet FortiClient VPN and EMS</a>

<hr />

## <a name="sonicwall">4. SonicWall SMA VPNs</a>

<hr />

## <a name="comparison">5. Comparing Three Vendors: Palo Alto, Fortinet, SonicWall</a>

*Palo Alto GlobalProtect* VPNs may be a strong option for large organizations/enterprises with technical expertise, a desire for granular app-level controls over traffic and policies, and are looking to integrate their VPN solutions with other Palo Alto networking products (such as Palo Alto Next-Generation Firewalls).

*Fortinet FortiClient VPN/EMS* may be a good choice for organizations that already use Fortinet's Security Fabric, face budget restrictions, and/or need to unite their endpoint security and remote access solutions with a centrally-managed interface.

*SonicWall SMA VPNs* offer physical and virtual deployment capabilities, multitenancy, endpoint management, app-based remote access control, and support for a diversity of devices.

| *Consideration* | [*Palo Alto GlobalProtect*](https://www.paloaltonetworks.com/sase/globalprotect) | [*Fortinet FortiClient VPN/EMS*](https://www.fortinet.com/support/product-downloads) | [*SonicWall SMA VPN*](https://www.sonicwall.com/products/remote-access) |
| :---: | :---: | :----: | :----: |
| **Deployment/Configurations** | On-Premises (using Palo Alto NGFWs). Licensing fees for mobile support. | Varied possible configurations. No licensing fees for default VPN package. | Virtual or physical. Virtual can be through private or public clouds (e.g., AWS, Azure, VMWare). |
| **VPN Access** | Supports secure remote access connections to corporate networks by using client-based apps. | SSL VPN and client-based IPsec connections are both supported, with the freely available VPN app allowing for basic connectivity. | Multiple connection options natively provided: Global VPN Client (via IPsec), Mobile Connect, and NetExtender (using an SSL thin-client). |
| **Management Approach** | Using Palo Alto NGFWs, with the GlobalProtect portal allowing endpoint configurations. | Either using FortiGate firewalls or the FortiClient EMS (for complex configurations). | SMA allows for virtual and physical device deployments and a conveniently centralized management mechanism. |
| **Endpoint Security Approach** | Primarily VPN-based, with alternative security available for mobile clients. | Both VPN and other mechanisms (e.g., app firewalls, anti-virus, web filtering), with the free version being just VPN-based. | Prior to network access being secured, Endpoint Control (EPC) technology evaluates device compliance and security posture. |
| **24/7 Protection** | Apps instantly adjust to user location, connecting to the gateway that best provides reliable/persistent protection. | 'Always-on' VPN option is available for reliable/persistent protection. | Provides an 'always-on' option to instantly connect when network access is initially detected, which can be modified to restrict network access when the VPN is not connected. |
| **Zero-Trust Network Access** | Prisma Access integrates zero-trust network access principles. | The FortiClient agent, integrated within the Fortinet Security Fabric, provides zero-trust network access (which EMS manages in a centralized approach). | SMA can provide granular access controls, permitting only trusted devices and authorized users to connect. |
| **Learning Curve** | May be more advanced/require some familiarity to get the hang of. | Beginner-friendly, with simple setup and GUI with well-organized panes. | Easy to access remotely via clientless access portal and SSL thin-clients. |

<hr />

## <a name="supplemental">6. Supplemental Resources</a>

* *[Palo Alto GlobalProtect Official Webpage](https://www.paloaltonetworks.com/sase/globalprotect)*
* *[Official Fortinet Product Downloads Page](https://www.fortinet.com/support/product-downloads)*
* *[SonicWall SMAs Official Webpage](https://www.sonicwall.com/products/remote-access)*
