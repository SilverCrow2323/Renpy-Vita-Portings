# Testing checklist

Use this checklist when evaluating a candidate. It is a suggested reporting structure, not a claim that every step is automated by this repository.

## Record the test target

- Game title and exact release/build.
- Ren'Py version, when identifiable.
- Source of the game and whether the test uses a legally obtained copy.
- Ren'Py Vita revision or package used.
- Any patches applied beyond the basic conversion.

## Record the observed behavior

- Does the application boot?
- Does the main menu render?
- Can a new game/session start?
- Does the issue happen immediately or at a specific scene?
- Does the game require video playback?
- Can the tester reproduce the issue consistently?

## Classify the outcome

| Result | Record as |
|---|---|
| Launches and reaches gameplay | Basic boot/session test passed |
| Launches but errors during a scene | Runtime/session failure |
| Fails before reaching the menu | Boot failure |
| Requires unsupported video playback | Compatibility limitation |
| Works only after patches | Patched result; list the patch separately |

## Evidence

- Keep logs and screenshots focused on the issue.
- Do not upload copyrighted game assets or full game data.
- Include the exact error text and the scene/action that triggered it.
- Distinguish the base conversion from any custom patch.

