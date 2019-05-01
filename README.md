1 Cel projektu 

Należy zaprojektować a następnie zaimplementować sekwencję operacji przetwarzania obrazów umożliwiającą policzenie obiektów (monet) znajdujących się na obrazie wejściowym oraz wyznaczenie sumy ich nominałów. 

2 Założenia projektowe 

Zakłada się, że obraz wejściowy jest kolorowy np. zdjęcie wykonane aparatem fotograficznym lub smartfonem. Dla ułatwienia można umieścić obiekty na jednolitym dowolnie wybranym podłożu, aby w miarę łatwo można było je oddzielić od tła. Algorytm powinien działać dla dowolnej liczby obiektów umieszczonych na zdjęciu. Dla celów testowych należy wykonać przynajmniej 15 zdjęć z różną liczbą obiektów, aby móc sprawdzić poprawność i dokładność działania algorytmu. Dodatkowe wymaganie techniczne: należy samodzielnie bez korzystania z funkcji bibliotecznych zaimplementować i wykorzystać w projekcie algorytm segmentacji i indeksacji np. metodą przez rozrost/podział obszaru (ang. region growing/splitting). Wybrane do analizy oraz wykonane obrazy wejściowe akceptuje prowadzący ćwiczenia. 

3 Wyniki ilościowe 

Należy zweryfikować poprawność i dokładność działania algorytmu i oszacować wynik w procentach. Dodatkowo należy policzyć jaki procent obszaru zdjęcia stanowią analizowane obiekty oraz wyznaczyć środek geometryczny masy tych obiektów (środek ciężkości). Dla każdego obiektu należy obliczyć współczynniki Fereta, Blaira-Blissa i Haralicka. Należy policzyć sumę nominałów monet znajdujących się na obrazie. 

4 Wyniki jakościowe 

Należy przygotować sprawozdanie z tego zadania projektowego zawierające: opis poszczególnych etapów przetwarzania, kody źródłowe oraz wyznaczone parametry. Sprawozdanie należy przygotować w formacie PDF. 

5 Implementacja 

Implementację należy wykonać w języku Python. Całość kodu należy dostarczyć w formacie notatnika typu Jupyter Notebook (*.ipynb). Notatnik powinien zawierać komentarze do kodu źródłowego. 2
