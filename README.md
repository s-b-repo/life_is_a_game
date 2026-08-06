# life_is_a_game

**Empty placeholder repo.** The only file previously committed was a
GPL-3 LICENSE — no source, no assets, no README before this one.

There are two sibling repos on the account for what looks like the
same project:

- [`s-b-repo/life-is-a-game`](https://github.com/s-b-repo/life-is-a-game)
  — has the custom gameplay (`PlayerMovement.cs`, spawn scripts, main
  scene). Uses lowercase `assets/` (Unity requires `Assets/`), missing
  `ProjectSettings/`, so it won't currently open in Unity.
- [`s-b-repo/life_is_a_game_unity_game`](https://github.com/s-b-repo/life_is_a_game_unity_game)
  — has the environment assets (Advanced Waypoint System, MK Glass
  Free, NVJOB Water Shaders, PostProcessing v1). Correct `Assets/`
  casing but missing `ProjectSettings/`.

## Recommended action

Either:

1. **Archive** this repo (`gh repo archive s-b-repo/life_is_a_game`) —
   nothing is lost, since the other two hold the actual content.
2. **Repurpose** it as the canonical name for a merged project that
   combines the custom code from `life-is-a-game` with the
   environment assets from `life_is_a_game_unity_game`, adds a proper
   `ProjectSettings/` and `Packages/manifest.json`, and pins a Unity
   editor version. That's a real project on its own — flagged as
   future work, not attempted in this refresh pass.

## License

GPL-3 (from the pre-existing `LICENSE`).
