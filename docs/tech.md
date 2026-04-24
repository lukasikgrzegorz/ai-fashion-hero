# Tech stack — Mock

## Założenia

Mockup budujemy jako **pojedyncze pliki HTML** — każda strona to osobny plik.

Każdy plik zawiera:
- **React** ładowany przez CDN (esm.sh / unpkg)
- **Tailwind CSS** przez CDN
- **shadcn/ui komponenty** wklejone inline bezpośrednio w pliku
- Babel standalone do transpilacji JSX w przeglądarce

## Zalety tego podejścia
- Zero konfiguracji, zero bundlera
- Łatwy deploy — wystarczy otworzyć plik w przeglądarce
- Każda strona jest samowystarczalna
