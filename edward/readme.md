# Projekt Strony Internetowej - Edward Korbus

### Informacje ogólne
Strona stworzona na rzecz zajęć projektowania stron jako jedna z podstaw zaliczenia przedmiotu. Te informacje w tym pliku dotyczą tylko mojej części projektu.

### Struktura foldera
W folderze "edward" znajdują się dwa główne pliki HTML:

- Main.html
  Główna podstrona (wizytówka)

- contact_form.html
  Strona z formularzem kontaktowym

Dodatkowo jeden plik CSS do obydwu stron:
- styles.css

W "edward" można też znaleźć folder ze zdjęciami ( jednym gifem ):
- img

### Główna strona (Main.html)
Strona główna składa się z:
- Nagłówka (header)
- Tytułu (h1) z animacją
- Głównego bloku opartego o flex-grid z 3 kolumnami
- Stopki (footer)

### Header
Header jest oparty o flexbox i zawiera 3 sekcje prowadzące do różnych miejsc:

- "< Strona główna" — link do index.html projektu
- "Więcej?" — link do tego pliku (readme.md)
- "Formularz Kontaktowy >" — link do contact_form.html

Każdy element posiada klasę "header-section". Header znajduje się przed <body>, co jest nietypowe, ale działa.

### Tytuł z animacją (type-line)
Element: "Edward Korbus" (w znaczniku h1)
Tekst jest animowany jak w efektach "maszyny do pisania".
Powoduje stopniowe pojawianie się liter.

### Flex-grid (3 kolumny)
Pod tytułem znajduje się blok z trzema sekcjami:

[ reklama ] — [ terminal/opis ] — [ reklama ]

Konstrukcja HTML:
```
<div class="flex-grid">
  <section class="grid-col side-col">...</section>
  <section class="grid-col main-col">...</section>
  <section class="grid-col side-col">...</section>
</div>
```

Charakterystyka:
- Dwie kolumny boczne ("side-col") pojawiają się lub znikają zależnie od szerokości ekranu (responsywność)
- Środkowa kolumna ("main-col") zawiera "terminal" z sekcjami opisowymi
- Całość oparta o Flexbox

### Terminal (terminal)
Środkowy element przekazuje informacje tekstowe w stylu terminala.

Zawiera cztery sekcje:
1. o_mnie:
   Krótki opis autora

2. umiejętności:
   Lista umiejętności + umiejętności miękkie

3. projekty:
   Informacja o projektach w GameMaker oraz Godot

4. kontakt:
   Informacja o adresie mailowym + odsyłka do formularza kontaktowego

Etykiety mają klasę "label" i wywołują toggle collapsed przez onclick (minimalny JS).

### Footer
Footer zawiera:
- dwa obrazki gif po bokach (img/icon.gif)
- tekst: "© 2026 ~ Edward Korbus ~ I'll sue ya if you steal this. Be afraid."
- prawa strona jest jednocześnie linkiem prowadzącym do filmu na YouTube (rickroll)

Struktura HTML:
```
<footer>
  <img ...>
  <span>...</span>
  <a><img ...></a>
</footer>
```

### Formularz kontaktowy (contact_form.html)
Plik dostępny z headera.
Pozwala wysłać zapytanie przez email (manualnie lub przez formularz).
Wykorzystuje ten sam plik CSS (styles.css).

### Podsumowanie
Projekt przedstawia osobistą wizytówkę z prostą nawigacją, animowanym tytułem, sekcjami w stylu terminala oraz stopką z elementem humorystycznym. Całość spełnia wymagania zaliczeniowe z projektowania stron.
