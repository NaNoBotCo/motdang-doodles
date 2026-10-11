# motdang-doodles

Every doodle [motdang.net](https://motdang.net/) drew from 2026-10-05 to 2026-10-11: 80,505 doodles, 82,750 versions. [motdang.net/doodles/](https://motdang.net/doodles/) shows a selection of them.

| File | Holds |
|---|---|
| `ledger.jsonl.gz` | One row per event, oldest first. A version row: `id`, `v`, `from` (date drawn), `e` (engine), `fp` (fingerprint of the drawing), `ph` (its parameters), `c` (category), `sub`, `d`, `th`, `en`, `href`. A row with `set` changes the words around the latest version. A row with `gone` dates the day a doodle stopped being drawn. |
| `params.jsonl.gz` | `{"ph": …, "p": …}`: the parameters each drawing was made from. A place portrait's `p.f` is the place: its kind, and what is drawn around it (hills, a river, a road, props, floors). |
| `engines/<e>.js` | The doodler engine each version was drawn with, named by the `e` in its row. |
| `counts.json` | Doodles and versions by category. |

Most rows are place portraits: one for each place in the Chiang Mai and Chiang Rai directories, drawn 2026-10-05 and 2026-10-06 and retired 2026-10-10.
