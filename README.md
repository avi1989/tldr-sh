# tldr
A POSIX shell client for [tldr-pages](https://github.com/tldr-pages/tldr).

# Installation
Installation of this script is really simple. All you need to do is to copy the (tldr script)[https://raw.githubusercontent.com/avi1989/tldr-sh/master/tldr] into a folder in your system PATH.

I have `/opt/bin` in my system path, so I can install it as follows

```sh
    curl -o /opt/bin/tldr https://raw.githubusercontent.com/avi1989/tldr-sh/master/tldr
    chmod +` /opt/bin/tldr
```

# Dependencies
TLDR attemptst to use [Glow](https://github.com/charmbracelet/glow) to render the output, if glow is not installed, it falls back to cat. I recommend installing glow for the best experience.