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

---

## Individual plugin repositories

Each plugin is also available as a standalone single-plugin marketplace from its own repository:

| Plugin | Repository | Standalone install |
|--------|------------|--------------------|
| `clojure-polylith` | [stoating/clojure-polylith-skill](https://github.com/stoating/clojure-polylith-skill) | `/plugin marketplace add stoating/clojure-polylith-skill` then `/plugin install clojure-polylith@clojure-polylith-skill` |
