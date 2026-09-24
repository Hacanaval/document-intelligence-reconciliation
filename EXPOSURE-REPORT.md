# Exposure Report — Document Intelligence & Reconciliation

> Date: 2026-09-24  
> Project: document-intelligence-reconciliation  
> Checker: rg with sensitive patterns

## Files checked

- `README.md`
- `assets/architecture.mmd`
- `assets/dashboard-mockup.html`
- `assets/dashboard-mockup.png` (visual inspection only)

## Patterns checked

- `coordinadora`
- `cm-analitica`
- `ext_`
- `dwh_`
- `public_`
- `novedad`
- `sigo`
- `890904713`
- `@coordinadora\.com`
- `hcanaval@coordinadora\.com`
- revision-style hashes
- long alphanumeric identifiers
- `projects/[a-z0-9-]+`

## Result

No sensitive patterns found in any text file.

## Visual assets reviewed

- `assets/dashboard-mockup.png` contains only fictional data:
  - fake voucher IDs (V-20260924-001)
  - fake references (REF-88421, REF-91204)
  - generic amounts in COP without real account context
- No real bank names, account numbers, or merchant data.

## Conclusion

Safe to publish.
