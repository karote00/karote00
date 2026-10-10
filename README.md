# I build systems that make complex things easier to change.

**Asa Tsai · Software architect · Taipei**

10+ years building frontend systems, design tools, and the architecture behind them.

I keep coming back to one question: **why should adding one feature require understanding the whole application?**

Years before Asyra, I proposed this direction at my previous company. It wasn't adopted, but the idea stayed with me. After leaving, I wrote it down as [Communication-Driven Development (CDD)](https://github.com/karote00/cdd-example/tree/main/docs-site/docs/concept): start with what needs to be communicated, and make responsibilities clear to both the system and the people building it.

[Asyra](https://github.com/karote00/asyra) grew out of those principles. I'm building it so the next person can understand, change, and extend a product without needing me beside them.

[Read the CDD docs](https://github.com/karote00/cdd-example/blob/main/docs-site/docs/concept/what-is-cdd.md)

## One foundation. Different worlds.

Asyra handles the shared infrastructure: editable state, transactions, Undo/Redo, and clear ownership. Each app brings its own rules and its own world.

### Design

A canvas editor with editable vectors, Undo/Redo, and optional AI and collaboration. A working product built on the same foundation.

[![Asyra Design: an editable cat drawing inside the canvas editor](https://raw.githubusercontent.com/karote00/asyra/main/apps/asyra-framework-site/public/product-evidence/asyra-design-7076-product-evidence.webp)](https://github.com/karote00/asyra/blob/main/docs/public/cases/asyra-design.md)

[Explore the editor](https://github.com/karote00/asyra/tree/main/apps/asyra-design) · [Follow the architecture](https://github.com/karote00/asyra/blob/main/docs/public/cases/asyra-design.md)

### Simulation

I'm starting with a robot workcell to build the architecture for a larger goal: simulating factory processes, including semiconductor fabs, to find problems before they happen on the floor. Over time, I want to bring my earthquake engineering background into building and factory safety analysis too. The current workbench explores geometry, clearance, and motion; it's an early development checkpoint.

[![Asyra Sim: a robot workcell in the experiment workbench](https://raw.githubusercontent.com/karote00/asyra/main/apps/asyra-framework-site/public/product-evidence/asyra-sim-workcell.webp)](https://github.com/karote00/asyra/tree/main/apps/asyra-sim)

[Explore the workbench](https://github.com/karote00/asyra/tree/main/apps/asyra-sim)

### FieldScope

A greenhouse modeling workspace with structures, crops, and a robot concept. The scene exists; patrol and harvesting simulation are still ahead.

[![FieldScope: a modeled greenhouse with crop rows](https://raw.githubusercontent.com/karote00/asyra/main/apps/asyra-framework-site/public/product-evidence/fieldscope-greenhouse.webp)](https://github.com/karote00/asyra/tree/main/apps/fieldscope)

[Explore the greenhouse](https://github.com/karote00/asyra/tree/main/apps/fieldscope)

## Make it easier to pick up the work.

The same question shows up in my other tools:

- [handoff-ai](https://github.com/karote00/handoff-ai) keeps project knowledge available across people, agents, and sessions.
- [context-rag](https://github.com/karote00/context-rag) finds the project context an agent needs for the task at hand.
- [local-leetcode-trainer](https://github.com/karote00/local-leetcode-trainer) brings coding practice and AI guidance into a local workflow.

I care about clear boundaries, predictable changes, and leaving enough context for whoever comes next. A good demo gets my attention. Being able to keep changing it is what makes me stay.

---

Taipei, Taiwan · Remote collaboration

[Let's talk on LinkedIn](https://www.linkedin.com/in/kunlung-tsai-00b0bb99/) · [Read the Asyra docs](https://github.com/karote00/asyra/blob/main/docs/public/index.md)
