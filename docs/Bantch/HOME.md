# Bantch

![diagram](https://www.plantuml.com/plantuml/svg/0/ZLIzRXin3DuD-1rOJmcGsakdJadS7xHD02D6iWRq7UC8q8cgA3b8YpvCaA50rw9FS2yMIkT_P-WDnfca-FsGkbE9669gRB_tnhZAffhWFaOlxqUZW0_3kOdtQPQ4GiKkael3YfiHri6WMzZaqsZyxkt4eelNbnSZYv4aQkXshDLe78MXBytxlGa5ONUKPYwUmE1QKliK34EDS4KAEkNAe8LpxLJT3t950schAEGYAKKde1mWDGYP4uB64meOTyUXmVPt-uy4F8am6e65oaeMQvJXuBZVcpvAfEP8l49CJNv7qCuJLYFcr0osmaO51tT0yNiYc5CWf_z0SNrtrEtqRsIcdSOSzDYotKRQvuH1cqPMKd30l6PPAvUYDLF8KTh3Mg7TddDoDOR78weuutwiM6GNzXX-zdkWpteowW4MjMvkrG1j2sVUMrDXDEmopw-uGAc2yL6XhmYhcAEVE3YgQ4F_BgaLxD0QfPa5x4mBACyAPe4VT8jq72jZAHOHkvomKOIp9Oi5msNxTq4smtxZQ4sXTQERr3upD2Mt1_TAprcjXzI6YlEaFsGh1mSHrMUna_4_8rfFw3KDtcGHaoyh3zMzgG_gCrpUZ0TTJZcBPoVjKzRWEO1GddLoAZsK3MVzrVrH6bWCKV1dNWu-8ohZ3giiiyx7cX-efyWjoftPMiqLoVMHRZ-l1GyonQsBze-IdeTCNc_0B5krNLbMfzEvtwFPI_pAT7Eck_dTqYrpct2P-rOqIrf-AbR2S2MdoKMdvEhoPNa1)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.