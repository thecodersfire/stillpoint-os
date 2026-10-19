# Built-in features for stillpoint-os

Purpose: mindfulness and reflection

1. **organize a personal routine** — run stillpoint-os-workspace. It creates ~/Documents/stillpoint-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run stillpoint-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/stillpoint-os-session-plans/.
3. **check routine readiness** — run stillpoint-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/stillpoint-os-workspace features/stillpoint-os-plan features/stillpoint-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for mindfulness and reflection:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Foliate** — com.github.johnfactotum.Foliate
3. **KeePassXC** — org.keepassxc.KeePassXC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
