# UChicago STAT 32960

Course materials for STAT 32960.

## Structure

- `lectures/`: LaTeX source fragments, one per lecture
- `notes/`: Master LaTeX source and compiled course notes
- `code/`: Examples, demonstrations, and assignments
- `figures/`: Figures used in lectures and notes
- `papers/`: Reference papers

## Building the notes

From the repository root, run:

```sh
latexmk -cd -pdf notes/stat_32960.tex
```

The master file includes every lecture from `lectures/` in numerical order.
The VS Code workspace is configured to rebuild the master notes whenever a
LaTeX source file is saved.
