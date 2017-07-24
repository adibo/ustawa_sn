# Ustawa o Sądzie Najwyższym
Zapis zmian w ustawie o Sądzie Najwyższym (2017 r.).
Sam projekt ustawy spowodował liczne protesty społeczne.

Po szybkim zatwierdzeniu ustawy o Sądzie Najwyższym pojawiły się pytania czy rzeczywiście ten sam tekst ustawy został zatwierdzony zarówno przez Sejm, jak i przez Senat (Senat przyjął uchwałę o przyjęciu ustawy przekazanej przez Sejm bez poprawek).

Niniejsze repozytorium jest zapisem obu wersji dokumentu, tak aby każdy mógł samemu stwierdzić jak wyglądały oba dokumenty.

Oba dokumenty zostały pobrane z oficjalnych źródeł - stron internetowych Sejmu i Senatu - i powinny wiernie odzwierciedlać to czym zajmowali się posłowie i senatorowie.
Proces obróbki
Z każdego z dokumentów (w formacie PDF) wyekstrahowałem sam text (copy-paste) i zachowałem do osobnych plików tekstowych. Następnie usunąłem z nich nr stron oraz odsyłacze (tj. np. dodatkowe informacje ze stopki stron - to po to by skupić się na samym tekście ustawy, nie na informacji pobocznych). Następnie wyjustowałem dokument senacki tak, by każda linia odpowiadała tej z dokumentu sejmowego (chodzi o to by linie się pokrywały - w idealnym przypadku oba dokumenty powinny mieć tylko te same linie, z tym samym tekstem każda.). Podczas procesu nie absolutnie dodawałem żadnego tekstu.
Dokument sejmowy następnie dodałem do repozytorium na github'ie (to znany informatykom serwis pomagający w pracy nad rozwijanym kodem źródłowym programów komputerowych - wybrałem go bo pomaga śledzić zmiany w kodzie). W kolejnym kroku skopiowałem tekst pliku sejmowego, podmieniając tym samym zawartość repozytorium (jeśli nic się nie zmieniło w tekście, zmiany nie będą widoczne). Nowy plik został "skomitowany", czyli zaktualizował zawartość repozytorium.

Wyniki
Rezultaty porównania obu wersji pliku z repozytorium można oglądać tu:
https://github.com/adibo/ustawa_sn/commit/08019f206dddcda3298b4a9b49a3988a3457b32d
Sami oceńcie czy dokumenty są takie same.

Analiza
Obie wersie się różnią. Część zmian rzeczywiście dotyczy drobnych poprawek (powiedziałbym edytorskich). Jednak część zmian to zupełnie inny tekst (zmienione lub dodane paragrafy). Załączam przykłady w postaci zrzutów ekranowych. Całość można ocenić na stronie jak powyżej w przeglądarce internetowej.

Źródła
Poniżej podaję źródła, z których pobrane zostały dokumenty do analizy (każdy dokument opatrzyłem sumą kontrolną (md5sum) gdyż dokument na stronie może zostać podmieniony).

Dokument sejmowy:
Został pobrany ze strony http://sejm.gov.pl/Sejm8.nsf/PrzebiegProc.xsp?nr=1727 i znajduje się na dole strony (koniec linii obrazującej przebieg prac legislacyjnych)
http://orka.sejm.gov.pl/opinie8.nsf/dok?OpenAgent&1727_u (1727_u.pdf, md5sum: c5ca9f4474026d5357a2c9ec50d3c856)

Dokument senacki:
Został pobrany ze strony http://www.senat.gov.pl/prace/senat/posiedzenia/tematy,490,1.html. Link do dokumentu: http://www.senat.gov.pl/download/gfx/senat/pl/senatuchwaly/3292/plik/567uch.pdf (1727.pdf, md5sum: eca25c7877ab39c4c9230dbbad1726b1)