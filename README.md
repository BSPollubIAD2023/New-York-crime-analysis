# New York Crime Analysis

Analiza danych dotyczących przestępczości w Nowym Jorku z wykorzystaniem metod statystycznych oraz modelu uczenia maszynowego.

## Cel projektu

Celem projektu było:

- zbadanie struktury przestępczości w Nowym Jorku,
- identyfikacja zależności pomiędzy cechami sprawców, miejscem zdarzenia i typem przestępstwa,
- wyodrębnienie grup podobnych przestępstw,
- zbudowanie modelu predykcyjnego klasyfikującego grupy przestępstw.

## Dane

W projekcie wykorzystano dane dotyczące aresztowań NYPD zawierające m.in.:

- rodzaj przestępstwa,
- dzielnicę miasta,
- sposób aresztowania,
- płeć sprawcy,
- grupę wiekową,
- rasę sprawcy,
- sezon wystąpienia zdarzenia.

## Analiza eksploracyjna

Przeprowadzono analizę:

- rozkładów zmiennych,
- zależności pomiędzy grupami demograficznymi a typami przestępstw,
- różnic pomiędzy dzielnicami Nowego Jorku,
- sezonowości zdarzeń.

## Metody statystyczne

W projekcie wykorzystano:

- test Shapiro-Wilka,
- test Levene'a,
- ANOVA Welcha,
- test Gamesa-Howella,
- permutacyjną analizę wariancji.

## Grupowanie przestępstw

Na podstawie charakterystyki przestępstw wyodrębniono pięć grup podobnych kategorii przestępstw.

## Model predykcyjny

Zbudowano model **Random Forest**, którego zadaniem była predykcja grupy przestępstw na podstawie:

- wieku sprawcy,
- płci,
- rasy,
- dzielnicy miasta,
- sezonu,
- sposobu aresztowania.

W celu ograniczenia problemu niezbalansowanych klas zastosowano dodatkowe wagi klas.

## Technologie

- R
- tidyverse
- ggplot2
- randomForest
- rstatix
- lmPerm

## Autor

**Bartłomiej Stola**
