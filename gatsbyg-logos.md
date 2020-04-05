# Gatsby Graphics Logos

Original logo

![Gatsby Graphics](images/logos/gatsbyg-logo.png)

Designed by:

- [Jorge Araica](https://github.com/summerhill5)
- [Jorge on Upwork](https://www.upwork.com/freelancers/~01abf139414e3d1c0d)

## Matplotlib

### Colormaps

```
python3 python/logos.py images/logos
```

## ImageMagick

### GIF

```
convert -delay 250 images/colormaps/gatsbyg-logo/*.png logo.gif
```

### Appending horizontally

```
convert -resize 25% images/colormaps/gatsbyg-logo/*.png +append images/logo-sprite-h-25.png
```

### Appending vertically

```
convert -resize 25% images/colormaps/gatsbyg-logo/*.png -append images/logo-sprite-v-25.png
```

## Links

- [Matplotlib Colormaps](https://matplotlib.org/tutorials/colors/colormaps.html)
- [ImageMagick](https://imagemagick.org/index.php)
