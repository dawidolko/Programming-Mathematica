# PROJEKT
Temat: Projekt o orbitach: Księżyc przedstawiony na wykresie 3D oraz animacja ruchu Marsa na tle gwiazd widziany z Ziemi
Autorzy: Dawid Olko, Michał Jacek Pilecki, 1 rok Informatyka gr.III
 
Projekt ten składa się z dwóch części: wykresu 3D orbity Księżyca wokół Ziemi oraz animacji ruchu Marsa na tle gwiazd widziany z Ziemi. W obu przypadkach użyto języka programowania Mathematica.
 
## Wykres 3D orbity Księżyca
W pierwszym etapie projektu obliczono parametry orbity Księżyca, takie jak półoś wielka (a), półoś mała (b), mimośród (e) oraz okres orbitalny (T). W celu obliczenia tych parametrów użyto stałej grawitacyjnej (G), masy Ziemi (M) i Księżyca (m), średniej odległości Księżyca od Ziemi (r) oraz średniej prędkości Księżyca (v). Następnie stworzono wykres 3D orbity Księżyca, który uwzględnia półoś wielką (a) i półoś małą (b).
 
## Animacja ruchu Marsa na tle gwiazd widziany z Ziemi
Animacja ruchu Marsa została stworzona za pomocą funkcji Manipulate w języku Mathematica. W animacji wykorzystano rotację wokół osi Y, aby pokazać zmieniającą się pozycję Marsa na tle gwiazd. Wszystkie elementy graficzne, takie jak gwiazdy, zostały wygenerowane losowo, a tekst i kolor tła zostały dostosowane do potrzeb projektu.
 
## W celu stworzenia animacji użyto następujących funkcji:
 
Manipulate: tworzenie interaktywnych wizualizacji z suwakami
Grid: organizowanie elementów graficznych w siatkę (tablicę)
Labeled: dodanie etykiety do elementu graficznego
Graphics3D: tworzenie grafik trójwymiarowych
ParametricPlot3D: tworzenie trójwymiarowego wykresu parametrycznego
Show: łączenie kilku wykresów lub elementów graficznych w jednym
W projekcie użyto również funkcji do inicjalizacji wartości przed uruchomieniem głównego kodu (Initialization), takich jak SeedRandom (ustawienie ziarna losowania dla funkcji generujących liczby losowe) oraz stars (generowanie gwiazd jako losowych punktów na płaszczyźnie).
 
Dokumentacja ta opisuje strukturę i funkcje użyte w projekcie, który składa się z dwóch części: wykresu 3D orbity Księżyca wokół Ziemi oraz animacji ruchu Marsa na tle gwiazd widziany z Ziemi.



# Główne funkcje użyte w projekcie
Ten kod to interaktywna wizualizacja pokazująca ruch Marsa na tle gwiazd, gdy jest obserwowany z Ziemi. Wykorzystuje funkcję Manipulate, która pozwala na interakcje z wizualizacją poprzez zmianę wartości parametru czasowego. Oto opis poszczególnych części kodu:
 
Manipulate - funkcja, która pozwala na interaktywne zmienianie wykresu poprzez zmianę wartości parametrów.

Grid - pozwala na wyświetlenie kilku obiektów graficznych w siatce (w tym przypadku dwóch różnych wizualizacji 3D).
 
Labeled - funkcja, która pozwala na dodanie etykiety do obiektu graficznego. Tutaj dodaje opis do wykresu z góry.
 
Graphics3D - pozwala na tworzenie trójwymiarowych obiektów graficznych.
 
Sphere - funkcja, która pozwala na generowanie sferycznych obiektów 3D.
 
RotationMatrix - funkcja do tworzenia macierzy obrotu w przestrzeni 3D.
 
ParametricPlot3D - funkcja generująca trójwymiarowy wykres parametryczny.
 
PlotStyle - pozwala na dostosowanie stylu linii wykresu, takiego jak grubość, przerywanie i kolor.
 
Lighting - funkcja służąca do dostosowywania oświetlenia w trójwymiarowych wykresach.
 
ViewVector, ViewPoint, ViewVertical, ViewAngle - funkcje służące do kontrolowania perspektywy i kąta widzenia w trójwymiarowych wykresach.
 
Boxed, SphericalRegion - funkcje służące do kontrolowania wyświetlania osi i regionu wykresu 3D.
 
Initialization - blok inicjalizacyjny, który definiuje zmienne potrzebne do działania wizualizacji (tutaj generuje pozycje gwiazd na tle).
