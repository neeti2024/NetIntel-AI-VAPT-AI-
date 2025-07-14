# NetIntel AI

This is a Next.js application built in Firebase Studio. It provides an interface for running security scans using popular open-source tools and leverages AI for report generation.

To get started, take a look at `src/app/page.tsx`.

## Prerequisites

This application acts as a frontend for several command-line security tools. For the scanning functionality to work, you must have the following tools installed on the server where this application is deployed:

- **nmap**: For network and port scanning.
- **nikto**: For web server vulnerability scanning.
- **dirb**: For web content and directory bruteforcing.

A `requirements.txt` file is included to list these dependencies. You can typically install them on a Debian/Ubuntu system with the following command:

```bash
sudo apt-get update && sudo apt-get install -y nmap nikto dirb
```

Please consult your operating system's package manager for installation instructions.
