# Numi Food Energy Plugin

Adds food energy units to Numi:

- `J` / `joule`
- `kJ` / `kilojoule`
- `cal` / `calorie` / `calories` (small calorie)
- `kcal` / `Calories` (food Calories on nutrition labels)

## Install

1. Open Numi.
2. Open the plugins/extensions folder (see Numi wiki).
3. Copy `food-energy.js` into that folder.
4. Reload Numi (or restart the app).

## Examples

- `250 kcal in kJ` -> `1046 kJ`
- `250 Calories in kJ` -> `1046 kJ` 
- `100 cal in J` -> `418.4 J`
- `5000 J in kcal` -> `1.195 kcal`
- `12 kJ in J` -> `12000 J`
