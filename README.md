# homebrew-tap
My custom homebrew tap and formulas.

- - -
## Formulas:
### ffmpeg

This formula is almost the same as  `homebrew-ffmpeg/ffmpeg/ffmpeg` , except:

1) it uses the full featured webp tools (`skyzyx/webp/webp-full`) , instead of the crippled homebrew default. (which strips your metadata, for example).
2) the option `—enable-libflite` was removed because there is no such homebrew package and it generates errors.

#### Installation: 

If you installed any other ffmpeg formula, uninstall it:

```
brew uninstall ffmpeg
```

then install this one:

```
brew tap exekutive/tap
brew install exekutive/tap/ffmpeg
```


Extra options are documented here: 
https://github.com/homebrew-ffmpeg/homebrew-ffmpeg


- - -

Homebrew package manager for MacOS: https://brew.sh/
