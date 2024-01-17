<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/karlstav/cava">Cava</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/cava/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/cava?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/cava/issues"><img src="https://img.shields.io/github/issues/catppuccin/cava?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/cava/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/cava?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/cava/main/assets/screenshot.webp" />
</p>

## Usage

1. Choose your flavour.
2. Copy the contents of _flavour_.cava into your Cava config file, as specified in [Cava's README](https://github.com/karlstav/cava#configuration). Typically, the config file is located at: `~/.config/cava/`. Ensure you replace the existing gradient settings.

> [!WARNING]
> Running any of the commands below may overwrite your existing cava configuration file.

  - Latte
      ```sh
      wget -O ~/.config/cava/config https://github.com/catppuccin/cava/raw/main/latte.cava
      ```

  - Frappé
      ```sh
      wget -O ~/.config/cava/config https://github.com/catppuccin/cava/raw/main/frappe.cava
      ```

  - Macchiato
      ```sh
      wget -O ~/.config/cava/config https://github.com/catppuccin/cava/raw/main/macchiato.cava
      ```

  - Mocha
      ```sh
      wget -O ~/.config/cava/config https://github.com/catppuccin/cava/raw/main/mocha.cava
      ```

3. Reload cava if it was already playing.

## 🙋 FAQ

- Q: **_"Error loading config. Only 'ncurses' output method supports HTML colors. "_**\
  A: As of version 0.7.0, ncurses is no longer the default output method. Adjust this in your config file.

  ```ini
  [output]
  method = ncurses
  ```

## 💝 Thanks to

-   [Pocco81](https://github.com/Pocco81)
-   [Sanjay Pavan](https://github.com/WitherCubes)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
