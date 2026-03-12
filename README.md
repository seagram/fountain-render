# fountain-render

A rust library for converting Fountain screenplays to HTML, PDF, and
FDX.

Responsible for handling:
- Page breaks
- Element spacing
- Element margins
- Dialogue/Dual Dialogue column layouts
- Title page rendering

Uses [fountain-rs](https://github.com/seagram/fountain-rs) for
converting `.fountain` files into an AST.
