# My Rad Team Debate Topic Generator

A magnificent repo top deftly pipe output in 'the unix way' and create inspiring and feisty topics for our team meetings.  YMMV if you are not a fun person.

## Requisites

At a minimum you need the unixial `fortune` command, which is almost certainly in your distribution.  For additional japery you'll need `cowsay` and `lolcat`

On a MacOS system, you can most easily get it all together via [Homebrew](https://brew.sh/)

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

_© 2022 All rights reserved, even the stupid ones.  By reading this you agree to waive all rights._
