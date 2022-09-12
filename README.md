To Reproduce The Error

```bash
python run_quarto.py
```

The Error I get:

```
assertion failed [block != nullptr]: BasicBlock requested for unrecognized address
(BuilderBase.h:550 block_for_offset)
/usr/local/bin/quarto: line 145:  9849 Trace/BPT trap: 5       "${QUARTO_DENO}" ${QUARTO_ACTION} ${QUARTO_DENO_OPTIONS} ${QUARTO_DENO_EXTRA_OPTIONS} "${QUARTO_IMPORT_ARGMAP}" "${QUARTO_TARGET}" "$@"
```

## Info about my system:

- OS: MacOS Monterey 12.5.1, Apple M1 Pro
- 
