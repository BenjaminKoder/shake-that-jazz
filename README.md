# Shake That Jazz

Spill i Python og Pygame fra 2023, med egne sprites og en butikk for oppgraderinger. Samle pizza, unngå hindringene og bruk pizzaen til å kjøpe oppgraderinger mellom rundene.

<img src="skjermbilde.jpg" alt="Skjermbilde av Shake That Jazz" width="640">

## Kontroller

| Tast | Handling |
|---|---|
| `Mellomrom` | Hopp |
| `A` / `←`, `D` / `→` | Gå til venstre og høyre |
| `R` | Start ny runde |
| `H` | Kjøp mer liv (mellom rundene) |
| `G` | Kjøp høyere hopp (mellom rundene) |
| `F` | Kjøp flere pizzaer (mellom rundene) |

## Kjør spillet

Krever Python 3 og Pygame. Kjør fra denne mappen, siden spillet laster bilder og lyd med relative stier.

```bash
pip install pygame
python Prosjekt.py
```

## Filer

- `Prosjekt.py` – spillet
- `spritesheetClass.py` – klasse som deler opp spritesheets til animasjoner
- `background/`, `jazzplayer/`, `pizza/`, `tuba/`, `spritesheets/` – grafikk
- `xcf/` – kildefilene til grafikken (GIMP)
- `IT pygame prosjekt Shake That Jazz.odp` – presentasjon av prosjektet
