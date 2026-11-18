# Updating guide statuses

The profile is a regular GitHub README with local PNG and SVG artwork. There are no external badge services, remote fonts, tracking widgets, or scripts running on the profile.

To change a game’s status, edit its row in README.md and change the image filename and alt text:

| Status | Image | Alt text |
| --- | --- | --- |
| Red X | not-started.svg | Not working on it / Not started |
| Green check | completed.svg | Completed / Updates may happen |
| Yellow clock | working.svg | Currently working on it |

catalog.json keeps the release list in an easy-to-edit format. If you change a status, update the matching catalog entry too. The banner and current-quest card show the initial one-in-progress / zero-completed state; update their SVG text when the project totals or active game change. The banner SVG embeds the published Nintendo Master Sword illustration. The README displays banner.png for reliable image rendering; re-export that PNG after changing the banner SVG. Layout, typography, and status icons remain editable vector graphics. Preserve the artwork credit in SOURCES.md.

Keep the register limited to official mainline originals, remakes, and remasters. Do not add separate entries for ports, spin-offs, compilations, or unofficial games.

Breath of the Wild and Tears of the Kingdom each have one guide entry covering the original release and Nintendo Switch 2 Edition. Keep their release years at 2017 and 2023, list all supported consoles in the platform column, and apply one status to each grouped entry. The banner counts guide entries rather than individual platform releases.

To set this up on the Zelda-Companion user profile, use a public repository named exactly Zelda-Companion, owned by Zelda-Companion. Keep README.md, banner.png, and all SVG files at the repository root. Upload the contents of this package, rather than the containing folder or ZIP file. GitHub will display the README on the profile automatically.
