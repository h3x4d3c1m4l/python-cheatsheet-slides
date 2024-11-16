# Herhaling
## Herhalen met lijstelementen

```python
print("Begin van script: ik word 1x geprint!")

mijn_list = ["tekst 1", "tekst 2", "tekst 3", "tekst 4"]

# Aangezien er vier elementen zitten in `mijn_list` levert dit stukje 4 prints op!
for item in mijn_list:
    print(item)

print("Einde van script: ik word ook 1x geprint!")
```

---

# Herhaling
## Herhalen zonder lijstelementen

```python
print("Begin van script: ik word 1x geprint!")

# Gebruik een bereik van 1 tot en met 4
for index in range(1, 5):
    print("tekst " + str(index))

print("Einde van script: ik word ook 1x geprint!")
```

---

# Herhaling
## While

Hetzelfde voorbeeld als 2 slides terug, maar aangepast naar `while`:
```python
print("Begin van script: ik word 1x geprint!")

mijn_list = ["tekst 1", "tekst 2", "tekst 3", "tekst 4"]

index = 0  # Begin bij het eerste element van de lijst
while index < len(mijn_list):
    # Print het huidige item in de lijst
    print(mijn_list[index])
    index += 1  # Verhoog de index om naar het volgende element te gaan

print("Einde van script: ik word ook 1x geprint!")
```
