# Built-in features for make-mend-os

Purpose: craft project planning

1. **organize work and records** — run make-mend-os-workspace. It creates ~/Documents/make-mend-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run make-mend-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/make-mend-os-session-plans/.
3. **check records and task readiness** — run make-mend-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/make-mend-os-workspace features/make-mend-os-plan features/make-mend-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for craft project planning:

1. **GIMP** — org.gimp.GIMP
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for craft project planning:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
3. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
4. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
5. **darktable** — develop RAW photos (org.darktable.Darktable)
6. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
7. **VLC** — review media files (org.videolan.VLC)
8. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
