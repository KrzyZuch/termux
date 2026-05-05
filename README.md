# Termux Linux Setup (Modified)

Poprawiony skrypt oryginalnie z [orailnoor/DroidDesk](https://github.com/orailnoor/DroidDesk).

## Zmiany:
- **Fix:** Naprawione ścieżki `/root/` → `$HOME` (Termux HOME to `/data/data/com.termux/files/home`)
- **Fix:** Auto-instalacja proot distro gdy brakuje
- **Dodano:** VS Code (code-oss) z TUR repo + skrót na pulpicie

## Użycie w Termux:
```bash
curl -sL https://raw.githubusercontent.com/KrzyZuch/termux/main/termux-linux-setup.sh -o setup.sh
bash setup.sh
```

