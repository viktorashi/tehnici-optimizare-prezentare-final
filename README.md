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

in settings.json din vscode de la [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop)
