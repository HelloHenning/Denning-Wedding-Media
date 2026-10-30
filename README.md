# Denning Wedding Media

Static media for the Denise & Henning wedding invitation website.

The website source remains in the private repository `HelloHenning/Denning-Wedding`. This public repository is intended to publish only finished, already-public website images and compatible MP4 videos through GitHub Pages.

## Transfer status (2026-10-30)

Copied and Git SHA verified against the original private repository:
- `images/Camping Party.jpg`
- `images/Seawall Piano-poster.jpg`
- `images/Seawall Engagement-poster.jpg`

**Still required before switching the live site:**
- `images/Garden Party.png`
- `images/Email symbol.png`
- `videos/Seawall Piano-compatible.mp4`
- `videos/Seawall Engagement-compatible.mp4`

The connected GitHub file-reading interface doesn't supply the contents of these larger binary files. They must be copied with authenticated Git or uploaded through GitHub's web UI. Use the original finalized files, without reconversion.

Do not transfer original, unused MP4s. Keep all original media in the private source repository.

## Publishing

Use GitHub Settings > Pages > Deploy from a branch > `main` > `/(root)`. The public asset base URL will be `https://hellohenning.github.io/Denning-Wedding-Media/` after publication.

**Migration safety:** Do not point the live Vercel website at this repository or remove its existing media until all seven public asset URLs are accessible and have been tested. The live website is intentionally unchanged until then.
