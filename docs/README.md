---
author: ankiedos
project: PLC++
---
# Spis Treści
* [1. Streszczenie](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Streszczenie)
* [1.1. Cpp.hpp](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Cpp.hpp)
  * [1.1.1. Typy Podstawowe](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Typy%2BPodstawowe)
* [1.2. Funkcje.hpp](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Funkcje.cpp)
  * [1.2.1. Funkcje::Zwroc()](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Funkce::Zwroc())
* [1.3. Mat.cpp](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Mat.cpp)
  * [1.3.1. Średnie](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/docs/README.md#Średnie)
# Streszczenie
## Patrz również: [Streszczenie streszczenia](https://github.com/Programista-Cpp/Sposzczone-jezyki-programowania/tree/master/README.md)
## Cpp.hpp
### Dołączanie
> Musisz dołączyć `Cpp.hpp` po wszystkich innych bibliotekach, ponieważ korzysta ona z "include guardów" tych bibliotek, np.:
> ```c++
> #include<iostream>
> #include<vector>
> #include<map>
> #include "Cpp.hpp"
> ```
> Jeśli masz dostęp do eksperymentalnej wersji standardu C++2b (nieważne jak zdobyłeś :smile:), w której jest:
> * std::ranges::accumulate();
> * lub std::colony;

Musisz zdefiniować

> ```c++
> #define __CPP_2b
> ```
### Typy Podstawowe


## Funkcje.cpp

### Funkcje::Zwroc()


## Mat.cpp

### Średnie
