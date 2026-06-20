# MeritoLab2

## Opis projektu

Prosty projekt w Pythonie zawierający:
- moduł z logiką (`app/calculator.py`)
- CLI (`main.py`)
- testy (`tests/`)
- automatyzację jakości kodu (black, pylint, pytest)
- CI w GitHub Actions

---

## Quick Start

### 1. Klonowanie repozytorium

```bash
git clone https://github.com/TomiMeritoStudent/MeritoLab2.git
cd MeritoLab2
```

### 2. Utworzenie środowiska

```cmd
scripts\create_venv.bat
```

### 3. Uruchomienie programu

```cmd
python main.py
```

### 4. Uruchomienie testów

```cmd
scripts\test.bat
```

### 5. Formatowanie kodu i jego sprawdzenie (Black)

```cmd
scripts\format.bat
scripts\format_check.bat
```

### 6. Lint (Pylint)

```cmd
scripts\lint.bat
```
