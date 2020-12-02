# Glossary

> unsorted yet...

* Virtualization
  * Hypervisor:
    * traditionally called a virtual machine monitor or VMM.
    * handles the translations between physical and virtual resources and manages the support of virtual machines (VMs)
  * host machine: The physical hardware that a hypervisor runs on
  * guest machine: the VMs the hypervisor creates and supports are collectively called guest machines
  * Type 1 Hypervisors:
    * runs directly on the host machine's physical hardware, and it's referred to as a bare-metal hypervisor
    * it doesn't have to load an underlying OS first. With direct access to the underlying hardware and no other software to contend with
    * low latency, more secure, hardware acceleration (if enabled), for enterprise computing
    * examples: VMware ESXi, Microsoft Hyper-V server and open source KVM
  * Type 2 Hypervisors:
    * typically installed on top of an existing OS
    * called a hosted hypervisor because it relies on the host machine's pre-existing OS to manage calls to CPU, memory, storage and network resources
    * less secure, client hypervisors (not used in data centers), hardware acceleration (if enabled) + software emulation
    * examples: VMware Fusion, Oracle VM VirtualBox, Oracle VM Server for x86, Oracle Solaris Zones, Parallels and VMware Workstation
  * ESXi
  * refs:
    * [What's the difference between Type 1 and Type 2 hypervisors?](https://searchservervirtualization.techtarget.com/feature/Whats-the-difference-between-Type-1-and-Type-2-hypervisors)

* Headless Computer:
  * a computer system or device that has been configured to operate without a monitor (the missing "head"), keyboard, and mouse.
  * typically controlled over a network connection
  * typically employed to reduce operating costs.
* Headless Software: software capable of working on a device without a graphical user interface
* Headless Webisites
* Headless Browser
