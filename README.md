# PythonCookbook

Moje reposytorium jest pod linkiem https://github.com/beardydeer/PythonCookbook oraz nazywa się [beardydeer/PythonCookbook](https://github.com/beardydeer/PythonCookbook)

Moj plan na ten tydzien

|    | P  | W  | S | C    | P   | S | N |
|----|----|----|---|------|-----|---|---|
| 5  | 1  | 2  | 3 | 4    | 5   |   |   |
| 6  | al | m  | a | kota |     |   |   |
| 7  | ha | ha |   | a ty | nie |   |   |
| 8  |    |    |   |      |     |   |   |
| 9  |    |    |   |      |     |   |   |
| 10 |    |    |   |      |     |   |   |
|    |    |    |   |      |     |   |   |
|    |    |    |   |      |     |   |   |
| 5  | 1  | 2  | 3 | 4    | 5   |   |   |
| 6  | al | m  | a | kota |     |   |   |
| 7  | ha | ha |   | a ty | nie |   |   |
| 8  |    |    |   |      |     |   |   |
| 9  |    |    |   |      |     |   |   |
| 10 |    |    |   |      |     |   |   |
|    |    |    |   |      |     |   |   |
|    |    |    |   |      |     |   |   |

## Jak uzywać git?

### Tworzenie nowego archiwum 

```shell
git init
```

![](2020-04-03-13-36-17.png)

> Co to zrobiło?

Utworzenie kopii archiwum na moim komputerze. 

### Ustawienie danych użytkownika

#### Ustawienie emailu

```shell
git config --global user.email "you@example.com"
```

#### Ustawianie nazwy użytkownika

```shell
git config --global user.name "Your Name"
```

### Jak połączyć lokalne archiwum ze źródłem na github.com (zdalne archiwum)?

```shell
git remonte add origin http://github.com/beardydeer/PythonCookbook.git
```

### Jak sprawdzić co jest zmodyfikowane?


```shell
git status
```

#### Jeden plik 

![](2020-04-03-13-09-16.png)

> Co to znaczy?

To znaczy że zmodyfikowano plik `README.md`. Ale ten plik nie jest zindeksowany (czerwony kolor), co jest nazywane brudnym plikiem. 

#### Wiele plików 

![](2020-04-03-14-01-26.png) 

> Co to znaczy?

To znaczy że zmodyfikowano pliki :

- `README.md` (zielony)
- `README.md` (czerwony)
- `2020-04-03-13-09-16.png` (czerwony)
- `2020-04-03-13-21-29.png` (czerwony)
- `2020-04-03-13-27-31.png` (czerwony)
- `2020-04-03-13-36-17.png` (czerwony)

Plik zielony jest zindeksowany, a pliki czerwone nie. Mamy sytuacje że plik `README.md` jest na zielono i czerwono. To znaczy że pewne zmiany w pliku `README.md` zindeksowane (`git add README.md`), a następnie pojawiły się nowe zmiany (brudne, czerwone). 


### Jak zidenksować moje modyfikacje?

#### Jeden plik (README.md)

```shell
git add README.md
```
> Co to znaczy?

To znaczy że modyfikacje w pliku `README.md` zideksowano.  

![](2020-04-03-13-21-29.png) 

> Ups jaki jest rezultat idenksowania, jak to sprawdzić?

```shell
git status
```

![](2020-04-03-13-27-31.png)

> O nie, nie wszystkie pliki są zindeksowane! Jak zindeksować wszystkie pliki?

#### Wszystkie pliki 

```shell
git add . 
```

# BRUDNOPIS

Jestem tutaj

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Rozdział 1 ....

Wcale nie


### Podrozdział 1 ...

![](2020-04-03-12-37-09.png)![](2020-04-03-12-37-09.png)

![](2020-04-03-12-37-27.png)


```py
print('Nie mam masła')

def maslo(ilosc, jakosc):
    print(ilosc, jakosc)
```

print('Nie mam masła')

def maslo(ilosc, jakosc):
    print(ilosc, jakosc)



#### Podpodrozdział 1 ....

##### ...

###### ....


