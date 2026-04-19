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
| `polylith` | `/plugin install polylith@stoating` | Clojure Polylith skill — components, bases, projects, interfaces, poly commands, workspace configuration, profiles, incremental testing, and setup |
| `aero` | `/plugin install aero@stoating` | Clojure Aero skill — read-config, tag literals (#env, #profile, #include, #ref, #or, #join, #merge), resolvers, profiles, extending with custom tags, and patterns for secrets, components, and schema validation |
| `babashka` | `/plugin install babashka@stoating` | Clojure Babashka skill - fast-starting bb scripts, bb.edn tasks, built-in namespaces, deps, pods, shell/process interop, CLIs, and SCI compatibility |
| `clojure-mcp` | `/plugin install clojure-mcp@stoating` | ClojureMCP skill - MCP server setup, CLI assistant and Claude Desktop integration, nREPL connection, tool profiles, config.edn, custom tools/prompts/resources, and troubleshooting |
| `integrant` | `/plugin install integrant@stoating` | Clojure Integrant skill — data-driven application architecture, init-key, halt-key!, suspend/resume, refs, refsets, composite keys, derived keywords, profiles, vars, expand-key, and REPL workflow |
| `flow-storm` | `/plugin install flow-storm@stoating` | Clojure FlowStorm skill - ClojureStorm setup, vanilla tracing, ClojureScript/shadow debugging, instrumentation controls, data windows, nREPL outputs, remote debugging, and trace limits |
| `hiccup` | `/plugin install hiccup@stoating` | Clojure Hiccup skill - HTML-as-data syntax, hiccup2.core rendering, escaping, raw HTML, render modes, page/form helpers, and safe server-side HTML generation |
| `malli` | `/plugin install malli@stoating` | Clojure Malli skill - data-driven schemas, validation, explain/humanize, coercion, transformers, generators, function schemas, registries, JSON Schema, Swagger, and CLJS usage |
| `portal` | `/plugin install portal@stoating` | Clojure Portal skill — tap-driven data inspection, portal.api, viewers, datafy/nav, nREPL middleware, remote clients, CLI usage, and editor launchers |
| `reagent` | `/plugin install reagent@stoating` | ClojureScript Reagent skill — Hiccup components, ratoms, reactions, rendering roots, React interop, hooks, compiler options, SSR, controlled inputs, and React 19 setup |
| `replicant` | `/plugin install replicant@stoating` | Clojure Replicant skill — data-driven DOM and string rendering, hiccup syntax, aliases, event handlers, life-cycle hooks, CSS transitions, and node memory |
| `reitit` | `/plugin install reitit@stoating` | Clojure/ClojureScript Reitit skill — route syntax, Ring router, middleware, coercion (malli/spec/schema), OpenAPI/Swagger docs, frontend browser routing, and interceptors |
| `shadow-cljs` | `/plugin install shadow-cljs@stoating` | ClojureScript shadow-cljs skill — project setup, shadow-cljs.edn builds, targets, watch/release commands, dev-http, REPLs, npm interop, testing, and troubleshooting |
| `clojure` | `/plugin install clojure@stoating` | Clojure style guide skill — formatting, naming, idiomatic patterns, namespace organization, functions, macros, documentation, and testing conventions |

---

## Individual plugin repositories

Each plugin is also available as a standalone single-plugin marketplace from its own repository:

| Plugin | Repository | Standalone install |
|--------|------------|--------------------|
| `polylith` | [stoating/clojure-polylith-skill](https://github.com/stoating/clojure-polylith-skill) | `/plugin marketplace add stoating/clojure-polylith-skill` then `/plugin install polylith@clojure-polylith-skill` |
| `aero` | [stoating/clojure-aero-skill](https://github.com/stoating/clojure-aero-skill) | `/plugin marketplace add stoating/clojure-aero-skill` then `/plugin install aero@clojure-aero-skill` |
| `babashka` | [stoating/clojure-babashka-skill](https://github.com/stoating/clojure-babashka-skill) | `/plugin marketplace add stoating/clojure-babashka-skill` then `/plugin install babashka@clojure-babashka-skill` |
| `clojure-mcp` | [stoating/clojure-clojure-mcp-skill](https://github.com/stoating/clojure-clojure-mcp-skill) | `/plugin marketplace add stoating/clojure-clojure-mcp-skill` then `/plugin install clojure-mcp@clojure-clojure-mcp-skill` |
| `integrant` | [stoating/clojure-integrant-skill](https://github.com/stoating/clojure-integrant-skill) | `/plugin marketplace add stoating/clojure-integrant-skill` then `/plugin install integrant@clojure-integrant-skill` |
| `flow-storm` | [stoating/clojure-flow-storm-skill](https://github.com/stoating/clojure-flow-storm-skill) | `/plugin marketplace add stoating/clojure-flow-storm-skill` then `/plugin install flow-storm@clojure-flow-storm-skill` |
| `hiccup` | [stoating/clojure-hiccup-skill](https://github.com/stoating/clojure-hiccup-skill) | `/plugin marketplace add stoating/clojure-hiccup-skill` then `/plugin install hiccup@clojure-hiccup-skill` |
| `malli` | [stoating/clojure-malli-skill](https://github.com/stoating/clojure-malli-skill) | `/plugin marketplace add stoating/clojure-malli-skill` then `/plugin install malli@clojure-malli-skill` |
| `portal` | [stoating/clojure-portal-skill](https://github.com/stoating/clojure-portal-skill) | `/plugin marketplace add stoating/clojure-portal-skill` then `/plugin install portal@clojure-portal-skill` |
| `reagent` | [stoating/clojure-reagent-skill](https://github.com/stoating/clojure-reagent-skill) | `/plugin marketplace add stoating/clojure-reagent-skill` then `/plugin install reagent@clojure-reagent-skill` |
| `replicant` | [stoating/clojure-replicant-skill](https://github.com/stoating/clojure-replicant-skill) | `/plugin marketplace add stoating/clojure-replicant-skill` then `/plugin install replicant@clojure-replicant-skill` |
| `reitit` | [stoating/clojure-reitit-skill](https://github.com/stoating/clojure-reitit-skill) | `/plugin marketplace add stoating/clojure-reitit-skill` then `/plugin install reitit@clojure-reitit-skill` |
| `shadow-cljs` | [stoating/clojure-shadow-cljs-skill](https://github.com/stoating/clojure-shadow-cljs-skill) | `/plugin marketplace add stoating/clojure-shadow-cljs-skill` then `/plugin install shadow-cljs@clojure-shadow-cljs-skill` |
| `clojure` | [stoating/clojure-clojure-skill](https://github.com/stoating/clojure-clojure-skill) | `/plugin marketplace add stoating/clojure-clojure-skill` then `/plugin install clojure@clojure-clojure-skill` |
