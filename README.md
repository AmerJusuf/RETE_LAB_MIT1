# RETE_LAB_MIT1
Rendszertervezés laboratórium, MIT1 mérés.
## 1. Feladat
Az előkészületeket elvégeztük
## 2. Feladat
### 2.1-2.2
A feladatleírást követve az alábbi kimenetet kaptuk:

![2 2](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/e420501c-7fd2-4d31-8985-1d5ae790f42f)

### 2.3
Kiegészítettük az alkalmazást, hogy az állapotok mellett a tranzíciókat is kiírja:
A kódban a statet lecseréltük transitionra, és a transition source-ját és target-jét irattuk ki.

![2 3](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/4e0c462b-7376-4860-a2c6-2023712e3e65)

### 2.4 - 2.5 
A csapda állapotok kiiratása:
Új statet adtunk a rendszerhez (NoKi), amibe a "Black" stateből megy tranzakció, de belőle nem vezet ki.

Az állapotokon végig iterálva a getName().isEmpty() fügvénnyel kerestük meg azokat az állapotokat amiknek nincs nevük, ezeknek új nevet adtunk:

![2 5](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/583f695a-e945-4d3c-91e4-d1aa9f4cdef5)




