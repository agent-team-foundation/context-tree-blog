# Blog Series Plan

## Overview

Five blog posts for the Context Tree / kael.im open source launch. Each essay defines one concept clearly and explores its consequences. Standalone but building on the last. Same tone across all: aw.network/ludens style, thinking clearly in public, not selling.

## Style Rules

- Same aw.network/ludens tone
- No dashes
- _Italics_ on key terms when first introduced
- Name patterns and concepts (like _context routing_ in Blog 1)
- Diagrams in each post
- Meme at the end of each post
- Same HTML template/CSS
- ~1500-2000 words each

## The Sequence

```
Blog 1: "The Missing Memory" ✅ DONE
  Problem + Context Tree concept.
  Reader leaves knowing: agents have no memory,
  context routing is the pattern, Context Tree is the fix.
        │
        ▼
Blog 2: "Agents Are Teammates, Not Tools"
  One idea: what changes when agents are peers, not utilities.
  Source: what-is-agent-team.md, members/NODE.md
  
  Defines: what a "tool" is vs what a "teammate" is.
  Examples: Alice owns strategy. Agent A owns backend.
  Agent A reviews PRs that touch its domain. Agent B
  asks Agent A for context before making a change.
  The team has 2 humans and 3 agents, and they all
  show up in the members/ subtree the same way.
        │
        ▼
Blog 3: "Ownership All the Way Down"
  One idea: every piece of knowledge needs an owner.
  Source: ownership-and-naming.md, NODE.md
  
  Defines: what "ownership" means in a Context Tree.
  NODE.md as the authority. Inheritance rules.
  Why a wiki fails (no ownership = no accountability = decay).
  Why CODEOWNERS generation from the tree is powerful.
  Concrete example: walk through a real tree structure,
  show who can approve what.
  
  This is the design essay. Opinionated.
  "If nobody owns it, nobody maintains it.
  If nobody maintains it, it dies."
        │
        ▼
Blog 4: "The Six Pillars"
  One idea: the full infrastructure stack for agent teams.
  Source: infrastructure.md
  
  This is the big one. Each pillar gets a short section:
  Autonomous Agent, Context Tree, Message System,
  Identity, Database, Workflow.
  
  Not a spec doc. A thesis: "here is everything you need
  to build a team where agents are real participants,
  and here is why each piece exists."
  
  Diagrams: how the 6 pillars connect to each other.
        │
        ▼
Blog 5: "Open Source Your Context"
  One idea: why organizational memory must be open.
  Source: open-source/node.md, NODE.md closing
  
  The philosophical closer.
  Proprietary context is a contradiction.
  The value is adoption, not lock-in.
  Ties back to Blog 1's meme.
  
  This is the Product Hunt launch post.
  Call to action: come build with us.
```

## Distribution Timeline

```
Week 0 (launch):  Blog 1  → HN, Twitter, Reddit
Week 1:           Blog 2  → Twitter thread, Reddit
Week 2:           Blog 3  → HN, Twitter
Week 3:           Blog 4  → HN (infra posts do well), Twitter
Week 4:           Blog 5  → Product Hunt + HN + Twitter + Reddit
```

## Open Questions

1. **Blog 2 vs Blog 3 order**: Blog 2 (teammates) is more accessible, Blog 3 (ownership) is more technical. Accessible first. Good?
2. **Blog 4 length**: infrastructure.md is dense. Should Blog 4 be longer (~3000 words) or split the 6 pillars across two posts?
3. **Blog 5 timing**: Tying it to a Product Hunt launch means we need to coordinate. Is that the plan, or standalone essay?
4. **Author attribution**: Blog 1 says "kael.im". Should future blogs have individual author names?
5. **Any topics missing?** Anything to cover that is not in the repo yet?
