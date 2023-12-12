# Proof-of-Concept - Dell Enterprise SONiC Multi-site DCI Example


[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](#-how-to-contribute)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Dell-Networking/PoC-DCI-Multisite-DES/blob/main/LICENSE.md)
[![GitHub issues](https://img.shields.io/github/issues/Dell-Networking/PoC-DCI-Multisite-DES)](https://github.com/Dell-Networking/PoC-DCI-Multisite-DES/issues)

Built and maintained by [Ben Goldstone](https://github.com/benjamingoldstone/) and [Contributors](https://github.com/Dell-Networking/PoC-DCI-Multisite-DES/graphs/contributors)

------------------

Welcome! In this proof-of-concept we'll be looking at the new Multi-Site DCI functionality introduced in Dell Enterprise SONiC 4.0. This allows users to more efficiently set up L2-adjacent connectivity between datacenters that are running VXLAN/BGP/EVPN. For accomplishing this, we utilize border gateways (BGW).

## Contents

- [Description and Objective](#-description-and-objective)
- [Requirements](#-requirements)
- [Network Diagram](#-network-diagram)
- [Verification Commands](#-verfication-commands)
- [How to Contribute](#-how-to-contribute)


## 🚀 Description and Objective

Walking through this example of how to leverage the new Multi-Site DCI functionality present in Dell Enterprise SONiC 4.0+ should get you familiar with building out L2 extension connectivity between datacenters enabling you to adopt these concepts into your production builds.


## 📋 Requirements

  * GNS3 / EVE-NG virtual environment or physical hardware
  * Dell Enterprise SONiC 4.0 or newer (virtual image for virtual environment or Enterprise-licensed version for hardware)
  * Ansible Core 2.12.10 or later.
  * The latest version of the SONiC collection from Ansible Galaxy:
		  - $ ansible-galaxy collection install dellemc.enterprise_sonic
## 🗺️ Network Diagram
![image](https://github.com/dcromie/PoC-DCI-Multisite-DES/assets/75340463/2cdc0a66-45d3-46fd-a319-e179ab452ad9)
![image](https://github.com/dcromie/PoC-DCI-Multisite-DES/assets/75340463/d70176df-d95f-4fa5-bfb8-832ea9e36d84)


## 👏 How to Contribute

We welcome contributions to the project. Please reference the [CONTRIBUTING](https://github.com/Dell-Networking/PoC-Index/blob/main/CONTRIBUTING.md) guide in the PoC-Index repo for more details (this guide is common across Dell Networking PoC projects).



