---
license: cc-by-nc-4.0
language:
- en
task_categories:
- text-generation
- question-answering
- summarization
- text-retrieval
tags:
- youtube
- youtube-transcripts
- travel
- food
- tourism
- vlogs
- transcript-corpus
- travel-media
- creator-archive
- retrieval
- nlp
size_categories:
- 1M<n<10M
---

# Samuel & Audrey YouTube Transcripts EN Corpus, 2012–2026

This dataset contains the English transcript archive from the **Samuel and Audrey - Travel and Food Videos** YouTube channel.

The corpus covers travel and food videos published between **2012 and 2026**. It includes full transcript records, cue-level transcript segments, YouTube video identifiers, publication dates, titles, view counts captured at export time, tags, source URLs, transcript text, and subtitle-style payloads where available.

It is intended for non-commercial research, retrieval workflows, summarization, travel media analysis, spoken travel-language study, destination and entity extraction, and archive organization.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/samuel-and-audrey-youtube-transcripts-en
- GitHub repository: https://github.com/samuelandaudreymedianetwork/samuel-and-audrey-youtube-transcripts-en
- Zenodo DOI: https://doi.org/10.5281/zenodo.18665704
- YouTube channel: https://youtube.com/@samuelandaudrey

## Dataset contents

| Record type | Count |
|---|---:|
| `youtube_transcript` | 1,397 |
| `youtube_transcript_segment` | 233,285 |

## Snapshot details

| Field | Value |
|---|---:|
| Full transcript records | 1,397 |
| Cue-level segment records | 233,285 |
| Records with titles | 1,397 |
| Records with URLs | 1,397 |
| Records with SRT payloads | 1,397 |
| Records with view counts | 1,397 |
| Approximate transcript words | 2,385,426 |
| Approximate segment text words | 2,385,389 |
| Date range | 2012-09-16 to 2026-02-03 |

## What is included

- full English transcript text
- cue-level transcript segment records
- subtitle-style `.srt` payloads where available
- YouTube video IDs and canonical URLs
- video titles and publication metadata
- tags and view counts at export time, where available
- source-channel metadata
- JSONL and CSV formats for full transcript records
- JSONL format for cue-level segment records
- data dictionary, schema, citation file, license file, manifest, checksums, and llms exports

Each row in `samuel-and-audrey-youtube-transcripts-en.jsonl` represents one full video transcript record.

Each row in `samuel-and-audrey-youtube-transcripts-en_segments.jsonl` represents one cue-level transcript segment.

## Files

- `samuel-and-audrey-youtube-transcripts-en.jsonl` — canonical full transcript records
- `samuel-and-audrey-youtube-transcripts-en.jsonl.gz` — compressed full transcript JSONL
- `samuel-and-audrey-youtube-transcripts-en.csv` — spreadsheet-friendly full transcript export
- `samuel-and-audrey-youtube-transcripts-en.csv.gz` — compressed CSV
- `samuel-and-audrey-youtube-transcripts-en_segments.jsonl` — cue-level transcript segment records
- `samuel-and-audrey-youtube-transcripts-en_segments.jsonl.gz` — compressed cue-level segment JSONL
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-samuel-and-audrey-youtube-transcripts-en.txt` — full plain-text JSONL export for the transcript records

## Potential use cases

This dataset may be useful for:

- travel-domain retrieval and search
- transcript summarization
- spoken travel-language analysis
- destination and entity extraction
- food, transport, accommodation, and logistics analysis
- temporal analysis of travel language and price mentions
- non-commercial travel research tools
- comparing spoken travel media with written travel articles
- studying long-running creator-authored media archives

## Limitations

This dataset contains transcripts and metadata, not video files.

Transcript quality may vary by video, date, source caption quality, speaker overlap, background noise, and automatic transcription limitations. Some transcripts may include imperfect punctuation, speaker ambiguity, repeated phrases, or transcription errors.

View counts and other platform metadata reflect the export time and may change after publication.

The dataset should not be treated as a complete record of current travel conditions, prices, or destination logistics. Travel information changes over time, and users should verify current details from up-to-date sources.

## Notes on cleanup and naming

The public Hugging Face repository uses the stable slug `samuel-and-audrey-youtube-transcripts-en`. The canonical data files use the same basename.

The earlier duplicate README file and large all-in-one `llms` bundle were replaced with a single clean README, a short `llms.txt` guide, and a separate full export file.

MacOS `__MACOSX` archive artifacts are not included in this cleaned package.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

For commercial licensing inquiries, expanded usage rights, media permissions, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *Samuel & Audrey YouTube Transcripts EN Corpus, 2012–2026*. Zenodo. https://doi.org/10.5281/zenodo.18665704
