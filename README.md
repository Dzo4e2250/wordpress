# Brezčasna Eleganca – predstavitvena stran

Ta projekt vsebuje preprosto statično spletno stran, navdahnjeno s sodobno predstavitveno estetiko, podobno izgledu na https://brezcasna-eleganca-2v.lovable.app/. Stran je napisana v HTML in CSS ter je pripravljena za lokalno predogledovanje.

## Struktura

- `index.html` – glavni dokument s predstavitvenimi sekcijami in povezavami na podstrani.
- `about.html`, `kolekcija.html`, `storitve.html`, `mnenja.html`, `kontakt.html` – podstrani z dodatnimi informacijami.
- `styles/main.css` – slogovna predloga z zasnovo za temen, eleganten vizualni slog.

## Predogled

Za hiter predogled strani lahko uporabite preprost HTTP strežnik, npr. z vgrajenim modulom v Pythonu:

```bash
python3 -m http.server 8000
```

Nato v brskalniku odprite `http://localhost:8000/index.html` in uporabite navigacijo za premikanje med podstranmi.
