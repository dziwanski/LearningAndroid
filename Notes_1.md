## Interfejs 
Interfejs użytkownika w każdej aplikacji składa się z dwóch typów elementów. 

- View (w tym artykule będę używał nazwy „Widok”), który jest czymś w rodzaju klocka, budującego interfejs:
  - Przycisk, 
  - obrazek, 
  - tekst, 
  - formularz do wpisywania tekstu – 

to wszystko są widoki – dokładniej rzecz biorąc te elementy rozszerzają klasę View.

- ViewGroup – jak sama nazwa wskazuje ten element jest odpowiedzialny za grupowanie widoków. Klasy rozszerzające klasę ViewGroup nazywamy layoutami (w tym artykule też będę używał tej nazwy). Pojedynczego widoku nie możemy sobie tak po prostu gdzieś wsadzić – musi on znajdować się w jakimś layoucie. Możesz sobie wyobrazić, że layout to coś, co przyjmuje jakieś przedmioty i układa je w odpowiedni dla siebie sposób.


## layouty

- Linear Layout – „liniowy” – ta nazwa idealnie oddaje jego działanie. Linear Layout po prostu układa elementy jeden za drugim. Wyróżniamy jego dwa warianty – Linear Layout z orientacją pionową oraz z orientacją poziomą.

- Relative Layout – „względny” lub „zależny” – układamy widoki na podstawie położenia innych elementów. Dla przykładu jeśli mamy 3 widoki A, B oraz C to, chcąc ułożyć je jeden pod drugim, musimy powiedzieć systemowi coś w stylu: „Przypnij widok A do góry, widok B do widoku A, a widok C do widoku B”.Relative Layout jest używany w sytuacjach, gdzie chcemy osiągnąć efekt niemożliwy do zrealizowania przy użyciu Linear Layout.

- Constraint Layout – ulepszony Relative Layout. Każdy widok opisywany jest przez tak zwane constrainty, czyli opis tego w jaki sposób widok ma być przypięty do innego widoku. 

## Rozdzielczości

„dp” czyli „density independent pixel” zamiast pikseli.

Możemy zdefiniować całkowicie osobny interfejs dla różnych wielkości ekranu

![Rodzaje rozdzielczości](http://img.android.com.pl/images/user-images/2018/09/1-3-960x553.png)


## Obrót ekranu
Przy zmianie orientacji, zazwyczaj następuje przeladowanie aplikacji.
Jest możliwość poinformowania systemu aby nie zatrzymywał naszej aplikacji przy obrocie telefonu lecz wtedy sami musimy zadbać o przeładowanie interfejsu.