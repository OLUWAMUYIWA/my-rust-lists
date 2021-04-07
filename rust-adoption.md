# Rust adoption notes

Notes about major production deployments of Rust.
Useful in cases where someone asks "who is actually using Rust?".

- **Firefox**

- **Facebook** uses Rust for source management and other things
  - https://github.com/facebookexperimental/mononoke

- **Amazon** in AWS Fargate container orchestration
  - https://blog.acolyer.org/2020/03/02/firecracker/
  - https://aws.amazon.com/blogs/aws/bottlerocket-open-source-os-for-container-hosting/

- **Google**
  - Fuchsia operating system and ChromeOS
    - https://news.ycombinator.com/item?id=22410460
  - Android's bluetooth stack
    - https://news.ycombinator.com/item?id=26647981
  - Android OS generally
    - https://security.googleblog.com/2021/04/rust-in-android-platform.html
    - https://news.ycombinator.com/item?id=26714478

- **Dropbox**'s storage backend is in Rust, probably other components as well
  - https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine

- **Cloudflare** uses Rust for multiple purposes

- **Reddit** uses Rust on every request for markdown parsing
  - and other projects

- **Apple**
  - https://www.reddit.com/r/rust/comments/fkngza/apple_hiring_rust_engineers_for_storage_and/

- **Microsoft**'s IoT Edge has a Rust component.

- **Mullvad**s VPN app
  - https://news.ycombinator.com/item?id=22410369

- **1password**
  - https://news.ycombinator.com/item?id=22410587

- **Sentry** metrics monitor has components written in Rust

- **Discord** uses rust
  - https://blog.discordapp.com/why-discord-is-switching-from-go-to-rust-a190bbca2b1f

- **Figma**'s (popular design tool) backend is in Rust

- **Linkerd** service mesh's sidecar component is written in Rust

- **Visual Studio Code** ships with ripgrep

- **System76**
  - https://www.reddit.com/r/rust/comments/eezdg6/those_who_use_rust_in_production_what_are_you/

- Rust is used by at least **33 blockchain companies**

- There are multiple companies building **Rust-in-secure-enclaves** products,
  including Baidu. Not huge yet, but if enclaves catch on, Rust will be in a lot
  of them.

- Rust **command-line programs** are increasingly popular, and Debian stable already
  ships with a number of them. ripgrep is particularly notable, but people
  outside of the Rust community are also using fd-find, exa, and hexyl.

- 4% of **Debian** packages are written in Rust.
  - (https://bioreports.net/debian-riscv64-port-status/,
     https://www.reddit.com/r/rust/comments/cap9ul/debian_10_released_contains_ripgrep_fdfind_exa/).
  - https://www.debian.org/releases/buster/amd64/release-notes/ch-whats-new.en.html
  - https://www.reddit.com/r/rust/comments/cap9ul/debian_10_released_contains_ripgrep_fdfind_exa/
  - https://bioreports.net/debian-riscv64-port-status/

- **Ticketmaster** uses Rust in their rewrite (what's the status?)


## Other lists

- https://www.reddit.com/r/programming/comments/cmcw7q/fixing_c_with_epochs/ew3mr4c?utm_source=share&utm_medium=web2x
  - my previous notes

- jturner's notes
  - https://www.jonathanturner.org/2018/07/snapshot-of-rust-popularity.html#rusts-commercial-users

- https://github.com/omarabid/rust-companies

- previous thread
  - https://news.ycombinator.com/item?id=22409838

- https://www.rust-lang.org/production

