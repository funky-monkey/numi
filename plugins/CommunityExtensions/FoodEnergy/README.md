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
- `250 Calories in kJ` -> `1046 kJ` (if Numi preserves case in aliases)
- `100 cal in J` -> `418.4 J`
- `5000 J in kcal` -> `1.195 kcal`
- `12 kJ in J` -> `12000 J`

## Note

Numi's plugin API requires custom units to be attached to a base unit. This plugin uses an internal base unit so energy conversions work, but you should treat these as food-energy-only units (not mass).

If Numi normalizes unit names to lowercase internally, `Calories` may conflict with `calories`. In that case, use `kcal` for food labels and `cal` for small calories.
