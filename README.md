# INSTALACE A POUŽITÍ BASH SCRIPTU

## INSTALACE

1. cd /usr/local/bin
2. sudo git clone https://github.com/dominikpatera/progtestc.git temp
3. sudo mv temp/progtestc .
4. sudo rm -r temp

## POUZITI
1. ve složce se skriptem v jazyce C vytvoř složku test
2. do složky vlož vzorová data z progtestu
3. v terminálu se přesuneme do složky s C skriptem
4. progtestc spustis pomocí "bash progtestc"
5. napises nazev skriptu napr "rgb.c"

Tutorial: https://www.dropbox.com/s/slvpswnpgyz1481/2020-10-05%2022-15-05.mkv?dl=0

# FORMÁT

Testovací data musí být v souborech txt s následujícími názvy

- XXXX_in.txt
- XXXX_out.txt

např. 0000_in.txt a 0000_out.txt nebo slovo_in.txt a slovo_out.txt
