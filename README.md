# Ibis Homebrew tap

Install the `ibis` command, which searches your reference library and cites from the
terminal or from an AI agent:

```sh
brew install ibiscite/tap/ibis
```

It runs on macOS (Apple silicon and Intel) and on Linux (x86-64). Shell completions for
bash, zsh and fish come with it. See the
[command line guide](https://github.com/ibiscite/ibis/blob/main/docs/cli.md) for what it
does, and [Ibis](https://github.com/ibiscite/ibis) for the desktop app.

The formula installs the archives published with each
[Ibis release](https://github.com/ibiscite/ibis/releases), checked against that
release's `SHA256SUMS` files. A daily workflow moves it to the newest stable release once
the new version installs and passes its test. To change the formula, edit
`.github/scripts/update-formula.sh` and run it; `Formula/ibis.rb` is generated.

Ibis is free software under the GNU Affero General Public License 3.0 or later.
