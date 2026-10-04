# Validation record

Date: 2026-10-04. Cleanup baseline commit: `884a00b611de7774fe23d85104ceebd378b35ec4`.

## Preservation and structure

- 113 retained blobs are unchanged at their current paths.
- 37 generated build/cache/executable entries are omitted from the current tree; the baseline history remains available.
- New documents and required configuration/path adaptations are recorded in the cleanup pull request. No existing source history is rewritten.
- Current filenames have no case-insensitive collisions. Markdown file links and generated-output ignore rules are checked before publication.

## Checks and limits

- Retained source, image, experiment-data, note, and historical project blobs match the originals.
- No unified build is provided or asserted. Individual files may depend on Linux/Windows APIs, external headers, original encodings, or unfinished exercise text.
- The cleanup does not claim complete solution correctness, comprehensive testing, or portable execution of all files.
- Both case-conflicting headers were recovered separately from Git objects: original `SeqList.h` is now `legacy/seq_list_c.h`; original `Seqlist.h` remains `legacy/Seqlist.h`.

