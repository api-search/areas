---
layout: area
slug: linuxunix
name: Linux/Unix System
description: A topic catalog of system-level APIs and interfaces available across Linux/Unix-like operating systems. Includes kernel system calls, POSIX standards, inter-process communication mechanisms (D-Bus, Netlink), virtual filesystems (procfs, sysfs), event-notification facilities (epoll, inotify), device management (udev, systemd), and userspace security interfaces.
tags:
- Kernel
- Linux
- Operating System
- System
- Unix
- POSIX
resource_count: 10
provider_count: 23
resources:
- name: System Calls API
  description: Low-level interface between user-space applications and the Linux kernel providing access to process management, file I/O, memory, networking, signals, and IPC primitives.
  url: https://man7.org/linux/man-pages/man2/syscalls.2.html
  tags:
  - Kernel
  - Low-Level
  - Syscalls
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/dir_section_2.html
  - type: Reference
    url: https://www.kernel.org/doc/html/latest/userspace-api/index.html
- name: POSIX API
  description: Portable Operating System Interface standards for Unix-like systems, defining a consistent application programming interface across platforms.
  url: https://pubs.opengroup.org/onlinepubs/9699919799/
  tags:
  - POSIX
  - Standards
  - Portability
  properties:
  - type: Documentation
    url: https://pubs.opengroup.org/onlinepubs/9699919799/
  - type: Specification
    url: https://standards.ieee.org/ieee/1003.1/7101/
- name: D-Bus API
  description: Inter-process communication and remote procedure call mechanism widely used on Linux desktop and system services.
  url: https://www.freedesktop.org/wiki/Software/dbus/
  tags:
  - IPC
  - Messaging
  - Desktop
  properties:
  - type: Documentation
    url: https://dbus.freedesktop.org/doc/dbus-specification.html
  - type: SourceCode
    url: https://gitlab.freedesktop.org/dbus/dbus
- name: Netlink API
  description: Socket-based interface for communication between the kernel and user space, particularly for networking and device subsystems.
  url: https://man7.org/linux/man-pages/man7/netlink.7.html
  tags:
  - Networking
  - Kernel
  - Sockets
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/man7/netlink.7.html
  - type: Reference
    url: https://www.kernel.org/doc/html/latest/userspace-api/netlink/intro.html
- name: procfs API
  description: Virtual filesystem providing process and system information through a hierarchical file-based interface.
  url: https://man7.org/linux/man-pages/man5/proc.5.html
  tags:
  - Filesystem
  - Process
  - Monitoring
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/man5/proc.5.html
  - type: Reference
    url: https://www.kernel.org/doc/html/latest/filesystems/proc.html
- name: sysfs API
  description: Virtual filesystem for kernel objects and device information presented under /sys.
  url: https://man7.org/linux/man-pages/man5/sysfs.5.html
  tags:
  - Filesystem
  - Kernel
  - Devices
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/man5/sysfs.5.html
  - type: Reference
    url: https://www.kernel.org/doc/html/latest/filesystems/sysfs.html
- name: inotify API
  description: Linux kernel subsystem for monitoring filesystem events such as file creation, deletion, and modification.
  url: https://man7.org/linux/man-pages/man7/inotify.7.html
  tags:
  - Filesystem
  - Monitoring
  - Events
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/man7/inotify.7.html
- name: epoll API
  description: I/O event notification facility for scalable monitoring of large numbers of file descriptors.
  url: https://man7.org/linux/man-pages/man7/epoll.7.html
  tags:
  - I/O
  - Events
  - Performance
  properties:
  - type: Documentation
    url: https://man7.org/linux/man-pages/man7/epoll.7.html
- name: udev API
  description: Device manager for the Linux kernel handling device nodes and hotplug events in /dev.
  url: https://www.freedesktop.org/software/systemd/man/udev.html
  tags:
  - Devices
  - Hardware
  - Hotplug
  properties:
  - type: Documentation
    url: https://www.freedesktop.org/software/systemd/man/udev.html
  - type: SourceCode
    url: https://github.com/systemd/systemd/tree/main/src/udev
