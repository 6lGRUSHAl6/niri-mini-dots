# niri-mini-dots

## Это самый простой, максимально минималистичный конфиг для Niri [Niri](https://github.com/YaLTeR/niri)
в нем я ориентировался только на удобство пользователю и легкость в установке

## Что внутри
 - `niri/` - конфиг самого Niri
 - `waybar/` - панелька сверху
 - `alacritty/` - терминал

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
 - закачиваем пакеты
```bash
sudo pacman -S --needed - < pkglist.txt
```
