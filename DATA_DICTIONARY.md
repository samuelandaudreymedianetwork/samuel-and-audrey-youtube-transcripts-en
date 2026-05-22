# Samuel & Audrey YouTube Transcripts EN Corpus, 2012–2026 — Data Dictionary

This file defines fields used across `samuel-and-audrey-youtube-transcripts-en.jsonl`, `samuel-and-audrey-youtube-transcripts-en.csv`, and `samuel-and-audrey-youtube-transcripts-en_segments.jsonl`.

| Field | Description |
|---|---|
| `record_id` | Stable dataset record identifier. |
| `record_type` | Record type: `youtube_transcript` or `youtube_transcript_segment`. |
| `id` | Original transcript identifier, where available. |
| `dataset` | Current dataset slug. |
| `source_channel` | YouTube channel associated with the transcript. |
| `source_platform` | Source platform, usually YouTube. |
| `channel_url` | Canonical channel URL. |
| `video_id` | YouTube video identifier. |
| `url` | Canonical YouTube video URL. |
| `published_at` | Publication timestamp, where available. |
| `video_date` | Normalized publication date, where available. |
| `title` | Video or transcript title. |
| `youtube_title` | YouTube title field from the source export, where available. |
| `view_count` | View count captured at export time, where available. |
| `tags` | Source tags field, where available. |
| `tags_list` | Array of tags associated with the video. |
| `language` | Normalized language code. |
| `lang` | Original or alternate language code field. |
| `channel` | Original channel field from the source export. |
| `domain` | Source domain field from the source export. |
| `source` | Original source field from the export. |
| `caption_source` | Caption source or extraction method, where available. |
| `caption_track_kind` | Caption track kind, where available. |
| `text` | Transcript text. For segment records, cue-level text. |
| `text_with_breaks` | Transcript text retaining line or paragraph breaks, where available. |
| `srt` | Subtitle-style transcript payload with timing information. |
| `original_filename` | Original transcript filename, where available. |
| `content_hash` | Hash for deduplication or integrity checks, where available. |
| `license` | Dataset license. |
| `segment_id` | Stable segment identifier for cue-level records. |
| `transcript_id` | Parent transcript identifier for cue-level segment records. |
| `start_ms` | Cue-level segment start time in milliseconds. |
| `end_ms` | Cue-level segment end time in milliseconds. |

## Notes

The full transcript files contain one record per video.

The segment file contains cue-level transcript records for retrieval and timing-aware analysis.

The dataset preserves transcript text and SRT timing payloads as source corpus material. Cleanup focused on package naming, documentation, metadata consistency, and file organization.
