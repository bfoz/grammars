# Grammars

A compendium of various grammar files for various and sundry grammars and parsers.

## Structure

Grammars are organized in directories that are named after the lowercased name of the language parsed by the directory's grammar. For example, the BNF grammar files for parsing BNF are located in the *bnf* directory.

Each grammar directory can optionally contain a *README.md* providing information about the grammar. Ideally, the README should include links to the source of the grammar files, if they've been imported from another source, or to additional information about the grammar (Wikipedia, etc).

## File naming conventions

Files for a particular grammar should be named using the same convention as the file's enclosing directory, and should use the conventional extension for that grammar format, unless otherwise noted in the table below. For example, the BNF file describing BNF itself is named *bnf.bnf*.

| Extension | Grammar format                                     |
|-----------|----------------------------------------------------|
| bnf       | Backus–Naur form or Backus normal Format           |
| ebnf      | Extended Backus-Normal Format (or the W3C variant) |
