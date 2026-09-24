<h1 align="center">Vivarium Collective</h1>

<p align="center"><em>Compose living models.</em></p>

<p align="center">
  <a href="https://vivarium-collective.github.io/viva-docs/"><b>📖 Read the Users Guide →</b></a>
</p>

---

**Vivarium** is a framework for building **multiscale biological models** by composing
independently-written simulators into one executable whole — and for turning the runs into
**auditable scientific evidence**. Independent formalisms (ODEs, flux-balance analysis,
PDEs, agent-based models) are wrapped as typed **Processes** and wired together through
explicit, checkable interfaces, so new science is a *new study*, not a patch to the model.

## Start here

### 📖 [The Vivarium Users Guide](https://vivarium-collective.github.io/viva-docs/)

The comprehensive guide to the whole ecosystem — foundations, building & running models,
turning runs into evidence, and a full reference. Includes a [quick start](https://vivarium-collective.github.io/viva-docs/quickstart/),
an [interactive bigraph explorer](https://vivarium-collective.github.io/viva-docs/explore/),
and a [searchable module catalog](https://vivarium-collective.github.io/viva-docs/catalog/).

## The stack

| Package | What it is |
|---|---|
| [**bigraph-schema**](https://github.com/vivarium-collective/bigraph-schema) | The type system beneath every store — types, ports, and the `apply` law that merges deltas so independent processes compose. |
| [**process-bigraph**](https://github.com/vivarium-collective/process-bigraph) | The engine and the composite / process / step / template primitives — the tick scheduler and the emitters that record state. |
| [**vivarium-workbench**](https://github.com/vivarium-collective/vivarium-workbench) | The AI-free dashboard server — investigations, studies, runs, analyses, and report cards, with every change committed to git. |
| [**viva-superpowers**](https://github.com/vivarium-collective/viva-superpowers) | The `/viva-*` Claude Code skills that author and run everything through the Workbench. All AI lives here, so the tool stays auditable. |

## Reference

The framework is described in **Agmon &amp; Spangler, *Process bigraphs and the architecture
of compositional systems biology*** (arXiv:2512.23754), which introduces **Vivarium 2.0** as
the open-source implementation, demonstrated with the **Spatio-Flux** microbial-ecosystem library.
