# SpectreNotes — wydania

Tu są tylko gotowe binarki SpectreNotes (notatki piórem na Windows, Rust + Direct2D).
Źródła są w osobnym repozytorium.

## Instalacja

1. Pobierz **[SpectreNotes-Setup.exe](https://github.com/AtmatiAdi/spectrenotes-releases/releases/latest/download/SpectreNotes-Setup.exe)** i uruchom.
2. Instalator pobiera bieżącą wersję, sprawdza sumę SHA-256 i instaluje ją dla Twojego
   konta (`%LOCALAPPDATA%\SpectreNotes\app`, skrót w menu Start, wpis w „Zainstalowane aplikacje").
   Bez uprawnień administratora.
3. Windows SmartScreen może ostrzec przed niepodpisanym instalatorem:
   „Więcej informacji → Uruchom mimo to".

Notatki i ustawienia leżą w `%APPDATA%\SpectreNotes` — odinstalowanie ich nie usuwa.

## Aktualizacje

Aplikacja sama sprawdza to repozytorium (po starcie i co 10 min). Gdy jest nowsza wersja,
w **Settings → Application** pojawia się „version X available" z przyciskami
**Download** (pasek postępu) i **Install and restart**. Nic nie pobiera się ani nie
instaluje bez kliknięcia.

## Zasoby każdego wydania

| plik | co to |
|---|---|
| `spectrenotes.exe` | aplikacja (przenośna — działa też bez instalacji) |
| `SpectreNotes-Setup.exe` | instalator |
| `SHA256SUMS.txt` | sumy kontrolne obu plików |

Adres najnowszej wersji jest stały:
`https://github.com/AtmatiAdi/spectrenotes-releases/releases/latest/download/<plik>`.
Przechowywane są trzy ostatnie wydania.
