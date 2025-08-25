# Anne Pro 2 QMK Keymap
## Guide 
go to qmk_firmware and edit the keymap.c
```bash
cd qmk_firmware/keyboards/annepro2/boards/keymaps/
```
```bash
cd asdf
```
```bash
nvim keymap.c
```
go back to main dir qmk_firmware
```bash
cd && cd qmk_firmware
```
compile the qmk_firmware and move to annepro dir with the annepro2-tools
```bash
make annepro2/c18
cp annepro_c18_asdf.bin ~/annepro
```
boot to annepro2 
```bash
sudo ./annepro2_tools ./annepro2_c18_asdf.bin
```
### Features
- (Home Row Keys)[https://precondition.github.io/home-row-mods#tldr-table]
- Toggle between FN1 and FN2 through Capslock key
### Requirements
- Linux, Neovim
- QMK, AnnePro2, AnnePro2 Tools
