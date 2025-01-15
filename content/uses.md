+++
title = "/Uses"
+++

This page covers some of the hardware and software I use in my daily life and
work. It can be nice to see what other people are using, I've discovered plenty
of tools I use today from lists like this, so I figured I'd create one too.

## Hardware

* **Thinkpad X1 Carbon**: I like small and require a trackpoint so there is no competition.
* **Synology DS218+**: This has been pretty solid. A selling point for me was they
  use [btrfs](https://btrfs.readthedocs.io/en/latest/) and has hardware
  accelerated video transcoding. It is also where I run
  [pihole](https://pi-hole.net/).
* **Pixel 7a**: We use [Google Fi](https://fi.google.com) for our service and I
  again prefer smaller and don't need much power, so I always go with the "a"
  versions.

Things I use less because I tend to work from my laptop:

* **Logitech MX Ergo**: When I'm not using the trackpoint I use a trackball. 

## Software

* **[Fedora](https://fedoraproject.org/)**: I've been through a lot of distros in
  the past almost 2 decades. In the last few years I've moved to Fedora and been
  quite happy. The key things that motivated my move are Fedora's move to
  [btrfs](https://btrfs.readthedocs.io/en/latest/) and that it tends to have a
  more recent kernel than other non-rolling release distros.
* **[stow](https://www.gnu.org/software/stow/)**: Before getting into the rest since
  many of them rely on dotfiles I have to call out stow which I use to manage my
  dotfiles into a single repository.
* **zsh**: My config is a mixture of things now, but checkout [Oh My
  Zsh](https://ohmyz.sh/) and
  [powerlevel10k](https://github.com/romkatv/powerlevel10k). I guess I need to
  move on to something new from p10k, maybe [Starship](https://starship.rs/).
  * And I have to call out
    [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
    which gives [fish](https://fishshell.com/) like command completions. I
    didn't want to switch to fish but really liked this feature when I tried out
    fish so was happy to find a plugin for Zsh.
* **[Emacs](https://www.gnu.org/software/emacs/)**: A few modes I'll call out:
  * [lsp-mode](https://emacs-lsp.github.io/lsp-mode/): I had a lot of issues
    with lsp's that turned me off of them for a long time but recently have been
    having success with lsp-mode and the [Erlang Language Platform](https://whatsapp.github.io/erlang-language-platform/).
  * [org-mode](https://orgmode.org/): Not just how I keep notes and track what
    to do, it is also how we write [Adopting
    Erlang](https://adoptingerlang.org/). See the
    [repo](https://github.com/adoptingerlang/adoptingerlang/) for how that is
    done with [ox-hugo](https://ox-hugo.scripter.co/) to generate a
    [Hugo](https://gohugo.io/) site hosted on
    [Netlify](https://www.netlify.com/).
  * [magit](https://magit.vc/): The best interface for git.
  * [consult](https://github.com/minad/consult/),
    [vertico](https://github.com/minad/vertico),
    [orderless](https://github.com/oantolin/orderless): Command search and
    navigation stuff.
  * [project-tab-groups](https://github.com/fritzgrabo/project-tab-groups): I
    use the built in `project.el` for managing projects and this will make a tab
    per project.
* **[foot](https://codeberg.org/dnkl/foot)**: No complaints with foot but I have
  been trying out ghostty as well.
* **[fzf](https://github.com/junegunn/fzf)**: Fuzzy finding.
* **[rofi](https://github.com/lbonn/rofi)**: A Wayland supporting fork. This is how
  I run apps.
* **[Fastmail](https://fastmail.com)**: My email provider. I've been happy with the
  webapp and Android app for many years now.
* **[Bitwarden](https://bitwarden.com/)**: Storing my passwords and stuff.
* **[orgzly](https://www.orgzly.com/)**: Viewing org-mode files on my phone. 
* **[syncthing](https://syncthing.net/)**: Mainly syncing org-mode files to my
  phone.
* **[Tailscale](https://tailscale.com/)**: Tailscale has been great for easily
  connecting my devices and allowing syncthing to do its thing.
* **[Ansible](https://www.ansible.com/)**: I have a playbook for setting up my
  machine after getting tired of doing it manually every time I got a new work
  machine or reinstalled.
* **[Hyprland](https://hyprland.org/)**: My move to Wayland started with
  [Sway](https://swaywm.org/) but I really prefer dynamic tiling (I was on
  [XMonad](https://xmonad.org/) prior to Sway). Hyprland has been the most
  complete and stable of the available dynamic tiling options. But I'm openly
  looking for alternatives as I await XMonad Wayland :)... I plan to even give a
  DE's tiling a shot when COSMIC DE is more complete.
* **[grocy](https://grocy.info/)**: Recipe storage I've been trying to get myself
  using over org-mode.

Programming specific:

* **[beamup](https://tsloughter.github.io/beamup/)**: I created this tool in part as a
  way to learn Rust and because I preferred the, now unmaintained,
  [erln8](https://github.com/metadave/erln8) way of handling switching versions
  by routing all calls through a single binary.
* **[mise](https://mise.jdx.dev/)**: For everything else, aside from Rust which I
  just use rustup, I've been using mise recently.
* **[Zeal](https://zealdocs.org/)**: For viewing documentation. I just wish it could
  handle stuff like [Hex](https://hex.pm/) the way
  [Dash](https://kapeli.com/dash) does.
