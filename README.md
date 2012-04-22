# [Solarized](http://ethanschoonover.com/solarized) theme for [Octopress](http://octopress.org/)

### Based on the [Solarized](http://ethanschoonover.com/solarized) website and the classic theme

# Install

```sh
git clone http://github.com/erikzaadi/solarized-octopress-theme .themes/solarized
rake install["solarized"]
```
_zsh users_: change the last line to
```zsh
rake install\['solarized'\]
```

# Customize

To toggle between light and dark mode, edit _sass/custom/_colors.scss_ and change **$sol** and **$solarized**:
```scss

$sol : light; // light or dark -  Recommended: set $solarized (code syntax highlighting theme) to the opposite of this
$solarized : dark;

```

# Screenshots

![Dark](https://github.com/erikzaadi/solarized-octopress-theme/raw/master/images/dark.png)

![Light](https://github.com/erikzaadi/solarized-octopress-theme/raw/master/images/light.png)
