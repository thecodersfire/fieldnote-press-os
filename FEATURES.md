# Built-in features for fieldnote-press-os

Purpose: journalism

1. **prepare a creative project** — run fieldnote-press-os-workspace. It creates ~/Documents/fieldnote-press-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run fieldnote-press-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/fieldnote-press-os-session-plans/.
3. **check project and export readiness** — run fieldnote-press-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/fieldnote-press-os-workspace features/fieldnote-press-os-plan features/fieldnote-press-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for journalism:

1. **Scribus** — org.scribus.Scribus
2. **Kdenlive** — org.kde.kdenlive
3. **Audacity** — org.audacityteam.Audacity

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for journalism:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
4. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
8. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
9. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
10. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
