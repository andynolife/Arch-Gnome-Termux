# Arch-Gnome-Termux
Installing GNOME Desktop Environment on Arch Linux PRoot-Distro

# installation

Updating and Upgrading Termux
> pkg update ; pkg upgrade

<details></br>
<summary><b><code>Install Arch Linux</code></b></summary>

* Arch Linux ARM64
```
pkg in proot-distro ; pd install archlinux ; pd login archlinux
```
___

Basic Pacman Commands
> pacman -Sy : Update list package.</br>
> pacman -Syu : Upgrade package.</br>
> pacman -S (pkg) : Install package.</br>
> pacman -R (pkg) : Delete package.</br>
> pacman -h : Help all commands.
---

## Desktop Environment

in arch run this command first:
> pacman -Syu

<details></br>
<summary><b><code>Preview</code></b></summary>
<p align="center"><img src="https://github.com/NOLEPERS2/Arch-Gnome-Termux/blob/e932738370d654208ac371d92e8f9f6a6fea4685/Screenshot_20240708-110912.png"</p>

```
pacman -S gnome-shell gnome-terminal gnome-shell-extensions gnome-tweaks wget
```
</details>

---

## Starting

* Termux-X11

Run this command on termux for staring the Arch Linux GNOME :
```
wget https://raw.githubusercontent.com/NOLEPERS2/Arch-Gnome-Termux/main/gnome_arch.sh ; chmod +x gnome_arch.sh ; ./gnome_arch.sh
```
