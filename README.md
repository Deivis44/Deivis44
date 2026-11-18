```text
==> DaaveyOS boot sequence initiated
==> Session ready · deivis@daaveyos

     ┌───────────┐
     │           │   Deivis: 
     │   ⚪  ⬛  ⚪   <says> Welcome to DaaveyOS.
     └───────────┘

deivis@daaveyos:~$ whoami
[session] Opening the local profile in a desktop window…
```

![User profile · David Santiago Muñoz Fernández. Systems Engineering student at Universidad Distrital. Currently webmaster at Colombia's Ministry of Agriculture and Rural Development. Based in Bogotá and open to internships and junior roles in Linux systems administration, IT infrastructure, and DevOps.](./assets/daaveyos-profile.svg)

```text
[session] Profile window closed. Back at the shell.

     ┌───────────┐
     │    ︵  ‿  ︵   Deivis: Let's check the work log.
     └───────────┘

deivis@daaveyos:~$ cat ~/work/madr.log
[role] Webmaster · Ministry of Agriculture and Rural Development
[ops]  Manage the TYPO3 portal, handle GLPI tickets, and document changes.
[seo]  Mapped 591 URLs to TYPO3 records and helped verify metadata updates.

deivis@daaveyos:~$ fastfetch

      ___           ___            deivis@daaveyos
     /__/\         /  /\
    |  |::\       /  /::|          OS  Arch-based Linux
    |  |:|:\     /  /:|:|          Host  DaaveyOS
  __|__|:|\:\   /  /:/|:|__            Lab  Raspberry Pi 5
 /__/::::| \:\ /__/:/ |:| /\       Uptime  Learning since 2020
 \  \:\~~\__\/ \__\/  |:|/:/       Shell  zsh
  \  \:\           |  |:/:/        DE  Hyprland (Wayland)
   \  \:\          |  |::/         Ops  Docker / Bash
    \  \:\         |  |:/             Net  Tailscale / VPS
     \__\/         |__|/             Desk  dotfiles / GNU Stow

deivis@daaveyos:~$ ls ~/projects
[file-manager] Opening the project directory…
```

[![GLUD Homelab — Raspberry Pi 5 with Docker, Tailscale, and a VPS tunnel](./assets/glud-homelab.svg)](./homelab-glud.md)
[![Arch Linux Dotfiles — Hyprland, Bash, and GNU Stow](./assets/arch-dotfiles.svg)](https://github.com/Deivis44/dotfiles)

[Chess](https://github.com/Deivis44/Chess) · University project in Java

```text
deivis@daaveyos:~$ contact --help
Open LinkedIn to get in touch, or browse the résumé archive.
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-085A9E?style=flat-square)](https://www.linkedin.com/in/david-munoz44/)

<details>
<summary><code>journalctl -b</code> · Full boot log</summary>

```text
==> Booting DaaveyOS [profile]
/dev/sda3: recovering journal
/dev/sda3: clean, 238075/59965440 files, 6019093/239842481 blocks

  --> Starting system initialization...

[    0.01s] :: Loading kernel modules
[    0.03s] :: Initializing hardware detection
[    0.05s] :: Starting udev daemon
[    0.07s] :: Mounting filesystems
[    0.09s] :: Loading network interfaces
[    0.12s] :: Starting system services

==> Login successful. Welcome back, Deivis!
```

</details>

<details>
<summary><code>resume --archive</code> · Archived résumés</summary>

```text
deivis@daaveyos:~$ resume --archive
[session] Opening the résumé archive…
```

Archived PDFs from February 2025.

[![Open CV Archive](Boton.png)](https://drive.google.com/drive/folders/1oYNx0hEfAhGNUxD47JWJN1M44ndzPiUd?usp=sharing)

</details>

```text
     ┌───────────┐
     │           │   Deivis: 
     │   ⚪  ‿  ⚪   <says> See you around. The shell is yours.
     └───────────┘

deivis@daaveyos:~$ █
```
