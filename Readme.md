## Benennung
Ordner mit der Benennung ".config{Ordner}" sollten unter "/home/username/.config/{ordner}" abgelegt werden.
Ordner wie ".tmux.conf" gehören dagegen direkt in "/home/username/"

## Zusätzliche Konfig:
Damit neovim alle Einstellungen übernimmt sollte am besten ":checkhealth" ausgeführt werden.
Dort wird sich unter anderem definitiv die "live-grep"-Extension von Telescope melden, weil das CLI-Tool 
"ripgrep" installiert sein muss. Bei Debian-basierten Distros also einfach "sudo apt install ripgrep",
dann sollte alles funktionieren.
- Es muss für .tmux.conf vorerst "TPM" der Tmux Plugin Manager installiert werden.


## Abhängigkeiten:
### Nvim
 - Node (für Mason)
 - luarocks (keine Ahnung glaube für Treesitter)
 - ripgrep (für Telescope)

### .zshrc
- [Antidote](https://antidote.sh) installieren: ```git clone --depth=1 https://github.com/mattmc3/antidote.git ${ZDOTDIR:-$HOME}/.antidote``` 
