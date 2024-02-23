# SSN. Lab. 11. Sieci rekurencyjne

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [rnn.ipynb](https://github.com/IS-UMK/ssn_lab_11/blob/master/rnn.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_lab_11/blob/master/rnn.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_lab_11/master?filepath=rnn.ipynb)

---

# Zadanie. 11. Przewidywanie ceny akcji

Plik [dane/cdr_d.csv](dane/cdr_d.csv) zawiera historyczne wyceny akcji spółki giełdowej CD Projekt notowanej na GPW. Dane zawierają wartości w interwałach dziennych od momentu debiutu spółki do ostatniej sesji z dnia 9 czerwca 2023 r. 

Zbuduj jak najlepszy model sieci rekurencyjnej przewidujący cenę zamknięcia na podstawie historycznych notowań. 
Wykorzystaj model do wyznaczenia przewidywanej ceny akcji CDR 
* na zamkniecie sesji w następnym dniu roboczym 12 czerwca 2023 r. (+1 dzień od ostatniej wyceny) 
* oraz przewidywaną cenę zamknięcia na koniec tygodnia 23 czerwca 2023 r. (+5 dni). <br>Do wyznaczenia ceny na koniec tygodnia  wykorzystaj model autoregresji albo zbuduj model przewidujący wycenę na 5 dni do przodu.

Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w Moodle lub prześlij do repozytorium GitHub.

---
## Materiały:

* Neurocomuting, [Recurrent neural networks](https://julien-vitay.net/lecturenotes-neurocomputing/3-deeplearning/9-RNN.html)
* [TensorFlow Examples](https://github.com/tensorflow/examples/tree/master/courses/udacity_intro_to_tensorflow_for_deep_learning)



