# Interview_Testing_PL
🟣 Interview questions and answers to help you prepare for your next technical tester interview in 2025.

# Python

Spis treści

- [**P_Q1**](#P_Q1) **- List vs Tuple vs Array vs Set vs Dict**
- [**P_Q2**](#P_Q2) **- Jakim językiem jest python? Czy jest językiem skryptowym?**
- [**P_Q3**](#P_Q3) **- Czym jest PEP 8?**
- [**P_Q4**](#P_Q4) **- Czy python jest językiem interpretowanym?  Wyjaśnij.**
- [**P_Q5**](#P_Q5) **- Czym są dekoratory w Pythonie?**
- [**P_Q6**](#P_Q6) **- Czym są list of comprehensions i dict of comprehensions?**
 
## P_Q1 - List vs Tuple vs Array vs Set vs Dict

| List | Tuple | Array | Set | Dict |
|-----------|-----------|-----------|-----------|-----------|
| Wartość 1 | Wartość 2 | Wartość 3 |Wartość 3 |Wartość 3 |
| Wartość A | Wartość B | Wartość C | Wartość C | Wartość C |

## P_Q2 - Jakim językiem jest python? Czy jest językiem skryptowym?

## P_Q3 - Czym jest PEP 8?
PEP oznacza Python Enhancement Proposal. Jest to zestaw zasad określających, jak formatować kod w Pythonie, aby był maksymalnie czytelny.

## P_Q4 - Czy python jest językiem interpretowanym?  Wyjaśnij.

Język interpretowany to każdy język programowania, który nie jest przekształcany na kod maszynowy przed uruchomieniem. Dlatego Python jest językiem interpretowanym.

## P_Q5 - Czym są dekoratory w Pythonie?

Dekoratory służą do dodawania wzorców projektowych do funkcji bez zmieniania jej struktury. Dekoratory zazwyczaj są definiowane przed funkcją, którą mają ulepszyć. Aby zastosować dekorator, najpierw definiujemy funkcję dekoratora. Następnie piszemy funkcję, do której ma zostać zastosowany dekorator, i dodajemy funkcję dekoratora powyżej tej funkcji. W tym celu używamy symbolu @ przed dekoratorem.

## P_Q6 - Czym są list of comprehensions i dict of comprehensions?

List of comprehensions i dict of comprehensions to kolejny, bardziej zwięzły sposób definiowania słowników i list w Pythonie.
Przykład list of comprehensions:

```python
x = [i for i in range(5)]
```

Powoduje to utworzenie listy:


```python
[0, 1, 2, 3, 4]
```

Przykład komprehensji słownika:

```python
x = {i: i + 2 for i in range(5)}  
```
Powoduje to utworzenie słownika:

```python
{0: 2, 1: 3, 2: 4, 3: 5, 4: 6}  
```
