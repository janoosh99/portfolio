# Portfolio - Julianna Janusz

Strona portfolio w jednym pliku `index.html`. Zdjęcia, logotypy i film są w folderze `assets`.

## Co jest w paczce

```
portfolio-julianna-janusz/
├── index.html        ← cała strona (to ją GitHub pokazuje jako stronę główną)
├── README.md         ← ta instrukcja
└── assets/
    ├── img/          ← zdjęcia i grafiki
    ├── logos/        ← logotypy marek
    └── video/        ← film z wydarzeń Selly
```

Ważne: `index.html` musi leżeć w głównym folderze repozytorium, a obok niego folder `assets`. Nie wrzucaj samego pliku .zip, tylko jego rozpakowaną zawartość.

## Jak wrzucić stronę na GitHub Pages (pierwszy raz)

1. **Rozpakuj paczkę.** Kliknij dwa razy `portfolio-julianna-janusz.zip`. Powstanie folder z plikami `index.html`, `README.md` i folderem `assets`.
2. **Załóż konto** na https://github.com (jeśli jeszcze go nie masz) i zaloguj się.
3. **Utwórz repozytorium.** Prawy górny róg: **+** → **New repository**.
   - Nazwa: np. `portfolio`. Strona będzie wtedy pod adresem `https://TWÓJ-LOGIN.github.io/portfolio/`.
   - Chcesz krótszy adres `https://TWÓJ-LOGIN.github.io/`? Nazwij repozytorium dokładnie `TWÓJ-LOGIN.github.io`.
   - Ustaw **Public**. Na darmowym koncie GitHub Pages działa tylko dla publicznych repozytoriów.
   - Kliknij **Create repository**.
4. **Wgraj pliki.** W nowym repozytorium kliknij link **uploading an existing file** (albo **Add file** → **Upload files**).
   - Otwórz rozpakowany folder, zaznacz `index.html`, `README.md` i folder `assets` i przeciągnij je do okna przeglądarki. Przeciągaj zawartość folderu, nie cały folder, żeby `index.html` trafił do głównego katalogu.
   - Poczekaj, aż pasek ładowania dojdzie do końca (to ok. 50 plików, GitHub przyjmuje do 100 naraz i do 25 MB na plik).
   - Na dole wpisz opis, np. `Pierwsza wersja portfolio`, zostaw **Commit directly to the main branch** i kliknij **Commit changes**.
5. **Włącz stronę.** W repozytorium wejdź w **Settings** → w lewym menu **Pages**.
   - W sekcji **Build and deployment** → **Source** wybierz **Deploy from a branch**.
   - W **Branch** wybierz `main` i folder `/ (root)`. Kliknij **Save**.
6. **Poczekaj 1-3 minuty** i odśwież stronę **Settings → Pages**. Na górze pojawi się adres strony i przycisk **Visit site**.
7. **Sprawdź stronę** na komputerze i na telefonie. Jeśli coś się nie wczytało, odśwież stronę z pominięciem pamięci (Mac: Cmd + Shift + R, Windows: Ctrl + F5).

## Jak podmienić stronę po zmianach

1. Zmień teksty w Claude Design (strona „Strona www”) albo poproś Claude o zmiany w czacie.
2. Napisz „eksportuj stronę”. Dostaniesz nową paczkę .zip.
3. Rozpakuj ją, wejdź w repozytorium na GitHubie → **Add file** → **Upload files** i przeciągnij nowe `index.html` i folder `assets`. Pliki o tych samych nazwach zostaną nadpisane.
4. Kliknij **Commit changes**. Po 1-3 minutach nowa wersja jest online.

Plik, którego już nie ma na stronie, możesz zostawić w repozytorium (nic nie psuje) albo usunąć: otwórz go na GitHubie → menu **...** → **Delete file**.

## Drobne zmiany bez Claude

- **Teksty:** na GitHubie otwórz `index.html`, kliknij ikonę ołówka i zmień tekst między znacznikami. Każda sekcja ma komentarz, np. `<!-- SEO I TEKSTY -->`. Na koniec **Commit changes**.
- **Zdjęcia:** wgraj nowy plik do `assets/img` pod tą samą nazwą co stary.
- **Kolory:** są na górze `index.html`, w bloku `:root` (np. `--olive`, `--rose`).

Animacje same się wyłączają, jeśli ktoś ma w systemie włączone ograniczenie ruchu.
