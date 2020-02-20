# README
---

README sur un projet de web crawler

A l'execution recuperation de nouveaux liens créés depuis 
la dernière execution

## Structure
---
La structure est la suivante

```
.
|-- Dockerfile
|-- docs/
|-- LICENSE
|-- mainjob/
|   |-- core.py
|   |-- __init__.py
|   `-- __main__.py
|-- README.md
`-- tests/

```

On utilise la structure classique d'un packaging Python,
présentée notamment dans "The Hitchhiker guide to Python" 
(https://docs.python-guide.org/writing/structure/).

On ajoute un __main__.py à côté du __init__.py,
ce premier sera éxécuté lors de l'invocation ```python -m mainjob```.

