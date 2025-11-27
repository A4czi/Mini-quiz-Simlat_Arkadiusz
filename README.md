# Mini-quiz-Simlat_Arkadiusz
📱 Mini Quiz – Opis Projektu
🎯 Cel

„Mini Quiz” to prosta aplikacja edukacyjna, w której użytkownik odpowiada na 5 losowych pytań wielokrotnego wyboru. Można rozpocząć quiz, zdobywać punkty i resetować wynik.

🧠 Jak działa aplikacja?

Po uruchomieniu widoczne są:

🏷️ tytuł: „Mini Quiz – Autor [imię]”,

▶️ ROZPOCZNIJ QUIZ,

🧮 Wynik: 0.

Po rozpoczęciu:

🎲 losowanych jest 5 pytań,

🅰️🅱️🅾️ każda odpowiedź do wyboru A/B/C,

🔄 wynik aktualizuje się na bieżąco,

🏁 po zakończeniu pojawia się komunikat:
„Koniec quizu! Twój wynik: X / 5”.

Dostępny jest też 🔁 RESETUJ QUIZ, który zeruje postęp.

✨ Wymagania funkcjonalne

Interfejs zawiera:

🏷️ tytuł,

▶️ start,

❓ obszar pytania,

🔘 trzy przyciski odpowiedzi,

🧮 wynik,

🔁 reset.

Zasady:

domyślnie widoczny jest tytuł + start + wynik 0,

po starcie pojawia się quiz,

po każdej odpowiedzi zmienia się wynik,

po 5 pytaniach — podsumowanie,

reset przywraca wszystko do stanu początkowego.

💻 Wymagania techniczne

Technologia: .NET MAUI (C#) lub Android Studio (Java)

Interfejs: XAML / XML

Pytania w tablicy obiektów (np. new Question(...))

Kod czytelny, projekt poprawnie się kompiluje i działa w emulatorze.

🚀 Instrukcja uruchomienia
📦 Oprogramowanie

MAUI: Visual Studio 2022 + .NET MAUI + Android SDK

Android Studio: Flamingo+, JDK 11/17, SDK 28+

📂 Import projektu

VS: Open project → wybierz .sln

Android Studio: Open → wybierz folder projektu

📱 Emulator

utwórz urządzenie (np. Pixel 5),

wybierz Android 12/13,

uruchom emulator.

▶️ Start

wybierz emulator,

kliknij Run,

aplikacja uruchomi się automatycznie.

🧪 Testowanie

Sprawdź:

widoczność elementów startowych,

poprawne wyświetlanie pytań,

losowanie 5 pytań,

naliczanie punktów,

komunikat końcowy,

działanie resetu.

Zrzuty Ekranu:
 
<img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 135901" src="https://github.com/user-attachments/assets/6c5f1cd2-5a0c-4024-b2f4-3d463d8f8e98" />

<img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 132049" src="https://github.com/user-attachments/assets/db987b50-81d4-4fa9-b6b3-5486e6994f9f" />
<img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 132132" src="https://github.com/user-attachments/assets/77d633c6-22d6-4642-b110-1f789b68ae20" />
