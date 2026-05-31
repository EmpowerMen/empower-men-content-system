# Foundations

This folder contains the foundational knowledge layer for the Empower Men Content System (ECS).

It is the repository’s source-of-truth library for reference material used in research, idea development, content planning, and AI-assisted content production. The files in this folder are not final publishable assets. They are structured inputs that support downstream workflows across the ECS.

## Purpose

The `foundations/` directory exists to:

- Store canonical reference material in a reusable format.
- Preserve notes, quotations, interpretations, and metadata from source materials.
- Provide AI-readable Markdown files that can be searched, indexed, and reused in content workflows.
- Separate upstream knowledge inputs from downstream content outputs.

## Folder structure

```text
foundations/
  books/
  media/
  misc/
  indexes/
```

### books/

Contains one Markdown file per book-based source.

Examples:
- `fire-in-the-belly-sam-keen-1991.md`
- `king-warrior-magician-lover-gillette-and-moore-1990.md`
- `warrior-magician-lover-king-rod-boothroyd-2018.md`

Use this folder for long-form written works that function as primary conceptual or intellectual sources.

### media/

Contains one Markdown file per media-based source, including lectures, audio recordings, and video material.

Examples:
- `audio.md`
- `video.md`
- `robert-moore-audio-lecture.md`
- `robert-l-moore-the-magician-within-lecture-1-of-5.md`

Use this folder for lecture recordings, lecture notes, interviews, talks, audio resources, video sources, and other non-book media references.

### misc/

Contains Markdown files for source material that does not fit cleanly into books or media.

Examples:
- `artwork.md`
- `quotations.md`
- `meditations.md`

Use this folder for artwork references, quote collections, short standalone texts, and other supporting material.

### indexes/

Contains navigation and manifest files for the foundations library.

Recommended contents:
- `sources-index.md` — human-readable index of all sources.
- `sources_manifest_all.csv` — machine-readable manifest for automation, QA, and ingestion workflows.

## Source categories

The foundations layer may include material such as:

- Books and long-form written works.
- Lectures and lecture notes.
- Audio recordings and talks.
- Video sources.
- Artwork references.
- Quote collections.
- Miscellaneous supporting material.

This structure keeps all foundational source material in one place while still distinguishing between source types.

## File format standard

Each source file should follow the same structure:

1. YAML frontmatter.
2. Source summary block.
3. `## Records` section.
4. One `### Record ###` subsection per original entry.
5. Original text preserved as closely as possible from the source dataset.

### Expected frontmatter fields

Typical frontmatter fields include:

- `title`
- `author`
- `year`
- `source_type`
- `original_source`
- `slug`
- `tags`
- `archetypes`
- `development_areas`
- `record_count`

## Naming convention

All source files should use lowercase, hyphenated filenames.

Pattern:

```text
source-title-author-year.md
```

Examples:
- `to-love-and-be-loved-sam-keen-1997.md`
- `ego-and-archetype-edward-edinger-1972.md`
- `robert-moore-audio-lecture.md`

Where a source does not have a clean author-year format, use the clearest normalized slug available.

## Working principles

- Treat files in `foundations/` as canonical references, not publishable content.
- Preserve original note text and metadata wherever possible.
- Prefer one file per source rather than one file per note.
- Update `indexes/` whenever new source files are added, moved, merged, or renamed.
- Keep classification logic consistent across `books`, `media`, and `misc`.

## Relationship to the rest of ECS

The `foundations/` folder sits upstream of content creation.

In practical terms:
- `foundations/` stores source knowledge.
- Other ECS folders can transform that knowledge into briefs, drafts, campaigns, posts, scripts, or other outputs.
- AI workflows should reference `foundations/` when retrieving source material for synthesis or development.

## Maintenance notes

When adding new sources:

1. Create or update the relevant Markdown file in the correct subfolder.
2. Preserve the agreed frontmatter schema.
3. Confirm the file naming convention is followed.
4. Update the source indexes in `indexes/`.
5. Reclassify files if a source is better suited to a different subfolder.

This keeps the foundations layer clean, searchable, and stable as the ECS grows.
