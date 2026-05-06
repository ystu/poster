# Agent Index

Use this file as the entry point for project-specific instructions. Keep detailed rules in the referenced documents.

## Workspace Encoding

This workspace contains Chinese Markdown files. When reading them in PowerShell, use UTF-8 explicitly to avoid mojibake:

```powershell
[Console]::OutputEncoding = [System.Text.UTF8Encoding]::new(); Get-Content -Raw -Encoding UTF8 -LiteralPath 'path'
```

## Posters

Before creating, editing, reviewing, or generating prompts for posters, read:

- `poster-rules.md`
