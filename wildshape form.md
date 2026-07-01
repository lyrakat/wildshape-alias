Transform into a known form. Spends a Wild Shape use and grants Temp HP equal to your Druid level (3x for
Circle of the Moon), keeping the higher amount if you already have temp HP. In combat it overlays your AC,
resistances, attacks, and per-ability save bonuses, with a Revert button.

__AC while shaped__
Your AC is the highest of every calculation that applies to you: the beast's AC, your subclass AC (Circle of
the Moon's 13 + WIS), and Unarmored Defense if you have it. Monk (10 + WIS + beast DEX) and Barbarian
(10 + beast CON + beast DEX) are detected from your sheet automatically; declare any other source once with
`!wildshape setup -unarmored`.

__Usage__
`!wildshape form Wolf`
`!wildshape Wolf`  (shortcut, no `form` needed)
`!wildshape Wolf -ac 18`  (force a specific AC this transform)
`!wildshape Wolf -noac`  (set no AC; your normal sheet AC stands)
