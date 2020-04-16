# NN-and-KNN-classifiers

Implementacja algorytmu klasyfikacji liści przy wykorzystaniu klasyfikatorów NN (Najbliższych sąsiadów) oraz K-NN (K-najbliższych sąsiadów). Program dokonuje klasyfikacji typów liści na podstawie dwóch wybranych cech. Została pokazana także tablica pomyłek (confusion matrix). W projekcie został użyty język Python oraz biblioteki: sklearn, matplotlib, pandas. 

Poniższy obrazek reprezentuje zbiór danych (różnych typów liści) które następnie zostały podzielone na podzbiór testowy oraz podzbiór treningowy.

<img src="photo/zbiórdanych.PNG" alt="zbiór danych" width="100%" height="100%">  

Wykres przedstawia dwa gatunki liści (kolor zielony oraz niebieski) a także próbki mające być poddane klasyfikacji za pomocą klasyfikatora najbliższych sąsiadów.

<img src="photo/NNprzedklasyfikacja.PNG" alt="próbki przed klasyfikacją NN" width="500" height="300" >

Wynik działania klasyfikatora NN. Żółte próbki zostały przyporządkowane odpowiednim gatunkom liści. 

<img src="photo/NNpoklasyfikacji.PNG" alt="próbki po klasyfikacji NN" width="500" height="300"> 

Próbki przed klasyfikacją K-NN. Klasyfikator ten w odróżnieniu od poprzedniego dokonuje przyporządkowania na podstawie określonych kilku najbliższych sąsiadów a nie tylko jednej najbliższej próbki jak w przypadku NN.  

<img src="photo/KNNprzedklasyfikacja.PNG" alt="próbki przed klasyfikacją K-NN" width="500" height="300"> 

Próbki po klasyfikacją K-NN.

<img src="photo/KNNpoklasyfikacji.PNG" alt="próbki po klasyfikacji K-NN" width="500" height="300"> 



