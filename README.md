# vscode-ilm — highlighting for localized keywords (.uhin)

**Status: placeholder.** Goal: highlight ILM/Hindawi localized keywords in any language. The grammar should be
**generated** from the per-language keyword registries (`construct,native_keyword,romenagri`) in
`project-ilm/ilm.codes/data/` and `registry/`, so a single build emits a highlighter for every language.

## Roadmap
- [ ] Build step: registry CSV -> `uhin.tmLanguage.json` keyword list (per language or merged).
- [ ] Injection grammar so the canonical (Latin) and native keyword both highlight.
- [ ] Bracket/scope rules per the HindiC++ spec.
- [ ] Marketplace publish.

Contribute via an issue/PR. Code GPL-3.0-or-later; docs/posters CC BY 4.0. (C) 1993-2026 Abhishek Choudhary.
