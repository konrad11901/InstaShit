# InstaShit.Bot

**InstaShit.Bot** to wersja InstaShita korzystająca z popularnego komunikatora Telegram. InstaShit.Bot automatycznie rozwiązuje dzienne sesje Insta.Linga. Potrafi obsłużyć wielu użytkowników.

## Publiczna instancja

Twórca InstaShita hostuje publiczną instancję InstaShit.Bota: https://t.me/InstaShitBot (uruchomiona w trakcie roku szkolnego). Korzystanie z tej instancji jest **darmowe przez pierwsze siedem dni**. Po upływie tego okresu należy zakupić abonament. **Wpływy z abonamentu przeznaczone są na rozwój projektu i utrzymanie serwera.**

## Własna instancja

Istnieje możliwość utworzenia własnej instancji InstaShit.Bota. Jest to **w pełni darmowe**.

### Pobieranie

Stabilne wydania można znaleźć na oficjalnej stronie InstaShita: https://instashit.pl. Archiwalne wersje można pobrać z serwisu [Github](https://github.com/konrad11901/InstaShit.Bot/releases). 

Do uruchomienia InstaShit.Bota konieczne jest zainstalowanie środowiska uruchomieniowego .NET Core 2.1 lub nowszego.

Istnieje możliwość samodzielnego skompilowania InstaShit.Bota. Jest to dobra opcja dla osób, które chcą korzystać z najnowszych funkcji InstaShit.Bota. Najnowszy kod źródłowy można pobrać z oficjalnej strony InstaShita lub z serwisu GitHub.

### Uruchamianie

Należy otworzyć wiersz poleceń i wpisać komendę:

```
dotnet <lokalizacja pliku InstaShit.Bot.dll>
```

### Konfiguracja

Do poprawnego działania InstaShit.Bota należy go skonfigurować.

Dostępne ustawienia:

* **TelegramBotToken** - token autoryzacyjny wygenerowany przez BotFathera. Więcej informacji [tutaj](https://core.telegram.org/bots#6-botfather).
* **Whitelist** - określa, czy dostęp do bota mają mieć tylko upoważnione osoby, czy wszyscy.

### Wiersz poleceń InstaShit.Bot

InstaShit.Bot posiada prosty wiersz poleceń. Aby uzyskać informacje na temat dostępnych komend, należy użyć polecenia _/help_.