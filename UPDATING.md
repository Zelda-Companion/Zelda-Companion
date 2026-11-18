# Updating guide statuses

The profile is a regular GitHub README with local SVG artwork. There are no external badge services, remote fonts, tracking widgets, or scripts running on the profile.

To change a game’s status, edit its row in README.md and change the image filename and alt text:

| Status | Image | Alt text |
| --- | --- | --- |
| Red X | not-started.svg | Not working on it / Not started |
| Green check | completed.svg | Completed / Updates may happen |
| Yellow clock | working.svg | Currently working on it |

catalog.json keeps the release list in an easy-to-edit format. If you change a status, update the matching catalog entry too. The banner and current-quest card show the initial one-in-progress / zero-completed state; update their SVG text when the project totals or active game change. All artwork is editable text-based SVG.

To set this up on the Zelda-Companion user profile, use a public repository named exactly Zelda-Companion, owned by Zelda-Companion. Keep README.md and all SVG files at the repository root. Upload the contents of this package, rather than the containing folder or ZIP file. GitHub will display the README on the profile automatically.
