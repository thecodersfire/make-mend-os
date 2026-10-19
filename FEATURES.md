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
