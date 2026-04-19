# stoating/plugins

A central Claude Code plugin marketplace cataloging all of stoating's plugins and skills for AI coding agents.

Built using [Claude Code's plugin marketplace format](https://code.claude.com/docs/en/plugin-marketplaces), and compatible with any agent that supports the [agents.md](https://agents.md/) convention via the individual plugin repositories.

---

## Installation

Add the marketplace once, then install any plugin from it:

```
/plugin marketplace add stoating/plugins
```

To update the catalog later:

```
/plugin marketplace update stoating
```

---

## Available plugins

| Plugin | Install command | Description |
|--------|----------------|-------------|
| `clojure-polylith` | `/plugin install clojure-polylith@stoating` | Clojure Polylith skill — components, bases, projects, interfaces, poly commands, workspace configuration, profiles, incremental testing, and setup |
| `clojure-aero` | `/plugin install clojure-aero@stoating` | Clojure Aero skill — read-config, tag literals (#env, #profile, #include, #ref, #or, #join, #merge), resolvers, profiles, extending with custom tags, and patterns for secrets, components, and schema validation |
| `clojure-babashka` | `/plugin install clojure-babashka@stoating` | Clojure Babashka skill - fast-starting bb scripts, bb.edn tasks, built-in namespaces, deps, pods, shell/process interop, CLIs, and SCI compatibility |
| `clojure-integrant` | `/plugin install clojure-integrant@stoating` | Clojure Integrant skill — data-driven application architecture, init-key, halt-key!, suspend/resume, refs, refsets, composite keys, derived keywords, profiles, vars, expand-key, and REPL workflow |
| `clojure-flow-storm` | `/plugin install clojure-flow-storm@stoating` | Clojure FlowStorm skill - ClojureStorm setup, vanilla tracing, ClojureScript/shadow debugging, instrumentation controls, data windows, nREPL outputs, remote debugging, and trace limits |
| `clojure-hiccup` | `/plugin install clojure-hiccup@stoating` | Clojure Hiccup skill - HTML-as-data syntax, hiccup2.core rendering, escaping, raw HTML, render modes, page/form helpers, and safe server-side HTML generation |
| `clojure-malli` | `/plugin install clojure-malli@stoating` | Clojure Malli skill - data-driven schemas, validation, explain/humanize, coercion, transformers, generators, function schemas, registries, JSON Schema, Swagger, and CLJS usage |
| `clojure-portal` | `/plugin install clojure-portal@stoating` | Clojure Portal skill — tap-driven data inspection, portal.api, viewers, datafy/nav, nREPL middleware, remote clients, CLI usage, and editor launchers |
| `clojure-reagent` | `/plugin install clojure-reagent@stoating` | ClojureScript Reagent skill — Hiccup components, ratoms, reactions, rendering roots, React interop, hooks, compiler options, SSR, controlled inputs, and React 19 setup |
| `clojure-replicant` | `/plugin install clojure-replicant@stoating` | Clojure Replicant skill — data-driven DOM and string rendering, hiccup syntax, aliases, event handlers, life-cycle hooks, CSS transitions, and node memory |
| `clojure-reitit` | `/plugin install clojure-reitit@stoating` | Clojure/ClojureScript Reitit skill — route syntax, Ring router, middleware, coercion (malli/spec/schema), OpenAPI/Swagger docs, frontend browser routing, and interceptors |
| `clojure-shadow-cljs` | `/plugin install clojure-shadow-cljs@stoating` | ClojureScript shadow-cljs skill — project setup, shadow-cljs.edn builds, targets, watch/release commands, dev-http, REPLs, npm interop, testing, and troubleshooting |

---

## Individual plugin repositories

Each plugin is also available as a standalone single-plugin marketplace from its own repository:

| Plugin | Repository | Standalone install |
|--------|------------|--------------------|
| `clojure-polylith` | [stoating/clojure-polylith-skill](https://github.com/stoating/clojure-polylith-skill) | `/plugin marketplace add stoating/clojure-polylith-skill` then `/plugin install clojure-polylith@clojure-polylith-skill` |
| `clojure-aero` | [stoating/clojure-aero-skill](https://github.com/stoating/clojure-aero-skill) | `/plugin marketplace add stoating/clojure-aero-skill` then `/plugin install clojure-aero@clojure-aero-skill` |
| `clojure-babashka` | [stoating/clojure-babashka-skill](https://github.com/stoating/clojure-babashka-skill) | `/plugin marketplace add stoating/clojure-babashka-skill` then `/plugin install clojure-babashka@clojure-babashka-skill` |
| `clojure-integrant` | [stoating/clojure-integrant-skill](https://github.com/stoating/clojure-integrant-skill) | `/plugin marketplace add stoating/clojure-integrant-skill` then `/plugin install clojure-integrant@clojure-integrant-skill` |
| `clojure-flow-storm` | [stoating/clojure-flow-storm-skill](https://github.com/stoating/clojure-flow-storm-skill) | `/plugin marketplace add stoating/clojure-flow-storm-skill` then `/plugin install clojure-flow-storm@clojure-flow-storm-skill` |
| `clojure-hiccup` | [stoating/clojure-hiccup-skill](https://github.com/stoating/clojure-hiccup-skill) | `/plugin marketplace add stoating/clojure-hiccup-skill` then `/plugin install clojure-hiccup@clojure-hiccup-skill` |
| `clojure-malli` | [stoating/clojure-malli-skill](https://github.com/stoating/clojure-malli-skill) | `/plugin marketplace add stoating/clojure-malli-skill` then `/plugin install clojure-malli@clojure-malli-skill` |
| `clojure-portal` | [stoating/clojure-portal-skill](https://github.com/stoating/clojure-portal-skill) | `/plugin marketplace add stoating/clojure-portal-skill` then `/plugin install clojure-portal@clojure-portal-skill` |
| `clojure-reagent` | [stoating/clojure-reagent-skill](https://github.com/stoating/clojure-reagent-skill) | `/plugin marketplace add stoating/clojure-reagent-skill` then `/plugin install clojure-reagent@clojure-reagent-skill` |
| `clojure-replicant` | [stoating/clojure-replicant-skill](https://github.com/stoating/clojure-replicant-skill) | `/plugin marketplace add stoating/clojure-replicant-skill` then `/plugin install clojure-replicant@clojure-replicant-skill` |
| `clojure-reitit` | [stoating/clojure-reitit-skill](https://github.com/stoating/clojure-reitit-skill) | `/plugin marketplace add stoating/clojure-reitit-skill` then `/plugin install clojure-reitit@clojure-reitit-skill` |
| `clojure-shadow-cljs` | [stoating/clojure-shadow-cljs-skill](https://github.com/stoating/clojure-shadow-cljs-skill) | `/plugin marketplace add stoating/clojure-shadow-cljs-skill` then `/plugin install clojure-shadow-cljs@clojure-shadow-cljs-skill` |
