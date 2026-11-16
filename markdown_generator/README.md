# Markdown generator

Optional scripts for turning a spreadsheet into publication or talk pages. Nothing here is published; the folder is excluded in `_config.yml`.

From the repository root:

```bash
python3 markdown_generator/publications.py markdown_generator/publications.csv
python3 markdown_generator/talks.py markdown_generator/talks.tsv
```

The `.ipynb` files are the same conversions with notes inline. `publications.tsv`, `publications.csv`, and `talks.tsv` are examples, not site content. Replace them before generating pages.
