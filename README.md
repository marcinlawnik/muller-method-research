# muller-method-research
A method for finding polynomial roots


## Materiały
### Opis metody:
[http://mech.utah.edu/~pardyjak/me2040/Lect5_RootsofPolynomials.pdf]
### Algorytm działania
[http://www.physics.arizona.edu/~restrepo/475A/Notes/sourcea-/node25.html]


## Instrukcja krótka:

- Dobieramy 3 punkty na przebiegu badanej funkcji i opieramy na nich parabolę
- Znajdujemy współczynniki tej paraboli, które sprawiają że przechodzi przez te 3 punkty
- Wyznaczamy punkt przecięcia paraboli z osią x, ten punkt jest przybliżeniem miejsca zerowego funkcji
- Używając wyznaczonego punktu, oraz dwóch poprzednich punktów, powtarzamy kroki 1-3 w celu uzyskania dokładniejszego wyniku

![obraz](https://user-images.githubusercontent.com/718163/32727575-429d060e-c87d-11e7-9187-9cc1b22cf17f.png)


## Algorytm

![obraz](https://user-images.githubusercontent.com/718163/32727758-080f5bc6-c87e-11e7-9bcb-a76652a09249.png)

## Przykład obliczeniowy

![img_20171113_141900_1](https://user-images.githubusercontent.com/718163/32727843-6aa1de80-c87e-11e7-9909-9557afd859ed.jpg)


## Program

`Source: http://www.geeksforgeeks.org/program-muller-method/`

In file mueller.cpp


### Użycie programu i sprawdzenie dokładności

![obraz](https://user-images.githubusercontent.com/718163/32728270-ebbc9b3a-c87f-11e7-92d2-67c2c1457c12.png)

Program dla danego wielomianu jest całkiem dokładny.
