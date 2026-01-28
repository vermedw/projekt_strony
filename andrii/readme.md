# Projekt: Responsywna Strona Internetowa

## 1. Informacje ogólne
**Temat strony:** Wizytówka Studenta Informatyki  
**Rodzaj projektu:** Strona internetowa HTML + CSS  
**Liczba osób w zespole:** 1

### Autorzy
- Andrii Ivanochko – podstrona wizytówka

---

## 2. Cel projektu
Celem projektu jest stworzenie responsywnej strony internetowej prezentującej wizytówkę studenta informatyki.  
Projekt realizuje wymagania z zakresu HTML5 i CSS, w tym semantykę, nowoczesne układy strony oraz animacje.

---

## 3. Struktura strony

Projekt składa się z następujących elementów:
- **Strona główna wizytówki**
- **Formularz kontaktowy**

---

## 4. Wykorzystane technologie

- **HTML5** – struktura i semantyka strony
- **CSS3** – stylizacja
- **Flexbox / Grid** – układ strony
- **Media Queries** – responsywność
- **Animacje CSS** – przejścia i transformacje

---

## 5. Semantyka HTML5

Na stronie zastosowano semantyczne znaczniki:
- `<header>` – nagłówek strony
- `<nav>` – menu nawigacyjne
- `<main>` – główna treść strony
- `<section>` – sekcje tematyczne
- `<article>` – karty z informacjami
- `<footer>` – stopka strony

---

## 6. Układ strony – Flexbox i Grid

- **Flexbox**:
  - menu nawigacyjne,
  - karty profilowe,
  - formularz kontaktowy,
  - stopka z ikonami.
- **Grid**:
  - układ kart informacyjnych (info-windows),
  - rozmieszczenie elementów w sekcjach.

---

## 7. Responsywność

Strona jest w pełni responsywna i dostosowuje się do różnych rozdzielczości ekranów:
- komputery,
- tablety,
- telefony komórkowe.

Zastosowano:
- media queries (breakpoint 768px),
- elastyczne jednostki (`%`, `px`, `vw`),
- elastyczne obrazy (`max-width: 100%`),
- flex-wrap dla układów.

---

## 8. Animacje i efekty CSS

Na stronie zastosowano:
- `transition` – płynne zmiany kolorów i transformacji,
- `transform` – przesuwanie elementów (translateY),
- efekty `hover` – na kartach, linkach, przyciskach,
- animacje `@keyframes` (appear),
- `scroll-behavior: smooth` – płynne przewijanie.

---

## 9. Formularz kontaktowy

Formularz kontaktowy zawiera:
- pole imię,
- pole adres e-mail,
- pole wiadomości,
- przycisk wysyłania.

Formularz wykorzystuje:
- walidację HTML (`required`, `type="email"`),
- stylizację CSS z efektami hover,
- animacje przy aktywnych polach formularza,
- wysyłanie przez `mailto`.

---

## 10. Linki

- [Katolicki Uniwersytet Lubelski](https://kul.pl/)
- [Profil na Facebooku](https://www.facebook.com/share/1QEJ655PgC/)
- [Profil na Instagramie](https://www.instagram.com/an_ivanochko/)

---

## 11. Struktura plików
projekt/
├── andrii.html
├── style.css
├── README.md
└── img/
├── profile.jpg
├── bg-profile.jpg
├── email.jpg
├── facebook.jpg
└── instagram.jpg

---

## 12. Podsumowanie

Projekt spełnia wszystkie wymagania:
- ✔ Strona tematyczna (wizytówka)
- ✔ Responsywność (media queries)
- ✔ Semantyka HTML5 (semantyczne tagi)
- ✔ Flexbox i Grid (oba zastosowane)
- ✔ Animacje CSS (transition, transform, keyframes)
- ✔ Podstrona autora (wizytówka)
- ✔ Formularz kontaktowy (z walidacją)

---

## 13. Możliwe rozszerzenia
- dodanie JavaScriptu dla dynamicznego menu mobilnego,
- walidacja formularza po stronie klienta z JavaScript,
- tryb ciemny (dark mode) z przełącznikiem,
- dodatkowe animacje i efekty wizualne,
- portfolio projektów jako kolejna sekcja.