# GLOBAL WEB SKILLS

A portable collection of Markdown skill specifications for AI assistants that help build, maintain, test, secure, and operate websites and web applications.

## Included skills

| File | Purpose |
|---|---|
| `CYBERSECURITY-SKILL.md` | Defensive application and infrastructure security across frontend, backend, APIs, databases, and deployment |
| `GLOBAL-LEGAL-COMPLIANCE-SKILL.md` | Global legal/compliance issue-spotting, jurisdiction mapping, and Brazil-specific coverage |
| `WEB-QA-MASTER-SKILL.md` | Functional, visual, accessibility, compatibility, and regression quality assurance |
| `DATABASE-GUARDIAN-SKILL.md` | Database reliability, integrity, performance, backup, migration, and recovery |
| `UPTIME-SENTINEL-SKILL.md` | Availability, performance, TLS, synthetic monitoring, alerting, and incident response |

## Compatibility

These files use plain Markdown and explicit instructions. They are not tied to a particular AI vendor, agent runtime, proprietary frontmatter format, or tool API. They can be adapted for systems that support skills, system prompts, project instructions, or repository-based agent guidance.

No Markdown file can force every AI product to load or obey it. Follow the target platform's import rules, and provide the relevant file as context when automatic skill loading is unavailable.

## Suggested repository layout

```text
global-web-skills/
├── README.md
└── skills/
    ├── CYBERSECURITY-SKILL.md
    ├── GLOBAL-LEGAL-COMPLIANCE-SKILL.md
    ├── WEB-QA-MASTER-SKILL.md
    ├── DATABASE-GUARDIAN-SKILL.md
    └── UPTIME-SENTINEL-SKILL.md
```

## Use

1. Choose the skill relevant to the task.
2. Give the AI the skill file and the actual project context.
3. Require it to inspect the real repository/configuration before making claims.
4. Require evidence for findings and tests.
5. Review and approve changes before production deployment.

Skills are guidance, not a substitute for professional security, legal, engineering, or operational review.

## Legal coverage warning

The global legal skill does **not** claim to contain every law in every country. That is impossible to guarantee in a static Markdown file: laws vary by territory, sector, business model, user location, and date, and change frequently. Instead, it provides a repeatable method to identify applicable jurisdictions, locate current primary legal sources, build a dated obligations register, and flag issues for qualified local counsel. It includes a Brazil-first checklist while requiring additional country-by-country analysis wherever relevant.

## Maintenance

- Review official sources before each material legal or security decision.
- Record source URLs, publication/effective dates, access dates, and uncertainty.
- Update dependencies and standards references as they evolve.
- Do not treat a passing automated scan as proof of security or legal compliance.
