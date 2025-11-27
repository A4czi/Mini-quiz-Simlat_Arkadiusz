# Mini-quiz-Simlat_Arkadiusz
Mini Quiz
Opis Projektu – „Mini Quiz” 

1. Cel projektu 

Celem projektu jest stworzenie mobilnej aplikacji edukacyjnej „Mini Quiz”, pozwalającej użytkownikowi rozwiązać prosty quiz wielokrotnego wyboru. Aplikacja umożliwia rozpoczęcie quizu, odpowiadanie na pytania, naliczanie punktów oraz resetowanie wyników. Projekt został wykonany zgodnie z wymaganiami dotyczącymi interfejsu, działania i struktury aplikacji. 

 

2. Opis ogólny działania aplikacji 

Aplikacja przedstawia użytkownikowi zestaw 5 losowo dobranych pytań. Każde pytanie posiada trzy możliwe odpowiedzi (A, B, C). Układ interfejsu jest pionowy, a wszystkie elementy są wyśrodkowane i mają zachowane marginesy. 

Po uruchomieniu widoczne są jedynie: 

tytuł aplikacji: „Mini Quiz – Autor [imię]”, 

przycisk „ROZPOCZNIJ QUIZ”, 

napis „Wynik: 0”. 

Po rozpoczęciu quizu: 

Losowane jest pięć pytań z tablicy. 

Wyświetlane jest aktualne pytanie i trzy przyciski odpowiedzi. 

Po każdym wyborze użytkownika aplikacja przechodzi do kolejnego pytania. 

Wynik jest aktualizowany na bieżąco. 

Po pięciu pytaniach pojawia się komunikat: 
„Koniec quizu! Twój wynik: X / 5”. 

Użytkownik może również skorzystać z przycisku „RESETUJ QUIZ”, który zeruje wynik i umożliwia ponowne rozpoczęcie zabawy. 

 

3. Wymagania funkcjonalne 

Interfejs użytkownika zawiera: 

Tytuł aplikacji w największej czcionce. 

Przycisk ROZPOCZNIJ QUIZ. 

Obszar pytania. 

Trzy przyciski odpowiedzi: A, B, C. 

Napis „Wynik: X”. 

Przycisk RESETUJ QUIZ. 

Zasady działania: 

Domyślnie widoczny jest tytuł, przycisk startu i wynik 0. 

Po rozpoczęciu quizu wyświetlane są pytania oraz przyciski wyboru. 

Po wybraniu odpowiedzi wynik jest aktualizowany. 

Po ostatnim pytaniu wyświetlane jest podsumowanie. 

Reset przywraca domyślne wartości i umożliwia rozpoczęcie quizu od nowa. 

 

4. Wymagania techniczne 

Projekt wykonany w .NET MAUI lub Android Studio. 

Interfejs zapisany w XAML (MAUI) lub XML (Android). 

Logika aplikacji zapisana w C# (.NET MAUI) lub Java (Android Studio). 

Pytania przechowywane są w tablicy obiektów, np.: 

new Question("Stolica Włoch to:", "Rzym", "Paryż", "Madryt", "Rzym"); 
 

Kod czytelny, z opisowymi nazwami metod i zmiennych. 

Projekt kompiluje się poprawnie i działa w emulatorze. 

 

Instrukcja Uruchomienia Aplikacji 

1. Wymagane oprogramowanie 

W zależności od użytej technologii: 

Wariant A: .NET MAUI 

Visual Studio 2022 (zainstalowane workloady: 
✔ .NET Multi-platform App UI 
✔ Android SDK 
✔ .NET 8/9) 

Wariant B: Android Studio 

Android Studio Flamingo lub nowsze 

JDK 11 lub 17 

Android SDK z API min. 28 

 

2. Import projektu 

W .NET MAUI 

Otwórz Visual Studio. 

Wybierz Open a project or solution. 

Wskaż plik rozwiązania .sln. 

Poczekaj na załadowanie i przywrócenie pakietów NuGet. 

W Android Studio 

Uruchom Android Studio. 

Kliknij Open. 

Wskaż katalog z projektem. 

Poczekaj na synchronizację Gradle. 

 

3. Konfiguracja emulatora 

Android 

Utwórz urządzenie w AVD Manager (np. Pixel 5). 

Wybierz obraz systemu: Android 12 lub 13. 

Włącz emulator. 

 

4. Uruchomienie aplikacji 

Wybierz urządzenie/emulator na górnym pasku. 

Kliknij Start / Run (Visual Studio: zielona strzałka ▶). 

Poczekaj na zbudowanie aplikacji i automatyczne uruchomienie jej w emulatorze. 

 

5. Testowanie działania 

Po uruchomieniu sprawdź: 

Widoczność tytułu i przycisku „ROZPOCZNIJ QUIZ”. 

Poprawne wyświetlanie pytań. 

Losowanie 5 pytań. 

Aktualizację wyniku po każdej odpowiedzi. 

Pojawienie się komunikatu końcowego. 

Działanie funkcji „RESETUJ QUIZ”. 

 

6. Reset projektu i ponowne uruchomienie 

Kliknij RESETUJ QUIZ w aplikacji. 

Lub ponownie wciśnij przycisk Run w środowisku IDE. 

 <img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 132035" src="https://github.com/user-attachments/assets/320cb541-af57-4543-aa74-ad282dc70415" />
<img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 132049" src="https://github.com/user-attachments/assets/db987b50-81d4-4fa9-b6b3-5486e6994f9f" />
<img width="1600" height="900" alt="Zrzut ekranu 2025-11-27 132132" src="https://github.com/user-attachments/assets/77d633c6-22d6-4642-b110-1f789b68ae20" />
