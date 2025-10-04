# PYTANIA NA EGZAMIN DYPLOMOWY, STUDIA I STOPNIA INŻYNIERSKIE KIERUNEK INFORMATYKA

# Spis treści
- [Algorytmy i struktury danych](#algorytmy-i-struktury-danych)
  - [1. Pojęcie algorytmu i jego prezentacja](#1-pojęcie-algorytmu-i-jego-prezentacja)
  - [2. Metody szacowania złożoności obliczeniowej algorytmów](#2-metody-szacowania-złożoności-obliczeniowej-algorytmów-złożoność-czasowa-pamięciowa-asymptotyczna-i-benchmarking)
  - [3. Przykłady algorytmów sortowania](#3-przykłady-algorytmów-sortowania-i-ich-złożoność-obliczeniowa)
  - [4. Drzewa poszukiwań binarnych](#4-drzewa-poszukiwań-binarnych-podstawowe-operacje-na-drzewach-sposoby-przechodzenia-drzewa)
  - [5. Metody przeszukiwania grafów i algorytm Dijkstry](#5-metody-przeszukiwania-grafów-i-wyznaczania-najkrótszej-ścieżki-na-przykładzie-algorytmu-dijkstry)
  - [6. Abstrakcyjne struktury danych](#6-abstrakcyjne-struktury-danych-listy-kolejki-stosy-słowniki)
  - [7. Strategia dziel i zwyciężaj, algorytmy zachłanne](#7-strategia-dziel-i-zwyciężaj-idea-algorytmu-zachłannego)
- [Architektura i organizacja komputerów](#architektura-i-organizacja-komputerów)
  - [8. Reprezentacja liczb całkowitych i zmiennoprzecinkowych](#8-reprezentacja-liczb-całkowitych-i-zmiennoprzecinkowych-w-systemach-binarnym-i-szesnastkowym)
  - [9. Specyfika programowania niskopoziomowego](#9-specyfika-programowania-niskopoziomowego)
  - [10. Obliczeniowe jednostki wykonawcze CPU, GPU, TPU, FPU](#10-obliczeniowe-jednostki-wykonawcze-cpu-gpu-tpu-fpu)
- [Sieci komputerowe](#sieci-komputerowe)
  - [11. Protokoły warstwy łącza danych, sieci i transportowej](#11-protokoły-warstwy-łącza-danych-sieci-oraz-transportowej-w-modelu-osi)
  - [12. Przydzielanie adresów przez DHCP](#12-przydzielanie-adresów-przez-protokół-dhcp)
  - [13. Wyliczanie adresów sieci, maski, rozgłoszeniowego w IPv4, IPv6](#13-wyliczanie-adresów-sieci-maski-rozgłoszeniowego-w-ipv4-ipv6)
  - [14. System DNS](#14-system-dns)
- [Bazy danych](#bazy-danych)
  - [15. Klucze główne i obce](#15-klucze-główne-klucze-obce-w-bazach-danych)
  - [16. Diagram związków encji](#16-diagram-związków-encji)
  - [17. Język SQL i podjęzyki DDL, DML, DCL](#17-język-baz-danych-sql-podjęzyki-ddl-dml-dcl)
  - [18. Instrukcja SELECT i łączenie tabel](#18-instrukcja-select-łączenie-danych-z-wielu-tabel)
- [Podstawy elektroniki i miernictwo elektroniczne](#podstawy-elektroniki-i-miernictwo-elektroniczne)
  - [19. Diody półprzewodnikowe, tranzystory](#19-diody-półprzewodnikowe-tranzystory)
  - [20. Układy scalone, impulsowe, cyfrowe](#20-układy-scalone-impulsowe-cyfrowe)
  - [21. Przetworniki ADC i DAC](#21-przetworniki-analogowo-cyfrowe-i-cyfrowo-analogowe)
- [Matematyka dyskretna](#matematyka-dyskretna)
  - [22. Schematy wyboru i tożsamości kombinatoryczne](#22-schematy-wyboru-i-tożsamości-kombinatoryczne)
  - [23. Liniowe równania rekurencyjne](#23-liniowe-równania-rekurencyjne)
  - [24. Grafy i ich własności](#24-grafy-i-ich-własności)
- [Programowanie strukturalne](#programowanie-strukturalne)
  - [25. Typy zmiennych](#25-typy-zmiennych-w-językach-programowania)
  - [26. Rodzaje pętli](#26-rodzaje-pętli)
  - [27. Zmienne typu adresowego (wskaźniki)](#27-zmienne-typu-adresowego-wskaźniki-zastosowanie-w-wybranym-języku-programowania)
  - [28. Funkcje, przekazywanie parametrów](#28-funkcje-przekazywanie-parametrów-przez-wartość-i-referencję)
- [Wizualizacja danych](#wizualizacja-danych)
  - [29. Definicja histogramu i typ wykresu](#29-definicja-histogramu-jakiego-typu-wykresu-warto-użyć-do-prezentacji)
  - [30. Biblioteki do tworzenia wykresów w Python](#30-biblioteki-wspierające-tworzenie-wykresów-za-pomocą-języka-python)
  - [31. Koncepcja "czystych danych/tidy data"](#31-omów-koncepcję-czystych-danychtidy-data)
  - [32. Etapy analizy i wizualizacji danych](#32-etapy-analizy-i-wizualizacji-danych)
- [Programowanie obiektowe](#programowanie-obiektowe)
  - [33. Składniki klasy i modyfikatory dostępu](#33-składniki-klasy-i-modyfikatory-dostępu)
  - [34. Obiekty a klasy, hermetyzacja](#34-obiekty-a-klasy-pojęcie-hermetyzacji)
  - [35. Pola i metody statyczne](#35-pola-i-metody-statyczne-w-klasie)
  - [36. Dziedziczenie, polimorfizm, szablony klas](#36-dziedziczenie-polimorfizm-szablony-klas)
  - [37. Klasy abstrakcyjne i interfejsy](#37-klasy-abstrakcyjne-i-interfejsy)
- [Systemy operacyjne](#systemy-operacyjne)
  - [38. Procesy, wątki, zarządzanie procesami](#38-procesy-wątki-zarządzanie-procesami)
  - [39. Synchronizacja procesów współbieżnych, semafory](#39-synchronizacja-procesów-współbieżnych-semafory)
- [Inżynieria oprogramowania](#inżynieria-oprogramowania)
  - [40. Cykle projektowania i życia oprogramowania](#40-cykle-projektowania-i-życia-oprogramowania)
  - [41. Metody i strategie testowania](#41-metody-oraz-strategie-testowania-oprogramowania)
- [Projektowanie systemów informatycznych](#projektowanie-systemów-informatycznych)
  - [42. Metodologie wytwarzania systemów](#42-metodologie-wytwarzania-systemów-informatycznych)
  - [43. Metody identyfikacji wymagań](#43-metody-identyfikacji-wymagań-systemu-informatycznego)
- [Podstawy logiki, algebra, analiza, metody probabilistyczne](#podstawy-logiki-algebra-analiza-metody-probabilistyczne)
  - [44. Działania na zbiorach](#44-działania-na-zbiorach)
  - [45. Rachunek zdań](#45-rachunek-zdań)
  - [46. Działania na macierzach](#46-działania-na-macierzach)
  - [47. Układy równań liniowych – twierdzenie Kroneckera-Capelliego](#47-układy-równań-liniowych--twierdzenie-kroneckera-capelliego)
  - [48. Pojęcie relacji i funkcji](#48-pojęcie-relacji-i-funkcji)
  - [49. Własności relacji](#49-własności-relacji-relacje-porządkujące-relacje-równoważności)
  - [50. Własności funkcji](#50-własności-funkcji-miejsca-zerowe-ciągłość-pochodna)
  - [51. Zmienna losowa i jej charakterystyki](#51-zmienna-losowa-i-jej-charakterystyki-liczbowe)
- [Programowanie deklaratywne](#programowanie-deklaratywne)
  - [52. Definicje unifikatora, algorytm unifikacji](#52-definicje-unifikatora-podstawienia-uzgadniającego-najogólniejszego-unifikatora-algorytm-unifikacji-i-twierdzenie-o-unifikacji)
  - [53. Budowa programu w Prologu](#53-budowa-programu-w-prologu-klauzule-fakty-reguły-definicje-predykatów-sposób-realizacji-programu)
- [Technika cyfrowa](#technika-cyfrowa)
  - [54. Systemy funkcjonalnie pełne](#54-systemy-zestawy-funkcjonalnie-pełne)
  - [55. Elementy pamięciowe w układach sekwencyjnych](#55-elementy-pamięciowe-stosowane-w-układach-sekwencyjnych)
  - [56. Rodzaje układów sekwencyjnych](#56-rodzaje-układów-sekwencyjnych-różnice-w-procedurach-ich-projektowania)
- [Systemy wbudowane](#systemy-wbudowane)
  - [57. Mikrokontrolery i systemy wbudowane](#57-mikrokontrolery-i-systemy-wbudowane)
  - [58. Tryby adresowania rozkazów mikrokontrolera](#58-tryby-adresowania-rozkazów-mikrokontrolera)
  - [59. Rodzaje transmisji szeregowej](#59-rodzaje-transmisji-szeregowej)
- [Sztuczna inteligencja i metody inżynierii wiedzy](#sztuczna-inteligencja-i-metody-inżynierii-wiedzy)
  - [60. Model obliczeniowy perceptronu](#60-model-obliczeniowy-perceptronu)
  - [61. Metody uczenia sieci neuronowych](#61-metody-uczenia-sieci-neuronowych)
  - [62. Mechanizm działania algorytmu genetycznego](#62-mechanizm-działania-algorytmu-genetycznego)
  - [63. Definicja entropii informacji i zastosowanie](#63-definicja-entropii-informacji-i-wybrane-zastosowanie-tego-pojęcia)
  - [64. Metody generacji reguł decyzyjnych](#64-metody-generacji-reguł-decyzyjnych)
  - [65. Uczenie się zespołowe](#65-uczenie-się-zespołowe)
- [Wprowadzenie do grafiki maszynowej](#wprowadzenie-do-grafiki-maszynowej)
  - [66. Modele barw](#66-modele-barw)
  - [67. Algorytmy rastrowe](#67-algorytmy-rastrowe)
  - [68. Formaty plików graficznych](#68-formaty-plików-graficznych)
  - [69. Przekształcenia afiniczne 3W](#69-przekształcenia-afiniczne-3w)
  - [70. Rzutowanie w grafice 3W](#70-rzutowanie-w-grafice-3w)
  - [71. Krzywe Béziera](#71-krzywe-béziera)
- [Problemy społeczne i zawodowe informatyki](#problemy-społeczne-i-zawodowe-informatyki)
  - [72. Trzy podstawowe obszary uzależnień komputerowych](#72-trzy-podstawowe-obszary-uzależnień-komputerowych)
  - [73. Ochrona własności intelektualnej vs patentowa](#73-zasadnicza-różnica-między-ochroną-własności-intelektualnej-i-ochroną-patentową)
  - [74. Szpiegostwo komputerowe](#74-szpiegostwo-komputerowe)

---

# Algorytmy i struktury danych

## 1. Pojęcie algorytmu i jego prezentacja
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 2. Metody szacowania złożoności obliczeniowej algorytmów. Złożoność czasowa, pamięciowa, asymptotyczna i benchmarking
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 3. Przykłady algorytmów sortowania i ich złożoność obliczeniowa
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 4. Drzewa poszukiwań binarnych. Podstawowe operacje na drzewach. Sposoby przechodzenia drzewa
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 5. Metody przeszukiwania grafów i wyznaczania najkrótszej ścieżki na przykładzie algorytmu Dijkstry
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 6. Abstrakcyjne struktury danych: listy, kolejki, stosy, słowniki
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 7. Strategia dziel i zwyciężaj, idea algorytmu zachłannego
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Architektura i organizacja komputerów

## 8. Reprezentacja liczb całkowitych i zmiennoprzecinkowych w systemach binarnym i szesnastkowym
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 9. Specyfika programowania niskopoziomowego
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 10. Obliczeniowe jednostki wykonawcze CPU, GPU, TPU, FPU
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Sieci komputerowe

## 11. Protokoły warstwy łącza danych, sieci oraz transportowej w modelu OSI
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 12. Przydzielanie adresów przez protokół DHCP
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 13. Wyliczanie adresów: sieci, maski, rozgłoszeniowego w IPv4, IPv6
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 14. System DNS
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Bazy danych

## 15. Klucze główne, klucze obce w bazach danych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 16. Diagram związków encji
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 17. Język baz danych SQL. Podjęzyki DDL, DML, DCL
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 18. Instrukcja SELECT, łączenie danych z wielu tabel
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Podstawy elektroniki i miernictwo elektroniczne

## 19. Diody półprzewodnikowe. Tranzystory
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 20. Układy scalone, impulsowe, cyfrowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 21. Przetworniki analogowo-cyfrowe i cyfrowo-analogowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Matematyka dyskretna

## 22. Schematy wyboru i tożsamości kombinatoryczne
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 23. Liniowe równania rekurencyjne
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 24. Grafy i ich własności
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Programowanie strukturalne

## 25. Typy zmiennych w językach programowania
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 26. Rodzaje pętli
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 27. Zmienne typu adresowego (wskaźniki). Zastosowanie w wybranym języku programowania
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 28. Funkcje. Przekazywanie parametrów przez wartość i referencję
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Wizualizacja danych

## 29. Definicja histogramu. Jakiego typu wykresu warto użyć do prezentacji?
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 30. Biblioteki wspierające tworzenie wykresów za pomocą języka Python
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 31. Omów koncepcję "czystych danych/tidy data"
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 32. Etapy analizy i wizualizacji danych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Programowanie obiektowe

## 33. Składniki klasy i modyfikatory dostępu
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 34. Obiekty a klasy, pojęcie hermetyzacji
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 35. Pola i metody statyczne w klasie
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 36. Dziedziczenie, polimorfizm, szablony klas
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 37. Klasy abstrakcyjne i interfejsy
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Systemy operacyjne

## 38. Procesy, wątki, zarządzanie procesami
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 39. Synchronizacja procesów współbieżnych. Semafory
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Inżynieria oprogramowania

## 40. Cykle projektowania i życia oprogramowania
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 41. Metody oraz strategie testowania oprogramowania
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Projektowanie systemów informatycznych

## 42. Metodologie wytwarzania systemów informatycznych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 43. Metody identyfikacji wymagań systemu informatycznego
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Podstawy logiki, algebra, analiza, metody probabilistyczne

## 44. Działania na zbiorach
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 45. Rachunek zdań
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 46. Działania na macierzach
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 47. Układy równań liniowych – twierdzenie Kroneckera-Capelliego
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 48. Pojęcie relacji i funkcji
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 49. Własności relacji: relacje porządkujące; relacje równoważności
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 50. Własności funkcji: miejsca zerowe, ciągłość, pochodna
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 51. Zmienna losowa i jej charakterystyki liczbowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Programowanie deklaratywne

## 52. Definicje unifikatora (podstawienia uzgadniającego), najogólniejszego unifikatora, algorytm unifikacji i twierdzenie o unifikacji
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 53. Budowa programu w Prologu: klauzule (fakty, reguły), definicje predykatów. Sposób realizacji programu
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Technika cyfrowa

## 54. Systemy (zestawy) funkcjonalnie pełne
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 55. Elementy pamięciowe stosowane w układach sekwencyjnych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 56. Rodzaje układów sekwencyjnych, różnice w procedurach ich projektowania
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Systemy wbudowane

## 57. Mikrokontrolery i systemy wbudowane
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 58. Tryby adresowania rozkazów mikrokontrolera
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 59. Rodzaje transmisji szeregowej
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Sztuczna inteligencja i metody inżynierii wiedzy

## 60. Model obliczeniowy perceptronu
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 61. Metody uczenia sieci neuronowych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 62. Mechanizm działania algorytmu genetycznego
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 63. Definicja entropii informacji i wybrane zastosowanie tego pojęcia
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 64. Metody generacji reguł decyzyjnych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 65. Uczenie się zespołowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Wprowadzenie do grafiki maszynowej

## 66. Modele barw
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 67. Algorytmy rastrowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 68. Formaty plików graficznych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 69. Przekształcenia afiniczne 3W
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 70. Rzutowanie w grafice 3W
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 71. Krzywe Béziera
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

---

# Problemy społeczne i zawodowe informatyki

## 72. Trzy podstawowe obszary uzależnień komputerowych
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 73. Zasadnicza różnica między ochroną własności intelektualnej i ochroną patentową
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**

## 74. Szpiegostwo komputerowe
**Odpowiedź:**
> **Tu wpisujesz swoją odpowiedź**
