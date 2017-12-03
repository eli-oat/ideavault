# IdeaVault

```
 ᕙ(⇀‸↼‶)ᕗ
  Idea Vault, forget fewer things.

       idea         Save an idea
       remember     List all ideas
       forget       Delete last idea

       --help       Show this message
       --version    Version number
```

## Install

Download and put `ideavault` and `helpers` someplace. I like to plop 'em in my home folder, and make them invisable with a leading "."

Make `ideavault` executable

```bash
chmod +x ideavault
```

Optionally create an alias to call the script from anywhere. Something along these lines, perhaps? 

```bash
alias iv="~/.ideavault"
alias ideavault="iv"
```

## Configure `DATABASE`

On line 10 of the script there is a variable, `DATABASE`. This should point to where you'd like your memories stored. Perhaps dropbox, or a git repo for cross-device syncing? 

At this point you should be good to go! 

## Extras

Want to use this script from your iOS device? Here's a [workflow](https://workflow.is/workflows/7a0c5a9ee33f4ee692220276691c057c) for that. 
