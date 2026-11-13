# Hi 👋, I'm Piotr.
**Full-Stack Software Engineer · Payments & ISO 20022**

I work across enterprise systems and independent product development. At **IBM**, I work in the **Financial Transaction Manager (FTM)** team. FTM is a payment-processing platform that financial institutions use to orchestrate and monitor their payments. My main area is payment message entry and repair, across both the user interface and the backend-for-frontend services.

Alongside IBM, I build my own projects, including **[SaaSyLand](https://github.com/saasyland/saasyland.com)**, an open-source foundation for production-ready SaaS apps, and the learning platforms **[reactprojects.com](https://reactprojects.com)** and **[angularprojects.com](https://angularprojects.com)**. Before IBM, I freelanced full-time, designing and delivering complete products for clients and owning everything from architecture and data modelling to backend, interface, deployment and support.

In all of these settings, most of my work has been about handling complexity: large forms with strict validation, data-heavy tables and filtering, booking and checkout flows, and payment data that has to be exactly right. I care about accessibility, performance and code that's still maintainable years later. The projects I enjoy most have a complex domain behind them: financial data, detailed standards, real-time updates, and workflows where small mistakes are expensive.

<br>

### Technical Ecosystem

| | Core | Regular | Familiar |
|---|---|---|---|
| **Languages** | `TypeScript` `JavaScript` | `Go` `Python` | `Java` `Kotlin` |
| **Frontend** | `React` `TanStack Start` `TanStack Router` `TanStack Query` `TanStack Table` `TanStack Form` `Next.js` `React Router (Remix)` `Carbon Design System` `Tailwind CSS` | `Angular` `Analog` `Spartan` | `Vue` `Nuxt` |
| **Backend** | `Node.js` `Bun` `Express` `REST` `tRPC` `oRPC` `Better Auth` `PostgreSQL` `SQLite` `Drizzle ORM` `Cloudflare D1` | `NestJS` `GraphQL` `gRPC` `Microservices` | `MongoDB` |
| **Infra & Testing** | `Docker` `Cloudflare Workers` `Git` `GitHub Actions` `Vitest` `React Testing Library` `Playwright` | `Vercel` `Neon` | `AWS` `Kubernetes` |

**Domain & practices:** ISO 20022 (pain, pacs) · payment message entry and repair · XML ⇄ JSON mapping · accessibility (WCAG) · i18n and time zones · WebSockets · auth and billing integrations · AI-assisted and agentic development

<br>

### Education & Background
* **BSc (Hons) Computer Science, Durham University (UK)** · *2019 – 2023* <br />
  Modules included deep learning and reinforcement learning. <br /> <br />
* **Before engineering** <br />
  I built my first websites at 16, for the bands I played drums in, and local businesses were soon asking me to build theirs.
  
  Before moving into engineering full-time, I spent around a decade in hospitality in England, working my way up to assistant manager. That meant running teams and shifts, handling pressure, resolving conflicts and dealing directly with unhappy customers. It still shapes how I work: I communicate clearly, stay calm when things go wrong, and keep the people using the product in view.

<br>

### Experience
* **IBM – Software Engineer, Financial Transaction Manager** · *Jul 2024 – present* <br />
  Full-stack engineer on FTM's web layer, working across the user interface and the Node.js backend-for-frontend services.
  * **Message entry and repair:** my main area. I build the flows for creating, viewing and repairing pain.001, pacs.008, pacs.009 and other ISO 20022 messages, on both the UI and the backend-for-frontend, working closely with other engineers. Recently I've focused mostly on repair, where operators fix payments that couldn't be processed automatically.
  * **Core data table:** I was entrusted with, and responsible for, replacing the deprecated Carbon for IBM Products Datagrid, one of the most important components in the product. I built the new table from scratch on the TanStack Table engine with Carbon Design System components, following Carbon's recommended migration path, and other engineers have extended it since.
  * **Time zones and formatting:** responsible for time-zone handling and locale-aware formatting of dates, numbers and currency amounts across the whole application. This was a real problem when I started: dates, times and amounts were handled inconsistently from screen to screen. Fixing it meant building one shared approach to time zones and formatting, then moving a large part of the application onto it.
  * **Backend-for-frontend:** parsing and generating ISO 20022 XML, transforming and validating JSON payloads, and mapping deeply nested message structures in both directions.
  * **Enterprise-scale quality:** large multi-section forms with standard-driven validation, plus accessibility, performance and maintainability in a large, long-lived TypeScript codebase.

* **Freelance – Software Engineer** · *Mar 2022 – Jun 2024* <br />
  Sole engineer on full-stack products for businesses, working directly with clients and owning everything from requirements to deployment and support.
  * **E-commerce:** a bilingual storefront and back office for a jewellery brand, with catalogue, filtering, cart, wishlist, email and Google sign-in, order management and an audit log, running serverless on Cloudflare.
  * **Booking:** a website with online appointment booking and authentication for a veterinary clinic (Next.js, TypeScript, PostgreSQL).
  * **Working with clients:** turning business needs into requirements, estimating and planning work, and explaining technical trade-offs to non-technical owners.

<br>

### Interests
* **Modern web development**
  I spend a lot of my own time on modern full-stack web development: building projects, trying new tools and following where the ecosystem is heading.
  
* **Markets**
  Outside of work, I trade and invest actively, and markets have been a big interest of mine for years, including the quantitative side.
  
* **System design and AI**
  I work with AI coding agents every day, and in my experience the results depend less on the model than on what surrounds it: a well-built harness, clear guardrails, solid tests, and an engineer's judgement about what to accept and what to throw away.

<br>

### Let's Connect
**[LinkedIn](https://www.linkedin.com/in/pjborowiecki/)** | **[Email](mailto:hello@pjborowiecki.com)** | **[pjborowiecki.com](https://pjborowiecki.com)**
