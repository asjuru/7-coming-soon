# Projektas 7 - Coming soon

md - [Github markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)



# Hot-keys:
>- div+a, div>a, div*5, .div - pagamina didesne struktura
>- Fn + home/end - nusoka i eilutes pradia / gala
>- Fn + shift + home/end - pazymi iki eilutes pradzios / galo
>- alt + rodekle (virsu, apacia) - perkelti eilutę
>- shift + alt + rodykle (virsu, apacia) - kopijuoja pazymetas - >- eilutes (net ir nepilnai pazymetas)
>- ctrl + d - multi redagavimas (kiek matosi ekrane)
>- ctrl + alt + rodykle (virsu, apacia) - multi redagavimas
>- ctrl + / - pakomentuoja eilutę(-s)
>- ctrl + rodykle (virsu, apacia) - judina slider'i nekeiciant eilutes
>- ctrl + L - pažymi visą esamą eilutę
>- alt + z - pasiziureti netelpancia eilute


# STYLE:
> style="pavadinimas: savybe; pavadinimas: savybe; pavadinimas: savybe;"

> style="color: red; font-size: 20px; font-weight: bold;"

- **color: red;**  -                  teksto spalva
- **background-color: red;** -         elemento fono spalva
- **background: red;** -                elemento fono spalva
- **font-family: Arial;** 
- **font-family: monospace;** -         visu raidziu plociai vienodi
- **font-size: 20px;**
- **line-hight: 20 px**             
auto: line hight > - - font size
- **font-weight: bold;**
- **text-style: italic;**

-->

- **Text decoration: none**    -          default pabraukimus ir kt nuima
- **text-transform: uppercase;**

-->

- **margin: 100px;** -                  atstumas tarp elementu - visomis kryptimis
- **margin-top: 100px;** 
- **margin-right: 100px;** 
- **margin-bottom: 100px;**
- **margin-left: 100px;**
- **margin: 0** -                       nebelieka tarpu tarp elementu

-->
### Elementu issiputimas: 
- **padding: 100px;** -                elementu issiputimas (nuo elemento krastu iki jo turinio) - visomis kryptimis
- **padding-top: 100px;**
- **padding-right: 100px;**
- **padding-bottom: 100px;**
- **padding-left: 100px;**

-->

### Display - elemento atvaizdavimo budas
- **display: block;** -             is virsaus i apacia (dauguma)
- **display: inline;** -            eina is vienos eiles i kita (a, span)
- **display: inline-block;** -      stengiasi buti vienoje eileje su kitais, bet jei netelpa - VISAS nusoka i nauja eile
- **display: flex;** -             telpa :D

-->
- **justify-content: space-around;** - 
- **justify-content: space-evenly;** - 
- **justify-content: space-between;** - 

-->

- **box-sizing: border-box;** - apibrezia, kad fiksuotas box dydis, turinys su tekstu, border ir padding turi tilpti jame

```
\* {box-sizing: border-box;
    padding: 0;
    margin: 0;
    }

NOTE:
* - savybes priskiriamos visiems elementams
padding ir margin po 0; kad narsykle pati nepriskirtu automatiskai.
```

-->

- **float:left** - (display nebeveikia naudojant float)
- **float:right**

-->

- **object-fit: contain**
- **object-position: top left** -     pirma x, po to y asis

-->

- **filter: invert(0);** -            juodas pav virsta baltu

-->

- **.link: nth-child(3) {}** -   CSS 3 elementui bus taikomas stilius
- **.link: nth-child(3n) {}**   kas treciam
- **.link: nth-of-type (2)** -   ziuri "lytis": a, span, div

-->

### SPALVOS PANAUDOJIMO VARIACIJOS:
- background-color: rgb(234, 235, 237);
- background-color: #EAEBED;
- background-color: hsl(220, 1%, 92%);

-->
```CSS
.btn {
    border-radius: 20px;         uzapvalina
    border: solid 1px #662C8C;}   remas, remo storis ir spalva
.btn:hover{
    background-color: red;}      atsiranda TIK uzvedus kursoriu
```
-->

```
<a class="link" href="#" target="_blank">
<i class="fa fa-linkedin" aria-hidden="true"></i> </a>
    - target="_blank" ir "blank" skirtumai:
    - (1) atidaro visad naujam lange; 
    - (2) wikipedijos psl ties skirtingais skyriais.
```
 -->
# Paint.net tipsai:
 - Paveiksliuka dedam be fono. Paint.net su "magic wand" galima nuimti fona ir issisaugoti png formatu.  Ctrl + I (invert) - pazymi fona, o po to pazymi ne fona.


# Kita
```
 main.cs failo fragmentas
header {
    background-color: red;
}
main {
    background-color: blue; 
}
main > p {
    font-size: 10px; color: aliceblue;
}
footer {
    background-color: green;
}

> NOTE: padeda identifikuoti konkretų header
main > article > header {
    color: blue;
    {      
```
---> 
<!DOCTYPE html>  GALIMA STYLE DETI I HEAD, O NE PRIE HEADER, MAIN IR KT.
<html lang="en">
<head>
    <...>

    <style>
        header {
            background-color: red;
        }
        main {
            background-color: blue;
        }
        footer {
            background-color: green;
        }
    </style>
</head> 


>- git config --global user.name
>- git config --global user.email

