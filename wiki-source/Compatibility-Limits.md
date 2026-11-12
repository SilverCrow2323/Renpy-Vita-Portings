# Compatibility limits

Ren'Py Vita is not a guarantee that every Ren'Py game will run on PlayStation Vita. This repository tracks practical test results and known constraints.

## Current documented limits

- Candidate games should be relatively basic.
- Video playback is not supported by the current porting path described in the project README.
- Some games trigger Ren'Py errors during a session.
- Some titles do not boot with a basic conversion.
- A basic conversion failure does not prove that a game can never run with additional patches.

> [!IMPORTANT]
> **MUST KNOW!!** Treat the status list as evidence from the tested conversion path, not as a universal compatibility verdict for every game version or future engine patch.

## How to read the status

| Label | Meaning |
|---|---|
| Testing | The project is currently evaluating the port |
| Future tests / suggestions | A candidate has been proposed but is not confirmed working |
| Available port | A separate port project is linked from the README |
| Failed basic conversion | The unpatched base Ren'Py-Vita conversion encountered a blocking error |

## When evaluating a candidate

- Check whether it depends on video playback.
- Identify the Ren'Py version used by the game if that information is available.
- Keep the original game files separate from generated Vita build output.
- Record the exact failure point rather than writing only "does not work".

