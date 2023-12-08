# Motivation
Overleaf has decided it wouuld be super fun to massively reduce compile time effectively making it useles. From now on I will use github in combination

# Prerequisites
```
sudo apt install texlive-full
sudo apt install texlive-full
```
# Compilation
```
NAME=`echo "$1" | cut -d'.' -f1`
xelatex  -file-line-error -halt-on-error $NAME.tex && xdg-open $NAME.pdf
```
