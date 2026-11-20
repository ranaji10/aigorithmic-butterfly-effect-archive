# AIgorithmic Butterfly Effect: the archive

Pictures, frames and transcripts from the 2021 archive of **[AIgorithmic Butterfly Effect](https://ranaji10.github.io/aigorithmic-butterfly-effect/)**, a slow, open artwork (2021–2046). This repository only holds files; the work, its rules and its door are in [the main repository](https://github.com/ranaji10/aigorithmic-butterfly-effect).

**Before you look.** This is raw material: a person thinking aloud through weeks that ended badly for him, strong language, private moments. It is public by his decision and with the agreement of the friends who appear in the calls. The site shows it as colour until a visitor chooses otherwise. Please make the same choice deliberately, and do not identify, profile or diagnose anyone from it.

**Anything here can be removed on request.** Open an issue titled `remove <id>` in the main repository, or use "Ask for removal" on the site. See the [charter](https://github.com/ranaji10/aigorithmic-butterfly-effect/blob/main/CHARTER.md), section 6.

| | |
|---|---|
| `i/w/mNNNNN.webp`, `i/t/mNNNNN.webp` | pictures, large and small. `m00001`–`m05909`: screenshots of the call window in the order they were pasted into the 2021 document; `m06xxx`: camera roll and other screenshots; `m07001`–`m07035`: made in 2026 from a recording that could not be read; `m07101` onward: camera photographs of November 2021 to January 2022 found on the author's drives in November 2026 (only those showing no people, screens, documents or names; the rest wait for his review) |
| `i/index.json`, `i/text.json` | size, group, date and sensitivity mark of every picture; what a machine read in them, read again on 16 Nov 2026: for screenshots of the call only the captions under the call window, for other pictures all readable words (surnames, links, addresses, numbers and anything that did not form words removed) |
| `i/sound.json` | where in the recordings each screenshot of the call was taken: recording, from which second to which, and at which second the caption has reached which of its words. Found by comparing the captions of 2021 with the speech model's hearing of 2026; a picture that was not found surely is not listed. The site plays that stretch of sound under the picture |
| `i/names.json` | where a machine read a listed first name written on screen: in which pictures, and in how many frames (one a minute, all of them read on 17 Nov 2026) of which call recordings. It says where a name was written, not who is in a picture |
| `i/doc.json` | what the 2021 document says around each pasted screenshot: section heading, hashtags, the words above it, margin comments (addresses, links, numbers and surnames removed; only for public pictures) |
| `r/index.json` | every public recording: calls, short phone videos, screen recordings of the phone (`screen`), one voice memo |
| `r/find.json` | everything heard in the recordings as one file, for the site's Find: for each recording one line per thing heard, `second<TAB>words`, the call chat, and where Hindi or Bengali was heard. A copy of the voice files and of nothing else; made again by `tools/search_build.py` of the site repository whenever one of them changes |
| `r/rNNN/f/NNNNN.webp`, `r/rNNN/s/NNNNN.webp` | one frame per minute (per 20 or 5 seconds for short recordings), large (long side 960 px) and small (320 px): the layer that was *seen* |
| `r/rNNN/voice.json` | the layer that was *said*, written down in 2026 by a very small speech model. It mishears, as the 2021 caption machine did. Also the call's chat, first names only |
| `v/` | short phone videos and the voice memo, small copies |
| branch [`audio`](https://github.com/ranaji10/aigorithmic-butterfly-effect-archive/tree/audio) | the sound of the calls: `rNNN/KKK.webm`, ten minutes each (KKK = second // 600), for the hours listed as `aud` in `r/index.json` |
| `x/unread/` | a recording that was cut off before it could write its own index, read anyway: as pictures, and its bytes as sound |

Not here: anything showing phone numbers, addresses, identity documents, chat or mail screens, messages from people who were never in the calls, or other people's posts. That material is held by the author for review.

Full-length originals: Internet Archive, items named `aigorithmic-butterfly-effect-…` (see `r/index.json`, fields `ia` and `file`).

© 2021–2026 Rana, [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Mirrors are welcome; honour removals.
