# Wprowadzenie do Data Science — Portfolio Studenta

Dokumentacja repozytorium ćwiczeniowego ze studiów podyplomowych.  
Prowadzący: dr inż. Krzysztof Ropiak  
Rok akademicki: 2026/2027

## 1. O projekcie

W tym repozytorium gromadzę skrypty w języku Python 3.14 oraz notatniki Jupyter realizowane w ramach przedmiotu.

Samuel   
Liotta

Głównym celem przedmiotu jest opanowanie **solidnych podstaw języka Python** oraz narzędzi pracy analityka danych, takich jak *Jupyter Notebook*, *Git* oraz biblioteka ***pandas 3.0***.

> Zasada przewodnia kursu (PEP 20 — *The Zen of Python*): > „Readability counts. Explicit is better than implicit.”

## 2. Wykorzystywane narzędzia i postęp prac

### 2.1. Narzędzia w projekcie
1. Środowisko wykonawcze i pakiety:
   - interpreter **CPython 3.14**,
   - menedżer pakietów i środowisk wirtualnych **uv**,
   - biblioteki analityczne:
     - `pandas` (>= 3.0),
     - `matplotlib` oraz `seaborn`.
2. Narzędzia deweloperskie:
   - edytor **Visual Studio Code**,
   - system kontroli wersji **Git** oraz serwis **GitHub**.

### 2.2. Status realizacji modułów
- [x] Moduł 0: Konfiguracja środowiska pracy i Jupyter Notebook
- [x] Moduł 1: Warsztat Git, Markdown oraz standard PEP 8
- [ ] Moduł 2: Typy danych, operatory i łańcuchy znaków
- [ ] Moduł 3: Kolekcje w języku Python

## 3. Szybki start (Uruchomienie środowiska)

Aby odtworzyć środowisko wirtualne `.venv` na podstawie pliku `pyproject.toml`, wykonaj w terminalu:

```bash
git clone https://github.com/twoj-login/wds-git-lab.git
cd wds-git-lab
uv sync
```

Przykładowy kod weryfikujący wersję biblioteki `pandas` w Pythonie 3.14:

```python
import pandas as pd

print(f"Zainstalowana wersja pandas: {pd.__version__}")
```

## 4. Podręczna tabela komend i dokumentacja

| Narzędzie | Polecenie | Zastosowanie | Liczba kroków |
| :--- | :--- | :--- | ---: |
| Git | `git status` | Sprawdzenie stanu plików w katalogu roboczym | 1 |
| Git | `git commit -m "..."` | Zapisanie nowej migawki w historii lokalnej | 2 |
| uv | `uv sync` | Synchronizacja pakietów z plikiem `pyproject.toml` | 1 |

Wzór na średnią arytmetyczną używany w modułach analitycznych:

$$\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$$

---

### Przydatne linki
- [Oficjalna dokumentacja Python 3.14](https://docs.python.org/3.14/)
- [Dokumentacja biblioteki pandas](https://pandas.pydata.org/docs/)
- [Moje notatki z kursu](notes.txt)