- name: systemd API
  description: System and service manager exposing a D-Bus interface for managing services, sockets, devices, mounts, and timers.
  url: https://www.freedesktop.org/wiki/Software/systemd/
  tags:
  - Init
  - Service Management
  - System
  properties:
  - type: Documentation
    url: https://www.freedesktop.org/software/systemd/man/
  - type: Reference
    url: https://www.freedesktop.org/wiki/Software/systemd/dbus/
  - type: SourceCode
    url: https://github.com/systemd/systemd
providers:
- slug: linuxunix
  name: Linux/Unix System
  description: A topic catalog of system-level APIs and interfaces available across Linux/Unix-like operating systems. Includes kernel system calls, POSIX standards, inter-process communication mechanisms (D-Bus, Netlink), virtual filesystems (procfs, sysfs), event-notification facilities (epoll, inotify), device…
  api_count: 10
  score_band: minimal
  score_composite: 23.8
  shared: 6
- slug: linux
  name: Linux
  description: Linux is an open-source Unix-like operating system kernel originally created by Linus Torvalds. This index catalogs the userspace and kernel programming interfaces exposed by Linux, including system calls, eBPF, ioctl, netlink, procfs, sysfs, GPIO, and security interfaces such as Seccomp, Landlock,…
  api_count: 10
  score_band: minimal
  score_composite: 23.8
  shared: 4
- slug: unix
  name: UNIX System Call
  description: Core UNIX/POSIX system calls providing low-level operating system interfaces for process management, file operations, interprocess communication, and system control.
  api_count: 11
  score_band: minimal
  score_composite: 22.7
  shared: 3
- slug: red-hat-enterprise-linux-8
  name: Red Hat Enterprise Linux 8
  description: Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution that provides a stable, secure, and high-performance operating system platform for modern IT environments. RHEL 8 is managed and accessed programmatically through Red Hat's cloud console APIs, subscription management APIs…
  api_count: 10
  score_band: developing
  score_composite: 51.4
  shared: 2
- slug: rhel
  name: Red Hat Enterprise Linux
  description: Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux platform, providing APIs and services for subscription management, security insights, compliance monitoring, vulnerability assessment, patch management, content delivery, and automation. The Red Hat Hybrid Cloud Console exposes…
  api_count: 8
  score_band: developing
  score_composite: 46.7
  shared: 2
- slug: debian
  name: Debian
  description: Debian is a free operating system distribution maintained by the Debian Project, a community of more than a thousand volunteers worldwide. Debian provides a number of developer-facing services including a source-code browsing API at sources.debian.org, the Bug Tracking System (BTS) at bugs.debian.o…
  api_count: 3
  score_band: thin
  score_composite: 44.9
  shared: 2
- slug: flatcar-container-linux
  name: Flatcar Container Linux
  description: Flatcar Container Linux is a CNCF incubating minimal, immutable Linux distribution designed for running containers. It provides automatic atomic updates through the Nebraska update server, ensuring nodes stay secure and consistent. Flatcar supports Kubernetes deployments on bare metal, cloud, and v…
  api_count: 1
  score_band: thin
  score_composite: 32.8
  shared: 2
- slug: systemd
  name: systemd
  description: systemd is a suite of basic building blocks for a Linux system. It runs as PID 1 and is the system and service manager that bootstraps the rest of the userspace, supervises long-running services, and exposes a coordinated set of D-Bus and Varlink IPC interfaces for managing services (systemd1), use…
  api_count: 16
  score_band: thin
  score_composite: 32.6
  shared: 2
- slug: shell-scripting
  name: Shell Scripting
  description: A collection of APIs and resources for Shell Scripting development, including utilities, documentation, and tools.
  api_count: 5
  score_band: minimal
  score_composite: 27.7
  shared: 2
- slug: gvisor
  name: gVisor
  description: gVisor is an application kernel written in Go that implements a substantial portion of the Linux system surface. It provides an additional layer of isolation between running applications and the host operating system, intercepting and handling application system calls in user space to reduce the at…
  api_count: 1
  score_band: minimal
  score_composite: 22.9
  shared: 2
- slug: red-hat
  name: Red Hat
  description: APIs and developer resources from Red Hat, a leading provider of enterprise open source solutions including Linux, cloud, container, and Kubernetes technologies.
  api_count: 49
  score_band: strong
  score_composite: 61.8
  shared: 1
