# GitHub profile and Zone01 migration plan

## Public profile repository

Create a public GitHub repository named exactly `Pkalliagkas1989` under the `Pkalliagkas1989` account, then place `README.md` at its root. GitHub will render it as the profile README.

Recommended profile bio:

> Junior software developer | Go, JavaScript and Rust | DevOps specialisation | Athens

## Safe first-wave Gitea mirrors

These local repositories use a Zone01 remote owned by `pkalliag` and are the best initial mirror candidates:

1. `RT` — flagship Rust project.
2. `road_intersection` — collaborative Rust simulation.
3. `chaikin` — collaborative graphics/algorithm project.
4. `filler` — individual project.
5. `piscine-rust` — learning archive; publish only if a curated archive supports the profile story.

Before publishing each repository:

- Confirm the curriculum and teammates permit a public mirror.
- Remove generated binaries, local files, secrets, datasets, and temporary audit material.
- Add a README that identifies the original Zone01 project and all contributors.
- Preserve existing commit history; do not squash or re-author teammates' work.
- Create a standalone GitHub repository, not a fork, if contribution-graph visibility is desired.
- Push the existing default branch and tags, then set the correct default branch on GitHub.

## Repositories that must not be mirrored without separate permission

- `gaidly` — confidential/NDA work.
- `drawing`, `localhost`, `backup_manager`, and `wget` — their Zone01 origins are owned by teammates.
- `public` — upstream 01-edu curriculum repository.
- Any client, employer, or organisation repository whose publication rights are unclear.

Link to original team repositories from the profile README instead.

## Commit attribution issues

- Most eligible commits use `p.kalliagkas@gmail.com`. Add and verify this exact address in the GitHub account.
- Some old local commits use `pkalliag@Panagiotiss-MacBook-Pro.local`; GitHub cannot associate a local-machine address.
- Social Network commits use `pkalliag@example.com`; GitHub treats generic addresses as unclaimable.
- Do not rewrite shared history only to change author emails. Use repository links, contributor documentation, and future commits with a verified email.

Recommended future Git configuration:

```bash
git config --global user.name "Panagiotis Kalliagkas"
git config --global user.email "p.kalliagkas@gmail.com"
```

## Recommended six profile pins

1. Forum Platform / `Notifications`
2. `RT` after its GitHub mirror is published
3. `bomberman-dom`
4. `gymboard_v1`
5. Social Network original team repository, if GitHub allows it based on recent contribution activity
6. `road_intersection` or `chaikin` after publication

## Final GitHub settings

- Set full name, bio, Athens location, LinkedIn URL, and profile photo.
- Enable the activity overview.
- Optionally enable anonymised private-contribution counts.
- Add repository descriptions and topic tags to every pinned project.
- Pin no more than six projects and keep the selection aligned with Go, JavaScript, Rust, and DevOps.

