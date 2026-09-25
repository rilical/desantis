---
name: desantis
description: Use when a user invokes desantis after rough notes, or wants scattered thoughts connected into distinct alternatives for an idea, piece of writing, project, or decision.
---

# Desantis

Connect the user's fragments into coherent alternatives while preserving their destination. The user owns the idea; help supply its missing middle. This is a general thinking workflow, not a product or startup template.

## Invocation

The user can type freely, then invoke `$desantis` or the host's skill command. Use the accompanying notes and relevant preceding conversation. A bare invocation refers to the latest substantive idea; do not make the user paste it again. If no idea is available, ask one question requesting their goal and rough thoughts.

Optional input: goal, fragments, fixed constraints, flexible choices, desired output. Ordinary paragraphs are sufficient.

## Develop the idea

1. Separate the intended outcome and fixed constraints from optional ingredients, assumptions, and unresolved choices. Preserve the user's stated direction; explicitly flag proposed changes to it.
2. Supply the missing connections: explain how the ingredients lead to the desired outcome and what must be true for that connection to work. Remove ingredients that do not help.
3. Build alternatives around different underlying choices. Each pair should differ on at least two meaningful dimensions appropriate to the domain: mechanism, responsibility, participant experience, scope, argument, or narrative structure. Names, channels, and before/after stages alone are not different ideas.
4. Check each alternative against the original goal and constraints. Describe its distinctive tradeoff, not just its benefits. Label unverified claims as assumptions; a coherent story is not validation.

## Output contract

User-requested count, length, format, and scope override these defaults. Deliver the alternatives themselves, not another prompt for generating them.

- **Core idea:** up to 50 words connecting the user's goal, fragments, and central unresolved choice.
- **Exactly three alternatives**, each containing:
  - A plain-language name.
  - **Concept:** 30 words stating the direction and its connection to the original goal.
  - **Connected version:** 100 words making the idea concrete and joining the missing middle. For writing, provide an actual proposed passage connecting the supplied opening toward the intended ending. For other ideas, show a concrete sequence or experience and why it serves the goal.
  - **Boundaries:** three short bullets stating what this version should not do or become.
  - **Difference and tradeoff:** one sentence explaining the substantive choice versus the other alternatives and its cost.
  - **Assumption to check:** one assumption and a small, domain-appropriate way to challenge it.
- **Recommendation:** up to 75 words choosing a direction, identifying what changed in the user's thinking, and naming the next useful check.

Before replying, check distinctness, fidelity to the original goal, and requested lengths. Count concept/passage words excluding headings. Keep business jargon out of non-business ideas. Remain in ideation: suggesting actions does not authorize executing them.
