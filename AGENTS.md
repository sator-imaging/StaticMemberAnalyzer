# References
- When implementing codefix provider: [Read this](./src/README.md)
- When using LINQ (System.Linq): [Read this](./src/README.md#linq-migration-guide)
- When adding new tests: [Read this](./test/README.md)
- Diagnostic reporting location fallback: Analyzers must always report diagnostics; when primary locations are null or missing, fall back to context node or symbol locations rather than exiting early.
