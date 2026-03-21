# MyHass.io Home Assistant App

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]

## About

MyHass.io provides secure, remote access to your Home Assistant
instance through a simple, cloud-powered connection.

This repository contains the official MyHass.io Home Assistant app,
allowing you to connect your local instance to your MyHass.io account
and access it from anywhere using your own dedicated subdomain.

The goal of this project is to remove the complexity of remote access.
No port forwarding, no reverse proxies, no VPN setup.
Just a secure, reliable connection that works out of the box.

## Installation

To get started with MyHass.io, you need to add the app repository to your Home Assistant instance.

### 🚀 Option 1 — One-click install (recommended)

Click the button below to automatically add the repository:

[![Open your Home Assistant instance and show the add app repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FMyHass-io%2Fhomeassistant-app-public)

---

### ⚙️ Option 2 — Manual installation

1. Open Home Assistant
2. Go to **Settings** > **Apps** > **Install app**
3. Open the menu (⋮) → **Repositories**
4. Add the following repository URL:

```txt
https://github.com/MyHass-io/homeassistant-app-public
```

## Apps provided by this repository

This repository contains the following apps

### &#10003; [MyHass.io](./myhass)

![Latest Version][myhassio-version-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports i386 Architecture][i386-shield]

Home Assistant secure remote access

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You could open an issue here on GitHub. Note, we use a separate
GitHub repository for each app. Please ensure you are creating the issue
on the correct GitHub repository matching the app.

- [Open an issue for the app: MyHass.io][myhassio-issue]

For a general repository issue or app ideas [open an issue here][issue]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg

[addon-myhassio]: https://github.com/MyHass-io/homeassistant-app-public/tree/v1.0.0
[addon-doc-myhassio]: https://github.com/MyHass-io/homeassistant-app-public/blob/v1.0.0/README.md
[myhassio-issue]: https://github.com/MyHass-io/homeassistant-app-public/issues
[myhassio-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg

[issue]: https://github.com/MyHass-io/homeassistant-app-public/issues
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html