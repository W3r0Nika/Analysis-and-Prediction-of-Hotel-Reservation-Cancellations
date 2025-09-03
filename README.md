# Analiza i przewidywanie anulowania rezerwacji hotelowych

## Opis projektu
Projekt został zrealizowany w ramach przedmiotu **"Eksploracja danych"** na Politechnice Lubelskiej.  
Celem pracy była analiza czynników wpływających na anulowanie rezerwacji hotelowych oraz budowa modeli predykcyjnych pozwalających przewidywać prawdopodobieństwo anulowania rezerwacji.  

---

## Zbiór danych
W projekcie wykorzystano publicznie dostępny zbiór danych dotyczący rezerwacji hotelowych.  

**Charakterystyka zbioru:**
- informacje o rodzaju hotelu, terminach i długości pobytu,  
- dane demograficzne klientów,  
- liczba pokoi, dzieci, dorosłych,  
- informacje o sposobie płatności i specjalnych życzeniach,  
- zmienna docelowa: **czy rezerwacja została anulowana** (tak/nie).  

---

## Cel projektu
- Zidentyfikowanie najważniejszych czynników wpływających na anulowanie rezerwacji.  
- Zbudowanie modeli predykcyjnych przewidujących prawdopodobieństwo anulowania.  
- Porównanie skuteczności wybranych algorytmów.  

---

## Wykorzystane technologie
- **Język programowania:** R  
- **Biblioteki:** tidyverse, ggplot2, caret, randomForest, rpart, e1071  

---

## Struktura projektu
1. **Przygotowanie danych**  
   - czyszczenie i uzupełnianie braków danych,  
   - transformacje zmiennych, kodowanie kategorii,  
   - podział na zbiór treningowy i testowy.  

2. **Eksploracyjna analiza danych (EDA)**  
   - wizualizacja rozkładów zmiennych,  
   - analiza korelacji,  
   - badanie zależności pomiędzy cechami a anulowaniem rezerwacji.  

3. **Modelowanie**  
   - Regresja logistyczna,  
   - Drzewa decyzyjne,  
   - Random Forest,  
   - Support Vector Machines (SVM).  

4. **Ewaluacja**  
   - accuracy, precision, recall, F1-score, AUC-ROC,  
   - porównanie skuteczności modeli.  

---

## Wyniki i wnioski
- Największy wpływ na anulowanie rezerwacji miały m.in. liczba wcześniejszych rezerwacji, czas pomiędzy dokonaniem rezerwacji a przyjazdem oraz kanał rezerwacyjny. 
- Modele oparte na drzewach decyzyjnych (Random Forest) osiągnęły najwyższą skuteczność w przewidywaniu anulowania rezerwacji.  
- Proste modele (np. regresja logistyczna) dawały interpretowalne, ale mniej dokładne wyniki.  

---

## Bibliografia
- Materiały dydaktyczne z przedmiotu *Eksploracja danych*  
- Dokumentacja R i pakietów: tidyverse, caret, randomForest   

