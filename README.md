# *thoughts*

"put your thoughts on the internet"

Install from any reasonable location with `./install.sh`

I can't make any promises about that install script! (maybe one day)

Currently you have to have GNU sed on your system or it won't work, or maybe it'll just work wrong. Who knows! I definitely have plans to make plans to make it overall more portable

To use:
* install
* from anywhere, type `thought`
* enter your thought (currently you have to use vim sorry it's hardcoded maybe one day I'll fix that)
* save and exit
* your thought is added to the html document found at `~/.local/share/thoughts/thoughts.html`
* it's a standalone webpage -- put it in a web root anywhere and rename it `index.html` and you're done!

*A note about formatting in thoughts*
Probably almost all characters are valid and won't break the script. Newlines are converted into `<br>` in all cases, so intentionally spaced out paragraphs are respected, but
```
if
   you
          type
   this
```
```
then
you
get
this
```

<3