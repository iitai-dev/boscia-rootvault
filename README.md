# Boscia Rootvault

Quartz-based Obsidian vault for `iitai-dev/boscia-rootvault`, published with GitHub Pages.

## Obsidian setup

1. Open Obsidian, choose "Open folder as vault", and select the `content/` folder inside this repo.
2. In Settings > Files and Links:
   - Set "New link format" to "Shortest path when possible".
   - Turn "Automatically update internal links" on.
   - Turn "Use [[Wikilinks]]" on.
   - Set "Default location for new notes" to "Vault folder (root)".
   - Create an `attachments/` folder and set it as the default attachment location.
3. In Settings > Core plugins, enable "Templates".
4. In Settings > Templates, set "Template folder location" to `templates`.
5. Install the community plugin "Obsidian Git".
   - Configure it with a GitHub PAT for authentication.
   - Optional: enable auto-push on an interval.

## Publishing

GitHub Pages should use "GitHub Actions" as the Pages source, not "Deploy from branch".

The site URL is:

https://iitai-dev.github.io/boscia-rootvault/
