# Motivation
Overleaf has decided it would be super fun to massively reduce compile time, effectively making it useless. From now on I will use GitHub in combination with texlife from bash to document my knowledge acquisition.

# Prerequisites
```
sudo apt install texlive-full
sudo apt-get install texlive-xetex
```
# Compilation
```
NAME=`echo "$1" | cut -d'.' -f1`
xelatex  -file-line-error -halt-on-error $NAME.tex && xdg-open $NAME.pdf
```

# sources
[diacritics](https://nepalgo.de/script/diacritics/)
