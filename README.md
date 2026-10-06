# Hi, I'm Musa

I build developer tools and the software that runs my companies.

I founded [Heraklet](https://heraklet.com). We do certification engineering for critical systems. I am an ISO/IEC 27001 Lead Auditor and an ISMS Lead Implementer, so security is part of how I ship.

My focus now is TypeScript performance.

## whyts: why is my TypeScript project slow?

[![npm version](https://img.shields.io/npm/v/whyts)](https://www.npmjs.com/package/whyts)

Large TypeScript projects become slow. `tsc` takes 30 seconds, then 60. The editor starts to lag. Most teams guess the cause. [whyts](https://github.com/musatoktas/whyts) measures it.

```sh
npx whyts --project .
```

whyts runs your own TypeScript compiler with `--generateTrace` and `--extendedDiagnostics`. Then it reads the trace. It finds the source expressions and the type comparisons that use the most check time.

What you get:

- **Measured hot spots**: the `file:line`, the check time, and the type comparison inside that check.
- **Project structure findings**: broad `include` patterns, barrel files with a large reach, and duplicate `@types` versions.
- **`whyts explain <file>`**: the import chain that puts a file in your program.
- **JSON output** for CI and scripts.

whyts does not guess. Each finding has a label: measured, observed, or review. It does not change your code. It makes no network calls. You do not need an account, an API key, or an LLM.

On a private codebase with 900,000 lines of TypeScript, whyts found the same type hot spot that engineers found by hand.

## Open source

I contribute to TypeScript and to the tools around it. I measure before I change code.

See [all my contributions](CONTRIBUTIONS.md).

## Things I run

- **[PayPartner](https://paypartner.ae)**: E-invoicing and business management software for companies in the UAE.
- **[MBD Travel](https://mbdtravel.com)**: A travel commerce platform for tours, hotels, and experiences.

## Ask me about

- TypeScript type-check performance
- ISO/IEC 27001 and information security management
- Certification engineering and compliance

## Contact

- Email: [musa.toktas@heraklet.com](mailto:musa.toktas@heraklet.com)
