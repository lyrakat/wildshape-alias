# Wild Shape 2024

Wild Shape for 2024 Druids: the core class at all levels and the Circle of the Land, Moon, Sea, and Stars
subclasses. Druid level, proficiency, ability modifiers, uses, temp HP, and max CR are read from your sheet
each time you run a command.

While shaped you keep your HP, Hit Dice, INT/WIS/CHA, class features, and feats; AC, physical stats, and
attacks come from the beast. In combat this is applied as a single init effect with a Revert button.

## Setup
1. `!wildshape setup` creates the Wild Shape uses counter.
2. At level 3, set your subclass: `!wildshape setup -subclass moon`.
3. At level 7, set your Elemental Fury option: `!wildshape setup -fury primal`.

## Learning a form
Forms are read from Avrae's compendium while in initiative, then stored on your character.
1. `!wildshape scan wolf -cr 1/4` adds the beast to combat so its stat block can be read.
2. `!wildshape learn -as Wolf` stores it and removes the temporary combatant.

## Commands
| Command | Description |
|---|---|
| `!wildshape` | Status and command list |
| `!wildshape setup` | Set subclass and options, create the uses counter |
| `!wildshape scan <beast>` | In combat, add the beast so it can be read |
| `!wildshape learn [-as Name]` | Store the scanned beast as a known form |
| `!wildshape forms` | List known forms and your limits |
| `!wildshape forget <name>` / `swap <old> for <new>` | Manage known forms |
| `!wildshape <form>` | Transform |
| `!wildshape revert` | End the form |
| `!wildshape attack <atk> -t <tgt>` | Roll a beast attack (`atk` also works) |
| `!wildshape check <skill>` / `save <ability>` | Roll using the higher of you or the beast |
| `!wildshape use <feature>` | Spend a use on a subclass feature |
| `!wildshape rest short` / `rest long` | Regain 1 / all uses |

## Notes
- Scan and learn run while in initiative; the beast is added to combat to read its stat block, then removed.
- Pass `-cr` (and `-fly` for flying beasts) when scanning so the eligibility check against your level applies.
- Skill checks while shaped use `!wildshape check`; in combat the effect adjusts automated saves directly.
- Duration, the Incapacitated end condition, spellcasting, and equipment are shown as reminders.

## Issues
Report bugs, problems, or missing and incomplete features at
https://github.com/lyrakat/wildshape-alias/issues

## Development
Parts of this code were written with AI assistance (Claude), reviewed and maintained by the repository owner.
