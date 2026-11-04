# MuseScore Studio code coverage

[![Coverage](https://musescore.github.io/mss_code_coverage/badge/coverage_badge.svg)](https://musescore.github.io/mss_code_coverage/)

Unit test code coverage of [musescore/MuseScore](https://github.com/musescore/MuseScore), served with GitHub Pages:
https://musescore.github.io/mss_code_coverage/

| Path | What | Updated by |
|---|---|---|
| `index.html` | overview: latest numbers and coverage over time | hand |
| `history.csv` | `date,commit,lines,functions` of every publish | CI, appends a row |
| `report/` | HTML report of the latest publish (genhtml) | CI, replaced |
| `badge/coverage_badge.svg` | badge for README | CI, replaced |

The data is published by the `Check: Unit Tests (utest)` workflow in musescore/MuseScore
(weekly, or manually with `code_coverage` and `publish_coverage_report` enabled).
