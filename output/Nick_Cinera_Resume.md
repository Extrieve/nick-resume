# Nick Cinera

Full-Stack Trading Systems Engineer | Low-Latency UI, Event-Driven Architecture, Capital Markets

New York, NY | 386-212-8631 | nicolas.cinera@gmail.com | linkedin.com/in/nickcinera | github.com/Extrieve

Goldman Sachs engineer building latency-sensitive trading platforms across React, TypeScript, Redux, AG Grid, Java, and WebSocket. Owns production workflows end-to-end: low-latency UI rendering, event-driven distributed systems, server-authoritative streaming models, feature-canary migrations, release configuration, and trader-facing reliability. Adept at using AI workflows and agentic coding systems to accelerate codebase navigation, design exploration, debugging, test generation, and technical writing while keeping validation rigorous.

## Core Strengths

- Trading Systems: Equity derivatives RFQ/RFS, DCM new issue workflows, pricing grids, P&L / fees, investor analytics
- Frontend Architecture: React, TypeScript, Redux Toolkit, redux-observable / RxJS, AG Grid Enterprise, Cypress, Jest, Karma/Jasmine
- Backend & Platform: Java, WebSocket streaming, REST APIs, distributed systems, Node.js, Python, Go, SQL, Docker, AWS, CI/CD
- Performance: Low-latency frontend performance, large-grid rendering, diff-based streaming, state synchronization, payload reduction
- Ownership: End-to-end product delivery, cross-team release engineering, migration planning, production hardening
- Foundations: Algorithms, C/C++, Java certification, machine-learning graduate study, competitive-programming leadership
- AI Workflows: Agentic coding systems, repo-aware code generation, AI-assisted debugging/refactoring, test scaffolding, review prep
- Systems Design: Server-authoritative projections, normalized/denormalized models, event handlers, shared domain libraries
- Delivery Quality: Production reliability, canary rollouts, parity validation, regression discipline, feature flags, safe migration sequencing

## Experience

### Goldman Sachs - Software Engineer, Global Markets - Equities
Apr 2025 - Present | New York, NY

- Technical owner for a real-time, multi-leg pricing grid used by traders to price and structure equity-derivatives RFQ/RFS inquiries; owns the React/TypeScript UI, Java server tier, WebSocket stream, and declarative release configuration.
- Migrated a legacy client-heavy pricer to a server-authoritative, event-driven streaming architecture behind a feature canary, running old and new paths in parallel through layout/parity validation before retiring legacy code.
- Implemented server-computed table layouts spanning tabs, columns, nested per-leg child grids, expansion state, styling, formatting, and cell renderers so the client stays thin and optimized for interaction/rendering.
- Modeled both normalized and denormalized projections for the same portfolio, enabling single-table and per-leg nested-grid views from a shared server-side layout engine and preserving parity with legacy trader workflows.
- Reduced redundant per-tick WebSocket payloads by publishing only changed table structure through value-equality / diff-based streaming and removing fields serialized on every market or valuation event.
- Delivered 378 commits across 1,437 files over 12 months (+55,204 / -19,575 LOC), including 188 commits on the pricing-grid/data layer and 35 of 38 server-tier commits in the core pricing engine.
- Uses AI-assisted and agentic engineering workflows for codebase search, implementation planning, refactor decomposition, test-case ideation, and review checklists while grounding changes in local builds, specs, and production constraints.

### Goldman Sachs - Software Engineer, Investment Banking - Debt Capital Markets
Feb 2023 - Apr 2025 | New York, NY

- Owned two production trading applications used daily by syndicate bankers, traders, and capital-markets originators for bond and loan new-issue workflows: investor targeting, demand aggregation, pricing/allocation, trade booking, and P&L / fee reconciliation.
- Built AG Grid-heavy React/TypeScript surfaces across two state paradigms: a Redux Toolkit / Module Federation investor-analytics host and a classic Redux + redux-observable syndicate-link platform.
- Maintained a Module Federation host that loaded federated investor-analytics remotes with runtime-injected origins across dev / QA / prod while keeping shared React/Redux dependencies singleton-safe.
- Built a cross-tab user-preferences framework for major grid views, persisting per-user column order, visibility, widths, pin state, and drag/reorder rules while unifying CSV/Excel export behavior with on-screen layout.
- Owned the syndicate-link P&L tab end-to-end, including GS Fees, Controllers Flash, Synd Fees, and Deal Table grids, with editable cell navigation, dirty-field highlighting, precision rules, value setters, and audit labeling.
- Led an investor-participation query workflow from input form to API, grid, and export, including multi-currency demand aggregation, conversion toggles, incompatible-mode suppression, export parity, and user-group tab gating.
- Managed Funds Flow integration through versioned NPM packages and branch-conditional CI install rules so integration testing could float against upstream releases without destabilizing production trains.
- Drove framework and dependency migrations across managed CI/CD pipelines, including React 17 to 18, AG Grid 23 to 30, node-sass removal, Highcharts upgrades, LaunchDarkly SDK upgrades, GS UI Toolkit upgrades, and Node/NPM version bumps.

### Goldman Sachs - Software Engineer Intern
Jun 2022 - Aug 2022 | Dallas, TX

- Returned full-time after internship; built production engineering context in a regulated financial-services environment.

## Education, Certifications & Leadership

### University of South Florida - M.S., Computer and Information Systems - Machine Learning Concentration
Dec 2022

- Technical Chairman, USF Society of Competitive Programmers; led ICPC-style preparation, coached students through algorithmic problem solving, and built training around data structures, complexity, correctness, and reasoning under constraints.
- Oracle Certified Professional, Java SE 8 Programmer II; Oracle Certified Associate, Java SE 8 Programmer. Bilingual English / Spanish.
