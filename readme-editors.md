## For editors
Two GVARs hold the code (logic and subclass data):
- wildshape-engine: 555fd5a3-216e-4ba5-8847-43db73c03c0f
- wildshape-profiles: eb6de7da-50ee-4ad9-8b02-2a91cc850c40

The subcommand aliases are thin wrappers that call the engine. Sync with Push Update (local to workshop).
Get Collection overwrites local files with the workshop copies. Push the two GVARs as well, since they hold
the logic.
