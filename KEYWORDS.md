
# KEYWORDS
![download](https://github.com/KRIISHSHARMA/CODE/assets/86760658/5b72aef7-b976-4088-81d2-d0d94c05d003)
1. **CISC** - Complex Instruction Set Computer- Closed
 source - intel, AMD
2. **RISC** - Reduced Instruction Set Computer- Closed source - ARM
3. **RISC-V**  - It is an ISA based on reduced instruction set computer (RISC) principles. It is Open Source unlike the parent RISC.
4. **Kernel** - programm to manage communication between software i.e. user-level applications and hardware i.e., CPU and disk memory  
- Kernel Programming Languages
  - C
  - Rust
  - C++
5. **DNS** - turns domain names into IP addresses, which allow browsers to get to websites and other internet resources.
6. **ISA** - Instruction Set Architecture - An Instruction Set Architecture (ISA) is part of the abstract model of a computer that defines how the CPU is controlled by the software. The ISA acts as an interface between the hardware and the software, specifying both what the processor is capable of doing as well as how it gets done.
7. **IP Addresss**- Internet Protcol (IPv4,IPv6)
 - Public IP - B/W Internet and Device, assigned by internet service provider to the device
 - Private IP - in a private network [starts with 10., 172.16, 192.168]
 - Local IP - [starts with 127.00.0]
9. **Port No.** - a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server.[for http - 80
 - SSH(Secure Shell) - 22
 - SMTP - 25  
 - Telnet - 23
 - https - 443
 - DNS - 53
10. **SSL**- Secure Socket Layer - IP Address + Port Number
11. **Seven Layers Of OSI**(Open Systems Interconnection)
 - L7 - Application
 - L6 - Presentation
 - L5 - Cryptography
 - L4 - Port Number(16 Bits)
 - L3 - IP Address (32 Bits) : Router
 - L2 - Hardware Address - NIC, MAC Address(48 Bits) : Ethernet :*SWITCH*
 - L1 - Digital (1 and 0)

12. **Switch** - connects devices in a network to each other, enabling them to talk by exchanging data packets. [ layer 2 of OSI]
13. **Virtual Machine** - created by using Hypervisor
14. **FPGA** - Field Programmable Gate Arrays  - Configurede after manufacturing
15. **Socket** - Software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network
16. **TCP** - Transmission Control Protocol (TCP) is a standard that defines how to establish and maintain a network conversation by which applications can exchange data
17. **MAC Address** - Media Access Control address is a unique identifier assigned for use as a network address in communications within a network segment.(48 bits)
18. **Protocol**- It is a standardized set of rules for formatting and processing data.
19. **Firmware** - It is a microcode or program that is embedded into the memory of hardware devices to help them operate
20. **TLS** - Transport Layer Security encrypts data sent over the Internet
21. **Cache** - a cache is a high-speed data storage layer which stores a subset of data (temporary mermory)
22. **STACK** - Stack is a linear data structure that follows a particular order in which the operations are performed. **LIFO** (Last In First Out)

23. Von Neuman Architecture 
Hagward Architecture 

24. **Debian** - Linux Software/OS Family
25. **VMware Workstation** - IT is a line of Desktop Hypervisor products which lets users run virtual machines, multiple OS
26. **VPN** - It establishes a digital connection between your computer and a remote server owned by a VPN provider, creating a point-to-point tunnel that encrypts your personal data, masks your IP address, and lets you sidestep website blocks and firewalls on the internet.
27. **Cryptography** - It is the practice and study of techniques for secure communication in the presence of adversarial behavior. It is about constructing and analyzing protocols that prevent third parties or the public from reading private messages. 
28. **Hypervisor** - It is a type of computer software, firmware or hardware that creates and runs virtual machines.
    - TYPE 1 : hypervisor runs directly on the host machine's physical hardware
    - TYPE 2 : hypervisor is typically installed on top of an existing OS.
      -- **kvm** - Kernel-based Virtual Machine is a free and open-source virtualization module in the Linux kernel that allows the kernel to function as a hypervisor.
      -- **xen** - Xen is a free and open-source type-1 hypervisor, providing services that allow multiple computer operating systems to execute on the same computer 
          hardware concurrently.
30. **BareMetal**- Fresh Servers
31. **IAM** - Identity and access management
32. **nginx** - proxy server
33. **apache** - client server - uses httpd(d stands for dameon:continuously runs in background) that creates a pool of child processes or threads to handle requests.
34. **OOPS** - "object oriented programming systum/structue", It is a programming model based on the concept of “objects,” which can contain data and code to manipulate that data.
 -The 4 pillers of **opps** :
  -**Encapsulation** :refers to the bundling of data, along with the methods that operate on that data, into a single unit.
  -**Abstraction**  :is the process of hiding the internal details of an application from the outer world.
  -**Inheritence** :one class inherits the attributes and methods of another class.
  -**Polymorphism** :is the method in an object-oriented programming language that performs different things as per the object's class, which calls it.
35. **Certificate Authority** - (CA) is a trusted entity that issues Secure Sockets Layer (SSL) certificates
36. **Certificate X.509** - The certificate is typically used to manage identity and security in computer networking and over the internet. For the internet, it is used in numerous protocols to ensure a malicious website doesn't fool a web browser. The X. 509 certificate is also used to secure email, device communications and digital signatures. 
  - (CA) ex:- GoDaddy , Let's Encrypt(open) etc.
  - Signing Certificate algorithm is Cryptography : RSA, Elliptic Curve
37. **Load Blanacer** - is a device that acts as a reverse proxy and distributes network or application traffic across a number of servers.
     -Algorithm is **ROUND ROBIN**
38. **Round Robin** - Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way. It is basically the preemptive version of First come First Serve CPU Scheduling algorithm. Round Robin CPU Algorithm generally focuses on Time Sharing technique.
39. **NAT** - ( network address translation ) It's a way to map multiple private addresses inside a local network to a public IP address before transferring the information onto the internet.<translates privete ip to publice ip and vica verse>
40. **ASIC** - ( App specific integrated ckt. ) is an integrated circuit chip customized for a particular use, rather than intended for general-purpose use, such as a chip designed to run in a digital voice recorder or a high-efficiency video codec. ex- ***BITCOIN MINER***
41. **containers** - Containers are packages of software that contain all of the necessary elements to run in any environment. In this way, containers virtualize the operating system and run anywhere, from a private data center to the public cloud or even on a developer's personal laptop.
42. **dockers** - Docker is a platform designed to help developers build, share, and run container applications. We handle the tedious setup, so you can focus on the code.
    ![containers_vs_vm-1-1](https://github.com/KRIISHSHARMA/basics/assets/86760658/a321e5fc-d1b7-460e-95be-cf81d7492832)
43. **LXC(liinux containers)** - Linux Containers is an operating-system-level virtualization method for running multiple isolated Linux systems on a control host using a single Linux kernel
44. **centralized computing** - Centralized computing is computing done at a central location, using terminals that are attached to a central computer.
45. **decentralized computing** - Decentralized computing is the allocation of resources, both hardware and software, to each individual workstation, or office location
46. **distributed computing** - Distributed computing is the method of making multiple computers work together to solve a common problem.
47. **pointers** - A pointer is a variable that stores the memory address of an object.
48. **API(Application Programming Interface)** - An application programming interface (API) is a way for two or more computer programs to communicate with each other.
                                               - rest api(representational state transfer architectural style)
                                               - grpc(Remote Procedure Calls)
                                               - graphql
    <img width="400" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/b3ef0ed8-6e5d-406d-abfe-a1f0d0a78526">

49. **qiskit** - Qiskit helps users schedule and run quantum programs on a variety of local simulators and cloud-based quantum processors.
50. **AES ENCRYPTION** - The algorithm described by AES is a symmetric-key algorithm, meaning the same key is used for both encrypting and decrypting the data.
51. **PKI** - PKI, or public key infrastructure, encompasses everything used to establish and manage public key encryption.
52. **fourier series** - A Fourier series is an expansion of a periodic function f(x) in terms of an infinite sum of sines and cosines
53. **fast fourier transformer** - It converts a signal into individual spectral components and thereby provides frequency information about the signal
54. **NUMA(Non Uniform Memory Access)** - Non-uniform memory access (NUMA) is a computer memory design used in multiprocessing, where the memory access time depends on the memory location relative to the processor. Under NUMA, a processor can access its own local memory faster than non-local memory (memory local to another processor or memory shared between processors).
55. **eBPF** - Extended Berkeley Packet Filter (eBPF) is a Linux kernel technology enabling engineers to build programs that run securely in kernel space.
56. **k8s(Kubernetes)** - Kubernetes automates operational tasks of container management and includes built-in commands for deploying applications, rolling out changes to your applications, scaling your applications up and down to fit changing needs, monitoring your applications, and more—making it easier to manage applications.
57. **huge pages** - HugePages optimizes the memory configuration of the Linux operating system.
58. **openstack** - OpenStack is a free, open standard cloud computing platform. It is mostly deployed as infrastructure-as-a-service in both public and private clouds where virtual servers and other resources are made available to users.
    -***neutron***- Neutron is an OpenStack project to provide "networking as a service" between interface devices (e.g., vNICs)
    -***nova***- A compute service responsible for creating virtual machine instances and managing their life cycle, as well as managing the hypervisor of choice.
    -***horizon**- A dashboard that creates a GUI for users to control the OpenStack deployment. This is an extensible framework to which vendors can add features
    -***swift***- An object and Binary Large Object (BLOB) storage service responsible for managing object-based storage
    -***Keystone***- An identity management system responsible for user and service authentication. 
59. **proxmox** - Proxmox VE is an open-source platform for server virtualization that offers robust capabilities for managing both KVM (Kernel-based Virtual Machine) hypervisors and Linux Containers (LXC). It's used by organizations large and small.
60. **HA(high availability)** - High availability (HA) is the ability of a system to operate continuously without failing for a designated period of time.
![data_center-information_flow-f_mobile](https://github.com/KRIISHSHARMA/basics/assets/86760658/03ec7947-f488-4e3d-ac1f-1903c32db2c6)
61. **IAC** - Infrastructure as code (IaC) uses DevOps methodology and versioning with a descriptive model to define and deploy infrastructure, such as networks, virtual machines, load balancers, and connection topologies.
62. **Brown field app** - Brownfield application development usually happens when you want to develop or improve upon an existing application, and compels you to work with previously created code.
    - ***monolithic*** - A monolithic application is built as a single unified unit 
63. **Green field app** - Greenfield software development refers to developing a system for a totally new environment and requires development from a clean slate – no legacy code around.
      -***microservices*** - microservices architecture is a collection of smaller, independently deployable services.
      - For a lightweight application, a monolithic system often suits better. For a complex, evolving application with clear domains, the microservices architecture will be the better choice.
64. **backend** -- ***caching*** :
 Caching is the process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly.
 ex: redis(Redis is an open-source in-memory storage, used as a distributed, in-memory key–value database, cache and message broker, with optional durability.)
  -- ***VCS*** : Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.
        ex: github , gitlab, bitbucket
  -- ***Database*** : -1. vector db (
Vector databases are typically used to power vector search use cases like visual, semantic, and multimodal search. More recently, they're paired with generative artificial intelligence (AI) text models to create intelligent agents that provide conversational search experiences.)
-2. sql(Structured query language (SQL) is a programming language for storing and processing information in a relational database.)
-3. NoSQL, (also referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases. ex(mongodb))
    <img width="400" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/50941e5d-1d55-496c-9c3b-d961c127b4fd">

66. **ddos** - A distributed denial-of-service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a targeted server, service or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic.
67. **cgroups** - cgroups (abbreviated from control groups) is a Linux kernel feature that limits, accounts for, and isolates the resource usage (CPU, memory, disk I/O, etc.) of a collection of processes.
68. **namespace** - create isolated environments for processes, separating them from the host system and other processes.
<cgroups, short for control groups, allow administrators to limit and distribute resources among different groups of processes. Namespaces, on the other hand, create isolated environments for processes, separating them from the host system and other processes.>
69. **borg** - Google created cgroups around 2006 to enable their Borg infrastructure, an app clustering system that is a spiritual precursor to Kubernetes.
<img width="312" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/74ed2acd-f036-41a3-93b7-ae396e306737">

70. **hyperscalers** - A hyperscaler is a type of large-scale data center that offers massive computing resources, typically in the form of an elastic cloud platform. Organizations use them to deploy and manage large-scale applications and services. ex: Amazon AWS, Microsoft Azure, Google GCP, Alibaba AliCloud, IBM, and Oracle
71. **HCI**- Hyperconverged infrastructure (HCI) is a software-defined, unified system that combines all the elements of a traditional data center: storage, compute, networking and management.
72. **pods** - Pods are the smallest deployable units of computing that you can create and manage in Kubernetes(specially made for deploying and managing containarized apps)
72.**kata containers**- Kata Containers is an open source community working to build a secure container runtime with lightweight virtual machines that feel and perform like containers, but provide stronger workload isolation using hardware virtualization technology as a second layer of defense.

<img width="559" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/32e49283-95b0-4afc-94bd-48dff4397e6e">
<img width="338" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/ef434407-4181-4a76-ab39-e079d01a8304">

73.**kubevirt** - KubeVirt is a virtual machine management add-on for Kubernetes. The aim is to provide a common ground for virtualization solutions on top of Kubernetes.
74.**overlay network**- An overlay network is a network that is built on top of another network and is supported by its infrastructure. An overlay network decouples network services from the underlying infrastructure by encapsulating one network packet inside of another packet.
75.**underlay network** -the underlay network means all the physical infrastructure that enables frames and packets to be forwarded from o one point to another. In other words, we can understand the underlay networks as the “place” on which it is possible to connect and communicate with networking devices.
<img width="560" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/ef9900a4-22a3-4b8e-959a-050f101e6ca6">
<img width="572" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/18fe86ac-dbbc-4371-a2ba-3c1e7b701c33">

76.**cni**- CNI stands for container network interface and it's a specification to configure network interfaces in Linux containers. And it is concerned mainly with adding, connecting and deleting disconnecting containers to networks.
77.**TUN && TAP**- In computer networking, TUN and TAP are kernel virtual network devices. Being network devices supported entirely in software, they differ from ordinary network devices which are backed by physical network adapters.
-***TUN*** :carries ip packets 
-***TAP*** :carries ethernet frames 
![image](https://github.com/KRIISHSHARMA/basics/assets/86760658/f2e17ee0-bf2f-4104-9622-c8eb08479015)

<img width="476" alt="image" src="https://github.com/KRIISHSHARMA/basics/assets/86760658/ca3d3dca-fd71-4e56-a138-bad672fa0bee">






 
