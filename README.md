# oasis652026

Reviewer-accessible sample from OASIS, a multilingual and multimodal dataset for culturally grounded spoken visual QA.

This repository contains records covering **all 18 Arabic-speaking countries** in OASIS. Each record pairs a culturally grounded image with multilingual descriptions and QA items (open-ended, multiple-choice, true/false) in English, MSA, Egyptian Arabic, and Levantine Arabic, with paired **human-recorded and synthetic speech** (English + MSA) for the open-ended and true/false questions.

The full curated OASIS dataset (~0.92M images, ~14.8M QA pairs across 18 Arabic-speaking countries and 4 languages, with paired synthetic and human speech) will be released at the camera-ready stage.

## Contents

- `data/<country>.jsonl`: one record per line with multilingual descriptions, QA items, and audio references (relative paths).
- `images/<country>/`: images, one folder per country.
- `audio/human/{en,msa}/<country>/`: human-recorded question audio.
- `audio/tts/{en,msa}/<country>/`: synthetic question audio.
- `croissant.json`, `stats.json`: machine-readable metadata.

## License

Released under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), non-commercial research use only.
