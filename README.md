# Reckless Amphitheater

The downloads of Reckless Amphitheater: a chess GUI and UCI engine host for Windows, macOS and Linux. Play against an
engine, analyse a position with several at once, and run matches and tournaments between them with clocks, opening
books, pondering, adjudication and PGN. `amphitheater-cli` runs the same matches and tournaments from the command line.

Every installer carries five chess engines, ready to play the moment the host first opens: Pawnstar, Zenith,
Pawnstar-Go, Pawnstar-RS and Stoopid Chess. Each is a separate program under the GNU General Public License version 3,
carried alongside the host and spoken to over UCI; `THIRD-PARTY-NOTICES.txt` in every download gives each one's
version, copyright and the repository its corresponding source is in.

| | | |
|---|---|---|
| macOS 13.3 (Ventura) or later, Apple silicon or Intel | [reckless-amphitheater-macos.pkg](https://github.com/reckless-technology/amphitheater-releases/releases/latest/download/reckless-amphitheater-macos.pkg) | signed and notarized installer |
| Windows 10 or 11, 64-bit | [reckless-amphitheater-win64-setup.exe](https://github.com/reckless-technology/amphitheater-releases/releases/latest/download/reckless-amphitheater-win64-setup.exe) | signed installer |
| Linux x64: Ubuntu 24.04 or later, and Debian-family systems with glibc 2.38 or later (Debian 13, Mint 22) | [reckless-amphitheater-linux-amd64.deb](https://github.com/reckless-technology/amphitheater-releases/releases/latest/download/reckless-amphitheater-linux-amd64.deb) | `sudo apt install ./reckless-amphitheater-linux-amd64.deb` |
| Linux x64, any distribution with glibc 2.38 or later | [reckless-amphitheater-linux-x64.zip](https://github.com/reckless-technology/amphitheater-releases/releases/latest/download/reckless-amphitheater-linux-x64.zip) | the host and the tool to run from anywhere |

On macOS the host is universal, and the five bundled engines are built for Apple silicon.

Every release is listed under [Releases](https://github.com/reckless-technology/amphitheater-releases/releases) with
its notes and `SHA256SUMS`, each file's checksum. The download page is at
[recklesstechnology.com](https://recklesstechnology.com/plugins/download/#amphitheater), and what the host does and how
to use it at [recklesstechnology.com/chess/amphitheater](https://recklesstechnology.com/chess/amphitheater/).

This repository holds the downloads alone; the source is at
[reckless-technology/amphitheater-chess](https://github.com/reckless-technology/amphitheater-chess), public to read
under a proprietary licence. Reckless Amphitheater is free to use under the end-user licence the installers show and
every download carries. The five bundled engines are open source, each in its own repository. Questions, bugs and
ideas: hello@recklesstechnology.com.
