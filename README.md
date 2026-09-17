# PA 5: The Scope Resolver

Public template: https://github.com/cwillpinto/cs379-pa05-scope-resolver

Full assignment: `PA_05_The_Scope_Resolver.md`.

## Setup
Paste your own completed `lexer.py`/`parser.py`/`symtable.py` in
first (bundled here even though PA 5's new code doesn't touch lexing
or parsing directly -- `symtable.py` imports from `parser.py`, which
imports from `lexer.py`, so the whole chain has to be importable).

## Run
```bash
python test_scope_resolver.py
```
Complete `resolve_name` in `scope_resolver.py`. The harness tests
static and dynamic mode separately, then replays the Part A "classic
divergence" example and confirms the two modes resolve `x` to
genuinely different declaration lines. Success Token prints once
every check passes.

## Submit
1. `PA5_Theory.pdf` (or `.md`)
2. `scope_resolver.py` (and your working `lexer.py`/`parser.py`/`symtable.py`)
3. The Success Token
