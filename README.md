# Darxygen

Theme implements dark colors implementation for doxygen documentation generator.
Selected colors are inspiration from Sublime Text syntax highligher for C language.

I did however change the blue from the original colors to calmer ones, because the original colors were a bit worse than the default theme.


# How to use it

Usage is very simple. You just need to modify your doxygen input file

```sh
# Add files to extra stylesheet

HTML_EXTRA_STYLESHEET  = "custom.css" \
                         "custom_dark_theme.css"
```

If you wish to use custom made HTML header and footer, enable this feature with

```sh
# Custom header
HTML_HEADER            = "html_header.html"

# Custom footer
HTML_FOOTER            = "html_footer.html"
```
