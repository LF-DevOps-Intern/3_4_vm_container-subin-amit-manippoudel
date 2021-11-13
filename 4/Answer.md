> Containers are a solution to the problem of getting software to run reliably when moved from one computing environment to another. This could be from a developer's laptop to a test environment, from a staging environment to production, or from a physical machine in a data center to a virtual machine in a private or public cloud.

+ A container can be as small as tens of megabytes, whereas a virtual machine with its own operating system can be several gigabytes in size. As a result, a single server can support far more containers than virtual machines.

+ Another big benefit is that virtual machines can take several minutes to boot up their operating systems and begin executing the programs they host, but containerized applications can begin virtually instantly. This means that containers can be instantiated "just in time" when needed and removed when no longer required, freeing up resources on their hosts.

+ A third advantage of containerization is that it allows for greater modularity. Instead of running an entire complex application within a single container, the application can be divided into modules (such as the database, the application front end, and so on). This is known as the microservices approach. Because each module is relatively simple, applications built in this manner are easier to manage, and changes to modules can be made without having to rebuild the entire application. Because containers are so light, individual modules (or microservices) can be instantiated only when needed and are ready almost immediately.

> Simply put, a container is an entire runtime environment: an application plus all of its dependencies, libraries and other binaries, and configuration files required to run it, all bundled into one package. Differences in operating systems and underlying infrastructure are abstracted away by containerizing the application platform and its dependencies.

> There are several examples in the industry where Docker is used to deploy micro-services within a micro-services architecture. Because of the small unit of services and Continuous Integration (CI) tools like Jenkins, etc, any rapid change to the functionality becomes easier and faster to deploy. Continuous Integration tools can easily build and deploy Docker images across application environments. Builds can be automated and efficiently monitored using the CI administrator console.

>Containers allow you to virtualize an operating system and run various workloads in a single OS instance. The hardware is virtualized with VMs in order to run multiple OS instances. The container's speed, agility, and portability offer it yet another tool for streamlining software development.
Container innovation offers an alternative technique for virtualization, in which a single functioning framework on a host may run a large number of cloud users.