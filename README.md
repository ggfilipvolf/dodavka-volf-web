# dodavkavolf.cz

Web půjčovny Dodávka Volf (Iveco Daily, Brno). Statický web na GitHub Pages, doména u Forpsi.

- `index.html` – celý web (styly a skript uvnitř)
- `img/` – logo, fotky dodávky
- `CNAME` – doména pro GitHub Pages

Změna = commit do `main`, GitHub Pages web nasadí sám do pár minut.

Formulář: v `index.html` nahoře ve skriptu doplnit `FORM_ENDPOINT` a `FORM_ACCESS_KEY` (formulářová služba), jinak se poptávky neodesílají.
