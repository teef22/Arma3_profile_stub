### Setup guide

Put this repo here if on Linux:
```zsh
/home/user/.steam/root/steamapps/compatdata/107410/pfx/drive_c/users/steamuser/Documents/Arma 3 - Other Profiles
```
or here if on Windows:
```zsh
C:\Users\User\Documents\Arma 3 - Other Profiles
```

Rename next directories and files to create proper new profile after cloning the repo:
1. Change parent directory name to your new profile name.
2. Change `*` in `*.Arma3Profile` file to your new profile name.
3. Change `*` in `*.vars.Arma3Profile` file to your new profile name.

If you wish to use spaces or other characters in you profile name use [percent-encoding](https://developer.mozilla.org/en-US/docs/Glossary/Percent-encoding?_sm_nck=1) alongside regular latin letters.

### FOV tips
If you wish to change the view FOV above the allowed limits of in game settings try one of the [Arma 3 FOV calculators](https://duckduckgo.com/?q=arma+3+fov+calculator). Config values you are interested in are `fovTop` and `fovLeft`. Put them into your `*.Arma3Profile` file after calculations are done.
