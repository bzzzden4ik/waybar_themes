## Waybar configs

This repo represents my personal waybar themes that consist of self-written configs that I implemented and used. These solutions make me happy so that is why I'd like to share them.

### Configs

Here are configs:

* Minimalistic_light - Without numbers and digits [+]
* Minimalistic_heavy - With numbers and digits [-]
* GlassMorph - Glass Morph based panel [+]
* GlassMorph_splited - Glass Morph based splited panel [-]
* Material_splited - Material styled splited panel [-]

### Project Structure

Here is project structure:
```text
waybar/
├── [theme_0]/
│        ├── config.jsonc
│        └── style.css
├── [theme_2]/
├── [theme_3]/
├── [theme_4]/
└── README.md
```

### Necessary things

First of all you must install _waybar_ package.

For **Debian** based systems _(Debian, Ubuntu)_:

```bash
sudo apt update
sudo apt install waybar
```

For **Red Hat** based systems _(RHEL, Fedora)_:

```bash
sudo dnf upgrade
sudo dnf install waybar
```

For **Arch** based systems _(Arch Linux, Manjaro)_:

```bash
sudo pacman -Syu
sudo pacman -S waybar
```

Also here is one thing that helps to **display icons correctly**.
You **must** use JetBrainsNerdMono/0xProto or another Nerd included fonts.

### How to use

Choose exact **Waybar Theme** and copy it straight to .config/waybar:

```bash
cp [theme_name]/* /home/[username]/.config/waybar/
```

After that restart your waybar:

```bash
killall waybar & waybar &
```

### Troubleshooting