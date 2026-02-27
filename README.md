<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/TomSchimansky/CustomTkinter">CustomTkinter</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/customtkinter/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/customtkinter?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/customtkinter/issues"><img src="https://img.shields.io/github/issues/catppuccin/customtkinter?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/customtkinter/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/customtkinter?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

> [!NOTE]
> This port has both a dynamic and static version. The dynamic version has different flavors for the light mode while the static version uses the flavor for both the light and dark theme. The dynamic theme does have
> The theme files also modify non-color elements, such as corner radius, border width, and fonts. They are based on the built-in [blue theme](https://github.com/TomSchimansky/CustomTkinter/blob/master/customtkinter/assets/themes/blue.json). You can freely adjust the non-color elements as wanted.

1. Download the flavor of your choice from [themes](themes). The dynamic theme uses a path like so: `themes/dynamic/<dark flavor>/<light flavor>/catppuccin-<dark flavor>-<light flavor>-<accent>`.
2. In your Python file, put `customtkinter.set_default_color_theme("path/to/catppuccin-{dark flavor}-{light flavor}-{accent}.json")` (replace `path/to` with the actual path and replace `{dark flavor}` with the dark flavor you chose, `{light flavor}` with the light flavor you chose, and `{accent}` with the accent you chose).
3. Enjoy!

## 🙋 FAQ

- Q: **_"How do I change themes with dynamic mode?"_**\
  A: To use the light theme put this in your code: `ctk.set_appearance_mode("light")`. The options are **light**, **dark**, and **System**.

## 💝 Thanks to

- [Scarce Koi](https://github.com/scarcekoi)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
