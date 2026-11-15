# AIgorithmic Butterfly Effect: the archive

Pictures, frames and transcripts from the 2021 archive of **[AIgorithmic Butterfly Effect](https://ranaji10.github.io/aigorithmic-butterfly-effect/)**, a slow, open artwork (2021–2046). This repository only holds files; the work, its rules and its door are in [the main repository](https://github.com/ranaji10/aigorithmic-butterfly-effect).

**Before you look.** This is raw material: a person thinking aloud through weeks that ended badly for him, strong language, private moments. It is public by his decision and with the agreement of the friends who appear in the calls. The site shows it as colour until a visitor chooses otherwise. Please make the same choice deliberately, and do not identify, profile or diagnose anyone from it.

**Anything here can be removed on request.** Open an issue titled `remove <id>` in the main repository, or use "Ask for removal" on the site. See the [charter](https://github.com/ranaji10/aigorithmic-butterfly-effect/blob/main/CHARTER.md), section 6.

| | |
|---|---|
| `i/w/mNNNNN.webp`, `i/t/mNNNNN.webp` | pictures, large and small. `m00001`–`m05909`: screenshots of the call window in the order they were pasted into the 2021 document; `m06xxx`: camera roll and other screenshots; `m07xxx`: made in 2026 from a recording that could not be read |
| `i/index.json`, `i/text.json` | size, group, date and sensitivity mark of every picture; what OCR read in them (surnames, links, addresses and numbers removed) |
| `i/doc.json` | what the 2021 document says around each pasted screenshot: section heading, hashtags, the words above it, margin comments (addresses, links, numbers and surnames removed; only for public pictures) |
| `r/index.json` | every public recording: calls, short phone videos, one voice memo |
| `r/rNNN/f/NNNNN.webp`, `r/rNNN/s/NNNNN.webp` | one frame per minute (per 20 or 5 seconds for short recordings), large (long side 960 px) and small (320 px): the layer that was *seen* |
| `r/rNNN/voice.json` | the layer that was *said*, written down in 2026 by a very small speech model. It mishears, as the 2021 caption machine did. Also the call's chat, first names only |
| `v/` | short phone videos and the voice memo, small copies |
| branch [`audio`](https://github.com/ranaji10/aigorithmic-butterfly-effect-archive/tree/audio) | the sound of the calls: `rNNN/KKK.webm`, ten minutes each (KKK = second // 600), for the hours listed as `aud` in `r/index.json` |
| `x/unread/` | a recording that was cut off before it could write its own index, read anyway: as pictures, and its bytes as sound |

Not here: anything showing phone numbers, addresses, identity documents, chat or mail screens, messages from people who were never in the calls, or other people's posts. That material is held by the author for review.

Full-length originals: Internet Archive, items named `aigorithmic-butterfly-effect-…` (see `r/index.json`, fields `ia` and `file`).

© 2021–2026 Rana, [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Mirrors are welcome; honour removals.
