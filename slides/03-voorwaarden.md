# Voorwaarden

## Als...tenzij...en anders
```python
temperatuur = 25

if temperatuur > 30:
    print("Het is heet!")
elif temperatuur > 20:
    print("Het is aangenaam.")
else:
    print("Het is koud.")
```

## Meerdere voorwaarden

```python
uur = 22
dag = "zaterdag"

if uur >= 21 and dag == "zaterdag":
    print("Het is weekend en laat op de avond!")
```

---

# Voorwaarden

## Item in de lijst of niet

```python
fruit = "appel"
fruitmand = ["appel", "banaan", "kers"]

if fruit in fruitmand:
    print(f"{fruit.capitalize()} zit in de fruitmand!")
else:
    print(f"{fruit.capitalize()} zit niet in de fruitmand.")
```

## Nagaan of iets _niet_ zo is

```python
login_gelukt = False

if not login_gelukt:
    print("Inloggen mislukt. Probeer het opnieuw.")
```
