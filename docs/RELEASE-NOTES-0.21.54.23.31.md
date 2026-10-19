# Build 0.21.54.23.31

Install sheet.html and sheet.css together in Roll20's custom sheet editor. This is a development build.

## Current checkpoint

- Custom class and racial ability rows offer Info or Roll, attribute selection, and a manual bonus. Player testing is in progress.
- CAST rolls explicit damage formulas such as 1d4+1 and 6d6 from Magic and Core. Magi's Missile and Lightning Bolt passed live Roll20 testing.
- Casting/resource regression checks passed locally: separate point pools, exhaustion, slot mode, class ownership and armor restrictions.
- Build .31 adds Help explaining manual damage, Damage Type, imports with blank/zero damage, and manual scaling. Casting code matches .30.

## Spell damage

Enter dice in Damage, not Damage Type. Compendium descriptions are not interpreted to generate or scale damage formulas. Use the owning class's caster level when calculating a manual formula and update it as needed. Apply spell-specific caps, saves, targets and missile rules manually.

## Known limitations

- New custom abilities may move when first saved. They work afterward; the movement is unresolved. The .29 row-ID guard is not a confirmed fix for that movement.
- Core currently shows at most 12 memorized spells per casting class.
- Spell attack rolls are pending.
- Combined class-specific imported levels need further verification and repair.
- Chat label spacing and dark-mode readability remain inconsistent for some players; Chrome was reported in one case.

This backup includes sheet code and project notes only. It excludes reference books, character records and screenshots. No Ethereal Knight class text or progression has been added.
