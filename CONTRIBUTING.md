# Contributing

Thanks for helping improve Awesome Jev.

## What belongs here

An entry should:

- be publicly accessible and link to its original source;
- use Jev or implement a clearly documented Jev-style typed-decision interface;
- show a concrete decision task such as classification, routing, scoring, ranking, verification, or guarding;
- explain what Jev decides and what deterministic code does;
- avoid unsupported performance, safety, or accuracy claims.

Open reproductions belong in **Open reproductions and research**, not in the official or SDK sections. Experiments that can trigger financial, medical, security, or physical actions must state their safety boundary and whether the path is simulated, read-only, or live.

## Add a project

1. Add one bullet to the most relevant section of `README.md`.
2. Use the canonical project name and repository URL.
3. Write one factual sentence describing the decision Jev makes.
4. Keep entries alphabetical within a section when practical.
5. Disclose in the pull-request description if you built or maintain the project.

Suggested format:

```md
- [Project name](https://github.com/owner/repo) - What Jev decides and how the result is used.
```

## Review notes

Maintainers may ask for a link to the specific file that calls Jev, an evaluation artifact, or clearer wording around limitations. A working demo is helpful but not required; public source and inspectable evidence matter more than popularity.
