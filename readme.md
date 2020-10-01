# Verkefni 3

## Lýsing

Skrifa skal HTML og CSS fyrir _Bókabúðina_.

Gefinn er grunnur að HTML, `index.html` og CSS, `styles.css`, leyfilegt er að breyta að öllu leiti.

Útlit þarf að passa við fyrirmyndir sem gefnar eru fyrir `1000px` og `400px`.

[Sjá fyrirmynd og virkni](fyrirmynd/).

## Útlit

### Letur og leturstærðir

Grunnstærð leturs skal vera `16px`, aðrar stærðar eru:

* `14px`
* `24px`

Leturgerðir eru:

* Montaga fyrir fyrirsagnir, annars Georgia eða serif letur
* Open Sans fyrir meginmál, annars Helvetica, Arial eða sans serif letur

Öll bil eru hálf, heilt eða tvöfalt margfeldi af grunn leturstærð.

Aðeins skal nota `em` og `rem` einingar fyrir stærðir fyrir utan:

* Skilgreiningu á grunnstærð
* Þykkt á `border`
* Lágmarks- og hámarksstærðir
* Hæð á myndum

Passa skal uppá að löng orð brotni snyrtilega milli lína.

### Litir

Litir eru:

* `#000000`
* `#222222`
* `#999999`
* `#cccccc`
* `#eeeeee`

### Breiddir og hæðir

Haus skal fylla upp í vafraglugga, sjá fyrirmynd og myndband af virkni.

Hver viðburður skal taka um `33%` af breidd í stærri gluggum en vera að lágmarki `200px`. Bil skal vera `16px` á milli viðburða en ekki þarf að passa upp á að hver viðburður sé nákvæmlega `33%`.

Hver vara skal taka um `25%` af breidd í stærri gluggum en vera að lágmarki `160px`. Bil skal vera `16px` á milli vara en ekki þarf að passa upp á að hver vara sé nákvæmlega `33%`.

Síða skal miðjusett innan vafra, efni skal vera að hámarki `800px`.

### Myndir

Í haus skal myndin `img/background.jpg` vera og fylla út í allt pláss og vera föst þegar síða er skrolluð.

Fyrir hverja vöru er gefin mynd í HTML sem skal vera `200px` há og fylla út í pláss sitt.

### Takmarkanir

Útlit skal setja upp með `flexbox`, ekki skal nota `float`, `position` eða `grid`.

Eftirfarandi eigindi ættu að vera nóg til að leysa verkefnið:

* `background` eigindi
* `border` eigindi
* `box-sizing`
* `color`
* `content`
* `display: flex`, sýnilausn notar aðeins þessa yfirlýsingu
* Flexbox eigindi
* `font` eigindi
* `list-style`
* `margin` eigindi
* `object-fit`
* `padding` eigindi
* `text` eigindi
* `width` og `height` eigindi
* `word-break`

Leyfilegt er að nota `calc()` til að reikna stærðir.

Leyfilegt er að nota alla selectora, æskilegt er að nota class selectora sem mest.

CSS skal vera án villna **og viðvarana** þegar keyrt í gegnum https://jigsaw.w3.org/css-validator/

## Mat

* 20% – Snyrtilega uppsett og gilt CSS
* 30% – Flexbox notað fyrir útlit
* 50% – Útlit skv. fyrirmynd

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 21. september 2020.

## Skil

Skila skal í Canvas í seinasta lagi fyrir lok dags þriðjudaginn 29. september 2020.

Skilaboð skulu innihalda slóð á verkefni ásamt zip skjali með lausn sem heitir ``verkefni4-<notendanafn>.zip`, t.d. `verkefni4-osk.zip`.

## Einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

## Myndir

* [Stanislav Kondratiev](https://unsplash.com/@technobulka)
* [Francesca Tirico](https://unsplash.com/@fra99)
* [Toa Heftiba](https://unsplash.com/@heftiba)
* [Andrew Neel](https://unsplash.com/@andrewtneel)
* [Christine Keller](https://unsplash.com/@christinekeller)

> Útgáfa 0.1
