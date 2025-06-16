
> 📘 This note is part of my personal learning journal while reading *Software Engineering for Data Scientists*.
> Some sentences are quoted directly from the book for educational purposes only.  
> All rights belong to the original author and publisher.


## Key point:

### Tools for Format and Linting 

```
pip install isort

isort amice_program.py
```

```
pip install black
pip install "black[jupyter]"

black amice_program.py

black amice_program.py --diff
```

```
pip install pylint

pylint amice_program.py
```

```
pip install flake8

flake8 amice_program.py
```

```
pip install ruff

ruff check amice_program.py
ruff format amice_program.py
```

## New! - Type Annotation

```
pip install mypy

mypy amice_program.py
```



---
tags: [personal-note, SE4DS, learning, non-commercial]
