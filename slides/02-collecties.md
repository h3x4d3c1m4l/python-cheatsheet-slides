# Collecties
## Typen

- list (Lijst, mutable)
- dictionary (Lijst van sleutelwoorden met een waarde)
- tuple (Lijst, immutable)
- set (Lijst, zonder dubbelen, zonder volgorde, mutable)

## Declareren

```python
mijn_list = ["tekst 1", "tekst 2"]
mijn_dict = {"Naam": "Voornaam Achternaam", "Leeftijd": 29}
mijn_tuple = ("tekst 1", "tekst 2")
mijn_set = {1, 2, 3}
```

Let op: Alle collecties kunnen in principe verschillende data typen door elkaar bevatten!

---

# Collecties
## List manipuleren

```python
mijn_list = ["tekst 1", "tekst 2"]
mijn_list[1] = "andere tekst" # Nu hebben we ["tekst 1", "andere tekst"]

mijn_list.remove("tekst 1") # Nu hebben we ["andere tekst"]
mijn_list.append("tekst 3") # Nu hebben we ["andere tekst", "tekst 3"]

mijn_list.pop() # Nu hebben we ["andere tekst"]
mijn_list.clear() # Nu hebben we []
```

## Dictionary manipuleren

```python
mijn_dict = {"Naam": "Voornaam Achternaam", "Leeftijd": 29}
mijn_dict["Naam"] = "Nieuwe Naam"
mijn_dict["Leeftijd"] = 30
```
