# Anaelle Cosmetic

Laser hair removal clinic in Jerusalem. `index.html` is the landing page.

## Instagram skills

The 13 `ig-*` skills in `.claude/skills/` are vendored from
github.com/Jakeschincariol/instagram-agent-skill (MIT).

Those skills read and write their data under `~/.claude/instagram/`. In this
project that data lives in the repo instead, at `.claude/instagram/`, so it
survives between cloud sessions:

- `.claude/instagram/voice.md` - voice profile (read before writing anything)
- `.claude/instagram/swipe.md` - written by `/ig-viral`
- `.claude/instagram/plan.md` - written by `/ig-plan`
- `.claude/instagram/log.md` - posting log

Whenever a skill mentions `~/.claude/instagram/<file>`, use
`.claude/instagram/<file>` in this repo, and commit changes to those files.

The Instagram account being worked on is **@efi_surgery** (EFI SURGERY:
facelift and thread lift trips to Shanghai and Seoul for Israelis), not
Anaelle Cosmetic. All Instagram output is in Hebrew, addressed in the plural
form, unless asked otherwise.
