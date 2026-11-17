# Style dataset

Machine-readable copy of the **public** Communication Style Quiz definitions.

| File | Format |
| --- | --- |
| [styles.json](styles.json) | JSON |
| [styles.yaml](styles.yaml) | YAML (same data) |

**Source:** `quiz-data.js` v1.1.0 and `scoring.js` v1.0.0, as shipped with [commstylequiz.com](https://commstylequiz.com/?utm_source=github&utm_medium=referral&utm_campaign=a_repo&utm_content=data) site v1.5.2 (2026-11-16).

The 13 quiz questions are **not** in this dataset. If you want a result, [take the free quiz](https://commstylequiz.com/?utm_source=github&utm_medium=referral&utm_campaign=a_repo&utm_content=data) — about three minutes, no sign-up, scored in your browser.

## What's in the file

- `source` — product, site version, and a note that questions are omitted
- `disclaimer` — the same limits the site states on the result page
- `scoring` — rules from the public “How this quiz works” section and `scoring.js` v1.0.0 (`order`, `balance_spread` of 2, five rules)
- `dimensions` — the four habits: Clarity (C), Connection (N), Structure (S), Spark (P), with `short`, `color`, and `measures`
- `styles` — the five results: The Pathfinder (C), The Bridge-Builder (N), The Blueprint (S), The Spark (P), and The Navigator (B), each with `oneLiner`, `tagline`, `summary`, `tips`, `inTheWild`, `underStress`, and `talkToMe`
- `templates` — result-page sentence templates (`blend`, `closeCall`, `why`, `disclaimerTop`) and the placeholder key

The Navigator is **not** a fifth measured dimension. It is assigned when the spread between the highest and lowest dimension scores is 2 points or less.

Colors are the ones used on the public result cards (`#E4572E`, `#17BEBB`, `#2E5EAA`, `#F4B400`).

## What this is not

This dataset is for reflection tools, writing aids, or your own notes. It is not a psychological, clinical or diagnostic instrument, and it has not been scientifically validated. Do not use it to score other people, to predict whether a relationship will work, or to make hiring or career decisions.

The model is original. It is not derived from MBTI, DISC, SOCIAL STYLE, or any commercial instrument, and this project is not affiliated with those publishers.

## License

[CC BY 4.0](../LICENSE). Attribution: Commstylequiz, https://commstylequiz.com
