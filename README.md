<div align="center">

# niri-mini-dots

</div>

<div align="center">

[![niri](https://img.shields.io/badge/niri-6750A4?style=flat-square&logo=wayland&logoColor=white)](https://github.com/YaLTeR/niri)

</div>

## Это самый простой, максимально минималистичный конфиг для Niri
в нем я ориентировался только на удобство пользователю и легкость в установке

## Что внутри
 - `niri/` - конфиг самого Niri
 - `waybar/` - панелька сверху
 - `alacritty/` - терминал
 - `fish/` - крутой шелл

### Как установить?
 - клонируем репо
```bash
git clone https://github.com/6lGRUSHAl6/niri-mini-dots.git
```
 - копируем конфиг niri
```bash
cp -r niri-mini-dots/niri ~/.config/
```
 - копируем конфиг вайбера
```bash
cp -r niri-mini-dots/waybar ~/.config/
```
 - копируем конфиг алакрити (скил инвокера из доты)
```bash
cp -r niri-mini-dots/alacritty ~/.config/
```
 - ставим конфиг fish
```bash
cp -r niri-mini-dots/fish ~/.config/
```
 - закачиваем пакеты
```bash
sudo pacman -S --needed - < pkglist.txt
```
 - меняем шелл
```bash
chsh -s $(which fish)
```
