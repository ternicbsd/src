# TernixBSD  

## Overview  
TernixBSD is a modern, high‑performance operating system that combines the stability and speed of FreeBSD with broad binary‑compatibility across multiple platforms. The repository contains the complete source code required to build, test, and extend the system.

## Key Features  

| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **FreeBSD‑grade performance** | Core kernel and subsystems are built on the proven FreeBSD codebase, delivering low latency and high throughput. |
| **Cross‑platform binary compatibility** | Native support for binaries from **BSD**, **Linux**, and **macOS**. Users can run a wide range of existing applications without modification. |
| **Unified environment**     | One operating system that simultaneously hosts applications from three major ecosystems, simplifying workflow and reducing the need for multiple installations or virtual machines. |
| **Extensible architecture** | Modular design makes it straightforward to add new drivers, filesystems, or compatibility layers. |

## Compatibility  

- **BSD applications** – Full compatibility with standard FreeBSD and other BSD‑derived software.  
- **Linux applications** – Integrated Linux compatibility layer (based on the FreeBSD `linux(4)` framework).  
- **macOS applications** – Experimental macOS binary compatibility, enabling a broader range of desktop and development tools to run directly on TernixBSD.

> **Note:** While the macOS compatibility layer is decent, it is still under active development. Contributions 
and feedback are welcome.

## Getting Started  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourorg/TernixBSD.git
   cd TernixBSD
   ```
2. **Build the system**

Follow the step-by-step guide in ``docs/BUILDING.md`` The script automatically fetches the required toolchains and dependecies.

3. **Install**

Instructions for installing TernixBSD on real hardware or in a virtual environment are provided in ``docs/INSTALLATION.md``. 


## License

TernixBSD is released under the BSD 2‑Clause License. See the ``LICENSE`` file for the full text.

## Contact & Support

Soon, currently, we need more progress first.
