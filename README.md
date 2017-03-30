# Nautilus scripts

## Scripts list
* 1253utf-8
* minScript
* OpenAsRoot
* relM3U
* TerminalHere
* TerminatorHere
* vtt2srt

## Help

### What's their usefulness?

### How do I install these scripts?
Copy the scripts in the <code>~/.local/share/nautilus/scripts</code> directory or
issue the following bash commands in a terminal.

```bash
cd "${HOME}"
mkdir -pv "${HOME}"/gitDirs
cd "${HOME}"/gitDirs
git clone https://github.com/drxspace/nautilus-scripts.git

cp -f "${HOME}"/gitDirs/nautilus-scripts/1253utf-8 "${HOME}"/.local/share/nautilus/scripts/1253utf-8
cp -f "${HOME}"/gitDirs/nautilus-scripts/minScript "${HOME}"/.local/share/nautilus/scripts/minScript
cp -f "${HOME}"/gitDirs/nautilus-scripts/OpenAsRoot "${HOME}"/.local/share/nautilus/scripts/OpenAsRoot
cp -f "${HOME}"/gitDirs/nautilus-scripts/relM3U "${HOME}"/.local/share/nautilus/scripts/relM3U
cp -f "${HOME}"/gitDirs/nautilus-scripts/TerminalHere "${HOME}"/.local/share/nautilus/scripts/TerminalHere
cp -f "${HOME}"/gitDirs/nautilus-scripts/TerminatorHere "${HOME}"/.local/share/nautilus/scripts/TerminatorHere
cp -f "${HOME}"/gitDirs/nautilus-scripts/vtt2srt "${HOME}"/.local/share/nautilus/scripts/vtt2srt
chmod 775 "${HOME}"/.local/share/nautilus/scripts/*

rm -rf "${HOME}"/gitDirs

```
