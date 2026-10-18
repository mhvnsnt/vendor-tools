# Cascadeur 2026.2.3 (Linux)

Physics-based, AI-assisted keyframe animation software — used in the
Western Heart pipeline for character animation work.

- **Version:** 2026.2.3 (released 01 Oct 2026; listed on cascadeur.com/download)
- **Platform:** Linux — the store keeps the Linux build
  (Windows 493.52 MB and Mac 497.15 MB builds also ship on the same page)
- **Binary:** `cascadeur-linux.tgz` — 581,257,231 bytes (~554.33 MB),
  stored as a release asset on `vendor-tools-v1`
- **SHA256:** `c3409b9915bf654d74f119b25822147bc81e4d0748b6878c897c23abf608b102`
- **Source page:** https://cascadeur.com/download
- **Direct download (no account needed):** the download page has no direct
  href — the free build is retrievable via the site's own REST endpoint:
  `GET https://cascadeur.com/rest/download/build?platform=linux&buildId=112`
  (build 112 = 2026.2.3), which redirects to
  `https://cdn.cascadeur.com/storage/builds/2026.2.3/linux/cascadeur-linux.tgz`.
  Only the OLDER-version buttons on that page redirect to `/sign-in`.
- **License:** Cascadeur **Basic — the FREE tier**. The download API
  returns `{"type":"free","planType":"basic"}` for this build.
  The CASCADEUR END-USER LICENCE AGREEMENT (version 2025.1, presented
  before download) applies — see `licenses/licence.txt` inside the tarball
  before use.
- **Retrieved:** 2026-10-18
- **Contents:** self-contained `cascadeur-linux/` tree (~1.3 GB extracted,
  bundled Qt6 libs under `lib/`); launcher is `cascadeur-linux/cascadeur`
- **Install:** extract anywhere and run `./cascadeur`
