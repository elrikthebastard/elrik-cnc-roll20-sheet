# Pending work

## First priority

- Generic custom class support for player-entered class name, level, Prime, BtH, HP/XP progression, and casting setup. Do not bundle Ethereal Knight text or tables. Custom ability data entry is already available; full custom class support is not yet implemented.

## Fixes and improvements

- Preserve ability row position while editing new records.
- Resolve each spell's level for its assigned casting class; handle combined compendium levels without guessing. Verify previously imported entries.
- Spell attack rolls for spells requiring a hit roll.
- Show all memorized spells in a scrolling Core panel roughly 12 rows tall, grouped by class and ordered by spell level.
- Editable campaign spell costs: requested defaults are 0 for cantrips and spell level for levels 1–9. Verify current controls before extending them.
- Chat-card label spacing and consistent light/dark mode styling, including Chrome.
- Favored Spell selection and sorting, separate from memorization.
- Attribute enhancements stored separately from base scores, with effective-score calculations.
- Temporary conditional AC and saving throw effects, with activation and condition reminders.
- Verify elf Racial Weapon Training.
- Optional configurable damage scaling; retain manual formula entry and override.

## Validation before wider use

- Continue Fiona's custom ability data-entry tests.
- Test Core and Magic casting, one resource deduction per cast, and insufficient-resource behavior on copied characters.
- .30 damage rolling has live user confirmation; .31 changes documentation only.
