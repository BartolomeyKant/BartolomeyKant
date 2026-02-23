# Anton Kitaev Senior C++ Software Engineer
<div class="row" style="display: flex;">
<div style ="margin: 0 1% 0 0;">
    <image src="images/photo_of_me.jpg" width="200" style="margin: auto auto;"/>
</div>
  
<div> 
    
**Contact information**

email: `notevill@gmail.com` <br>
telegram: [@bartolomey_kant](https://t.me/bartolomey_kant) <br>
linkedin: [linkedin.com/in/anton-kitaev](https://linkedin.com/in/anton-kitaev) <br>
github: [github.com/BartolomeyKant](https://github.com/BartolomeyKant) <br>

### Summary

I am a **C++** software engineer with more than 6 years of experience developing 
cross-platform applications. 
I have a strong background in modern **C++17 and later** features, 
including template metaprogramming (*no fear of SFINAE*), RAII, lambdas, and smart pointers. 
I always write code with a focus on readability, maintainability, and performance. 
My passion is creating code tools and libraries that simplify development and 
improve the expressiveness of language idioms.

</div>
</div>

## Skills

- **Languages:** C++ (17/20), Python, Bash, SQL.
- **Systems & Networking:** Linux, Windows, FreeBSD, ESP-IDF, TCP/UDP, epoll, IOCP, kqueue, POSIX API.
- **Architecture & Patterns:** Template Metaprogramming (*SFINAE + Concepts*), RAII, Asynchronous Programming, Reflection Systems, RPC Design.
- **Frameworks & Libraries:** Qt (QML), Boost, Unity (Unit Testing), CPack.
- **DevOps & Tools:** CMake, Git, Docker, SCons, GDB, Bloaty.

## Experience

### Aethernet 2024 - 2026

Æthernet is a cloud connectivity platform focused on energy-efficient IoT devices, 
abstracting secure communication and network infrastructure for distributed 
and resource-constrained systems, while remaining applicable to any application 
requiring reliable network communication.

As a **C++ software engineer**, I rebuilt most of the client library from a 
proof-of-concept state to near-production readiness, including:

- A **reflection-like system** and serialization/deserialization module in **pure C++17** with minimal use of macros.
- A **custom smart pointer** for graphs capable of resolving circular links.
- An **event system** with support for multiple RAII subscriptions, recursive calls, 
and event object life extension.
- An **action system** for asynchronous operations running concurrently on a **single thread**.
- **Aether API RPC** protocol support with method invoking and dispatching.
- **TCP/UDP networking** using pure POSIX and WinSock APIs, with **platform-specific 
pollers (epoll, kqueue, IOCP)**.
- Build support for Linux, macOS, Windows, FreeBSD, and ESP32 (with ESP-IDF and Arduino IDE).
- Unit testing with the Unity framework.

Also, I:

- Perform **code reviews** and help colleagues better understand the codebase, 
providing guidance on its effective and correct usage.
- Participate in **API and RPC protocol design**.
- Contribute to third-party libraries used or planned for use in the project.
- Constantly research and experiment with new technologies, techniques, and tools 
to optimize **project performance and binary size**.

### Tensor 2021 - 2024

**Software Engineer / Team Lead**

Developed a high-performance cross-platform desktop application for remote 
administration serving **100k+ monthly users**.

- Implemented fundamental core modules including the **pipeline system**, 
**serialization/reflection engines**, and **event-driven** communication layers.
- Designed and implemented custom GUI widgets and integrated system-level 
services for **file and clipboard buffer sharing**.
- **Managed the desktop development team**, overseeing the full delivery lifecycle 
from low-level logic to final deployment.
- Automated multi-platform distribution (**Linux RPM, Windows MSI, macOS DMG**) 
using **CMake** and **CPack**.

### Progress 2019 - 2021

**Software Engineer**

Contributed to specialized networking and terminal solutions within a 
high-velocity development team:

- **Election Terminal:** Built frontend and backend components for a secure 
touch-screen voting interface using **C++** and **Qt (QML)**.
- **PBX Operator Terminal:** Developed a Linux-based touchscreen application 
tailored for telecommunication operators.
- **Networking Infrastructure:** Integrated VPN tunneling protocols (PPTP, L2TP, 
IPsec/StrongSwan) into the **XORP-based router platform** using C++ and SCons.
- **Tooling:** Designed a lightweight **automated testing framework** utilizing 
Bash and Docker.
