# homebrew-tap
My homebrew tap for custom formulas.


### ffmpeg

Same as  `homebrew-ffmpeg/ffmpeg/ffmpeg` , with the exception that it uses the full featured webp tools (`skyzyx/webp/webp-full`) , instead of the crippled homebrew default. (which strips your metadata, for example).

###### Installation: 

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


