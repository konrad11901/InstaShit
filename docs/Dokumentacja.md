# Dokumentacja InstaShit

## Wprowadzenie

**InstaShit** to bot do polskiego serwisu [Insta.Ling](https://instaling.pl). InstaShit to nie tylko zwykły skrypt bezmyślnie rozwiązujący dzienną sesję Insta.Linga - imituje on prawdziwego użytkownika poprzez m.in. robienie nierównych odstępów między pytaniami oraz popełnianie błędów w odpowiedziach (zgodnie z preferencjami użytkownika).

Wszystkie projekty InstaShit są dostępne **całkowicie za darmo** na licencji [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

## Projekty InstaShit

### Stabilne, w pełni wspierane

* [InstaShitCore](InstaShitCore.md) - baza dla wszystkich projektów InstaShit (nie jest samodzielnym programem)
* [InstaShit.CLI](InstaShit.CLI.md) - wersja InstaShita działająca w wierszu poleceń dla systemów Windows, macOS i Linux
* [InstaShit.Bot](InstaShit.Bot.md) - bot korzystający z komunikatora Telegram, automatycznie wykonuje sesję Insta.Linga raz dziennie, obsługuje wielu użytkowników

### Porzucone projekty (bez wsparcia)

* [InstaShit.Android](InstaShit.Android.md) - wersja InstaShita dla systemu Android (5.0+)

Kliknięcie w nazwę projektu przekierowuje do jego dokumentacji.

## Konfiguracja InstaShita

Do poprawnego działania InstaShita należy go skonfigurować.

Dostępne ustawienia:

* **Login** - login/adres e-mail używany do zalogowania się się do serwisu Insta.Ling
* **Password** - hasło używane do zalogowania się do serwisu Insta.Ling
* **MinimumSleepTime** - minimalny czas oczekiwania między pytaniami
* **MaximumSleepTime** - maksymalny czas oczekiwania między pytaniami
* **IntelligentMistakesData** - dane wykorzystywane do popełniania błędów w odpowiedziach (więcej informacji poniżej) - pole nieobowiązkowe

Jeśli ustawiono IntelligentMistakesData:

* **AllowTypo** - określa, czy pozwalać na literówki w błędnych odpowiedziach
* **AllowSynonym** - określa, czy pozwalać na synonimy w błędnych odpowiedziach

Zaawansowane ustawienia (do ręcznej konfiguracji):

* **AnswerMarketingQuestions** - określa, czy odpowiadać na pytania sponsorowane (które zachęcają do zakupu słówek) - to ustawienie zdaje się nie mieć żadnego wpływu na wynik sesji. Domyślna wartość: nie (false)
* **Debug** - określa, czy wypisywać dane diagnostyczne, które mogą pomóc w znalezieniu źródła potencjalnego błędu. Domyślna wartość: nie (false)
