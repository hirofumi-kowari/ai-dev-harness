# AI-Driven Development with a Harness

[日本語](README.ja.md)

Two short videos that explain one way of putting AI to work on an existing business system: **people set the rules, AI does the work, machines check the result, and people accept it.** The subject system is a fictional employee reservation application. No customer names, products or real code appear.

Narration is in Japanese (synthetic voice). English subtitles are planned.

## 1. Harness explained (6 min)

The vocabulary used in both videos — specification, guardrails, automated checks, quality gate, harness — and why writing a rule down is not the same as having it followed.

<!-- To show the player inline: open this file in GitHub's web editor, drag harness-explained.ja.mp4 onto this line, and GitHub inserts an embeddable URL. Until then, the link below opens GitHub's own player. -->
[▶ Harness explained (Japanese narration)](harness-explained.ja.mp4)

## 2. Development loop demo (11 min)

One modification request, end to end: the AI reads the specification and guardrails, proposes a design, raises the questions it cannot decide, updates the design document, implements, builds, generates and runs tests, drives the browser for screen tests, gets reviewed by a second AI, passes the quality gate, and hands the evidence to a person for acceptance. The last scenes show how the lesson from this change becomes an organisational standard for the next one.

[▶ Development loop demo (Japanese narration)](dev-loop-demo.ja.mp4)

## Terms

| Term | Meaning |
|---|---|
| Specification | Requirements and design documents. What to build. Decided by people, per project |
| Guardrails | Conventions, permitted operations, checklists. Shared across projects |
| Automated checks | Scripts that run before a tool call, after an edit, and at the end |
| Quality gate | The end-of-work check: not "done" until the agreed completion conditions are met |
| Harness | The whole arrangement: rules by people, execution by AI, judgement by machines, acceptance by people |

## Related

How the specification itself is prepared for such a loop — what a person must decide, what evidence the AI must cite, which questions it must raise instead of guessing — is the subject of **[SpecLingua](https://github.com/hirofumi-kowari/spec-lingua)**.

## License

The videos and this text are licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0). See [LICENSE.ja.md](LICENSE.ja.md) for a Japanese summary.
