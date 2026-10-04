# C Programming Practice

Early C-language exercises and a mixed collection of related programming notes.

## Navigation

Topics include control flow, arrays, pointers, strings, dynamic memory, linked lists, and small games. Additional C++, Python, and C# material is preserved as historical study work. `legacy/seq_list_c.h` and `legacy/Seqlist.h` are distinct original C and C++ headers; the former was renamed to avoid a case-insensitive filesystem collision.

```text
legacy/          Original source, notes, images, data, and project files
docs/catalog.md  Original-to-current file mapping and cleanup record
```

See the [complete source index](docs/catalog.md). Generated compiler outputs and editor caches are excluded from the current tree; original commits remain intact.

## Working with this archive

This collection is not one application and has no unified build. Select an exercise, inspect its dependencies and entry point, and build it in a separate project. Several files use Visual Studio, Windows APIs, GBK-encoded comments, or missing course-specific headers. Preserve the original encoding when editing.

Visual Studio project files are historical references after relocation and may need their source paths updated before reuse. Source names and internal relative paths are retained within `legacy/`, apart from documented filename conflict handling.

## Validation

The cleanup verifies preservation of retained file bytes, filename compatibility, and document links. It does not assert that all historical exercises compile or that their comments and algorithms are correct. See [validation record](docs/validation.md).
