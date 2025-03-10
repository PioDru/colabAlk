# Notebooki Jupyter PoC systemu do analizy obrazowań medycznych trenowanego na symulowanych danych

## Opis

To repozytorium zawiera notatniki Jupyter użyte do trenowania modeli ML za pomoca zasobów Google Colab. 
Projekt został przygotowany jako część PoC systemu do analizy obrazowych danych medycznych.

## Zawartość repozytorium

- **breast_usg (1).ipynb**  
  Notatnik prezentujący analizę danych USG piersi w kontekście wykrywania raka piersi.

- **chest_xray_pneumonia.ipynb**  
  Notatnik zawierający analizę rentgenowską klatki piersiowej w kontekście wykrywania zapalenia płuc.

- **breast_cancer_image_calssification_effecientb3_pdr.ipynb**  
  Notatnik prezentujący próbę wykorzystania modelu bazowego do analizy danych USG piersi w kontekście wykrywania raka piersi.

- **usgValidFilenames.csv**
  Plik CSV zawierajacy liste plików z datasetu USG, co do których nie było watpliwości w pracy: https://www.sciencedirect.com/science/article/pii/S2352340923003669
  

## Jak rozpocząć

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/PioDru/colabAlk.git
   ```
   
Otwórz wybrany notatnik w swoim ulubionym środowisku Jupyter lub bezpośrednio w Google Colab (trening odbywał się korzystajac z GPU T4).
Uruchom wszystkie komórki notatnika.
Dostosuj kod do własnych potrzeb, aby eksperymentować z analizą symulowanych danych.

## Wymagania
Przeglądarka internetowa.
Konto Google do korzystania z Google Colab.
Podstawowa znajomość języka Python oraz środowiska Jupyter Notebook.

