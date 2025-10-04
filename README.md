# PYTANIA NA EGZAMIN DYPLOMOWY, STUDIA I STOPNIA INŻYNIERSKIE KIERUNEK INFORMATYKA

# Spis treści
- [Algorytmy i struktury danych](#algorytmy-i-struktury-danych)
  - [1. Pojęcie algorytmu i jego prezentacja](#1-pojecie-algorytmu-i-jego-prezentacja)
  - [2. Metody szacowania złożoności obliczeniowej algorytmów](#2-metody-szacowania-zlozonosci-obliczeniowej-algorytmow)
  - [3. Przykłady algorytmów sortowania](#3-przyklady-algorytmow-sortowania)
  - [4. Drzewa poszukiwań binarnych](#4-drzewa-poszukiwan-binarnych)
  - [5. Metody przeszukiwania grafów i algorytm Dijkstry](#5-metody-przeszukiwania-grafow-i-algorytm-dijkstry)
  - [6. Abstrakcyjne struktury danych](#6-abstrakcyjne-struktury-danych)
  - [7. Strategia dziel i zwyciężaj, algorytmy zachłanne](#7-strategia-dziel-i-zwyciężaj-algorytmy-zachlane)
- [Architektura i organizacja komputerów](#architektura-i-organizacja-komputerow)
  - [8. Reprezentacja liczb całkowitych i zmiennoprzecinkowych](#8-reprezentacja-liczb-calkowitych-i-zmiennoprzecinkowych)
  - [9. Specyfika programowania niskopoziomowego](#9-specyfika-programowania-niskopoziomowego)
  - [10. Obliczeniowe jednostki wykonawcze CPU, GPU, TPU, FPU](#10-obliczeniowe-jednostki-wykonawcze-cpu-gpu-tpu-fpu)
- [Sieci komputerowe](#sieci-komputerowe)
  - [11. Protokoły warstwy łącza danych, sieci i transportowej](#11-protokoly-warstwy-lacza-danych-sieci-i-transportowej)
  - [12. Przydzielanie adresów przez DHCP](#12-przydzielanie-adresow-przez-dhcp)
  - [13. Wyliczanie adresów sieci, maski, rozgłoszeniowego w IPv4, IPv6](#13-wyliczanie-adresow-sieci-mask-rozgłoszeniowego-w-ipv4-ipv6)
  - [14. System DNS](#14-system-dns)
- [Bazy danych](#bazy-danych)
  - [15. Klucze główne i obce](#15-klucze-glowne-i-obce)
  - [16. Diagram związków encji](#16-diagram-zwiazkow-encji)
  - [17. Język SQL i podjęzyki DDL, DML, DCL](#17-jezyk-sql-i-podjezyki-ddl-dml-dcl)
  - [18. Instrukcja SELECT i łączenie tabel](#18-instrukcja-select-i-laczenie-tabel)
- [Podstawy elektroniki i miernictwo elektroniczne](#podstawy-elektroniki-i-miernictwo-elektroniczne)
  - [19. Diody półprzewodnikowe, tranzystory](#19-diody-polprzewodnikowe-tranzystory)
  - [20. Układy scalone, impulsowe, cyfrowe](#20-uklady-scalone-impulsowe-cyfrowe)
  - [21. Przetworniki ADC i DAC](#21-przetworniki-adc-i-dac)
- [Matematyka dyskretna](#matematyka-dyskretna)
  - [22. Schematy wyboru i tożsamości kombinatoryczne](#22-schematy-wyboru-i-tozsamosci-kombinatoryczne)
  - [23. Liniowe równania rekurencyjne](#23-liniowe-rownania-rekurencyjne)
  - [24. Grafy i ich własności](#24-grafy-i-ich-wlasnosci)
- [Programowanie strukturalne](#programowanie-strukturalne)
  - [25. Typy zmiennych](#25-typy-zmiennych)
  - [26. Rodzaje pętli](#26-rodzaje-petli)
  - [27. Zmienne typu adresowego (wskaźniki)](#27-zmienne-typu-adresowego-wskazniki)
  - [28. Funkcje, przekazywanie parametrów](#28-funkcje-przekazywanie-parametrow)
- [Wizualizacja danych](#wizualizacja-danych)
  - [29. Definicja histogramu i typ wykresu](#29-definicja-histogramu-i-typ-wykresu)
  - [30. Biblioteki do tworzenia wykresów w Python](#30-biblioteki-do-tworzenia-wykresow-w-python)
  - [31. Koncepcja "czystych danych/tidy data"](#31-koncepcja-czystych-danychtidy-data)
  - [32. Etapy analizy i wizualizacji danych](#32-etapy-analizy-i-wizualizacji-danych)
- [Programowanie obiektowe](#programowanie-obiektowe)
  - [33. Składniki klasy i modyfikatory dostępu](#33-skladniki-klasy-i-modyfikatory-dostepu)
  - [34. Obiekty a klasy, hermetyzacja](#34-obiekty-a-klasy-hermetyzacja)
  - [35. Pola i metody statyczne](#35-pola-i-metody-statyczne)
  - [36. Dziedziczenie, polimorfizm, szablony klas](#36-dziedziczenie-polimorfizm-szablony-klas)
  - [37. Klasy abstrakcyjne i interfejsy](#37-klasy-abstrakcyjne-i-interfejsy)
- [Systemy operacyjne](#systemy-operacyjne)
  - [38. Procesy, wątki, zarządzanie procesami](#38-procesy-watki-zarzadzanie-procesami)
  - [39. Synchronizacja procesów współbieżnych, semafory](#39-synchronizacja-procesow-wspolbieznych-semafory)
- [Inżynieria oprogramowania](#inzynieria-oprogramowania)
  - [40. Cykle projektowania i życia oprogramowania](#40-cykle-projektowania-i-zycia-oprogramowania)
  - [41. Metody i strategie testowania](#41-metody-i-strategie-testowania)
- [Projektowanie systemów informatycznych](#projektowanie-systemow-informatycznych)
  - [42. Metodologie wytwarzania systemów](#42-metodologie-wytwarzania-systemow)
  - [43. Metody identyfikacji wymagań](#43-metody-identyfikacji-wymagan)
- [Podstawy logiki, algebra, analiza, metody probabilistyczne](#podstawy-logiki-algebra-analiza-metody-probabilistyczne)
  - [44. Działania na zbiorach](#44-dzialania-na-zbiorach)
  - [45. Rachunek zdań](#45-rachunek-zdan)
  - [46. Działania na macierzach](#46-dzialania-na-macierzach)
  - [47. Układy równań liniowych – twierdzenie Kroneckera-Capelliego](#47-uklady-rownan-liniowych-twierdzenie-kroneckera-capelliego)
  - [48. Pojęcie relacji i funkcji](#48-pojecie-relacji-i-funkcji)
  - [49. Własności relacji](#49-wlasnosci-relacji)
  - [50. Własności funkcji](#50-wlasnosci-funkcji)
  - [51. Zmienna losowa i jej charakterystyki](#51-zmienna-losowa-i-jej-charakterystyki)
- [Programowanie deklaratywne](#programowanie-deklaratywne)
  - [52. Definicje unifikatora, algorytm unifikacji](#52-definicje-unifikatora-algorytm-unifikacji)
  - [53. Budowa programu w Prologu](#53-budowa-programu-w-prologu)
- [Technika cyfrowa](#technika-cyfrowa)
  - [54. Systemy funkcjonalnie pełne](#54-systemy-funkcjonalnie-pelne)
  - [55. Elementy pamięciowe w układach sekwencyjnych](#55-elementy-pamieciowe-w-ukladach-sekwencyjnych)
  - [56. Rodzaje układów sekwencyjnych](#56-rodzaje-ukladow-sekwencyjnych)
- [Systemy wbudowane](#systemy-wbudowane)
  - [57. Mikrokontrolery i systemy wbudowane](#57-mikrokontrolery-i-systemy-wbudowane)
  - [58. Tryby adresowania rozkazów mikrokontrolera](#58-tryby-adresowania-rozskazow-mikrokontrolera)
  - [59. Rodzaje transmisji szeregowej](#59-rodzaje-transmisji-szeregowej)
- [Sztuczna inteligencja i metody inżynierii wiedzy](#sztuczna-inteligencja-i-metody-inzynierii-wiedzy)
  - [60. Model obliczeniowy perceptronu](#60-model-obliczeniowy-perceptronu)
  - [61. Metody uczenia sieci neuronowych](#61-metody-uczenia-sieci-neuronowych)
  - [62. Mechanizm działania algorytmu genetycznego](#62-mechanizm-dzialania-algorytmu-genetycznego)
  - [63. Definicja entropii informacji i zastosowanie](#63-definicja-entropii-informacji-i-zastosowanie)
  - [64. Metody generacji reguł decyzyjnych](#64-metody-generacji-regul-decyzyjnych)
  - [65. Uczenie się zespołowe](#65-uczenie-sie-zespolowe)
- [Wprowadzenie do grafiki maszynowej](#wprowadzenie-do-grafiki-maszynowej)
  - [66. Modele barw](#66-modele-barw)
  - [67. Algorytmy rastrowe](#67-algorytmy-rastrowe)
  - [68. Formaty plików graficznych](#68-formaty-plikow-graficznych)
  - [69. Przekształcenia afiniczne 3W](#69-przeksztalcenia-afiniczne-3w)
  - [70. Rzutowanie w grafice 3W](#70-rzutowanie-w-grafice-3w)
  - [71. Krzywe Béziera](#71-krzywe-beziera)
- [Problemy społeczne i zawodowe informatyki](#problemy-spoleczne-i-zawodowe-informatyki)
  - [72. Trzy podstawowe obszary uzależnień komputerowych](#72-trzy-podstawowe-obszary-uzaleznien-komputerowych)
  - [73. Ochrona własności intelektualnej vs patentowa](#73-ochrona-wlasnosci-intelektualnej-vs-patentowa)
  - [74. Szpiegostwo komputerowe](#74-szpiegostwo-komputerowe)

# Algorytmy i struktury danych

## 1. Pojęcie algorytmu i jego prezentacja
**Odpowiedź:**

## 2. Metody szacowania złożoności obliczeniowej algorytmów
**Odpowiedź:**

## 3. Przykłady algorytmów sortowania
**Odpowiedź:**

## 4. Drzewa poszukiwań binarnych
**Odpowiedź:**

## 5. Metody przeszukiwania grafów i algorytm Dijkstry
**Odpowiedź:**

## 6. Abstrakcyjne struktury danych
**Odpowiedź:**

## 7. Strategia dziel i zwyciężaj, algorytmy zachłanne
**Odpowiedź:**

# Architektura i organizacja komputerów

## 8. Reprezentacja liczb całkowitych i zmiennoprzecinkowych
**Odpowiedź:**

## 9. Specyfika programowania niskopoziomowego
**Odpowiedź:**

## 10. Obliczeniowe jednostki wykonawcze CPU, GPU, TPU, FPU
**Odpowiedź:**

# Sieci komputerowe

## 11. Protokoły warstwy łącza danych, sieci i transportowej
**Odpowiedź:**

## 12. Przydzielanie adresów przez DHCP
**Odpowiedź:**

## 13. Wyliczanie adresów sieci, maski, rozgłoszeniowego w IPv4, IPv6
**Odpowiedź:**

## 14. System DNS
**Odpowiedź:**

# Bazy danych

## 15. Klucze główne i obce
**Odpowiedź:**

## 16. Diagram związków encji
**Odpowiedź:**

## 17. Język SQL i podjęzyki DDL, DML, DCL
**Odpowiedź:**

## 18. Instrukcja SELECT i łączenie tabel
**Odpowiedź:**

# Podstawy elektroniki i miernictwo elektroniczne

## 19. Diody półprzewodnikowe, tranzystory
**Odpowiedź:**

## 20. Układy scalone, impulsowe, cyfrowe
**Odpowiedź:**

## 21. Przetworniki ADC i DAC
**Odpowiedź:**

# Matematyka dyskretna

## 22. Schematy wyboru i tożsamości kombinatoryczne
**Odpowiedź:**

## 23. Liniowe równania rekurencyjne
**Odpowiedź:**

## 24. Grafy i ich własności
**Odpowiedź:**

# Programowanie strukturalne

## 25. Typy zmiennych
**Odpowiedź:**

## 26. Rodzaje pętli
**Odpowiedź:**

## 27. Zmienne typu adresowego (wskaźniki)
**Odpowiedź:**

## 28. Funkcje, przekazywanie parametrów
**Odpowiedź:**

# Wizualizacja danych

## 29. Definicja histogramu i typ wykresu
**Odpowiedź:**

## 30. Biblioteki do tworzenia wykresów w Python
**Odpowiedź:**

## 31. Koncepcja "czystych danych/tidy data"
**Odpowiedź:**

## 32. Etapy analizy i wizualizacji danych
**Odpowiedź:**

# Programowanie obiektowe

## 33. Składniki klasy i modyfikatory dostępu
**Odpowiedź:**

## 34. Obiekty a klasy, hermetyzacja
**Odpowiedź:**

## 35. Pola i metody statyczne
**Odpowiedź:**

## 36. Dziedziczenie, polimorfizm, szablony klas
**Odpowiedź:**

## 37. Klasy abstrakcyjne i interfejsy
**Odpowiedź:**

# Systemy operacyjne

## 38. Procesy, wątki, zarządzanie procesami
**Odpowiedź:**

## 39. Synchronizacja procesów współbieżnych, semafory
**Odpowiedź:**

# Inżynieria oprogramowania

## 40. Cykle projektowania i życia oprogramowania
**Odpowiedź:**

## 41. Metody i strategie testowania
**Odpowiedź:**

# Projektowanie systemów informatycznych

## 42. Metodologie wytwarzania systemów
**Odpowiedź:**

## 43. Metody identyfikacji wymagań
**Odpowiedź:**

# Podstawy logiki, algebra, analiza, metody probabilistyczne

## 44. Działania na zbiorach
**Odpowiedź:**

## 45. Rachunek zdań
**Odpowiedź:**

## 46. Działania na macierzach
**Odpowiedź:**

## 47. Układy równań liniowych – twierdzenie Kroneckera-Capelliego
**Odpowiedź:**

## 48. Pojęcie relacji i funkcji
**Odpowiedź:**

## 49. Własności relacji
**Odpowiedź:**

## 50. Własności funkcji
**Odpowiedź:**

## 51. Zmienna losowa i jej charakterystyki
**Odpowiedź:**

# Programowanie deklaratywne

## 52. Definicje unifikatora, algorytm unifikacji
**Odpowiedź:**

## 53. Budowa programu w Prologu
**Odpowiedź:**

# Technika cyfrowa

## 54. Systemy funkcjonalnie pełne
**Odpowiedź:**

## 55. Elementy pamięciowe w układach sekwencyjnych
**Odpowiedź:**

## 56. Rodzaje układów sekwencyjnych
**Odpowiedź:**

# Systemy wbudowane

## 57. Mikrokontrolery i systemy wbudowane
**Odpowiedź:**

## 58. Tryby adresowania rozkazów mikrokontrolera
**Odpowiedź:**

## 59. Rodzaje transmisji szeregowej
**Odpowiedź:**

# Sztuczna inteligencja i metody inżynierii wiedzy

## 60. Model obliczeniowy perceptronu
**Odpowiedź:**

## 61. Metody uczenia sieci neuronowych
**Odpowiedź:**

## 62. Mechanizm działania algorytmu genetycznego
**Odpowiedź:**

## 63. Definicja entropii informacji i zastosowanie
**Odpowiedź:**

## 64. Metody generacji reguł decyzyjnych
**Odpowiedź:**

## 65. Uczenie się zespołowe
**Odpowiedź:**

# Wprowadzenie do grafiki maszynowej

## 66. Modele barw
**Odpowiedź:**

## 67. Algorytmy rastrowe
**Odpowiedź:**

## 68. Formaty plików graficznych
**Odpowiedź:**

## 69. Przekształcenia afiniczne 3W
**Odpowiedź:**

## 70. Rzutowanie w grafice 3W
**Odpowiedź:**

## 71. Krzywe Béziera
**Odpowiedź:**

# Problemy społeczne i zawodowe informatyki

## 72. Trzy podstawowe obszary uzależnień komputerowych
**Odpowiedź:**

## 73. Ochrona własności intelektualnej vs patentowa
**Odpowiedź:**

## 74. Szpiegostwo komputerowe
**Odpowiedź:**
