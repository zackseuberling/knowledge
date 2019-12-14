# Commit Ettiqute

- [My commit message workflow](https://dev.to/shreyasminocha/how-i-do-my-git-commits-34d)
- [The seven rules of a great Git commit message](https://chris.beams.io/posts/git-commit/#seven-rules)

## Write better commits with a custom template

### Basic git commit template:

```
# If applied, this commit will…

# Explain why this change is being made

# Provide links to any relevant tickets, articles or other resources
```


# Custom log formatting

- [Advanced Git log](https://www.atlassian.com/git/tutorials/git-log)

Set up custom `git log` formatting with a template:

```bash
git log --branches --remotes --tags --graph --oneline --decorate
```

Example output:

```
* 126aa7f (HEAD -> PROTOTYPE-toggle-feelings) toggle effects between z-score and votes
*   8b194c7 (origin/develop, origin/HEAD, develop) Merge pull request #649 from Leafly-com/lt-550-change-buy-nearby-url
|\
| * fe43732 fix: remove period for calculated from x products
| * dcdaff0 fix: change buy nearby url to availability page
|/
*   5cc481d Merge pull request #648 from Leafly-com/zs-strain-info-above-header
|\
| * 94a3c02 (origin/zs-strain-info-above-header) fix: ensure strain info is above header
* |   61c878a Merge pull request #647 from Leafly-com/LT-298-fix-country-code
|\ \
| * | eada461 (origin/LT-298-fix-country-code) now correctly calling is canada for all strains flavor spelling
|/ /
| | * a1e033e (origin/lt-406-add-found-in-carousel-to-strain) Rename GenreCarousel to PlaylistCarousel
| | * c62fbdb Move playlist carousel back to genre carousel
| | * db914fd [LT-406] Add GenreCarousel to strains page
| | * ec029ca Refactor genrecarousel more
| | * b90479f Refactor out PlaylistCarousel from GenreCarousel
| | * 6b41e23 [LT-406] Refactor playlist url
| | * 4711e32 feat: [LT-406] Extract playlist component from genre playlists
| | | * 4ef4963 (origin/carousel-height-fix) improvement(straincard carousel): update card height with window resize
| | | * ad6d79f add comment about issue to track
| | | * 8375e3e fix(carousel): update height when browser resizes
| |_|/
|/| |
* | |   1f4bb1f Merge pull request #645 from Leafly-com/LT-298-flavour-spelling
```
