MARQÈ — prototyp strony (v4, scroll-scrub hero)
===============================================

Pliki:
- index.html — strona główna (PL/EN)
- polityka-prywatnosci.html — RODO (SZKIC — do weryfikacji przez prawnika)

Jak oglądać: rozpakuj CAŁY folder i otwórz index.html (usuń starą wersję przed rozpakowaniem nowej).

HERO — SCROLL-SCRUB (silnik z Twojego szablonu)
-----------------------------------------------
- Wideo przewija się scrollem (0–60% ścieżki), tekst hero znika do 30%,
  overlay "Marka, content, kampanie — jeden zespół." widoczny 30–62%,
  biała sekcja "Nie każdy jest naszym klientem." nasuwa się 55–100%.
- Desktop: momentum wheel + obsługa klawiatury i kotwic menu.
- Mobile: natywny scroll. Reduced motion: wideo gra w pętli, bez skrubu.

WIDEO (Slot 01): w index.html znajdź id="bg-video" i podmień src na swój showreel.
Zalecane: MP4 H.264, 1920×1080, 6–10 s, bez dźwięku, do ~12 MB.
Teraz stoi tymczasowe demo z szablonu (Cloudinary) — wymaga internetu.

Sloty 02–04 (zdjęcia projektów 4:5, 800×1000): dodaj data-img="plik.jpg" do wiersza projektu.

FORMULARZ: prototyp otwiera program pocztowy (mailto). Na produkcji podłącz wysyłkę.
COOKIES: baner bez zapisu wyboru; na produkcji zapis zgody + Consent Mode v2.
