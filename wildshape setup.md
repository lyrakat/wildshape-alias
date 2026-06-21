Creates the Wild Shape uses counter and stores your subclass and options. Druid level, proficiency, and
ability modifiers are read from your sheet on each command.

__Usage__
`!wildshape setup`
`!wildshape setup -subclass moon`

__Arguments__
`-subclass land|moon|sea|stars`: your Circle.
`-fury primal|potent`: your level 7 Elemental Fury option (Primal Strike adds damage to beast attacks).
`-color #RRGGBB` `-thumb <url>`: embed appearance.

Run setup again when you make a new choice:
- Level 3: set your Circle, e.g. `!wildshape setup -subclass moon`.
- Level 7: set your Elemental Fury option, e.g. `!wildshape setup -fury primal`.

At level 3+ with no subclass set, `!wildshape` and transforming will show a reminder.
