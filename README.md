# Awesome Proxmox VE with stars

<div align="center">

![Proxmox VE Banner](https://www.proxmox.com/images/proxmox/Proxmox-logo-800.png)

  <h3>The Ultimate Collection of Proxmox VE Resources</h3>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/issues) ⭐ 1,092 | 🐛 0 | 📅 2026-08-26
[![Stars](https://img.shields.io/github/stars/Corsinvest/awesome-proxmox-ve?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve) ⭐ 1,092 | 🐛 0 | 📅 2026-08-26
[![Forks](https://img.shields.io/github/forks/Corsinvest/awesome-proxmox-ve?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/fork) ⭐ 1,092 | 🐛 0 | 📅 2026-08-26

  <p><em>A comprehensive collection of <strong>excellent</strong> <a href="https://pve.proxmox.com">Proxmox VE</a> resources including documentation, tools, tutorials, and community contributions.</em></p>
</div>

***

## Contents

* [Proxmox VE](#proxmox-ve)
* [Management](#management)
* [VPS Control Panels](#vps-control-panels)
* [VDI](#vdi)
* [Monitoring](#monitoring)
* [Backup Tools](#backup-tools)
* [Storage](#storage)
* [Inventory](#inventory)
* [AI](#ai)
* [API & SDKs](#api--sdks)
* [Other Tools](#other-tools)
* [CV4PVE Suite](#cv4pve-suite)
* [Mobile Apps](#mobile-apps)
* [Desktop Apps](#desktop-apps)
* [Documentation](#documentation)
* [Tutorials, Blogs & Video](#tutorials-blogs--video)
* [Templates & Marketplace](#templates--marketplace)
* [Security Tools & Best Practices](#security-tools--best-practices)
* [Community, Forum & Social](#community-forum--social)
* [Utilities & Scripts](#utilities--scripts)
* [Benchmark & Comparisons](#benchmark--comparisons)
* [YouTube Channels](#youtube-channels)
* [Forums](#forums)
* [Contributing](#contributing)
* [License](#license)

***

## Proxmox VE

* [Proxmox Virtual Environment](https://proxmox.com/en/products/proxmox-virtual-environment/overview)\
  Complete, open-source server management platform for enterprise virtualization.\
  \[[Download ISO](https://proxmox.com/en/downloads/proxmox-virtual-environment/iso)] • \[[Install Docs](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html)] • \[[Forum](https://forum.proxmox.com/)]

***

## Management

* [CV4PVE-ADMIN (Web UI)](https://corsinvest.it/cv4pve-admin-proxmox/)
  Powerful and easy-to-use web administration interface for monitoring/manage multiple Proxmox VE clusters from a single portal.
  [GitHub](https://github.com/Corsinvest/cv4pve-admin) ⭐ 400 | 🐛 3 | 🌐 C# | 📅 2026-08-27
* [P3Portal](https://github.com/P3Portal-org/p3portal) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22
  Web portal to manage Proxmox VE: cluster dashboard, Ansible/Packer automation, networking/SDN/firewall, VM/LXC lifecycle and fine-grained RBAC. Core is AGPLv3; an optional Plus edition adds declarative Stacks (OpenTofu), pools & quotas, 4-eyes approval and visual editors.
* [MultiPortal](https://multiportal.io/)
* [Convoy](https://convoypanel.com/)
* [PegaProx](https://pegaprox.com/) — Datacenter management UI with unified multi-cluster control, intelligent load balancing and seamless cross-cluster migrations.
* [ProxCenter](https://www.proxcenter.io/) — Modern web interface for multi-cluster management, cross-hypervisor migration and workload balancing from a single pane of glass.
* [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager)
* [AtlasPVE](https://atlaspve.com) — Safety-focused control layer for Proxmox VE: live map of VMs and storage, host updates sorted by impact, snapshot-before-change and one-click rollback. Commercial, early access.
* [Tainer](https://tainer.sh) — Management platform for Proxmox VE.

***

## CV4PVE Suite

**Advanced official Corsinvest tools for integrated multi-platform Proxmox VE management.**

* [**CV4PVE-AUTOSNAP**](https://github.com/Corsinvest/cv4pve-autosnap) ⭐ 563 | 🐛 4 | 🌐 C# | 📅 2026-07-03
  Automatic snapshot tool for Proxmox VE VMs and containers with retention policies.
* [**CV4PVE-ADMIN**](https://github.com/Corsinvest/cv4pve-admin) ⭐ 400 | 🐛 3 | 🌐 C# | 📅 2026-08-27
  Web management platform for Proxmox VE clusters — like vCenter but for Proxmox.
* [**CV4PVE-PEPPER**](https://github.com/Corsinvest/cv4pve-pepper) ⭐ 150 | 🐛 2 | 🌐 C# | 📅 2026-04-14
  CLI launcher for SPICE remote viewer on Proxmox VE VMs with automatic ticket handling.
* [**CV4PVE-VDI**](https://github.com/Corsinvest/cv4pve-vdi) ⭐ 124 | 🐛 3 | 🌐 C# | 📅 2026-07-30
  Desktop VDI client for Proxmox VE — SPICE, VNC, RDP and SSH console launchers.
* [**CV4PVE-BOTGRAM**](https://github.com/Corsinvest/cv4pve-botgram) ⭐ 93 | 🐛 0 | 🌐 C# | 📅 2026-04-09
  Telegram bot to manage and monitor Proxmox VE from your mobile.
* [**CV4PVE-API-POWERSHELL**](https://github.com/Corsinvest/cv4pve-api-powershell) ⭐ 90 | 🐛 0 | 🌐 PowerShell | 📅 2026-07-15\
  Official PowerShell module and CmdLets for managing Proxmox VE from Windows, Azure DevOps, etc.
* [**CV4PVE-CLI**](https://github.com/Corsinvest/cv4pve-cli) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-07-14
  kubectl-style remote CLI for Proxmox VE with multi-cluster support and shell completion.
* [**CV4PVE-API**](https://github.com/Corsinvest/cv4pve-api-dotnet) ⭐ 84 | 🐛 1 | 🌐 C# | 📅 2026-06-01\
  Official Corsinvest API client to integrate, develop and customize Proxmox in .NET/C# ([NuGet](https://www.nuget.org/packages/Corsinvest.ProxmoxVE.Api/)).
* [**CV4PVE-API-PHP**](https://github.com/Corsinvest/cv4pve-api-php) ⭐ 83 | 🐛 1 | 🌐 PHP | 📅 2026-05-29\
  Official PHP API client and library for automating Proxmox in PHP/Composer environments.
* [**CV4PVE-API-JAVA**](https://github.com/Corsinvest/cv4pve-api-java) ⭐ 78 | 🐛 0 | 🌐 Java | 📅 2026-07-26\
  Official Java API client.
* [**CV4PVE-REPORT**](https://github.com/Corsinvest/cv4pve-report) ⭐ 55 | 🐛 2 | 🌐 C# | 📅 2026-06-01
  Export Proxmox VE infrastructure to a navigable Excel report — like RVTools for Proxmox.
* [**CV4PVE-DIAG**](https://github.com/Corsinvest/cv4pve-diag) ⭐ 51 | 🐛 3 | 🌐 C# | 📅 2026-08-31
  Diagnostic and health-check tool for Proxmox VE clusters.
* [**CV4PVE-API-JAVASCRIPT**](https://github.com/Corsinvest/cv4pve-api-javascript) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-29\
  Official JavaScript client for Node.js and frontend (automation, webapps).
* [**CV4PVE-METRICS-EXPORTER**](https://github.com/Corsinvest/cv4pve-metrics-exporter) ⭐ 27 | 🐛 0 | 🌐 C# | 📅 2026-04-20
  Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
* [**CV4PVE-NODE-PROTECT**](https://github.com/Corsinvest/cv4pve-node-protect) ⭐ 18 | 🐛 0 | 🌐 C# | 📅 2026-04-20
  Backup and restore Proxmox VE node configuration files via SSH.

**Related online suite:**

* [cv4pve-tools.com](https://www.cv4pve-tools.com)\
  Official Corsinvest portal for metrics, comparator, converter, online tools and demos, documentation and API reference.

***

## VPS Control Panels

* [Proxmox VE VPS For WHMCS](https://www.modulesgarden.com/products/whmcs/proxmox-ve-vps)
* [SolusVM](https://solusvm.com/)
* [Virtualizor](https://www.virtualizor.com/) \[[Docs](https://www.virtualizor.com/docs/)]

***

## VDI

* [PVE-VDIClient](https://github.com/joshpatten/PVE-VDIClient) ⭐ 1,088 | 🐛 44 | 🌐 Python | 📅 2026-04-10 — Lightweight VDI kiosk client for launching Proxmox VE VM consoles.
* [CV4PVE-VDI](https://github.com/Corsinvest/cv4pve-vdi) ⭐ 124 | 🐛 3 | 🌐 C# | 📅 2026-07-30 — Official Corsinvest desktop VDI client for Proxmox VE with SPICE, VNC, RDP and SSH console launchers.
* [Kasm Workspaces](https://www.kasmweb.com/) — Streaming containerized desktops and apps with Proxmox VE as an autoscale provider.

***

## Monitoring

* [Pulse](https://github.com/rcourtman/Pulse) ⭐ 6,656 | 🐛 38 | 🌐 Go | 📅 2026-09-02 — Real-time monitoring for Proxmox VE and PBS with guest, storage and backup visibility, alerting, and a multi-client mode for providers.
* [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter) ⭐ 1,448 | 🐛 32 | 🌐 Python | 📅 2026-08-28
* [check\_pve](https://github.com/nbuchwitz/check_pve) ⭐ 134 | 🐛 10 | 🌐 Python | 📅 2026-02-05 — Icinga/Nagios plugin to monitor Proxmox VE nodes, VMs, storage and cluster health.
* [cv4pve-metrics-exporter](https://github.com/Corsinvest/cv4pve-metrics-exporter) ⭐ 27 | 🐛 0 | 🌐 C# | 📅 2026-04-20 — Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
* [Proxmox Atlas](https://github.com/Losstarot85/proxmox-atlas) ⭐ 16 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-29 — Real-time multi-cluster monitoring dashboard for Proxmox VE infrastructure
* [CheckMK](https://checkmk.com/blog/proxmox-monitoring)
* [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php)
* [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/)
* [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/)
* [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/)
* [Zabbix](https://www.zabbix.com/de/integrations/proxmox)

***

## Backup Tools

* [CV4PVE-AUTOSNAP](https://github.com/Corsinvest/cv4pve-autosnap) ⭐ 563 | 🐛 4 | 🌐 C# | 📅 2026-07-03
  * Snapshot automation with policies for Proxmox VE.
* [proxmox-backup](https://github.com/tis24dev/proxmox-backup) ⭐ 515 | 🐛 3 | 🌐 Go | 📅 2026-08-31
* [Joulenap](https://github.com/Joulenap/joulenap) ⭐ 123 | 🐛 0 | 🌐 Python | 📅 2026-08-27 — Web UI and scheduler for backups to a Proxmox Backup Server that stays powered off: wakes it, runs the backups, prunes, garbage-collects and shuts it down. Any number of PVE hosts and PBS, PBS to PBS sync, notifications.
* [PBS\_Chunk\_Checker](https://github.com/VoltKraft/PBS_Chunk_Checker) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2026-04-27
* [pve-bindsnap](https://github.com/bitranox/pve-bindsnap) ⭐ 6 | 🐛 0 | 🌐 Perl | 📅 2026-08-27
  * Snapshot LXC containers that have bind/device mounts, which stock Proxmox greys out. Can also exclude specific volumes from a snapshot. Works with the GUI, API, pct and cv4pve-autosnap.
* [pbs-autobackup](https://github.com/ferr079/pbs-autobackup) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-07-31 — Unattended backup cycle for a Proxmox Backup Server that stays powered off: Wake-on-LAN, enable the storage, vzdump every node, prune, garbage-collect, then shut the host back down.
* [BACKUP EAGLE](https://www.backup-eagle.com/product/proxmox)
* [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/)
* [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) \[[Docs](https://www.bdrsuite.com/technical-documents/)] \[[Download](https://www.bdrsuite.com/vembu-bdr-suite-download/)]
* [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/)
* [Commvault Backup\&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) \[[Docs](https://documentation.commvault.com/11.38/essential/backups_for_proxmox_vms.html)]
* [NAKIVO Backup & Replication](https://www.nakivo.com/proxmox-backup/) \[[Trial](https://www.nakivo.com/resources/download/trial-download/)] \[[Docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)]
* [Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) \[[Download](https://proxmox.com/en/downloads/proxmox-backup-server)] \[[Docs](https://pbs.proxmox.com/docs/installation.html)]
* [SEP sesam](https://www.sep.de/solutions/proxmox-hypervisor/)
* [Storware Backup\&Recovery](https://storware.eu/solutions/virtual-machine-backup-and-recovery/proxmox-ve-backup-and-recovery/)
* [Veeam Backup for Proxmox](https://www.veeam.com/blog/veeam-backup-for-proxmox.html)
* [Vinchin Backup & Recovery](https://www.vinchin.com/proxmox-backup.html) \[[Trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html)] \[[Docs](https://helpcenter.vinchin.com/)]

***

## Storage

* [TrueNAS Proxmox VE Storage Plugin](https://github.com/WarlockSyno/TrueNAS-Proxmox-VE-Storage-Plugin) ⚠️ Archived
* [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin) ⭐ 41 | 🐛 14 | 🌐 Perl | 📅 2026-05-03
* [Proxmox VE Plugin for HPE Nimble Storage (iSCSI)](https://github.com/brngates98/pve-nimble-plugin) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2026-07-20 — Integration of HPE Nimble Storage arrays with Proxmox VE over iSCSI, using the Nimble REST API to create and manage volumes.
* [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/)
* [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/)
* [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html)
* [StorPool](https://storpool.com/proxmox-virtual-environment) — High-performance distributed storage platform with native Proxmox VE integration.
* [Everpure](https://support.everpuredata.com/access?dita:id=m_proxmox) — Storage technology integrations for Proxmox VE.

***

## Inventory

* [netbox-proxbox](https://github.com/netdevopsbr/netbox-proxbox) ⭐ 589 | 🐛 4 | 🌐 Python | 📅 2026-09-02 — NetBox plugin to sync and inventory Proxmox VE clusters, nodes and VMs.
* [CV4PVE-REPORT](https://github.com/Corsinvest/cv4pve-report) ⭐ 55 | 🐛 2 | 🌐 C# | 📅 2026-06-01 — Export Proxmox VE infrastructure to a navigable Excel report — like RVTools for Proxmox.
* [iTop CMDB: Data collector for Proxmox](https://www.itophub.io/wiki/page?id=extensions%3Acombodo-proxmox-data-collector) — Combodo data collector to import Proxmox VE assets into the iTop CMDB.
* [netbox Enterprise Proxmox VE Integration](https://netboxlabs.com/docs/integrations/platform-integrations/proxmox-ve/) — Official NetBox Labs integration to inventory Proxmox VE infrastructure.
* [Proxmox Virtual Environment CMDB importer](https://versio.io/en/import-proxmox-cmdb-configuration-item.html) — Import Proxmox VE configuration items into the Versio.io CMDB.

***

## AI

* [Proximo](https://github.com/john-broadway/proximo) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2026-09-01 — AI-driven natural-language assistant for managing Proxmox VE.
* [ProxmoxMCP-Plus](https://github.com/rodaddy/ProxmoxMCP-Plus) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2026-08-23 — Enhanced Proxmox MCP server with advanced virtualization management and full OpenAPI integration.
* [ProxmoxMCP](https://github.com/rodaddy/ProxmoxMCP) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-03-13 — MCP server for Proxmox VE management, enabling AI assistants to control VMs, containers, and cluster resources.

***

## API & SDKs

### Community Maintained

#### Python

* [Proxmoxia (Wrapper)](https://github.com/baseblack/Proxmoxia) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2013-06-02
* [proxmox-utils (Console Client)](https://github.com/remofritzsche/proxmox-utils) ⚠️ Archived
* [pmxc (Console Client)](https://github.com/pcdummy/pmxc) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2021-08-18
* [proxmoxer](https://pypi.python.org/pypi/proxmoxer)

#### PowerShell

* [cv4pve-api-powershell](https://github.com/Corsinvest/cv4pve-api-powershell) ⭐ 90 | 🐛 0 | 🌐 PowerShell | 📅 2026-07-15

#### Ruby

* [nledez/proxmox](https://github.com/nledez/proxmox) ⭐ 38 | 🐛 8 | 🌐 Ruby | 📅 2019-03-21

#### NodeJS

* [cv4pve-api-javascript](https://github.com/Corsinvest/cv4pve-api-javascript) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-29
* [npm:proxmox](https://www.npmjs.com/package/proxmox)
* [AmiCole/pvea](https://github.com/AmiCole/pvea)

#### C\#

* [cv4pve-pepper](https://github.com/Corsinvest/cv4pve-pepper) ⭐ 150 | 🐛 2 | 🌐 C# | 📅 2026-04-14
* [cv4pve-botgram](https://github.com/Corsinvest/cv4pve-botgram) ⭐ 93 | 🐛 0 | 🌐 C# | 📅 2026-04-09
* [cv4pve-cli](https://github.com/Corsinvest/cv4pve-cli) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-07-14
* [cv4pve-api-dotnet](https://github.com/Corsinvest/cv4pve-api-dotnet) ⭐ 84 | 🐛 1 | 🌐 C# | 📅 2026-06-01
* [ProxmoxSharp](https://github.com/ionelanton/ProxmoxSharp) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2016-12-16

#### PHP

* [ProxmoxVE](https://github.com/ZzAntares/ProxmoxVE) ⭐ 176 | 🐛 10 | 🌐 PHP | 📅 2023-02-02
* [pve2-api-php-client](https://github.com/CpuID/pve2-api-php-client) ⭐ 96 | 🐛 9 | 🌐 PHP | 📅 2024-06-24
* [cv4pve-api-php](https://github.com/Corsinvest/cv4pve-api-php) ⭐ 83 | 🐛 1 | 🌐 PHP | 📅 2026-05-29
* [MrKampf/proxmoxVE](https://github.com/MrKampf/proxmoxVE) ⭐ 60 | 🐛 7 | 🌐 PHP | 📅 2026-08-04
* [pve-cli-utils](https://github.com/aheahe/pve-cli-utils) ⭐ 10 | 🐛 0 | 🌐 PHP | 📅 2021-01-31

#### Java

* [cv4pve-api-java](https://github.com/Corsinvest/cv4pve-api-java) ⭐ 78 | 🐛 0 | 🌐 Java | 📅 2026-07-26
* [pve2-api-java](https://github.com/Elbandi/pve2-api-java) ⭐ 24 | 🐛 2 | 🌐 Java | 📅 2012-05-23

#### Perl

* [Net-Proxmox-VE (CPAN)](http://search.cpan.org/~djzort/Net-Proxmox-VE-0.006/)

#### Go

* [proxmox-api-go](https://github.com/Telmate/proxmox-api-go) ⭐ 491 | 🐛 55 | 🌐 Go | 📅 2026-08-30
* [go-proxmox](https://github.com/luthermonson/go-proxmox) ⭐ 283 | 🐛 2 | 🌐 Go | 📅 2026-08-09
* [Packer Plugin for Proxmox VE](https://developer.hashicorp.com/packer/integrations/hashicorp/proxmox)

#### Terraform

* [terraform-provider-proxmox (Telmate)](https://github.com/Telmate/terraform-provider-proxmox) ⭐ 2,948 | 🐛 124 | 🌐 Go | 📅 2026-08-30

***

## Other Tools

* [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE) ⭐ 29,468 | 🐛 20 | 🌐 Shell | 📅 2026-09-01
* [ProxMenux](https://github.com/MacRimi/ProxMenux) ⭐ 2,925 | 🐛 25 | 🌐 TypeScript | 📅 2026-09-01
* [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox) ⭐ 2,207 | 🐛 113 | 🌐 Go | 📅 2026-09-01
* [PVE-mods](https://github.com/Meliox/PVE-mods) ⭐ 1,899 | 🐛 19 | 🌐 Shell | 📅 2026-08-23
* [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility) ⭐ 966 | 🐛 10 | 🌐 Shell | 📅 2026-05-17
* [ProxLB](https://github.com/gyptazy/ProxLB) ⭐ 893 | 🐛 16 | 🌐 Python | 📅 2026-01-15
* [pvetui](https://github.com/devnullvoid/pvetui) ⭐ 718 | 🐛 12 | 🌐 Go | 📅 2026-08-31
* [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) ⭐ 579 | 🐛 0 | 🌐 Ruby | 📅 2026-08-30 — GitOps workflow to manage Proxmox VE infrastructure declaratively.
* [proxmox-backup](https://github.com/tis24dev/proxmox-backup) ⭐ 515 | 🐛 3 | 🌐 Go | 📅 2026-08-31
* [Cluster API Provider for Proxmox VE (CAPMOX)](https://github.com/ionos-cloud/cluster-api-provider-proxmox) ⭐ 477 | 🐛 117 | 🌐 Go | 📅 2026-08-31
* [pve-microvm](https://github.com/rcarmo/pve-microvm) ⭐ 369 | 🐛 2 | 🌐 Shell | 📅 2026-08-24 — Run lightweight microVMs on Proxmox VE.
* [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale) ⭐ 302 | 🐛 3 | 🌐 Python | 📅 2026-07-20
* [osx-proxmox](https://github.com/lucid-fabrics/osx-proxmox-next) ⭐ 267 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - One-command macOS VM automation for Proxmox 9 with TUI wizard, recovery auto-download, and AMD/Intel support.
* [LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) ⭐ 256 | 🐛 18 | 🌐 Python | 📅 2026-08-25
* [lws](https://github.com/fabriziosalmi/lws) ⭐ 74 | 🐛 8 | 🌐 Python | 📅 2026-07-26 — Unified CLI for Proxmox, LXC, and Docker.
* [Proxmox Manager](https://github.com/TimInTech/proxmox-manager) ⭐ 71 | 🐛 1 | 🌐 Shell | 📅 2026-08-31 — CLI toolkit for common Proxmox VE administration tasks.
* [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2026-08-16
* [proxtagger](https://github.com/reginleif88/proxtagger) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-05-12
* [ProxCLMC](https://github.com/gyptazy/ProxCLMC) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2026-01-15 — Lightweight tool to determine the maximum CPU compatibility level supported across all nodes in a Proxmox VE cluster.
* [ProxSnap](https://github.com/gyptazy/ProxSnap) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-01-22 — Lightweight CLI tool for auditing and cleaning up snapshots across Proxmox VE clusters.
* [Proxmox Report Generator](https://github.com/AungThuMyint/ProxmoxReportGenerator) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-06-11 — Generate infrastructure reports for Proxmox VE clusters.
* [valheim-proxmox](https://github.com/PawelSzymanski89/valheim-proxmox) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-04 — One-command Valheim dedicated server in an LXC, with a web panel for players, bans, worlds, backups and mods.
* [ProxDeploy](https://github.com/NordicsSys/proxdeploy) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-08 — Production-ready Python CLI to deploy, list, and destroy KVM guests from YAML templates, with cloud-init, SSH provisioning, dry-run, and API retry resilience.
* [proxmox-ftagent](https://github.com/Flowtriq/proxmox-ftagent) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 — One-command LXC deployment of the Flowtriq DDoS detection agent on Proxmox VE, with automatic dependency and systemd service setup.
* [Snapbridge](https://github.com/abdoufermat5/snapbridge) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-04-16 - Rust CLI for managing Proxmox snapshots on NetApp ONTAP-backed storage (for both NAS and SAN).
* [Ansible Module - Proxmox VE Cluster](https://docs.ansible.com/ansible/latest/collections/community/general/proxmox_module.html)
* [ProxSave](https://proxsave.dev/) — Backup and restore of Proxmox PBS & PVE system files — save your entire environment and restore it at any time.

***

## Tutorials, Blogs & Video

* [ServeTheHome - Proxmox VE Tutorials](https://www.servethehome.com/tag/proxmox-ve/)
* [Techno Tim - Proxmox Guides (Blog & Video)](https://technotim.live/tags/proxmox/)
* [Nick Sherlock - macOS on Proxmox](https://www.nicksherlock.com/tag/proxmox/)
* [VirtualizationHowTo - Proxmox](https://www.virtualizationhowto.com/tag/proxmox-ve/)
* [The Homelab Wiki - Proxmox Section](https://wiki.homelabos.com/other/proxmox/)

***

## Templates & Marketplace

* [TrueNAS SCALE Community Catalog](https://github.com/truecharts/apps) ⭐ 1,353 | 🐛 16 | 🌐 Go Template | 📅 2026-09-01
* [LinuxServer Container Templates](https://github.com/linuxserver/docker-templates) ⭐ 41 | 🐛 0 | 📅 2026-07-18
* [TurnKey Linux Proxmox LXC Templates](https://www.turnkeylinux.org/docs/proxmox-lxc)
* [TTECK Proxmox LXC Templates & Utilities](https://tteck.github.io/Proxmox/)

***

## Security Tools & Best Practices

* [Proxmox Security Best Practices (official)](https://pve.proxmox.com/wiki/Security)
* [OpenSCAP - Security audit tool](https://www.open-scap.org/)
* [Falco Security - Runtime Linux Security](https://falco.org/)
* [Official Proxmox Firewall Guide](https://pve.proxmox.com/pve-docs/pve-firewall.8.html)
* [fail2ban for Proxmox (HowToForge)](https://www.howtoforge.com/tutorial/how-to-protect-proxmox-ve-with-fail2ban-and-ufw/)
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 886 | 🐛 2 | 🌐 Python | 📅 2026-08-29 - Open source (GPL-3.0) autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes.

***

## Community, Forum & Social

* [Official Proxmox Forum](https://forum.proxmox.com/)
* [Reddit Proxmox VE](https://www.reddit.com/r/Proxmox/)
* [Telegram Proxmox Italy](https://t.me/ProxmoxVE_Italia)
* [Discord Proxmox Global (unofficial)](https://discord.gg/WvG4Yc0)
* [Discord Proxcord (unofficial)](https://discord.gg/w9Y5UPz4FG)
* [Facebook Proxmox Group](https://www.facebook.com/groups/proxmox/)

***

## Utilities & Scripts

* [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE) ⭐ 29,468 | 🐛 20 | 🌐 Shell | 📅 2026-09-01
* [Proxmox Dark Theme (User script)](https://github.com/Weilbyte/PVEDiscordDark) ⭐ 2,540 | 🐛 14 | 🌐 Sass | 📅 2023-03-04
* [Proxmox VE Clean Snapshots](https://github.com/Corsinvest/cv4pve-autosnap) ⭐ 563 | 🐛 4 | 🌐 C# | 📅 2026-07-03
* [pve-disk-shrink](https://github.com/Garfieldttt/pve-disk-shrink) ⭐ 34 | 🐛 0 | 🌐 Shell | 📅 2026-08-15 — Dialog-based offline shrinking of Proxmox VE VM disks and LXC volumes (zvol/qcow2/LVM), no live ISO or manual partitioning needed.
* [Proxmox Wake on LAN](https://github.com/Aizen-Barbaros/Proxmox-WoL) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2023-03-24
* [Proxmox VMID Updater](https://github.com/sannier3/proxmox-vmid-updater) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 - Safely renames QEMU VM and LXC container VMIDs, including configurations, storage volumes, snapshots, backups, HA and firewall resources, with transactional rollback.
* [homelab-scripts](https://github.com/ferr079/homelab-scripts) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-07-31 — Small shell toolbox for a Proxmox homelab: cluster and container status through the API, TLS expiry checks for services behind a reverse proxy, bulk HTTP availability checks, and a Loki query wrapper.
* [pve-zsync (ZFS backup/snapshots)](https://pve.proxmox.com/wiki/PVE-zsync)
* [Proxmox VE Backup Checker](https://github.com/paulie1231/pve-backup-check)
* [PVE7to8 - Major Upgrade Script](https://github.com/Corsinvest/cv4pve-pve7to8)
* [Proxmox Mail Gateway Custom Themes](https://github.com/IgorG1/PMG-Theme)
* [ProxMox Repo Manager/No-Subscription Script](https://tteck.github.io/Proxmox/)

***

## Benchmark & Comparisons

* [ServeTheHome Proxmox Benchmarks](https://www.servethehome.com/?s=proxmox+benchmark)
* [OpenBenchmarking Proxmox Results](https://openbenchmarking.org/testbed/2202159-NE-PROXMOXV55)
* [IdleWatt - Homelab Mini-PC Idle-Power & Passthrough Finder](https://idlewatt.vercel.app)

***

## YouTube Channels

### International Channels

* [Proxmox Server Solutions (Official Channel)](https://www.youtube.com/@ProxmoxServerSolutionsGmbH)\
  Webinars, releases, new Proxmox features.
* [ServeTheHome](https://www.youtube.com/c/ServeTheHomeVideo)\
  Proxmox guides, hardware, servers and storage.
* [Techno Tim](https://www.youtube.com/c/TechnoTimLive)\
  Cluster setup, installation, automated backups with Proxmox.
* [Lawrence Systems](https://www.youtube.com/c/LawrenceSystems/search?query=proxmox)\
  Enterprise deep-dives, security and tutorials.
* [Craft Computing](https://www.youtube.com/c/CraftComputing/search?query=proxmox)\
  Real homelab use cases, containers, storage.
* [The Digital Life](https://www.youtube.com/c/TheDigitalLife/search?query=proxmox)\
  Tutorials, LXC, scripting.
* [DB Tech](https://www.youtube.com/c/DBTechYT/search?query=proxmox)\
  Guides on containers and services.

### Italian Channels

* [Stefano Droghetti](https://www.youtube.com/@stefanodroghetti/search?query=proxmox)\
  Italian tutorials on installation, containers and Proxmox use cases.
* [Maurizio Leo](https://www.youtube.com/@MaurizioLeo/search?query=proxmox)\
  Homelab and virtualization.
* [Francesco Mainardi](https://www.youtube.com/@francescomainardi/search?query=proxmox)

***

## Mobile Apps

### Android

* [Proxmox VE Android App](https://play.google.com/store/apps/details?id=com.proxmox.app.pve_flutter_frontend) — Official app to manage VMs, containers, hosts and clusters.
* [ProxMon](https://play.google.com/store/apps/details?id=dev.reimu.proxmon) — View nodes, storage pools, VMs and containers statuses.
* [ProxMan (Android)](https://play.google.com/store/apps/details?id=com.windium.proxman) — Manage Proxmox VE nodes, VMs and containers from Android.
* [Mobile SSH](https://mobile-ssh.github.io) — SSH, SFTP and terminal client for administering Proxmox nodes and guests from Android.

### iOS

* [ProxMan](https://proxman.app) — App for managing Proxmox VE and Proxmox Backup Server environments.
* [Proxmox VE Companion](https://apps.apple.com/de/app/proxmox-ve-companion/id6748314140) — Monitor and manage Proxmox VE environments from iOS.
* [ProxMate](https://apps.apple.com/de/app/proxmate/id6470526961) — Manage your Proxmox server from iOS.
* [ProxMate Backup](https://apps.apple.com/de/app/proxmate-backup/id6618157722) — Manage Proxmox Backup Servers.
* [ProxMobo](https://proxmobo.app/) — Monitoring and management app for Proxmox VE and Proxmox Backup Server.
* [Reeve](https://reeveapp.io) — Monitor and manage Proxmox VE nodes, VMs, and containers from iOS.
* [Mobile SSH](https://mobile-ssh.github.io) — SSH, SFTP and terminal client for administering Proxmox nodes and guests from iOS.

***

## Desktop Apps

### macOS

* [ProxmoxBar](https://github.com/ryzenixx/proxmoxbar-macos) ⭐ 178 | 🐛 2 | 🌐 Swift | 📅 2026-08-26 — Native macOS menu bar app for monitoring and controlling Proxmox VE resources.

***

## Documentation

* [Proxmox Hardening Guide](https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide) ⭐ 551 | 🐛 0 | 📅 2026-02-09 — Actionable recommendations to secure Proxmox VE and Proxmox Backup Server.
* [10 Ways to Ruin Your Proxmox Setup](https://github.com/SwamiRama/10-ways-to-ruin-proxmox) ⭐ 159 | 🐛 1 | 📅 2026-01-05 — Common mistakes and how to avoid them.
* [free-pmx](https://free-pmx.pages.dev/)
* [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox)
* [Proxmox VE Wiki](https://pve.proxmox.com/wiki/Main_Page)
* [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/)

***

## Forums

* [Proxmox Support Forum](https://forum.proxmox.com/)
* [Reddit: Proxmox](https://www.reddit.com/r/Proxmox/)

***

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

The short version: **new entries are always appended at the end of their section**, one suggestion per pull request.

***

## License

This list is under the [Creative Commons Attribution-ShareAlike 1.0 Generic License](https://creativecommons.org/licenses/by-sa/1.0/).
Terms of the license are summarized in the link above.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
