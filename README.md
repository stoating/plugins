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
| `clojure-integrant` | `/plugin install clojure-integrant@stoating` | Clojure Integrant skill — data-driven application architecture, init-key, halt-key!, suspend/resume, refs, refsets, composite keys, derived keywords, profiles, vars, expand-key, and REPL workflow |
| `clojure-replicant` | `/plugin install clojure-replicant@stoating` | Clojure Replicant skill — data-driven DOM and string rendering, hiccup syntax, aliases, event handlers, life-cycle hooks, CSS transitions, and node memory |
| `clojure-reitit` | `/plugin install clojure-reitit@stoating` | Clojure/ClojureScript Reitit skill — route syntax, Ring router, middleware, coercion (malli/spec/schema), OpenAPI/Swagger docs, frontend browser routing, and interceptors |

---

## Individual plugin repositories

Each plugin is also available as a standalone single-plugin marketplace from its own repository:

| Plugin | Repository | Standalone install |
|--------|------------|--------------------|
| `clojure-polylith` | [stoating/clojure-polylith-skill](https://github.com/stoating/clojure-polylith-skill) | `/plugin marketplace add stoating/clojure-polylith-skill` then `/plugin install clojure-polylith@clojure-polylith-skill` |
| `clojure-aero` | [stoating/clojure-aero-skill](https://github.com/stoating/clojure-aero-skill) | `/plugin marketplace add stoating/clojure-aero-skill` then `/plugin install clojure-aero@clojure-aero-skill` |
| `clojure-integrant` | [stoating/clojure-integrant-skill](https://github.com/stoating/clojure-integrant-skill) | `/plugin marketplace add stoating/clojure-integrant-skill` then `/plugin install clojure-integrant@clojure-integrant-skill` |
| `clojure-replicant` | [stoating/clojure-replicant-skill](https://github.com/stoating/clojure-replicant-skill) | `/plugin marketplace add stoating/clojure-replicant-skill` then `/plugin install clojure-replicant@clojure-replicant-skill` |
| `clojure-reitit` | [stoating/clojure-reitit-skill](https://github.com/stoating/clojure-reitit-skill) | `/plugin marketplace add stoating/clojure-reitit-skill` then `/plugin install clojure-reitit@clojure-reitit-skill` |
