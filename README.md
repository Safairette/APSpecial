## APSpecial

Adds a new advanced ammotype for pistols and revolvers to make them a bit more viable versus heavier armor

Some calibers are now semi-arbitrarily relegated to the "heavy" category, reducing the stat scaling of the ammo type
These calibers are as follows:

.44 Magnum, 4.6x30mm, .50 AE, .357 Magnum, .454 Casull, .460 S&W Magnum, .500 S&W Magnum, 7.62x25mm Tokarev and 5.7x28mm

Uses the following formulas for the stat conversion:

All recipes
- Steel - AP steel cost * 0.7
- Uranium - AP steel cost * 0.1
- CHemfuel - AP steel cost * 0.1

Regular calibers
- RHA - AP RHA * 1.5, rounded to int
- MPa - AP MPa * 1.3
- Damage - AP Damage * 0.8, rounded to int

Heavy calibers
- RHA - AP RHA * 1.3, rounded to int
- MPa - AP MPa * 1.3
- Damage - AP Damage * 0.7, rounded to int

All AP-S projectiles also receive a 20% speed increase
