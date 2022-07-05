# Nord rofi theme
<p align="center"><a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://github.com/davatorium/rofi">Rofi</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/undiabler/nord-rofi-theme/master/image1.png"/><img src="https://raw.githubusercontent.com/undiabler/nord-rofi-theme/master/image2.png"/><blockquote>Font: <a href="https://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released">Envy Code R</a> 10px.</blockquote></p>

## Getting started
### Installation

1. Copy <a href="nord.rasi">nord.rasi</a> file to `~/.config/rofi/nord.rasi`
2. Add the following lines to your rofi config (`~/.config/rofi/config.rasi`):
```
configuration {
    font: "Envy Code R 10";
    width: 30;
    line-margin: 10;
    lines: 6;
    columns: 2;

    display-ssh:    "";
    display-run:    "";
    display-drun:   "";
    display-window: "";
    display-combi:  "";
    show-icons:     true;
}


@theme "~/.config/rofi/nord.rasi"
```
