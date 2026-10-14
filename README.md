# git-config

Personal git configuration and global ignore list.

## Files

| Source | Installed to |
| --- | --- |
| `gitconfig` | `~/.gitconfig` |
| `gitconfig.local.example` | `~/.gitconfig.local.example` (copy to `~/.gitconfig.local` and set your identity) |
| `config/git/ignore` | `~/.config/git/ignore` |

`~/.gitconfig` includes `~/.gitconfig.local` at the end, so your real name and email go there and stay out of this repo.
The `manifest` file lists the mapping and is read by the [dotfiles](https://github.com/NBAFrigge/dotfiles) bootstrap.
