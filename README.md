# Home Assistant Community Add-on: WireGuard

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports i386 Architecture][i386-shield]

WireGuard: fast, modern, secure VPN tunnel.

## About

[WireGuard®][wireguard] This fork aims to make Wireguard available as a client (instead of acting as a server) on Home Assistant installations. 

As (like me myself) several people are asking to have Home Assistant connect as a client to an Wireguard Server I decided to make that possible. 

I haven an ISP that keeps me behind CG-NAT (in Germany also called DS-Lite) so no chance to connect to my home assistant solution from the internet. Only chance is so have an wireguard server running somewhere else (for example a small VPS solution at some hosting company) and connect to that server and on the server expose a port/domain (behind nginx-proxy with SSL encryption) ...

[:books: Read the full add-on documentation][docs]

## Support

Got questions?

Please [open an issue here][issue] GitHub.

## Authors & contributors

The original setup of this repository is by [Franck Nijhof][frenck].

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/hassio-addons/addon-wireguard.svg
[commits]: https://github.com/hassio-addons/addon-wireguard/commits/main
[contributors]: https://github.com/hassio-addons/addon-wireguard/graphs/contributors
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[docs]: https://github.com/hassio-addons/addon-wireguard/blob/main/wireguard/DOCS.md
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/t/home-assistant-community-add-on-wireguard/134662?u=frenck
[frenck]: https://github.com/frenck
[github-actions-shield]: https://github.com/hassio-addons/addon-wireguard/workflows/CI/badge.svg
[github-actions]: https://github.com/hassio-addons/addon-wireguard/actions
[github-sponsors-shield]: https://frenck.dev/wp-content/uploads/2019/12/github_sponsor.png
[github-sponsors]: https://github.com/sponsors/frenck
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/hassio-addons/addon-wireguard/issues
[license-shield]: https://img.shields.io/github/license/hassio-addons/addon-wireguard.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[patreon-shield]: https://frenck.dev/wp-content/uploads/2019/12/patreon.png
[patreon]: https://www.patreon.com/frenck
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[reddit]: https://reddit.com/r/homeassistant
[releases-shield]: https://img.shields.io/github/release/hassio-addons/addon-wireguard.svg
[releases]: https://github.com/hassio-addons/addon-wireguard/releases
[repository]: https://github.com/hassio-addons/repository
[wireguard]: https://www.wireguard.com
