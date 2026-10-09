# Patches

`build.sh` applies `libgit2/*.patch` in order to the libgit2 release source.

| Patches | Upstream | Fixes |
|---|---|---|
| `0001`–`0004` | [libgit2#7339](https://github.com/libgit2/libgit2/pull/7339) | A negation in a nested `.gitignore` (`!.env`) now overrides a parent rule, matching Git. |

Remove a patch once its fix ships in the pinned libgit2 release, then bump `LIBGIT2_BUILD`.
