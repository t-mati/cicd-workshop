# Baseline — pomiar stanu wyjściowego

Plik uzupełniasz w ZADANIU 01. Czasy odczytujesz w zakładce **Actions**. Wystarczy dokładność
do sekundy.

## Czasy kroków — przebieg na `main`

| Krok | Czas |
|---|---|
| Set up job | 0s  |
| Checkout | 1s |
| Set up Node | 1s |
| Install dependencies | 29s |
| Install Playwright browsers | 16s |
| Unit tests | 0s |
| API tests | 20s |
| UI tests | 2m 21s |
| Upload Playwright report | 2s |
| Post Set up Node | 0s |
| Post Checkout | 0s |
| Complete job | 0s |
| **Cały przebieg** | 3m 33s |

## Czas do pierwszego czerwonego sygnału

| Branch | Czas samego testu | Od startu przebiegu do informacji o błędzie |
|---|---|---|
| `demo/failing-unit` | 1s | 1m 1s |
| `demo/failing-search` | 3m 5s | 4m 6s|

Co na `demo/failing-unit` stało się z testami API i UI:

## `demo/failing-lint` i `demo/failing-security`

| Branch | Wynik przebiegu | Dlaczego tak |
|---|---|---|
| `demo/failing-lint` | 3m 28s | |
| `demo/failing-security` | 4m 7s | |

## Pięć problemów obecnego pipeline’u

1.
2.
3.
4.
5.

## Pomiary z kolejnych zadań

Tu dopisujesz pomiary i odpowiedzi z kolejnych zadań, pod nagłówkiem z numerem zadania.
