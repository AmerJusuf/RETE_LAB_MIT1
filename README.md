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
Új statet adtunk a rendszerhez, amibe a "Black" stateből megy tranzakció, de belőle nem vezet ki.

Az állapotokon végig iterálva a getName().isEmpty() fügvénnyel kerestük meg azokat az állapotokat amiknek nincs nevük, ezeknek új nevet adtunk:

![2 5](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/583f695a-e945-4d3c-91e4-d1aa9f4cdef5)

## 3. Feladat
### 3.1 - 3.2
- InterFaceObserveSupport: Öröklést engedélyezi vagy letiltja a listener interfaceknel
- RuntTimeService: Engedélyezi vagy letiltja a ciklusok léptetését
- TimerService: Engedélyezi vagy letiltja a timert (after 1 s)

### 3.3 - 3.4 

![3 4](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/ba91b037-f697-4a0a-8f12-e5854ad418d4)

### 3.5 - 3.6
While ciklusban beolvasunk egy stringet, ha a bemenet "exit", a ciklusból kilépünk, ha a string egyezik egy esemény nevével, meghívjuk a megfelelő eseményt:

![3 6](https://github.com/AmerJusuf/RETE_LAB_MIT1/assets/113386462/77feef6a-edec-46d0-b62a-571c3744d7f4)

## 4. Fealadat

### 4.1 
A gráf sokkal kiterjedtebb lett.

### 4.2
A képen látható a whiteTime-=1 kifejezés absztrakt szintaxis
fája:


### 4.3
A 2-es feladatban kiegészített kódrészletben, az elemeken végig iterálva az instanceof EventDefinition és a VariableDefinition típusokat kiirattuk:


### 4.4 - 4.7
A változók nevei és bemenő események nevei alapján a konzolra kiír egy szöveget, amely java
kódként értelmezve az a 3.5-ös feladat általánosítását végzi el. 


  

