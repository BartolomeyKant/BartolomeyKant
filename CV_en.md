# Anton Kitaev

C++ Software Engineer (*Systems, Networking, Cross-Platform*)

EU Relocation Ready | Remote Worldwide

notevill@gmail.com |
t.me/bartolomey_kant |
linkedin.com/in/anton-kitaev |
github.com/BartolomeyKant

## Summary

 * 6+ years of experience in cross-platform **C++** development (linux, windows, macos, embedded). 
* Deep expertise in systems programming: modern C++17/20, template metaprogramming, and custom library design (reflection, serialization).
* Networking using TCP/UDP and platform specific I/O (epoll, kqueue, IOCP).
* Architect and delivered core components for desktop remote administration tool used by over 100K monthly users.
* Build cross-platform c++ client library for connectivity service from concept to production ready state.

## Experience

### Aethernet Inc

*C++ Software Engineer | from june 2024*

Æthernet is a cloud connectivity platform focused on energy-efficient IoT devices,
abstracting secure communication and network infrastructure for distributed
and resource-constrained systems, while remaining applicable to any application
requiring reliable network communication.

As a **C++ software engineer**, I rebuilt most the c++ client library from a
proof-of-concept state to near-production readiness:

- Architectured and build **reflection-like system** on **pure C++17**
with minimal use of macros, which provide types-safe and reliable access
to class members and automatic **serialization/deserialization** function with
simple one line declaration and makes implementation of API and data saving/loading
much easier.
- Developed a **custom smart pointer** on graphs capable of resolving circular links.
This allows to implement a unique objects system with ability to load and unload
any object from persistent storage during runtime, replace saved
instance implementation depending on platform.
This significantly  simplify writing secure and reliable code without fear of
memory leaks and memory errors.
- Built a single-threaded asynchronous framework to manage concurrent operations,
ensuring predictable execution and preventing race conditions without explicit synchronisation.
- Implemented the networking layer with POSIX/WinSock APIUs and platform specific
I/O (epoll, kqueue, IOCP) to ensure optimal performance and low latency across
all aupported platforms, with room to add additional implementation like LoRa,
Bluetooth LE or satellite networks.
- Co-designed the core RPC protocol and API for client-server and client-client
communication.
- Built and maintained the cross-platform build system with CMake, enabling a
single code base to target Linux, macOS, Windows, FreeBSD and ESP32 embedded devices.
- Implemented unit testing practices with Unity framework and test running on github CI.
The test coverage saved a lot of time by not manual testing and not fixing reappearing bugs during high paced development process.

### Tensor

*Software Engineer / Team Lead | oct. 2021 - june 2024*

Architect and delivered core components for a high-performance cross-platform
desktop application for remote administration serving **100k+ monthly users**.

- **Managed the desktop development team**, overseeing the full delivery lifecycle
from low-level logic to final deployment.
- Implemented fundamental core modules including the **pipeline system**,
**serialization/reflection engines**, and **event-driven** communication layers.
- Designed and implemented custom GUI widgets and integrated system-level
services for **file and clipboard buffer sharing**.
- Automated multi-platform distribution (**Linux RPM, Windows MSI, macOS DMG**)
using **CMake** and **CPack**. All in one codebase maintained by the development
team which reduces cost for packaging tuning and fixing for installation related bugs.

### Progress

*Software Engineer | oct. 2019 - oct. 2021*

Contributed to specialized networking and terminal solutions within a 
high-velocity development team:

- **Election Terminal:** Built frontend and backend components for a secure
touch-screen voting interface using **C++** and **Qt (QML)**.
- **PBX Operator Terminal:** Developed a Linux-based touchscreen application
tailored for telecommunication operators.
- **Networking Infrastructure:** Integrated VPN tunneling protocols (PPTP, L2TP, 
IPsec/StrongSwan) into the **XORP-based router platform** using C++, SCons, Buildroot.
- **Tooling:** Designed a lightweight **automated testing framework** utilizing 
Bash and Docker.

## Education

*Ufa State Aviation Technical University | 2011 - 2017*

Master of Engineering - MEng, Mechatronics, Robotics, and Automation Engineering

## Skills

C++ (17/20) | Python | Bash | Linux | Windows | TCP/UDP | POSIX API | CMake | CPack | Git | Docker | Qt | Boost | Template Metaprogramming | Asynchronous Programming | GDB
