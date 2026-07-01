Creates the Wild Shape uses counter and stores your subclass and options. Druid level, proficiency, and
ability modifiers are read from your sheet on each command.

__Usage__
`!wildshape setup`
`!wildshape setup -subclass moon`

__Arguments__
`-subclass land|moon|sea|stars`: your Circle.
`-fury primal|potent`: your level 7 Elemental Fury option (Primal Strike adds damage to beast attacks).
`-unarmored <formula>`: declare an Unarmored Defense formula for AC while shaped, e.g.
`-unarmored "13+dex"` for Draconic Resilience. Monk (`10+wis+dex`) and Barbarian (`10+con+dex`) are
detected automatically, so you only need this for other sources. Physical abilities use the beast's mod
and mental abilities use yours. Clear it with `-unarmored none`.
`-color #RRGGBB` `-thumb <url>`: embed appearance.

Run setup again when you make a new choice:
- Level 3: set your Circle, e.g. `!wildshape setup -subclass moon`.
- Level 7: set your Elemental Fury option, e.g. `!wildshape setup -fury primal`.

At level 3+ with no subclass set, `!wildshape` and transforming will show a reminder.
