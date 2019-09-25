# Programmeerimise alused
Antud kursus annab ülevaate programmeerimise aluste baasteadmistest PHP keele baasil.
## Ajakava
### 20.09.2019
* Tarkvara installeerimine
    * [PhpStorm](https://www.jetbrains.com/phpstorm/)
    * [git](https://git-scm.com/)

* Tarkvara seadistamine
    * Litsensi vormistamine
    * PhpStorm põhiseadistus (line numers, soft wrap)
    * git.exe ühendus PhpStormiga
    * github.com repo loomine ning ühendamine PhpStormiga
### 25.09.2019
* git kasutamine käsurealt
Kui repo ei ole initaliseeritud, siis tuleb see ära teha

```
git init
```


Nüüd lisa muudatused faili jälgimissüsteemi
```
git add failinimi
```

Koosta kirjeldus antud muudatusele
```
git commit -m "Kirjelda"
```
Lükka lokaalsest repost kirjeldus kaugreposse ( näiteks github.com )
```
git push -uf origin master
```
 Siis origin on ühenduse nimi ja master peaharu
 
 ## PhpStorm võimalused
 * Phpstormi abil saab ilma terminalita muudatusi committida ja pushida/pullida.
    * PhpStormi programmis võtad lahti VCS toolbari juurest.
    * Ning sealt annab võimaluse committida, ning VCS -> Git alt saab ka pushida ning pullida
    
```
PhpStorm -> VCS -> Commit
```
Ning edasi lähed :
```
PhpStorm -> VCS -> Git -> Push
```
Ja kui infot tahad Githubist PhpStormi tuua, siis kasutad:
```
PhpStorm -> VCS -> Git -> Pull
```