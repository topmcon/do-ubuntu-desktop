# do-ubuntu-desktop
Transform any DigitalOcean Ubuntu droplet into a full GNOME desktop with NoMachine

## Overview

This repository provides a simple, automated way to convert your DigitalOcean Ubuntu droplet into a full desktop environment with remote access. Perfect for:

- 🖥️ Having a cloud-based development environment
- 🔒 Isolated testing without affecting production sites
- 🌐 Access your desktop from anywhere
- 💻 Full GUI applications (browsers, IDEs, etc.)

## What Gets Installed

- **GNOME Desktop Environment** - Full-featured Linux desktop
- **NoMachine** - High-performance remote desktop server
- **Firefox** - Web browser
- **Development Tools** - git, vim, build tools, etc.

## Quick Start

See [quick-start.md](quick-start.md) for detailed instructions.

### TL;DR

```bash
# SSH into your droplet
ssh root@YOUR_DROPLET_IP

# Download and run the setup script
curl -O https://raw.githubusercontent.com/topmcon/do-ubuntu-desktop/main/setup-desktop.sh
chmod +x setup-desktop.sh
sudo bash setup-desktop.sh

# Create user, reboot, then connect with NoMachine client
```

## Requirements

- DigitalOcean Ubuntu 24.04 droplet
- At least 2GB RAM (4GB+ recommended)
- Root or sudo access

## Support

For issues or questions, open an issue on GitHub.

## License

MIT
