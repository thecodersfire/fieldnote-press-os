# Built-in features for fieldnote-press-os

Purpose: journalism

1. **prepare a creative project** — run fieldnote-press-os-workspace. It creates ~/Documents/fieldnote-press-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run fieldnote-press-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/fieldnote-press-os-session-plans/.
3. **check project and export readiness** — run fieldnote-press-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/fieldnote-press-os-workspace features/fieldnote-press-os-plan features/fieldnote-press-os-check "$HOME/.local/bin/"
