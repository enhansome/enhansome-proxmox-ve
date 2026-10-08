# Awesome Proxmox VE with stars

<div align="center">

![Proxmox VE Banner](https://www.proxmox.com/images/proxmox/Proxmox-logo-800.png)

  <h3>The Ultimate Collection of Proxmox VE Resources</h3>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/issues)
[![Stars](https://img.shields.io/github/stars/Corsinvest/awesome-proxmox-ve?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve)
[![Forks](https://img.shields.io/github/forks/Corsinvest/awesome-proxmox-ve?style=flat-square\&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/fork)

  <p><em>A comprehensive collection of <strong>excellent</strong> <a href="https://pve.proxmox.com">Proxmox VE</a> resources including documentation, tools, tutorials, and community contributions.</em></p>
</div>

***

## Contents

* [Proxmox VE](#proxmox-ve)
* [Management](#management)
* [CV4PVE Suite](#cv4pve-suite)
* [VPS Control Panels](#vps-control-panels)
* [VDI](#vdi)
* [Monitoring](#monitoring)
* [Backup Tools](#backup-tools)
* [Storage](#storage)
* [Networking](#networking)
* [Inventory](#inventory)
* [AI](#ai)
* [API & SDKs](#api--sdks)
* [Infrastructure as Code](#infrastructure-as-code)
* [Kubernetes](#kubernetes)
* [Cluster & Autoscaling](#cluster--autoscaling)
* [Other Tools](#other-tools)
* [Migration](#migration)
* [Tutorials, Blogs & Video](#tutorials-blogs--video)
* [Training](#training)
* [Templates & Marketplace](#templates--marketplace)
* [Security Tools & Best Practices](#security-tools--best-practices)
* [Community, Forum & Social](#community-forum--social)
* [Utilities & Scripts](#utilities--scripts)
* [Benchmark & Comparisons](#benchmark--comparisons)
* [YouTube Channels](#youtube-channels)
* [Mobile Apps](#mobile-apps)
* [Desktop Apps](#desktop-apps)
* [Smart Home](#smart-home)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [License](#license)

***

## Proxmox VE

* [PXvirt](https://github.com/jiangcuo/pxvirt) ⭐ 1,803 | 🐛 44 | 🌐 Shell | 📅 2026-07-22 - Fork of Proxmox VE for ARM and LoongArch architectures.
* [Proxmox on NixOS](https://github.com/SaumonNet/proxmox-nixos) ⭐ 1,392 | 🐛 35 | 🌐 Nix | 📅 2026-09-12 - Unofficial port of the Proxmox VE hypervisor to NixOS.
* [Proxmox Virtual Environment](https://proxmox.com/en/products/proxmox-virtual-environment/overview)\
  Complete, open-source server management platform for enterprise virtualization.\
  \[[Download ISO](https://proxmox.com/en/downloads/proxmox-virtual-environment/iso)] • \[[Install Docs](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html)] • \[[Forum](https://forum.proxmox.com/)]

***

## Management

* [CV4PVE-ADMIN (Web UI)](https://corsinvest.it/en/cv4pve/admin/)
  Powerful and easy-to-use web administration interface for monitoring/manage multiple Proxmox VE clusters from a single portal.
  [GitHub](https://github.com/Corsinvest/cv4pve-admin) ⭐ 410 | 🐛 3 | 🌐 C# | 📅 2026-10-07
* [PVMSS](https://github.com/julienhmmt/pvmss) ⭐ 52 | 🐛 2 | 🌐 Go | 📅 2026-10-07 - Lightweight self-service web portal that lets users create and manage VMs without access to the Proxmox VE web UI.
* [ferrum](https://github.com/anand34577/ferrum) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-06 - Fleet dashboard for Proxmox VE clusters and standalone nodes with live inventory, backups, HA, firewall and alerting.
* [P3Portal](https://github.com/P3Portal-org/p3portal) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22
  Web portal to manage Proxmox VE: cluster dashboard, Ansible/Packer automation, networking/SDN/firewall, VM/LXC lifecycle and fine-grained RBAC. Core is AGPLv3; an optional Plus edition adds declarative Stacks (OpenTofu), pools & quotas, 4-eyes approval and visual editors.
* [Proxion](https://github.com/C2Tech-sys/proxion) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-06 - Open-source web console for managing Proxmox VE nodes, VMs and containers.
* [MultiPortal](https://multiportal.io/)
* [Convoy](https://convoypanel.com/)
* [PegaProx](https://pegaprox.com/) - Datacenter management UI with unified multi-cluster control, intelligent load balancing and seamless cross-cluster migrations.
* [ProxCenter](https://www.proxcenter.io/) - Modern web interface for multi-cluster management, cross-hypervisor migration and workload balancing from a single pane of glass.
* [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager)
* [AtlasPVE](https://atlaspve.com) - Safety-focused control layer for Proxmox VE: live map of VMs and storage, host updates sorted by impact, snapshot-before-change and one-click rollback. Commercial, early access.
* [Tainer](https://tainer.sh) - Management platform for Proxmox VE.

***

## CV4PVE Suite

**Advanced official Corsinvest tools for integrated multi-platform Proxmox VE management.**

* [**CV4PVE-AUTOSNAP**](https://github.com/Corsinvest/cv4pve-autosnap) ⭐ 565 | 🐛 3 | 🌐 C# | 📅 2026-10-07
  Automatic snapshot tool for Proxmox VE VMs and containers with retention policies.
* [**CV4PVE-ADMIN**](https://github.com/Corsinvest/cv4pve-admin) ⭐ 410 | 🐛 3 | 🌐 C# | 📅 2026-10-07
  Web management platform for Proxmox VE clusters: like vCenter but for Proxmox.
* [**CV4PVE-PEPPER**](https://github.com/Corsinvest/cv4pve-pepper) ⭐ 150 | 🐛 1 | 🌐 C# | 📅 2026-10-07
  Open a Proxmox VE SPICE or VNC console from the command line.
* [**CV4PVE-VDI**](https://github.com/Corsinvest/cv4pve-vdi) ⭐ 130 | 🐛 3 | 🌐 C# | 📅 2026-10-07
  Desktop VDI client for Proxmox VE: SPICE, VNC, RDP and SSH console launchers.
* [**CV4PVE-BOTGRAM**](https://github.com/Corsinvest/cv4pve-botgram) ⭐ 93 | 🐛 0 | 🌐 C# | 📅 2026-10-07
  Telegram bot to manage and monitor Proxmox VE from your mobile.
* [**CV4PVE-API-POWERSHELL**](https://github.com/Corsinvest/cv4pve-api-powershell) ⭐ 92 | 🐛 0 | 🌐 PowerShell | 📅 2026-10-07\
  Official PowerShell module and CmdLets for managing Proxmox VE from Windows, Azure DevOps, etc.
* [**CV4PVE-BARC**](https://github.com/Corsinvest/cv4pve-barc) ⭐ 88 | 🐛 24 | 🌐 Shell | 📅 2023-08-04
  Incremental backup and restore for Ceph RBD images on Proxmox VE.
* [**CV4PVE-CLI**](https://github.com/Corsinvest/cv4pve-cli) ⭐ 86 | 🐛 0 | 🌐 C# | 📅 2026-10-07
  kubectl-style remote CLI for Proxmox VE with multi-cluster support and shell completion.
* [**CV4PVE-API**](https://github.com/Corsinvest/cv4pve-api-dotnet) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-10-07\
  Official Corsinvest API client to integrate, develop and customize Proxmox in .NET/C# ([NuGet](https://www.nuget.org/packages/Corsinvest.ProxmoxVE.Api/)).
* [**CV4PVE-API-PHP**](https://github.com/Corsinvest/cv4pve-api-php) ⭐ 83 | 🐛 1 | 🌐 PHP | 📅 2026-10-07\
  Official PHP API client and library for automating Proxmox in PHP/Composer environments.
* [**CV4PVE-API-JAVA**](https://github.com/Corsinvest/cv4pve-api-java) ⭐ 79 | 🐛 0 | 🌐 Java | 📅 2026-10-07\
  Official Java API client.
* [**CV4PVE-METRICS-GRAFANA**](https://github.com/Corsinvest/cv4pve-metrics-grafana) ⭐ 70 | 🐛 1 | 🌐 HTML | 📅 2021-12-06
  Grafana + InfluxDB + Telegraf monitoring stack for Proxmox VE.
* [**CV4PVE-REPORT**](https://github.com/Corsinvest/cv4pve-report) ⭐ 62 | 🐛 1 | 🌐 C# | 📅 2026-10-07
  Export Proxmox VE infrastructure to a navigable Excel, HTML or JSON report: like RVTools for Proxmox.
* [**CV4PVE-DIAG**](https://github.com/Corsinvest/cv4pve-diag) ⭐ 55 | 🐛 2 | 🌐 C# | 📅 2026-10-07
  Diagnostic and health-check tool for Proxmox VE clusters.
* [**CV4PVE-API-JAVASCRIPT**](https://github.com/Corsinvest/cv4pve-api-javascript) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-07\
  Official JavaScript client for Node.js and frontend (automation, webapps).
* [**CV4PVE-METRICS-EXPORTER**](https://github.com/Corsinvest/cv4pve-metrics-exporter) ⭐ 28 | 🐛 0 | 🌐 C# | 📅 2026-10-07
  Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
* [**CV4PVE-NODE-PROTECT**](https://github.com/Corsinvest/cv4pve-node-protect) ⭐ 19 | 🐛 0 | 🌐 C# | 📅 2026-10-07
  Backup and restore Proxmox VE node configuration files via SSH.

**Related online suite:**

* [corsinvest.it/en/cv4pve](https://corsinvest.it/en/cv4pve/)\
  Official Corsinvest page of the cv4pve suite.

***

## VPS Control Panels

* [Proxmox VE VPS For WHMCS](https://www.modulesgarden.com/products/whmcs/proxmox-ve-vps)
* [SolusVM](https://solusvm.com/)
* [Virtualizor](https://www.virtualizor.com/) \[[Docs](https://www.virtualizor.com/docs/)]

***

## VDI

* [PVE-VDIClient](https://github.com/joshpatten/PVE-VDIClient) ⭐ 1,095 | 🐛 44 | 🌐 Python | 📅 2026-04-10 - Lightweight VDI kiosk client for launching Proxmox VE VM consoles.
* [OpenUDS](https://github.com/VirtualCable/openuds) ⭐ 215 | 🐛 1 | 📅 2026-10-06 - Open-source multiplatform VDI connection broker with Proxmox VE support.
* [CV4PVE-VDI](https://github.com/Corsinvest/cv4pve-vdi) ⭐ 130 | 🐛 3 | 🌐 C# | 📅 2026-10-07 - Official Corsinvest desktop VDI client for Proxmox VE with SPICE, VNC, RDP and SSH console launchers.
* [Kasm Workspaces](https://www.kasmweb.com/) - Streaming containerized desktops and apps with Proxmox VE as an autoscale provider.

***

## Monitoring

* [Pulse](https://github.com/rcourtman/Pulse) ⭐ 6,794 | 🐛 108 | 🌐 Go | 📅 2026-10-08 - Real-time monitoring for Proxmox VE and PBS with guest, storage and backup visibility, alerting, and a multi-client mode for providers.
* [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter) ⭐ 1,462 | 🐛 37 | 🌐 Python | 📅 2026-10-07
* [PVE-UPS](https://github.com/ffind-dev/pve-ups) ⭐ 305 | 🐛 6 | 🌐 Python | 📅 2026-10-04 - UPS shutdown appliance for Proxmox VE with a web wizard, an alternative to NUT.
* [check\_pve](https://github.com/nbuchwitz/check_pve) ⭐ 135 | 🐛 13 | 🌐 Python | 📅 2026-09-10 - Icinga/Nagios plugin to monitor Proxmox VE nodes, VMs, storage and cluster health.
* [pbs-exporter](https://github.com/natrontech/pbs-exporter) ⭐ 63 | 🐛 10 | 🌐 Go | 📅 2026-10-05 - Prometheus exporter for Proxmox Backup Server.
* [cv4pve-metrics-exporter](https://github.com/Corsinvest/cv4pve-metrics-exporter) ⭐ 28 | 🐛 0 | 🌐 C# | 📅 2026-10-07 - Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
* [Proxmox Atlas](https://github.com/Losstarot85/proxmox-atlas) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-29 - Real-time multi-cluster monitoring dashboard for Proxmox VE infrastructure
* [pve-metrics-exporter](https://github.com/drumandbytes/pve-metrics-exporter) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-10-04 - Prometheus and Glance exporter for Proxmox VE: node, VM and LXC resource usage plus CPU/GPU/NVMe temperatures from lm-sensors.
* [CheckMK](https://checkmk.com/blog/proxmox-monitoring)
* [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php)
* [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/)
* [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/)
* [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/)
* [Zabbix](https://www.zabbix.com/de/integrations/proxmox)
* [Fivenines](https://fivenines.io/features/proxmox-monitoring) - Hosted monitoring for Proxmox VE clusters, QEMU VMs and LXC containers, with an open-source agent.
* [Datadog](https://docs.datadoghq.com/integrations/proxmox/) - Datadog integration for monitoring Proxmox VE.
* [Grafana: Proxmox via Prometheus](https://grafana.com/grafana/dashboards/10347-proxmox-via-prometheus/) - Grafana dashboard for the Prometheus Proxmox VE exporter.
* [ManageEngine OpManager](https://www.manageengine.com/network-monitoring/proxmox-monitoring.html) - Proxmox monitoring with the OpManager network and infrastructure monitoring platform.
* [XorMon](https://xormon.com/server/monitoring/Proxmox/Proxmox-monitoring.php) - Performance monitoring for Proxmox VE alongside servers, storage, databases and cloud.

***

## Backup Tools

* [ProxSave](https://github.com/tis24dev/proxsave) ⭐ 528 | 🐛 2 | 🌐 Go | 📅 2026-10-06 - Backup and restore of Proxmox PBS & PVE system files: save your entire environment and restore it at any time. \[[Site](https://proxsave.dev/)]
* [proxmox-backup-arm64](https://github.com/wofferl/proxmox-backup-arm64) ⭐ 430 | 🐛 0 | 🌐 Shell | 📅 2026-10-05 - Build scripts for Proxmox Backup Server on arm64.
* [Joulenap](https://github.com/Joulenap/joulenap) ⭐ 127 | 🐛 1 | 🌐 Python | 📅 2026-10-06 - Web UI and scheduler for backups to a Proxmox Backup Server that stays powered off: wakes it, runs the backups, prunes, garbage-collects and shuts it down. Any number of PVE hosts and PBS, PBS to PBS sync, notifications.
* [PBS\_Chunk\_Checker](https://github.com/VoltKraft/PBS_Chunk_Checker) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-04-27
* [ProxSnap](https://github.com/gyptazy/ProxSnap) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2026-01-22 - Lightweight CLI tool for auditing and cleaning up snapshots across Proxmox VE clusters.
* [pve-bindsnap](https://github.com/bitranox/pve-bindsnap) ⭐ 7 | 🐛 0 | 🌐 Perl | 📅 2026-08-27
  * Snapshot LXC containers that have bind/device mounts, which stock Proxmox greys out. Can also exclude specific volumes from a snapshot. Works with the GUI, API, pct and cv4pve-autosnap.
* [pbs-autobackup](https://github.com/ferr079/pbs-autobackup) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-07-31 - Unattended backup cycle for a Proxmox Backup Server that stays powered off: Wake-on-LAN, enable the storage, vzdump every node, prune, garbage-collect, then shut the host back down.
* [BACKUP EAGLE](https://www.backup-eagle.com/product/proxmox)
* [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/)
* [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) \[[Docs](https://www.bdrsuite.com/technical-documents/)] \[[Download](https://www.bdrsuite.com/vembu-bdr-suite-download/)]
* [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/)
* [Commvault Backup\&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) \[[Docs](https://documentation.commvault.com/v11/software/backups_for_proxmox_vms.html)]
* [NAKIVO Backup & Replication](https://www.nakivo.com/proxmox-backup/) \[[Trial](https://www.nakivo.com/resources/download/trial-download/)] \[[Docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)]
* [Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) \[[Download](https://proxmox.com/en/downloads/proxmox-backup-server)] \[[Docs](https://pbs.proxmox.com/docs/installation.html)]
* [SEP sesam](https://www.sep.de/solutions/proxmox-hypervisor/)
* [Storware Backup\&Recovery](https://storware.eu/solutions/virtual-machine-backup-and-recovery/proxmox-ve-backup-and-recovery/)
* [Veeam Backup for Proxmox](https://www.veeam.com/blog/veeam-backup-for-proxmox.html)
* [Vinchin Backup & Recovery](https://www.vinchin.com/proxmox-backup.html) \[[Trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html)] \[[Docs](https://helpcenter.vinchin.com/)]
* [Cloud-PBS](https://cloud-pbs.com/) - Hosted Proxmox Backup Server in the cloud for Proxmox VE backups.
* [Proxmox Backup Client](https://pbs.proxmox.com/docs/backup-client.html) - Official command-line client for Proxmox Backup Server.
* [Rubrik](https://www.rubrik.com/solutions/proxmox-ve) - Data protection for Proxmox VE workloads.

***

## Storage

* [TrueNAS Proxmox VE Storage Plugin](https://github.com/truenas/truenas-proxmox-plugin) ⭐ 405 | 🐛 15 | 🌐 Shell | 📅 2026-10-07
* [ANAS](https://github.com/ccebelenski/anas) ⭐ 189 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-06 - Storage management inside the Proxmox VE web UI: ZFS and hybrid RAID pools, SMB/NFS shares, iSCSI target, snapshots and replication.
* [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin) ⭐ 43 | 🐛 12 | 🌐 Perl | 📅 2026-09-06
* [SharedLVM](https://github.com/delltech1/proxmox-sharedlvmthin) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-10-05 - Snapshot-capable shared FC/iSCSI SAN storage for Proxmox VE 9 clusters on top of an existing shared LVM volume group.
* [Proxmox VE Plugin for HPE Nimble Storage (iSCSI)](https://github.com/brngates98/pve-nimble-plugin) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2026-09-29 - Integration of HPE Nimble Storage arrays with Proxmox VE over iSCSI, using the Nimble REST API to create and manage volumes.
* [Snapbridge](https://github.com/abdoufermat5/snapbridge) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2026-04-16 - Rust CLI for managing Proxmox snapshots on NetApp ONTAP-backed storage (for both NAS and SAN).
* [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/)
* [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/)
* [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html)
* [StorPool](https://storpool.com/proxmox-virtual-environment) - High-performance distributed storage platform with native Proxmox VE integration.
* [Everpure](https://support.everpuredata.com/access?dita:id=m_proxmox) - Storage technology integrations for Proxmox VE.

***

## Networking

* [NetBird on Proxmox VE](https://docs.netbird.io/get-started/install/proxmox-ve) - Install guide for the NetBird open-source zero trust networking platform on Proxmox VE.
* [tailmox](https://github.com/willjasen/tailmox) ⭐ 231 | 🐛 4 | 🌐 Shell | 📅 2026-09-19 - Cluster Proxmox VE nodes over Tailscale.
* [Tailscale](https://tailscale.com/docs/integrations/proxmox) - Guide to running Tailscale on Proxmox VE hosts.

***

## Inventory

* [netbox-proxbox](https://github.com/emersonfelipesp/netbox-proxbox) ⭐ 601 | 🐛 3 | 🌐 Python | 📅 2026-10-07 - NetBox plugin to sync and inventory Proxmox VE clusters, nodes and VMs.
* [Netbox-SSOT](https://github.com/bl4ko/netbox-ssot) ⭐ 75 | 🐛 15 | 🌐 Go | 📅 2026-10-06 - Microservice that syncs objects from multiple sources, Proxmox VE included, into NetBox.
* [CV4PVE-REPORT](https://github.com/Corsinvest/cv4pve-report) ⭐ 62 | 🐛 1 | 🌐 C# | 📅 2026-10-07 - Export Proxmox VE infrastructure to a navigable Excel, HTML or JSON report: like RVTools for Proxmox.
* [Homedex](https://github.com/HarshShah0203/homedex) ⭐ 61 | 🐛 7 | 🌐 Go | 📅 2026-09-27 - Read-only homelab inventory that lists Proxmox VE nodes, VMs and LXC containers with a PVEAuditor token and links them to Docker services, reverse proxy routes and certificate expiry.
* [Proxmox Report Generator](https://github.com/AungThuMyint/ProxmoxReportGenerator) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-06-11 - Generate infrastructure reports for Proxmox VE clusters.
* [iTop CMDB: Data collector for Proxmox](https://www.itophub.io/wiki/page?id=extensions%3Acombodo-proxmox-data-collector) - Combodo data collector to import Proxmox VE assets into the iTop CMDB.
* [netbox Enterprise Proxmox VE Integration](https://netboxlabs.com/docs/integrations/platform-integrations/proxmox-ve/) - Official NetBox Labs integration to inventory Proxmox VE infrastructure.
* [Proxmox Virtual Environment CMDB importer](https://versio.io/en/import-proxmox-cmdb-configuration-item.html) - Import Proxmox VE configuration items into the Versio.io CMDB.

***

## AI

* [ProxmoxMCP-Plus](https://github.com/RekklesNA/ProxmoxMCP-Plus) ⭐ 574 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - Enhanced Proxmox MCP server with advanced virtualization management and full OpenAPI integration.
* [ProxmoxMCP](https://github.com/canvrno/ProxmoxMCP) ⭐ 293 | 🐛 15 | 🌐 Python | 📅 2025-02-19 - MCP server for Proxmox VE management, enabling AI assistants to control VMs, containers, and cluster resources.
* [Proximo](https://github.com/john-broadway/proximo) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2026-10-03 - AI-driven natural-language assistant for managing Proxmox VE.
* [mcp-proxmox](https://github.com/antonio-mello-ai/mcp-proxmox) ⭐ 16 | 🐛 6 | 🌐 Python | 📅 2026-09-21 - MCP server for managing Proxmox VE clusters through AI assistants.

***

## API & SDKs

### Community Maintained

#### Python

* [Proxmoxia (Wrapper)](https://github.com/baseblack/Proxmoxia) ⭐ 76 | 🐛 1 | 🌐 Python | 📅 2013-06-02
* [proxmox-utils (Console Client)](https://github.com/sitrox/proxmox-utils) ⚠️ Archived
* [pmxc (Console Client)](https://github.com/jochumdev/pmxc) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2021-08-18
* [proxmox-sdk](https://github.com/emersonfelipesp/proxmox-sdk) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-09-17
* [proxmoxer](https://pypi.python.org/pypi/proxmoxer)

#### PowerShell

* [cv4pve-api-powershell](https://github.com/Corsinvest/cv4pve-api-powershell) ⭐ 92 | 🐛 0 | 🌐 PowerShell | 📅 2026-10-07

#### Ruby

* [nledez/proxmox](https://github.com/nledez/proxmox) ⭐ 38 | 🐛 8 | 🌐 Ruby | 📅 2019-03-21

#### NodeJS

* [cv4pve-api-javascript](https://github.com/Corsinvest/cv4pve-api-javascript) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-07
* [npm:proxmox](https://www.npmjs.com/package/proxmox)

#### C\#

* [cv4pve-api-dotnet](https://github.com/Corsinvest/cv4pve-api-dotnet) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-10-07
* [ProxmoxSharp](https://github.com/ionelanton/ProxmoxSharp) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2016-12-16

#### PHP

* [ProxmoxVE](https://github.com/ZzAntares/ProxmoxVE) ⭐ 177 | 🐛 10 | 🌐 PHP | 📅 2023-02-02
* [pve2-api-php-client](https://github.com/CpuID/pve2-api-php-client) ⭐ 96 | 🐛 9 | 🌐 PHP | 📅 2024-06-24
* [cv4pve-api-php](https://github.com/Corsinvest/cv4pve-api-php) ⭐ 83 | 🐛 1 | 🌐 PHP | 📅 2026-10-07
* [MrKampf/proxmoxVE](https://github.com/MrKampf/proxmoxVE) ⭐ 60 | 🐛 7 | 🌐 PHP | 📅 2026-08-04
* [pve-cli-utils](https://github.com/aheahe/pve-cli-utils) ⭐ 10 | 🐛 0 | 🌐 PHP | 📅 2021-01-31

#### Java

* [cv4pve-api-java](https://github.com/Corsinvest/cv4pve-api-java) ⭐ 79 | 🐛 0 | 🌐 Java | 📅 2026-10-07
* [pve2-api-java](https://github.com/Elbandi/pve2-api-java) ⭐ 24 | 🐛 2 | 🌐 Java | 📅 2012-05-23

#### Perl

* [Net-Proxmox-VE (CPAN)](http://search.cpan.org/~djzort/Net-Proxmox-VE-0.006/)
* [pve-apiclient (official)](https://git.proxmox.com/?p=pve-apiclient.git;a=summary)

#### Go

* [proxmox-api-go](https://github.com/Telmate/proxmox-api-go) ⭐ 492 | 🐛 58 | 🌐 Go | 📅 2026-09-23
* [go-proxmox](https://github.com/luthermonson/go-proxmox) ⭐ 293 | 🐛 1 | 🌐 Go | 📅 2026-09-30

***

## Infrastructure as Code

* [terraform-provider-proxmox (Telmate)](https://github.com/Telmate/terraform-provider-proxmox) ⭐ 2,954 | 🐛 130 | 🌐 Go | 📅 2026-09-14
* [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox) ⭐ 2,249 | 🐛 97 | 🌐 Go | 📅 2026-10-08
* [Ansible Role - Proxmox](https://github.com/lae/ansible-role-proxmox) ⭐ 693 | 🐛 23 | 🌐 Python | 📅 2026-07-13 - Ansible role that installs Proxmox VE on Debian hosts and builds the cluster.
* [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) ⭐ 594 | 🐛 1 | 🌐 Ruby | 📅 2026-09-25 - GitOps workflow to manage Proxmox VE infrastructure declaratively.
* [Pulumi Proxmox VE](https://github.com/muhlba91/pulumi-proxmoxve) ⭐ 226 | 🐛 25 | 🌐 Go | 📅 2026-10-07 - Pulumi provider for creating and managing Proxmox VE resources.
* [Ansible Collection - community.proxmox](https://github.com/ansible-collections/community.proxmox) ⭐ 144 | 🐛 86 | 🌐 Python | 📅 2026-10-06
* [foreman\_fog\_proxmox](https://github.com/theforeman/foreman_fog_proxmox) ⭐ 114 | 🐛 66 | 🌐 Ruby | 📅 2026-09-21 - Foreman plugin that adds Proxmox VE as a compute resource.
* [Packer Plugin for Proxmox VE](https://developer.hashicorp.com/packer/integrations/hashicorp/proxmox)
* [OpenTofu Provider for Proxmox](https://search.opentofu.org/provider/bpg/proxmox/latest) - OpenTofu registry entry for the bpg Proxmox provider.

***

## Kubernetes

* [Proxmox CSI Plugin](https://github.com/sergelogvinov/proxmox-csi-plugin) ⭐ 863 | 🐛 17 | 🌐 Go | 📅 2026-10-02 - Kubernetes CSI driver that provisions persistent volumes on Proxmox VE storage.
* [TJ's Kubernetes Service](https://github.com/zimmertr/TJs-Kubernetes-Service) ⭐ 556 | 🐛 2 | 🌐 HCL | 📅 2026-10-07 - Provision highly available Kubernetes clusters on Proxmox VE with Talos and OpenTofu.
* [Cluster API Provider for Proxmox VE (CAPMOX)](https://github.com/ionos-cloud/cluster-api-provider-proxmox) ⭐ 488 | 🐛 125 | 🌐 Go | 📅 2026-10-06
* [Proxmox Cloud Controller Manager](https://github.com/sergelogvinov/proxmox-cloud-controller-manager) ⭐ 345 | 🐛 3 | 🌐 Go | 📅 2026-10-01 - Kubernetes cloud controller manager for Proxmox VE.
* [Proxmox Kubernetes Engine (PKE)](https://github.com/Caprox-eu/Proxmox-Kubernetes-Engine) ⭐ 244 | 🐛 2 | 📅 2026-09-13 - Deploy and manage highly available Kubernetes clusters directly on Proxmox VE.
* [cluster-api-provider-proxmox (k8s-proxmox)](https://github.com/k8s-proxmox/cluster-api-provider-proxmox) ⭐ 177 | 🐛 26 | 🌐 Go | 📅 2026-04-27 - Cluster API provider implementation for Proxmox VE.
* [Karpenter Provider for Proxmox](https://github.com/sergelogvinov/karpenter-provider-proxmox) ⭐ 136 | 🐛 10 | 🌐 Go | 📅 2026-10-01 - Karpenter node autoscaling provider for Proxmox VE.

***

## Cluster & Autoscaling

* [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale) ⭐ 304 | 🐛 1 | 🌐 Python | 📅 2026-09-17
* [LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) ⭐ 261 | 🐛 15 | 🌐 Python | 📅 2026-09-07
* [ProxLB](https://github.com/credativ/ProxLB) ⭐ 166 | 🐛 15 | 🌐 Python | 📅 2026-09-17
* [ProxPatch](https://github.com/gyptazy/ProxPatch) ⭐ 114 | 🐛 3 | 🌐 Rust | 📅 2026-09-26 - Rolling patch orchestration for Proxmox VE clusters: migrates running VMs, then updates and reboots nodes one at a time.
* [ProxCLMC](https://github.com/credativ/ProxCLMC) ⭐ 37 | 🐛 1 | 🌐 Rust | 📅 2026-05-12 - Lightweight tool to determine the maximum CPU compatibility level supported across all nodes in a Proxmox VE cluster.

***

## Other Tools

* [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE) ⭐ 29,754 | 🐛 18 | 🌐 Shell | 📅 2026-10-08
* [OSX-PROXMOX](https://github.com/luchina-gabriel/OSX-PROXMOX) ⭐ 7,814 | 🐛 3 | 🌐 Shell | 📅 2026-09-27 - Script to install macOS on Proxmox VE 7 to 9.
* [ProxMenux](https://github.com/MacRimi/ProxMenux) ⭐ 3,111 | 🐛 19 | 🌐 TypeScript | 📅 2026-10-08
* [PVE-mods](https://github.com/Meliox/PVE-mods) ⭐ 1,955 | 🐛 19 | 🌐 Shell | 📅 2026-10-05
* [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility) ⭐ 982 | 🐛 10 | 🌐 Shell | 📅 2026-05-17
* [OpenCore-ISO](https://github.com/LongQT-sea/OpenCore-ISO) ⭐ 853 | 🐛 1 | 🌐 C | 📅 2026-08-18 - Preconfigured OpenCore ISO image to run macOS on Proxmox VE and QEMU/KVM.
* [pvetui](https://github.com/devnullvoid/pvetui) ⭐ 739 | 🐛 1 | 🌐 Go | 📅 2026-10-03
* [intel-igpu-passthru](https://github.com/LongQT-sea/intel-igpu-passthru) ⭐ 546 | 🐛 1 | 🌐 Shell | 📅 2026-06-04 - Intel GVT-d iGPU passthrough for Proxmox VE, QEMU and KVM.
* [pve-microvm](https://github.com/rcarmo/pve-microvm) ⭐ 413 | 🐛 1 | 🌐 Shell | 📅 2026-10-07 - Run lightweight microVMs on Proxmox VE.
* [PVE Scripts Local](https://github.com/community-scripts/ProxmoxVE-Local) ⭐ 379 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-05 - Local web UI to browse and run the Proxmox VE Helper-Scripts.
* [dockur/proxmox](https://github.com/dockur/proxmox) ⭐ 323 | 🐛 4 | 🌐 Shell | 📅 2026-08-30 - Proxmox VE node running inside a Docker container, for labs and CI.
* [osx-proxmox](https://github.com/lucid-fabrics/osx-proxmox-next) ⭐ 278 | 🐛 0 | 🌐 Python | 📅 2026-09-20 - One-command macOS VM automation for Proxmox 9 with TUI wizard, recovery auto-download, and AMD/Intel support.
* [pve-notebuddy](https://github.com/JangaJones/pve-notebuddy) ⭐ 208 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-09 - Web UI to generate formatted Proxmox guest notes.
* [Proxmox Manager](https://github.com/TimInTech/proxmox-manager) ⭐ 85 | 🐛 0 | 🌐 Shell | 📅 2026-09-26 - CLI toolkit for common Proxmox VE administration tasks.
* [pvecontrol](https://github.com/enix/pvecontrol) ⭐ 81 | 🐛 14 | 🌐 Python | 📅 2026-10-05 - CLI to control and inspect Proxmox VE clusters.
* [lws](https://github.com/fabriziosalmi/lws) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2026-10-05 - Unified CLI for Proxmox, LXC, and Docker.
* [proxtagger](https://github.com/Reginleif86/proxtagger) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-05-12
* [valheim-proxmox](https://github.com/PawelSzymanski89/valheim-proxmox) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - One-command Valheim dedicated server in an LXC, with a web panel for players, bans, worlds, backups and mods.
* [proxmox-guestos-customization](https://github.com/RobertLukan/proxmox-guestos-customization) ⭐ 3 | 🐛 10 | 🌐 Python | 📅 2026-09-27 - Clone and customize Windows templates on Proxmox VE (hostname, network, domain join) through the QEMU guest agent.
* [ProxDeploy](https://github.com/NordicsSys/proxdeploy) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-08 - Production-ready Python CLI to deploy, list, and destroy KVM guests from YAML templates, with cloud-init, SSH provisioning, dry-run, and API retry resilience.

***

## Migration

* [proxmove](https://github.com/ossobv/proxmove) ⭐ 293 | 🐛 17 | 🌐 Python | 📅 2026-04-21 - Migrate VMs between different Proxmox VE clusters with minimal downtime.
* [machine-to-proxmox-lxc-ct-converter](https://github.com/my5t3ry/machine-to-proxmox-lxc-ct-converter) ⭐ 153 | 🐛 4 | 🌐 Shell | 📅 2025-06-05 - Convert any GNU/Linux machine into a Proxmox LXC container.
* [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2026-08-16
* [Migrate to Proxmox VE](https://pve.proxmox.com/wiki/Migrate_to_Proxmox_VE) - Official wiki page on migrating VMs from other hypervisors, with the ESXi import wizard.

***

## Tutorials, Blogs & Video

* [ServeTheHome - Proxmox VE Tutorials](https://www.servethehome.com/tag/proxmox-ve/)
* [Techno Tim - Proxmox Guides (Blog & Video)](https://technotim.live/tags/proxmox/)
* [Nick Sherlock - macOS on Proxmox](https://www.nicksherlock.com/category/proxmox/)
* [VirtualizationHowTo - Proxmox](https://www.virtualizationhowto.com/tag/proxmox-ve/)
* [The Homelab Wiki - Proxmox Section](https://wiki.homelabos.com/other/proxmox/)
* [Peira Labs - Homelab & Proxmox Guides](https://peira.dev/tags/proxmox/)

***

## Training

* [Proxmox VE Training Courses](https://www.proxmox.com/en/services/training-courses/training) - Official training courses from Proxmox Server Solutions.
* [Corsinvest Training](https://corsinvest.it/en/training/proxmox-ve/) - Proxmox VE training courses by Corsinvest.
* [Croit Academy](https://www.croit.io/academy/topics/proxmox) - Proxmox VE trainings and workshops.
* [Fast Lane](https://www.flane.de/en/courses/proxmox) - Instructor-led Proxmox courses.

***

## Templates & Marketplace

* [TrueNAS SCALE Community Catalog](https://github.com/trueforge-org/truecharts) ⭐ 1,356 | 🐛 11 | 🌐 Go Template | 📅 2026-10-08
* [LinuxServer Container Templates](https://github.com/linuxserver/docker-templates) ⭐ 41 | 🐛 0 | 📅 2026-07-18
* [TurnKey Linux Proxmox LXC Templates](https://www.turnkeylinux.org/docs/proxmox-lxc)
* [TTECK Proxmox LXC Templates & Utilities](https://tteck.github.io/Proxmox/)

***

## Security Tools & Best Practices

* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 1,007 | 🐛 8 | 🌐 Python | 📅 2026-10-01 - Open source (GPL-3.0) autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes.
* [proxmox-ftagent](https://github.com/Flowtriq/proxmox-ftagent) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 - One-command LXC deployment of the Flowtriq DDoS detection agent on Proxmox VE, with automatic dependency and systemd service setup.
* [Proxmox Security Best Practices (official)](https://pve.proxmox.com/wiki/Security)
* [OpenSCAP - Security audit tool](https://www.open-scap.org/)
* [Falco Security - Runtime Linux Security](https://falco.org/)
* [Official Proxmox Firewall Guide](https://pve.proxmox.com/pve-docs/pve-firewall.8.html)
* [fail2ban for Proxmox (HowToForge)](https://www.howtoforge.com/tutorial/how-to-protect-proxmox-ve-with-fail2ban-and-ufw/)
* [Proxmox VE Security Advisories](https://forum.proxmox.com/threads/proxmox-virtual-environment-security-advisories.149331/) - Official list of security advisories for Proxmox VE.
* [Proxmox VE Security Reporting](https://pve.proxmox.com/wiki/Security_Reporting) - Official procedure for reporting a vulnerability to Proxmox.

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

* [pvetools](https://github.com/ivanhao/pvetools) ⭐ 5,264 | 🐛 56 | 🌐 Shell | 📅 2024-09-23 - Script for common Proxmox VE host setup: email, Samba, NFS, ZFS memory limit, nested virtualization and PCI passthrough.
* [Proxmox Dark Theme (User script)](https://github.com/Weilbyte/PVEDiscordDark) ⭐ 2,542 | 🐛 14 | 🌐 Sass | 📅 2023-03-04
* [PVE-Tools-9](https://github.com/PVE-Tools/PVE-Tools-9) ⭐ 2,184 | 🐛 3 | 🌐 Shell | 📅 2026-09-17 - One-click maintenance script for Proxmox VE 9: VM lifecycle, host networking and firewall, GPU/PCI passthrough and system maintenance (Chinese).
* [proxmox-stuff](https://github.com/DerDanilo/proxmox-stuff) ⭐ 1,330 | 🐛 2 | 🌐 Shell | 📅 2026-07-02 - Collection of scripts and tools written for Proxmox.
* [Proxmox Updater](https://github.com/BassT23/Proxmox) ⭐ 645 | 🐛 8 | 🌐 Shell | 📅 2026-10-07 - Updater script for Proxmox VE.
* [ProxmoxScripts (CCPVE)](https://github.com/coelacant1/ProxmoxScripts) ⭐ 638 | 🐛 37 | 🌐 Shell | 📅 2026-04-29 - Scripts for management and task automation in Proxmox VE.
* [ProxMorph](https://github.com/IT-BAER/proxmorph) ⭐ 619 | 🐛 3 | 🌐 CSS | 📅 2026-09-23 - CSS themes for Proxmox VE, PBS and PDM that plug into the native color theme selector.
* [zamba-lxc-toolbox](https://github.com/bashclub/zamba-lxc-toolbox) ⭐ 454 | 🐛 35 | 🌐 Shell | 📅 2026-10-05 - Script collection to set up LXC containers on Proxmox VE with ZFS, including a Samba file server that exposes ZFS snapshots as Previous Versions.
* [proxmox-hetzner](https://github.com/ariadata/proxmox-hetzner) ⭐ 333 | 🐛 3 | 🌐 Shell | 📅 2026-09-21 - Install Proxmox VE on a Hetzner dedicated server without a KVM console.
* [proxmox\_toolbox](https://github.com/Tontonjo/proxmox_toolbox) ⭐ 319 | 🐛 0 | 🌐 Shell | 📅 2026-09-20 - Toolbox for the first configuration of Proxmox VE and Proxmox Backup Server.
* [pve-disk-shrink](https://github.com/Garfieldttt/pve-disk-shrink) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2026-08-15 - Dialog-based offline shrinking of Proxmox VE VM disks and LXC volumes (zvol/qcow2/LVM), no live ISO or manual partitioning needed.
* [Proxmox Wake on LAN](https://github.com/Aizen-Barbaros/Proxmox-WoL) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2023-03-24
* [Proxmox VMID Updater](https://github.com/sannier3/proxmox-vmid-updater) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 - Safely renames QEMU VM and LXC container VMIDs, including configurations, storage volumes, snapshots, backups, HA and firewall resources, with transactional rollback.
* [homelab-scripts](https://github.com/ferr079/homelab-scripts) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-07-31 - Small shell toolbox for a Proxmox homelab: cluster and container status through the API, TLS expiry checks for services behind a reverse proxy, bulk HTTP availability checks, and a Loki query wrapper.
* [proxmox-ct-deploy](https://github.com/answ-kaz/proxmox-ct-deploy) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-09-27 - Deploy a Docker Compose app to an LXC container from your laptop over LAN or Tailscale: `pct push` sync, migrations after the DB is healthy, generation-managed Postgres backups, and the Cloudflare Tunnel / webhook gotchas.
* [proxmox-homelab-scripts](https://github.com/danymexi/proxmox-homelab-scripts) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-10-03 - Scripts for a single-node home lab: LXC provisioning, Cloudflare Tunnel setup, an Ollama + Open WebUI stack and scheduled backups.
* [pve-zsync (ZFS backup/snapshots)](https://pve.proxmox.com/wiki/PVE-zsync)
* [ProxMox Repo Manager/No-Subscription Script](https://tteck.github.io/Proxmox/)

***

## Benchmark & Comparisons

* [ServeTheHome Proxmox Benchmarks](https://www.servethehome.com/?s=proxmox+benchmark)
* [OpenBenchmarking Proxmox Results](https://openbenchmarking.org/testbed/2202159-NE-PROXMOXV55)
* [IdleWatt - Homelab Mini-PC Idle-Power & Passthrough Finder](https://idlewatt.vercel.app)

***

## YouTube Channels

### International Channels

* [Proxmox Server Solutions (Official Channel)](https://www.youtube.com/@ProxmoxVe)\
  Webinars, releases, new Proxmox features.
* [ServeTheHome](https://www.youtube.com/c/ServeTheHomeVideo)\
  Proxmox guides, hardware, servers and storage.
* [Techno Tim](https://www.youtube.com/c/TechnoTimLive)\
  Cluster setup, installation, automated backups with Proxmox.
* [Lawrence Systems](https://www.youtube.com/@LAWRENCESYSTEMS/search?query=proxmox)\
  Enterprise deep-dives, security and tutorials.
* [Craft Computing](https://www.youtube.com/c/CraftComputing/search?query=proxmox)\
  Real homelab use cases, containers, storage.
* [The Digital Life](https://www.youtube.com/c/TheDigitalLife/search?query=proxmox)\
  Tutorials, LXC, scripting.
* [DB Tech](https://www.youtube.com/c/DBTechYT/search?query=proxmox)\
  Guides on containers and services.
* [apalrd's adventures](https://www.youtube.com/@apalrdsadventures/search?query=proxmox)\
  Proxmox, IPv6 and deep dives.
* [Jim's Garage](https://www.youtube.com/@Jims-Garage/search?query=proxmox)\
  k3s, Proxmox and self-hosting.

### Italian Channels

* [Stefano Droghetti](https://www.youtube.com/@stefanodroghetti/search?query=proxmox)\
  Italian tutorials on installation, containers and Proxmox use cases.
* [Maurizio Leo](https://www.youtube.com/@MaurizioLeo/search?query=proxmox)\
  Homelab and virtualization.
* [Francesco Mainardi](https://www.youtube.com/@francescomainardi/search?query=proxmox)

***

## Mobile Apps

### Android

* [Proxmox VE Android App](https://play.google.com/store/apps/details?id=com.proxmox.app.pve_flutter_frontend) - Official app to manage VMs, containers, hosts and clusters.
* [ProxMon](https://play.google.com/store/apps/details?id=dev.reimu.proxmon) - View nodes, storage pools, VMs and containers statuses.
* [ProxMan (Android)](https://play.google.com/store/apps/details?id=com.windium.proxman) - Manage Proxmox VE nodes, VMs and containers from Android.
* [Mobile SSH](https://mobile-ssh.github.io) - SSH, SFTP and terminal client for administering Proxmox nodes and guests from Android.
* [ProxMate Backup](https://play.google.com/store/apps/details?id=com.itss.proxmatebackup) - Overview of your Proxmox Backup Server from Android.

### iOS

* [ProxMan](https://proxman.app) - App for managing Proxmox VE and Proxmox Backup Server environments.
* [Proxmox VE Companion](https://apps.apple.com/de/app/proxmox-ve-companion/id6748314140) - Monitor and manage Proxmox VE environments from iOS.
* [ProxMate](https://apps.apple.com/de/app/proxmate/id6470526961) - Manage your Proxmox server from iOS.
* [ProxMate Backup](https://apps.apple.com/de/app/proxmate-backup/id6618157722) - Manage Proxmox Backup Servers.
* [ProxMobo](https://proxmobo.app/) - Monitoring and management app for Proxmox VE and Proxmox Backup Server.
* [Reeve](https://reeveapp.io) - Monitor and manage Proxmox VE nodes, VMs, and containers from iOS.
* [Mobile SSH](https://mobile-ssh.github.io) - SSH, SFTP and terminal client for administering Proxmox nodes and guests from iOS.

***

## Desktop Apps

### macOS

* [ProxmoxBar](https://github.com/ryzenixx/proxmoxbar-macos) ⭐ 186 | 🐛 0 | 🌐 Swift | 📅 2026-10-02 - Native macOS menu bar app for monitoring and controlling Proxmox VE resources.

### Windows & Linux

* [Nexus Terminal](https://github.com/evdanil/vscode-NexTerminal) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-04 - VS Code and VSCodium extension that syncs Proxmox VMs and containers into SSH profiles and opens their web consoles.
* [VirtDeck](https://github.com/mcluremail/virtdeck) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - Native desktop client for Proxmox VE: monitoring, VM/container management, backups and direct Proxmox Backup Server integration (PySide6, Windows and Linux).

***

## Smart Home

* [Proxmox VE Custom Integration for Home Assistant](https://github.com/dougiteixeira/proxmoxve) ⭐ 970 | 🐛 12 | 🌐 Python | 📅 2026-10-06 - Home Assistant integration to poll data and control a Proxmox VE instance.
* [Proxmox Extended Sensors](https://github.com/Javisen/proxmox_sensors) ⭐ 71 | 🐛 6 | 🌐 Python | 📅 2026-10-07 - Monitoring and control of Proxmox VE and Proxmox Backup Server in Home Assistant.

***

## Documentation

* [smallab-k8s-pve-guide](https://github.com/ehlesp/smallab-k8s-pve-guide) ⭐ 1,189 | 🐛 0 | 🌐 Shell | 📅 2026-07-06 - Guide to running a small Kubernetes cluster on a single Proxmox VE node.
* [Proxmox Hardening Guide](https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide) ⭐ 568 | 🐛 0 | 📅 2026-02-09 - Actionable recommendations to secure Proxmox VE and Proxmox Backup Server.
* [Ubuntu-CloudInit-Docs](https://github.com/UntouchedWagons/Ubuntu-CloudInit-Docs) ⭐ 556 | 🐛 1 | 📅 2026-06-07 - Short guide to building an Ubuntu VM template with cloud-init.
* [10 Ways to Ruin Your Proxmox Setup](https://github.com/SwamiRama/10-ways-to-ruin-proxmox) ⭐ 162 | 🐛 1 | 📅 2026-01-05 - Common mistakes and how to avoid them.
* [free-pmx](https://free-pmx.pages.dev/)
* [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox)
* [Proxmox VE Wiki](https://pve.proxmox.com/wiki/Main_Page)
* [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/)
* [Proxmox VE API Viewer](https://pve.proxmox.com/pve-docs/api-viewer/index.html) - Official interactive API reference.

***

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

The short version: **new entries are always appended at the end of their section**, one suggestion per pull request.

***

## License

This list is released into the public domain under the [Creative Commons Zero v1.0 Universal](LICENSE) license.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-08._
