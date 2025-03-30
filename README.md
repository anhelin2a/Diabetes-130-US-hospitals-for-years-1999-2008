# Analiza Hospitalizacji Pacjentów z Cukrzycą

## Opis projektu
Projekt dotyczy analizy danych dotyczących hospitalizacji pacjentów z cukrzycą w 130 amerykańskich szpitalach w latach 1999–2008. Celem jest określenie ryzyka ponownej hospitalizacji pacjentów w ciągu 30 dni od momentu ich wypisu.

## Zbiór danych
- **Nazwa**: Diabetes 130-US hospitals for years 1999-2008
- **Źródło**: Dokumentacja szpitalna pacjentów z cukrzycą
- **Typ danych**: Kategoryczne, liczbowe
- **Brakujące wartości**: Tak

## Metodologia
1. **Eksploracja danych** – analiza cech i brakujących wartości.
2. **Przetwarzanie danych** – zmiana kategorii, usuwanie wartości odstających.
3. **Analiza statystyczna** – zależności między cechami.
4. **Modelowanie ML** – przewidywanie ryzyka ponownej hospitalizacji.
5. **Wizualizacja wyników** – wykresy, macierze korelacji.

## Kluczowe wnioski
- Wiek i liczba hospitalizacji są istotnymi czynnikami wpływającymi na ryzyko ponownej hospitalizacji.
- Pacjenci przyjmujący określone leki mają wyższe prawdopodobieństwo powrotu do szpitala.
- Brak kontroli poziomu glukozy we krwi może znacząco zwiększać ryzyko kolejnej hospitalizacji.
- Pacjenci, którzy byli hospitalizowani krócej niż 4 dni, rzadziej wracają do szpitala w porównaniu do tych, którzy pozostawali dłużej.

## Wykorzystane technologie
- **Python**: pandas, numpy, scikit-learn, seaborn, matplotlib
- **Jupyter Notebook**
- **Machine Learning**: klasyfikacja ponownej hospitalizacji

## Uruchomienie
1. Pobierz repozytorium.
2. Zainstaluj wymagane biblioteki:
   ```bash
   pip install pandas numpy seaborn scikit-learn matplotlib jupyter
   ```
3. Uruchom Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Otwórz plik `project.ipynb` i wykonaj kolejne komórki.
