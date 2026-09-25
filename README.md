# Desantis

A general-purpose agent skill for connecting rough thoughts into coherent,
genuinely different alternatives. For writing, projects, decisions, or any idea
with a destination and a missing middle.

You own the goal. The agent helps connect the pieces.

## Use it

Write your thoughts in ordinary paragraphs, then invoke the skill:

```text
I want a neighborhood learning group. Shared meals, skill swaps,
local hosts. Little money, no social feed. The goal is practical
learning and real local connections. Help me connect these ideas.

$desantis
```

You can also invoke it after an existing conversation; no need to repeat the notes.
Use your agent's skill invocation syntax (`$desantis` in Codex).

By default, it returns:

- A synthesis of your core idea.
- Three alternatives, each with a 30-word concept and a 100-word connected version.
- What each alternative should not do, its tradeoff, and an assumption to check.
- A recommendation tied to your original goal.

Override the count, length, or format whenever useful:

```text
$desantis — give me two alternative bridges for this essay,
each under 80 words. End with one sentence explaining the difference.
```

For writing, it drafts actual passages. For other ideas, it describes concrete
experiences or sequences. Different names or before/after stages alone do not
count as different ideas. Suggestions are proposals, not validated facts or
permission to execute actions.

## Install

Clone this repository into a directory named `desantis` under your agent's skills
directory. For agents using the shared skills directory:

```bash
git clone https://github.com/rilical/desantis.git ~/.agents/skills/desantis
```

If your agent uses another skills directory, use that location instead. If
`desantis` is already installed, keep it rather than overwriting it. Reload skills
or start a fresh session if it does not appear.

The skill is self-contained in [SKILL.md](SKILL.md); `agents/openai.yaml` supplies
optional display metadata. No scripts, API keys, or external services are required
by the skill itself. Output quality and exact word counts still depend on the agent.

## License

[MIT](LICENSE).
