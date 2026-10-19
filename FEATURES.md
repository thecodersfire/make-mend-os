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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
4. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
5. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
8. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
9. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
10. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
13. **GNOME Maps** (org.gnome.Maps) — look up places and plan routes.
14. **GNOME Weather** (org.gnome.Weather) — check local weather conditions.
15. **GNOME Calendar** (org.gnome.Calendar) — schedule sessions, deadlines, and events.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
2. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
3. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
4. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
5. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
6. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
7. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
8. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
9. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
10. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
11. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
12. **Ark** (org.kde.ark) — open and create common project archive files.
13. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
14. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
15. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for craft project planning. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Kid3** (org.kde.kid3) — Edit audio tags and album metadata in batches.
8. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
9. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
10. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
11. **KolourPaint** (org.kde.kolourpaint) — Make quick annotations and simple raster image edits.
12. **Kamoso** (org.kde.kamoso) — Capture webcam photos and short videos.
13. **KWave** (org.kde.kwave) — Record and edit audio waveforms.
14. **Elisa** (org.kde.elisa) — Organize and play a local music library.
15. **EasyEffects** (com.github.wwmm.easyeffects) — Adjust audio input and output with equalizers and effects.