- slug: microsoft-windows-10
  name: Microsoft Windows 10
  description: Collection of APIs and developer resources for building applications on the Windows 10 platform, including Universal Windows Platform (UWP), Win32, and Windows Runtime APIs for desktop, mobile, and IoT applications.
  api_count: 17
  score_band: developing
  score_composite: 58.5
  shared: 1
- slug: cubefs
  name: CubeFS
  description: CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot and cold data tiers, and is widely used to back cloud-native…
  api_count: 2
  score_band: developing
  score_composite: 47.9
  shared: 1
- slug: microsoft-windows-server
  name: Microsoft Windows Server
  description: APIs and integration points for Microsoft Windows Server operating system including management, networking, storage, virtualization, security, and remote administration capabilities for enterprise server infrastructure.
  api_count: 16
  score_band: developing
  score_composite: 46.1
  shared: 1
- slug: ubuntu
  name: Ubuntu
  description: Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise services including Ubuntu Pro, MAAS,…
  api_count: 8
  score_band: thin
  score_composite: 39.1
  shared: 1
- slug: microsoft-windows
  name: Microsoft Windows
  description: A collection of APIs and developer resources for Microsoft Windows operating system.
  api_count: 8
  score_band: thin
  score_composite: 35.6
  shared: 1
- slug: canonical
  name: Canonical
  description: Canonical is the company behind Ubuntu, the world's most popular open source operating system for cloud, servers, desktops, IoT, and Kubernetes. Canonical publishes a broad set of developer APIs spanning the Ubuntu and Canonical ecosystem — the Snap Store and Snapcraft, the Charmhub charm marketpla…
  api_count: 9
  score_band: thin
  score_composite: 32.7
  shared: 1
- slug: runc
  name: Runc
  description: runc is a CLI tool for spawning and running containers on Linux according to the OCI (Open Container Initiative) specification. It is the reference implementation of the OCI runtime specification and is used as the default low-level container runtime by Docker, containerd, Podman, and other contain…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 1
- slug: civil-infrastructure-platform
  name: Civil Infrastructure Platform
  description: The Civil Infrastructure Platform (CIP) is a Linux Foundation collaborative project that builds an industrial-grade open source base layer for civil infrastructure systems such as transportation, power generation and distribution, building and city management, industrial control, and healthcare equ…
  api_count: 5
  score_band: minimal
  score_composite: 28.4
  shared: 1
- slug: command-line-interface
  name: Command Line Interface
  description: Command Line Interface (CLI) is a text-based way of interacting with software by typing commands at a prompt. Modern CLI design draws on decades of UNIX conventions while incorporating contemporary practices around discoverability, human-friendly output, machine-readable formats, configuration, sub…
  api_count: 4
  score_band: minimal
  score_composite: 25.0
  shared: 1
- slug: linux-server
  name: Linux Server
  description: Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, an…
  api_count: 7
  score_band: minimal
  score_composite: 23.8
  shared: 1
- slug: elisa
  name: ELISA
  description: ELISA (Enabling Linux in Safety Applications) is a Linux Foundation project that creates shared tools and processes to help companies build and certify Linux-based safety-critical applications. It addresses functional safety requirements for automotive, medical, and industrial systems using Linux.
  api_count: 1
  score_band: minimal
  score_composite: 21.2
  shared: 1
- slug: suse
  name: SUSE
  description: SUSE is a global provider of open source enterprise solutions including SUSE Linux Enterprise Server (SLES), SUSE Rancher Prime for Kubernetes management, SUSE Manager (SUMA) for Linux systems management, and SUSE Edge and Security solutions. SUSE products expose REST and "A-REST" APIs for automati…
  api_count: 2
  score_band: minimal
  score_composite: 13.8
  shared: 1
related:
- slug: linux-server
  name: Linux Server
  shared: 1
- slug: command-line-interface
  name: Command Line Interface
  shared: 1
repo: https://github.com/api-evangelist/linuxunix
overview: 'Linux/Unix System on the [APIs.io](https://apis.io/) network is a curated area collecting 10 resources — specifications, tools, and documentation — for this subject.


  23 providers on the network work in this area, including Linux/Unix System, Linux, UNIX System Call, Red Hat Enterprise Linux 8, Red Hat Enterprise Linux, Debian, and 17 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Linux Server and Command Line Interface. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
