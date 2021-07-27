# programmer-dvorak-kmap

Programmer's Dvorak keymap file for linux.

## Usage

```bash
gzip -k dvorak-programmer.kmap
sudo loadkeys dvorak-programmer.kmap.gz
```

for example, on debian

```bash
sudo apt install console-data
cp dvorak-programmer.kmap.gz /usr/share/keymaps/i386/dvorak/
sudo loadkeys /usr/share/keymaps/i386/dvorak/dvorak-programmer.kmap.gz
```