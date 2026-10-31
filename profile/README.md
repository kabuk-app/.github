<img src="https://raw.githubusercontent.com/kabuk-app/.github/main/profile/logo.svg" alt="" width="72" height="72">

# Kabuk

Kabuk is an SSH client that keeps everything on your side. Your hosts, keys and snippets live in an
encrypted vault that only you can open. There is no account to create and no cloud service that holds
your data. Your devices sync with each other directly, or through a free relay that only passes along
data it cannot read. You can run your own relay if you prefer.

We started it because carrying your own server list from one machine to another should not need an
account or a company in the middle. Kabuk is free and open source.

Kabuk is early and not released yet. Nothing here is ready to install.

## Projects

- [app](https://github.com/kabuk-app/app): the client for desktop, Android, iOS and the web
- [core](https://github.com/kabuk-app/core): the shared Rust engine for encryption, vault, sync and SSH
- [proto](https://github.com/kabuk-app/proto): the wire protocol
- [relay](https://github.com/kabuk-app/relay): a server you can host to connect your devices
- [bridge](https://github.com/kabuk-app/bridge): a server you can host so the web app can reach SSH hosts
- [website](https://github.com/kabuk-app/website) and [docs](https://github.com/kabuk-app/docs): kabuk.app
- [design](https://github.com/kabuk-app/design): the design system

## Open and closed

The client, core, protocol, relay and bridge are open source under GPLv3. A paid enterprise offering
is planned for companies, and its server code and admin panels will be closed source. The open client
only talks to it through a documented public API.

## Links

Website: https://kabuk.app

Contributing, security reports and the code of conduct are in this organization's
[.github repository](https://github.com/kabuk-app/.github).
