## Nikita Koreshkov

I build web products end to end: the interface layer, the API behind it, and the database under that. Most of my work is client-facing sites for real businesses, where the design is heavy and the device budget is not, so a large part of what I do is making motion affordable.

### Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| [luno-agency](https://github.com/NikitaKoreshkov/luno-agency) | Site and client area for a digital agency. WebGPU scroll headline, refracting glass header, frame-budget watchdog, Postgres auth with OTP and Google sign-in. [Live](https://luno-agency-nknpro.vercel.app) | Next.js 16, three.js/WebGPU, GSAP, Postgres |
| [FinKeyMemory](https://github.com/NikitaKoreshkov/FinKeyMemory) | Four-tier temporal memory for AI agents: as-of fact store, scene blocks, self-regenerating persona, maintenance cycle. Published to PyPI. | Python |
| [ledvl-store](https://github.com/NikitaKoreshkov/ledvl-store) | Lighting-equipment store for a Vladivostok supplier: price-list filter engine, admin panel, Excel import, Docker Compose stack. Running in production at ledvl.ru. | Next.js 14, NestJS 11, PostgreSQL, MinIO |
| [stepwave-store](https://github.com/NikitaKoreshkov/stepwave-store) | Sneaker storefront on Spring Boot with a Thymeleaf catalog, email-code reset and a client area. Revisited in 2026: the README lists the defects found against the running app and how each was fixed. | Java 17, Spring Boot, PostgreSQL |
| [pechnoyproekt](https://github.com/NikitaKoreshkov/pechnoyproekt) | Catalog, cost calculator and portfolio for a construction business. | Next.js, TypeScript |
| [4snab](https://github.com/NikitaKoreshkov/4snab) | Warehouse manager interface with amoCRM integration. | Next.js, TypeScript |

### What I optimize for

- Frame budgets over frame drops. Effects get a measured device tier and a downgrade path instead of a fixed GPU assumption.
- Auth that is boring and correct: hashed OTP, short-lived digests, server-side session revocation, rate limits in the database rather than in memory.
- Pages that ship as HTML first. Heavy sections mount lazily, so the first paint never waits on a shader.

### Toolchain

TypeScript, React and Next.js across the front end; Tailwind and CSS modules for styling; Node and Python on the backend; Postgres for storage; Vercel for delivery.
