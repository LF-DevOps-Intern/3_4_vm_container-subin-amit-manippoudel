# Container
> Container-based virtualization makes use of kernel features to provide processes with an isolated environment. Containers,     unlike hypervisor-based virtualization, do not have their own virtualized hardware and instead use the hardware of the host system. As a result, software running in containers communicates directly with the host kernel and must be compatible with the host's operating system and CPU architecture. Because containers do not need to emulate hardware or boot an entire operating system, they can start in a few milliseconds and are more efficient than traditional virtual machines.
    Container images are typically smaller than virtual machine images because they do not require a complete toolchain to run an operating system, such as device drivers, the kernel, or the init system.
    This is one of the reasons why container-based virtualization has grown in popularity in recent years. The small resource fingerprint enables better performance on both a small and large scale, while still providing relatively strong security benefits.

> Benefits of Container

+ Containers are small and light.
    Containers only use the binaries and libraries that they require. This means they boot much faster than VMs. Boot times in seconds versus boot times in minutes can make a huge difference in the world of web applications. Being more lightweight also necessitates the use of less hardware and operating systems.
+ Containers can be moved around.
    A container can be run anywhere a container engine can be run. This means that arguments about an environment being the source of a problem with an app should be reduced. If it ran for development on their container, it should also run for QA and production.
+ Containers make microservices possible.
    Microservices, in a nutshell, are small services that communicate with one another to form a larger application or service. Individual microservices are decoupled to make testing easier, single points of failure are reduced, and development velocity is increased.
