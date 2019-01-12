# Python - základy 1

## Materiály

*Není potřeba číst všechny materiály. Ovšem pokud není jasný nějaký koncept, doporučuji podívat se na více zdrojů. Každý z nich může vysvětlovat ho trochu jinak.*

1. Datové typy
  - [Slidy](https://docs.google.com/presentation/d/1T5EzaqzAVje3-8MpazjgXn4NVv0n4rcP2iVt97uPuGI/edit?usp=sharing)
  - [Dokumentace](https://docs.python.org/3.7/library/stdtypes.html?)
  - [Learn Python - Socratica](https://www.youtube.com/playlist?list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-)
  - [Sentdex - Python 3 Basics Tutorial Series](https://www.youtube.com/playlist?list=PLQVvvaa0QuDe8XSftW-RAxdo6OmaeL85M)
  - Celá čísla (`int`) a desetinná čísla (`float`)
    - [Dokumentace - `int`](https://docs.python.org/3.7/library/functions.html?highlight=int#int)
    - [Dokumentace - `float`](https://docs.python.org/3.7/library/functions.html?highlight=float#float)
    - [Tutorials point](https://docs.python.org/3.7/library/functions.html?highlight=float#float)
    - [W3schools](https://www.w3schools.com/python/python_numbers.asp)
  - Řetězce (`str`)
    - [Metoda `format`](https://pyformat.info/)
    - [Dokumentace](https://www.w3schools.com/python/python_numbers.asp)
    - [Pyladies](https://naucse.python.cz/2018/pyladies-praha-podzim-cznic/beginners/str/)
    - [Tutorials point](https://www.tutorialspoint.com/python/python_strings.htm)
    - [W3schools](https://www.w3schools.com/python/python_strings.asp)
  - Seznamy (`list`)
    - [Dokumentace](https://docs.python.org/3/tutorial/introduction.html#lists)
    - [Pyladies](https://naucse.python.cz/2018/pyladies-praha-podzim-cznic/beginners/list/)
    - [Tutorials point](https://www.tutorialspoint.com/python/python_lists.htm)
    - [W3schools](https://www.w3schools.com/python/python_lists.asp)
  - Slovníky (`dict`)
    - [Dokumentace](https://docs.python.org/3.7/library/stdtypes.html?highlight=dict%20built#dict)
    - [Pyladies](https://naucse.python.cz/2018/pyladies-praha-podzim-cznic/beginners/dict/)
    - [Tutorials point](https://www.tutorialspoint.com/python/python_dictionary.htm)
    - [W3schools](https://www.w3schools.com/python/python_dictionaries.asp)
  - N-tice (`tuple`)
    - [Dokumentace](https://docs.python.org/3.7/library/stdtypes.html?#tuples)
    - [Pyladies](https://naucse.python.cz/2018/pyladies-praha-podzim-cznic/beginners/tuple/)
    - [Tutorials point](https://www.tutorialspoint.com/python/python_tuples.htm)
    - [W3schools](https://www.w3schools.com/python/python_tuples.asp)
  - Množina (`set`)
    - [Dokumentace](https://docs.python.org/3.7/library/stdtypes.html?h#set-types-set-frozenset)
    - [Tutorials point](https://www.tutorialspoint.com/python/python_sets.htm)
    - [W3schools](https://www.w3schools.com/python/python_sets.asp)
2. Proměnné
  - [Tutorials point](https://www.tutorialspoint.com/python/python_variable_types.htm)
  - [W3schools](https://www.w3schools.com/python/python_variables.asp)
3. Podmínky
  - [Slidy](https://docs.google.com/presentation/d/1xH4evS4ovDHahGkN6slsUWncmxmtJBw54A9fkP75NTo/edit?usp=sharing)
  - [Tutorials point](https://www.tutorialspoint.com/python/python_if_else.htm)
  - [W3schools](https://www.w3schools.com/python/python_conditions.asp)
4.  Cykly
  - [Slidy](https://docs.google.com/presentation/d/1xH4evS4ovDHahGkN6slsUWncmxmtJBw54A9fkP75NTo/edit?usp=sharing)
  - [Pyladies](https://naucse.python.cz/2018/pyladies-praha-podzim-cznic/beginners/while/)
  - [Tutorials point](https://www.tutorialspoint.com/python/python_loops.htm)
  - [W3schools](https://www.w3schools.com/python/python_for_loops.asp)

## Cvičení

*Doporučuji během vyplnění cvíčení dělat poznámky pro následnou diskuzi a dovysvětlení.*

1.
  - Zadání
    - Vytísknout na obrazovku řetězec pozpátku
  - Příklad vstupu
    - `'python'`, `'apple'`, `'bob'`
  - Příklad výstupu
    - `'nohtyp'`, `'elppa'`, `'bob'`

2.
  - Zadání
    - Spojít seznam řětězců do jednoho řetězce
  - Příklad vstupu
    - `['L', 'e', 'n', 'k', 'a']`, `['1', '2', '3']`, `['a']`
  - Příklad výstupu
    - `'Lenka'`, `'123'`, `'a'`


3.
  - Zadání
    - Zjistít rozdíl mezi prvním a druhým seznamem
  - Příklad vstupu
    - `[1, 2, 3, 5, 7, 8]` a `[1, 2, 4, 5, 6, 8]`, `['a', 'c', 'd']` a `['d', 'a', 'b']`, `[1, 2, 3]` a `[1, 2, 3]`
  - Příklad výstupu
    - `[3, 7]`, `['c']`, `[]`


4.
  - Zadání
    - Přidát hodnoty druhého slovníku k prvnímu
  - Příklad vstupu
    - `{'a': 1, 'c': 2, 'd': 3}` a `{'e': 1, 'f': 15}`, `{'a': 1, 'c': 2, 'd': 3}` a `{'c': 1, 'f': 15}`, `{'a': 1, 'c': 2, 'd': 3}` a `{1: 'c', 2: 'b'}`
  - Příklad výstupu
    - `{'a': 1, 'c': 2, 'd': 3, 'e': 1, 'f': 15}`, `{'a': 1, 'c': 1, 'd': 3, 'f': 15}`, `{1: 'c', 2: 'b', 'a': 1, 'c': 2, 'd': 3}`


5.
  - Zadání
    - Sečíst všechny hodnoty ve slovníku
  - Příklad vstupu
    - `{'a': 1, 'c': 2, 'd': 3}`, `{'věk': 10, 'věk': 20}`, `{'hodnota': 100}`
  - Příklad výstupu
    - `6`, `20`, `100`

6.
  - Zadání
    - Najít nějkratší prvek seznamu
  - Příklad vstupu
    - `['jablka', 'hrušky', 'kiwi', 'ananas']`, `['abc', ['a', 'b'], 'lmn']`, `['abc', 'dce', 'lmn']`
  - Příklad výstupu
    - `'kiwi'`, `['a', 'b']`, `'abc'`


7.
  - Zadání
    - Vytvořit slovník ze seznamu, kde klíčem bude prvek seznamu a hodnotou jeho delka
  - Příklad vstupu
    - `['jablka', 'hrušky', 'kiwi', 'ananas']`, `['abc', ('a', 'b'), 'lmn']`, `['']`
  - Příklad výstupu
    - `{'ananas': 6, 'hrušky': 6, 'jablka': 6, 'kiwi': 4}`, `{('a', 'b'): 2, 'abc': 3, 'lmn': 3}`, `{'': 0}`


8.
  - Zadání
    - Vytisknout n-tici, kde první prvek je počet lichých čísel v seznamu a druhý prvek je počet sudých čísel 
  - Příklad vstupu
    - `[1, 2, 3]`, `[1, 3]`, `[0, 2, 3]`
  - Příklad výstupu
    - `(2, 1)`, `(2, 0)`, `(1, 2)`

9.
  - Zadání
    - Vytisknout samohlasky v řetězci velkými pismeny 
  - Příklad vstupu
    - `'python'`, `'ou'`, `'krk'`
  - Příklad výstupu
    - `'pythOn'`, `'OU'`, `'krk'`


10.
  - Zadání
    - Vytisknout počet hvězdiček (`*`) dle hodnot v seznamu
  - Příklad vstupu
    - `[1, 2, 3]`, `[5, 0, 5]`, ``
  - Příklad výstupu
``` 
*
**
***
```
, 
```
***
**
*
```
,

```
*****

*****
```
