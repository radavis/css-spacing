# CSS Spacing Helper Classes

The code in `spacing.scss` will create 3-character helper classes with the following format:

```no-highlight
.[margin, padding][all, top, right, bottom, left, horizontal, vertical][small(10px), medium(20px), large(40px), none(0px)]
.[m, p][a, t, r, b, l, h, v][s, m, l, n]

.mbl -> margin bottom large (40px)
.pts -> padding top small (10px)
.man -> margin all none (0px)
```

## Build

```
$ sass --watch spacing.scss
```

## Development

```html
<link rel="stylesheet" href="https://rawgit.com/radavis/css-spacing/master/spacing.css">
```

## Production

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/radavis/css-spacing/---git-sha---/spacing.css">
```

## Credits

* https://gist.github.com/syahrasi/5092653
* https://github.com/stubbornella/oocss
* https://rawgit.com/
