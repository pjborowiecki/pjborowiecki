# Hi 👋, I'm Piotr.
**Full-Stack Software Engineer · Payments & ISO 20022**

I build software across enterprise systems and independent product development. At **IBM**, I work in the **Financial Transaction Manager (FTM)** team. FTM is a payment-processing platform that financial institutions use to orchestrate and monitor their payments. My main area is payment message entry and repair, across both the user interface and the backend-for-frontend services.

Alongside IBM, I build my own projects in public, including **[SaaSyLand](https://github.com/saasyland/saasyland.com)**, an open-source foundation for production-ready SaaS apps, and two project-based course sites, **[reactprojects.com](https://reactprojects.com)** and **[angularprojects.com](https://angularprojects.com)**, which are in progress. Before IBM, I freelanced full-time, designing and delivering complete products for clients and owning everything from architecture and data modelling to backend, interface, deployment and support.

In all of these settings, most of my work has been about handling complexity: large forms with strict validation, data-heavy tables and filtering, booking and checkout flows, and payment data that has to be exactly right. I care about accessibility, performance and code that's still maintainable years later. The projects I enjoy most have a complex domain behind them: financial data, detailed standards, real-time updates, and workflows where small mistakes are expensive.

<br>

### Technical Ecosystem

| | Core | Regular | Familiar |
|---|---|---|---|
| **Languages** | `TypeScript` `JavaScript` | `Go` `Python` `Java` | `Kotlin` `C++` |
| **Frontend** | `React` `TanStack Start` `TanStack Router` `TanStack Query` `TanStack Table` `TanStack Form` `Next.js` `React Router (Remix)` `Carbon Design System` `Tailwind CSS` | `Angular` `Analog` `Spartan` | `Vue` `Nuxt` |
| **Backend** | `Node.js` `Bun` `Express` `REST` `tRPC` `oRPC` `Better Auth` `PostgreSQL` `SQLite` `Drizzle ORM` `Cloudflare D1` | `NestJS` `GraphQL` `gRPC` `Microservices` | `Spring Boot` `Kafka` `Redis` `MongoDB` |
| **Infra & Testing** | `Cloudflare Workers` `Git` `GitHub Actions` `Vitest` `React Testing Library` `Playwright` |  `Docker`  | `AWS` `Kubernetes` |

**Domain & practices:** ISO 20022 (pain, pacs) · payment message entry and repair · XML ⇄ JSON mapping · accessibility (WCAG) · i18n and time zones · WebSockets · auth and billing integrations · AI-assisted and agentic development · machine learning with PyTorch (deep learning, reinforcement learning, time-series forecasting)

<br>

### Open Source

I fix bugs upstream in the libraries I build with. Each fix includes a regression test.

**Merged and released**

* **[Video.js](https://github.com/videojs/video.js)** (40k+ stars)
  * [#9765](https://github.com/videojs/video.js/pull/9765): thumbnails stopped loading with HLS media adapters, because the track lookup rejected any media that wasn't an HTML element. Shipped in `@videojs/utils` 10.5.0.
* **[Fumadocs](https://github.com/fuma-nama/fumadocs)** (13k+ stars)
  * [#3826](https://github.com/fuma-nama/fumadocs/pull/3826): the MDX client loader typed every page's `frontmatter` and `default` exports as `unknown`, a type regression for all of its users. Shipped in `fumadocs-mdx` 15.6.1.
  * [#3856](https://github.com/fuma-nama/fumadocs/pull/3856): with TanStack Router, `usePathname()` gave components that mount during a navigation the next page's path, causing React hydration mismatches. Shipped in `fumadocs-core` 16.19.3.
  * [#3857](https://github.com/fuma-nama/fumadocs/pull/3857): every code block rendered an unnamed region landmark, so any page with two or more failed axe-core's `landmark-unique` accessibility rule. Shipped in `fumadocs-ui` 16.19.3.
* **[Takumi](https://github.com/kane50613/takumi)** (3k+ stars)
  * [#2560](https://github.com/kane50613/takumi/pull/2560): in the Rust rendering core, a font registered as `Geist` was hidden by the built-in, Latin-only Geist, so Cyrillic and Latin Extended text rendered as missing-glyph boxes, including through `googleFonts(["Geist"])`. Merged with follow-up commits from the maintainer. Shipped in Takumi 2.21.0.

**Landed by the maintainer, crediting my patch**

* **[Motion](https://github.com/motiondivision/motion)** (35k+ stars)
  * [#4089](https://github.com/motiondivision/motion/issues/4089): `LazyMotion` turned a failed async `features` import into an unhandled promise rejection. The repository only accepts pull requests from collaborators, so I posted a fix with a test on a branch, and the maintainer landed the same approach in [#4093](https://github.com/motiondivision/motion/pull/4093).

**In review**

* **[TanStack Router](https://github.com/TanStack/router)** (15k+ stars)
  * [#8934](https://github.com/TanStack/router/pull/8934): with SSR scroll restoration, the first render after hydration scrolled the window back to the top, undoing any scrolling a visitor did while the page hydrated.

<br>

### Experience

**IBM – Software Engineer, Financial Transaction Manager** · *Jul 2024 – present*

* **Message entry and repair:** I build the flows for creating, viewing and repairing pain.001, pacs.008, pacs.009 and other ISO 20022 messages, on both the UI and the backend-for-frontend, working closely with other engineers. Recently I've focused mostly on repair, where operators fix payments that couldn't be processed automatically.
* **Core data table:** I was entrusted with, and responsible for, replacing the deprecated Carbon for IBM Products Datagrid, one of the most important components in the product. I built the new table from scratch on TanStack Table with Carbon Design System components, following Carbon's recommended migration path, and other engineers have extended it since.
* **Time zones and formatting:** responsible for time-zone handling and locale-aware formatting of dates, numbers and currency amounts across the application. These were handled inconsistently from screen to screen, so I built one shared approach and moved a large part of the application onto it.
* **Backend-for-frontend:** parsing and generating ISO 20022 XML, transforming and validating JSON payloads, and mapping deeply nested message structures in both directions.
* **AI-assisted development:** daily use of AI coding tools and agents within enterprise standards for code review, security and quality.
* **Enterprise-scale quality:** large multi-section forms with standard-driven validation, plus accessibility, performance and maintainability in a large, long-lived codebase.

**Freelance – Software Engineer** · *Mar 2022 – Jun 2024*

* **E-commerce:** a bilingual storefront and back office for a jewellery brand, with customer accounts, order management and an audit log, running serverless on Cloudflare.
* **Booking:** a website with online appointment booking and authentication for a veterinary clinic (Next.js, TypeScript, PostgreSQL). The code is [open source](https://github.com/pjborowiecki/ARKA-Veterinary-Clinic-Page-and-Appointment-Booking-System), with 160+ stars.
* **Working with clients:** as the sole engineer, turning business needs into requirements, estimating and planning work, and explaining technical trade-offs to non-technical owners.
* **Open source:** created [SaaSyLand](https://github.com/saasyland/saasyland.com), an open-source starter kit for production-ready SaaS apps, with 430+ stars and 100+ forks.

<br>

### Education

**BSc (Hons) Computer Science, Durham University (UK)** · *2019 – 2023* <br />
Dissertation: *Probabilistic Time Series Forecasting with Diffusion*. <br />
Modules included Reinforcement Learning (98%, the top result in my year) and Deep Learning.

<br>

### Interests
* **Modern web development** <br />
I built my first websites at 16, for the bands I played drums in, and local businesses were soon asking me to build theirs. I still spend a lot of my own time on modern full-stack web development: building projects, trying new tools and following where the ecosystem is heading.
* **Markets** <br />
Outside of work, I trade and invest actively, and markets have been a big interest of mine for years, including the quantitative side.
* **AI-assisted engineering** <br />
I work with AI coding agents every day, and in my experience the results depend less on the model than on what surrounds it: a well-built harness, clear guardrails, solid tests, and an engineer's judgement about what to accept and what to throw away.

<br>

### Let's Connect
**[LinkedIn](https://www.linkedin.com/in/pjborowiecki/)** | **[Email](mailto:hello@pjborowiecki.com)**
