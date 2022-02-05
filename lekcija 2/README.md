## CSS
- html -> koristi se za pravljenje "kostura" stranice
- css -> korisit se za uljepsavanje html-a

- css se moze pisati na 3 nacina:
  - Unutar taga -> <p style=""></p>
  - U html fajlu ali u posebnim tagovima (prije body taga) -> <style></style>
  - u odvojenom fajlu

- u koliko zelimo koristiti odvojeni fajl za css, moramo html fajlu reci gdje je nas css fajl
- to radimo tako sto u <head></head> zalijepimo slj:
  <link rel="stylesheet" href="imeCssFajla.css">
- takoder css fajl mora imati .css ekstenziju

## CLASS and ID
- koristimo ih da bi rekli css-u koji tag zelimo urediti
- id -> "licno ime" taga, jedinstven, samo jedan u fajlu
- id u css referenciamo sa #imeID-a{}

- class -> "prezime taga", dijeli ga vise tagova, svi tagovi koji imaju istu klasu isto ce biti uredeni
- class u css referenciramo sa .imeClass-e{}


## DIV
- <div></div> -> kutija/kontejner
- koristi se za grupisanje drugih tagova
