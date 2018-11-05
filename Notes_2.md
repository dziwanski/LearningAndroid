# Czas życia aplikacji

## Aktywność

Aktywność to najważniejsza rzecz każdej aplikacji. W uproszczeniu możemy przyjąć, że jest to każdy ekran, który zajmuje powierzchnię całego wyświetlacza telefonu.

Za każdym razem, gdy otwieramy jakąś aplikację, to system uruchamia jej domyślną aktywność.

> Sterujemy aplikacją przy pomocy aktywności.

## Stany aplikacji

![Stany Aplikacji](http://img.android.com.pl/images/user-images/2018/10/cykl-zycia-aplikacji-android-640x386.png)

### 4 stany życia aplikacji:
| Aktywność | Opis |
| - | - |
| Active | Gdy aktywność jest widoczna na pelnym ekranie |
| Paused | Użytkownik uruchomi inną aplikacje, ale nie przysłoni naszej aplikacji w całości |
| Stopped | Użytkownik otworzy inną aplikację która zasłoni naszą całkowicie lub gdy aplikacja zostanie zminimalizowana. |
| Destroyed | Gdy mamy dużo uruchomionych aplikacji, to system może zniszczyć naszą aktywność która jest zapauzowana lub zatrzymana w celu odzyskania pamięci. Jest to ostatni moment kiedy możemy zapisać ważne dane. |


