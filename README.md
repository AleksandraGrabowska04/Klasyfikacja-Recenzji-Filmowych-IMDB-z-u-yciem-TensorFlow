# Projekt: Klasyfikacja Recenzji Filmowych (IMDB) z użyciem TensorFlow

Celem niniejszego projektu jest stworzenie i porównanie czterech różnych modeli sieci neuronowych do klasyfikacji recenzji filmowych jako pozytywne lub negatywne. W projekcie wykorzystano popularny zbiór danych IMDB Reviews, zawierający 50 000 recenzji filmów, równomiernie podzielonych na klasy pozytywne i negatywne.

Projekt realizowany jest w języku Python z użyciem biblioteki TensorFlow, w środowisku Google Colab. Przed przystąpieniem do budowy modeli wykonano podstawowy preprocessing danych, w tym wektoryzację tekstów, ustalenie długości sekwencji oraz przygotowanie danych treningowych i testowych.

W ramach projektu zaimplementowano i przetestowano cztery różne architektury sieci neuronowych:

  - MLP (Multilayer Perceptron) - prosty model gęsto połączony, używany jako baseline.

  - LSTM (Long Short-Term Memory) - sieć rekurencyjna, lepiej radząca sobie z analizą sekwencji.

  - CNN (Convolutional Neural Network) - sieć konwolucyjna, która wykrywa lokalne wzorce w tekście.

  - GRU + Attention (Gated Recurrent Unit z mechanizmem uwagi) - lekka sieć rekurencyjna, która zapamiętuje kontekst sekwencji i skupia się na najważniejszych słowach dzięki warstwie uwagi (attention). Działa szybciej niż LSTM i często osiąga podobne wyniki.

Każdy z modeli został oceniony na podstawie metryk takich jak dokładność (accuracy), strata (loss), macierz błędów oraz krzywe uczenia się. Na końcu projektu dokonano porównania skuteczności wszystkich modeli i wskazano najlepszy z nich wraz z uzasadnieniem wyboru.

**Członkowie zespołu**
  - Aleksandra Grabowska
  - Jakub Malinowski
  - Jakub Markowski
  - Krystian Dzikiewicz
