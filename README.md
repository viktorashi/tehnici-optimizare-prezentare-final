compilat cu

```json
            "name": "lualatexmk",
            "command": "latexmk",
            "args": [
                "-f",
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "-lualatex",
                "-outdir=%OUTDIR%",
                "%DOC%"
            ],
            "env": {}
```
