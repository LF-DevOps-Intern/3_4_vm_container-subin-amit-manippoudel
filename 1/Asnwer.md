> A virtual machine (VM) is a virtual environment that functions similarly to a computer inside a computer. It runs on a separate partition of the host computer, with its own CPU power, memory, operating system (e.g., Windows, Linux, macOS), and other resources. This enables end users to run applications on virtual machines and use them in the same way they would on a physical workstation.

+ Virtual machines (VMs) are made possible by virtualization technology. Virtualization employs software to simulate virtual hardware, allowing multiple virtual machines (VMs) to run on a single machine. The physical machine is referred to as the host, and the VMs that run on it are referred to as guests. 	
 A hypervisor is a piece of software that manages this process. The hypervisor is in charge of managing and provisioning resources from the host to guests, such as memory and storage. It also schedules operations in VMs so that they do not compete for resources. Virtual machines (VMs) can only function if there is a hypervisor to virtualize and distribute host resources.
 A "virtual machine" (VM) is a tightly isolated software container that contains an operating system and an application. Each self-contained VM is completely autonomous. Using multiple VMs on a single computer allows multiple operating systems and applications to run on a single physical server, or "host." A thin layer of software known as a "hypervisor" decouples the virtual machines from the host and dynamically allocates computing resources to each virtual machine as needed.



> Types of hypervisors

There are two types of hypervisors used in virtualization.

+ Type 1 hypervisors

    Type 1 hypervisors (also known as bare metal hypervisors) run on the underlying physical hardware. Virtual machines (VMs) communicate directly with hosts to allocate hardware resources, with no additional software layers in between.

    Host machines that run type 1 hypervisors are only used for virtualization. They are common in server-based environments such as enterprise data centers. Citrix Hypervisor (previously XenServer), VMware vSphere, and Microsoft Hyper-V are examples of type 1 hypervisors.

    To handle guest activities such as creating new virtual machine instances or managing permissions, a separate management tool is required.

+ Type 2 hypervisors

    Type 2 hypervisors (also known as hosted hypervisors) run on the operating system of the host computer.

    Hosted hypervisors route VM requests to the host operating system, which allocates the necessary physical resources to each guest. Because every VM action must first pass through the host operating system, type 2 hypervisors are slower than type 1 hypervisors.

    Guest operating systems, unlike bare-metal hypervisors, are not bound to physical hardware. Users can run VMs and continue to use their computers as usual. As a result, type 2 hypervisors are appropriate for personal users or small businesses that do not have dedicated virtualization servers.
