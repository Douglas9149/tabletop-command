# Tabletop Command v8.1 — GitHub Pages and personal editing

This is an unofficial fan-made Warhammer 40,000 helper. All rules and points should be checked against current official references. Not affiliated with Games Workshop.

## What's improved

- **Aggressor Squad: Close-quarters Firestorm** now explicitly shows **+1 Strength within 9 inches**, covering melee and ranged attacks, with base and modified Strength examples. It is a unit ability costing **0 CP**, not the similarly named Firestorm Assault Force detachment bonus.
- The **Firestorm Assault Force** detachment bonus is separate: +1 Strength to eligible ranged attacks within **12 inches**, and Assault on eligible ranged weapons. Multiple valid bonuses can stack.
- Increased incomplete-summary checks. A vague statement about Strength, AP, damage or saves without the numeric change will be treated as requiring reference verification.
- **Personal ability explanations** can be edited directly from detailed unit pages without coding. They save locally with your other app data and export with your JSON backup. They do **not** change the canonical reference or automatically synchronize across your friends' browsers.
- The live tracker shows the edited local explanations.

## Publish to GitHub Pages (GitHub Free)

1. Go to https://github.com/new and create a PUBLIC repository named `tabletop-command` (or another name). You can optionally initialize it with a README.
2. Once the repository opens, click **Add file → Upload files** or the **uploading an existing file** link.
3. Extract the ZIP and upload `index.html` to the **root** of your repo (not nested in a folder). `README.md` and `.nojekyll` are optional.
4. Commit changes to `main`.
5. Repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
6. Open the published link displayed by GitHub. It is typically `https://YOUR-USERNAME.github.io/tabletop-command/`.

**Access/editing:** GitHub Pages is public on a free account. Anyone can browse the site. Users can edit their own locally stored armies and notes in the interface. Those edits are NOT shared with other browsers. Grant Jason GitHub collaborator **Write** permission if you want him to edit the website source, through repository Settings → Collaborators → Add people. Only grant source access to people you trust. Owen does not need GitHub or coding skills to use the site's army builder. Real shared accounts/sync would need a backend.

## Backups

Before migrating from v8, use Settings & backups → Export. Import on the GitHub Pages URL after publishing. Never upload exported JSON files or personal information to the public repository. Export again periodically, particularly after modifying ability explanations.

## Scope of accuracy

This update corrects the identified Aggressor ability and improves incomplete-summary warnings, but **does not certify every unit or ability in the wider catalogue as accurate**. A few dozen reference profiles are partially filled; hundreds of other catalogue entries remain index-only. Always check current faction packs and points before buying models, building competitive lists or applying rules.
