+++
title = "Privilege boundary"
slug = "privilege-boundary"
template = "initiatives/privilege-boundary.html"
+++

### Sudo-rs

The sudo and su utilities mediate a critical privilege boundary on almost every open-source operating system
that powers the Internet.

Sudo-rs is a sudo alternative that doesn't suffer from memory safety vulnerabilities and is
designed to minimize attack surface.

### Project status

Sudo-rs was [first released](https://www.memorysafety.org/blog/sudo-first-stable-release/) on Aug 29, 2023. The project is under development to add cross-platform support and improve compatibility with the original sudo utility.

We'd like to thank Todd Miller, maintainer of the original sudo utility, for his advice and guidance on our implementation.

### Roadmap

See <a href="/initiatives/workplan-sudo-rs">the sudo-rs roadmap</a>.

### Links

- [GitHub](https://github.com/memorysafety/sudo-rs)

### History

The initial development of sudo-rs was started and funded by the [Internet Security Research Group](https://www.abetterinternet.org/) as part of the [Prossimo project](https://www.memorysafety.org/). A joint development effort between [Tweede golf](https://tweedegolf.nl/en) and [Ferrous Systems](https://ferrous-systems.com/) resulted in the first release. In July 2024 the [sudo-rs moved to the Trifecta Tech Foundation](https://www.memorysafety.org/).

        