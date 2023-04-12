# My Rad Team Debate Topic Generator

A magnificent repo to create inspiring & feisty topics for our team meetings.  Via unix pipes in the shell! YMMV if you are not a fun person.

## Requisites

At a minimum you need the unixial `fortune` command, which is almost certainly in your distribution.  For additional japery you'll need `cowsay` and `lolcat`

On MacOS, you can easily get it all together via [Homebrew](https://brew.sh/)

```
# install Homebrew from <https://brew.sh/>
brew install fortune
brew install cowsay
brew install lolcat
```

## Prepare fortune file

See `howto` on how to prepare a fortune file and where to put it

An example fortune file is provided as `fortunes-templ`

## Usage

```
fortune webteam | cowthink -W 30 -f sheep | lolcat -p 1 -a -d 1 -s 36
```

Or place the above incantation into a shell script, a la `beginulate`

_Fin_

_© 2023 All rights reserved, even the stupid ones.  By reading this you agree to waive all rights._
