# SuperSimpleResume

This is super simple pandoc based resume generator:

* CSS for page formatting (and little bit of pandoc cli arguments as workarounds)
* Pandoc for pdf creation
* rake as build system

# Build dependencies

* rake (ruby based build system)
* pandoc

# How to build resume?

```
rake pdf
```

# How to make your own resume?

Just edit `resume.md` file

# How to cusomize layout?

* Edit `style.css`
* Edit `margin_size` variable in `rakefile`
