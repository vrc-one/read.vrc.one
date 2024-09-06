This repository stores the source files for read.vrc.one.

## Getting Started

### Install required tools

```bash
pipx install mkdocs-material --include-deps
```

### Clone the repository

```bash
git clone git@github.com:vrc-one/read.vrc.one.git
```

### Start editing

- We use the following structure for the site:
```
docs/                        - Contains the contents of the site.
├─ books/                    - Contains the books.
│  ├─ book-name-a/           - A specific book A.
│  │  ├─ chapter-name-1.md   - Chapter 1 of the book A.
│  │  └─ chapter-name-2.md   - Chapter 2 of the book A.
│  └─ book-name-b/           - A specific book B.
│     ├─ chapter-name-1.md   - Chapter 1 of the book B.
│     └─ chapter-name-2.md   - Chapter 2 of the book B.
└─ documents/                - Contains the documents.
   └─ TBC...
mkdocs.yml                   - The configuration file for the site.
```

- To add a new book, create a new folder in `docs/books/` and add the chapters as markdown files.
- To add a new document, create a new folder in `docs/documents/` and add the content as markdown files.
- After adding the content, update the `nav` section in `mkdocs.yml` to include the new content.
