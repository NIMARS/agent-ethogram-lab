# Public Manifest

Manifest version: 0.1.0  
Status: public baseline allowlist  
Updated: 2026-07-28

## Purpose

This manifest defines the files intended for the initial public Agent Ethogram
Lab repository. Publication should follow an allowlist: a file is reviewed for
release because it is listed here, not merely because it is absent from an
ignore rule.

## Intended public files

| Path | Intended content |
|---|---|
| `README.md` | Public overview, status, guardrails, and license notice |
| `PROJECT_SCOPE.md` | Public scope, exclusions, and maturity |
| `INDEPENDENT_DEVELOPMENT.md` | General development and AI-assistance statement |
| `PUBLIC_MANIFEST.md` | This public allowlist and boundary |
| `docs/concept-note.md` | Minimal, non-implementing concept description |
| `docs/research-questions.md` | High-level candidate research questions |
| `docs/public-roadmap.md` | Review-gated public roadmap |
| `docs/glossary.md` | Minimal public terminology |
| `.gitignore` | Accidental-file exclusions; not a security boundary |
| `.gitattributes` | Repository text and line-ending conventions |

Files not listed above require an explicit manifest update and a new publication
review before they are added.

## Excluded categories

The following are not approved for this public baseline:

- private repository history or metadata;
- internal source archives, working notes, conversations, and task lists;
- detailed research instruments, test scenarios, scoring systems, or
  unpublished methods;
- datasets, interaction traces, annotations, or unpublished experimental
  results;
- credentials, tokens, local configuration, logs, or environment files;
- personal, contractual, legal, financial, customer, or partner information;
- third-party material without verified publication rights;
- internal evidence packages or timestamping records.

## Release checks

Before the first push and before every release:

1. Confirm that every tracked path is listed in this manifest.
2. Review the complete reachable Git history, not only the working tree.
3. Check for credentials, personal information, binary files, and unexpected
   metadata.
4. Confirm that every third-party item has a documented source and usable
   license.
5. Verify that status words such as *draft*, *planned*, *tested*, and
   *validated* match reality.
6. Confirm that the license notice is still accurate.
7. Ensure no nested repository or private export was copied into this one.

## Important limitation

Ignore files reduce accidental staging but do not protect secrets and do not
remove previously committed content. This manifest is a review control, not a
technical or legal guarantee.
