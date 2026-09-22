# MDAnalysis — AIDEAL five-condition preparation

**Setup only: five baseline source branches; treatments and evaluation pending. No model is selected; this new setup made zero model calls.**
The date in the study/ref names is the setup start date, 2026-09-21; preparation continued after midnight.

[Shared AIDEAL study guide](https://github.com/ZhuochengShang/AIDEAL/blob/setup/2026-09-21-library-five-conditions/studies/mdanalysis/2026-09-21-five-condition-setup/README.md) · [Source/setup identities](study.json) · [Shared workflow](https://github.com/ZhuochengShang/AIDEAL/blob/setup/2026-09-21-library-five-conditions/docs/SUMMARY.md)

The source repository and shared AIDEAL serve different purposes: these branches hold library source; shared AIDEAL holds prompts, controller/harness code, settings conventions and future reports. The companion repository requires private access.
Publication policy keeps GitHub Actions disabled while preparation is pending; upstream CI has not validated this setup.

## Source identity and attribution

Upstream: [https://github.com/MDAnalysis/mdanalysis.git](https://github.com/MDAnalysis/mdanalysis.git); selected commit [81b8ef51e5bc1aa2824294ac6c52818c74975658](https://github.com/MDAnalysis/mdanalysis/commit/81b8ef51e5bc1aa2824294ac6c52818c74975658).
Preparation snapshot: [89a9feae2cbeeb6ed90ec91706a16ef8a64fcc27](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/commit/89a9feae2cbeeb6ed90ec91706a16ef8a64fcc27); tree `cd8e34787e5316476544eae4f7f40b467b3d0bbc` is exactly the upstream tree. This new commit does not ship upstream ancestry.

Original documentation selected for future attachment: [README.rst](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/blob/89a9feae2cbeeb6ed90ec91706a16ef8a64fcc27/README.rst). Source-branch root READMEs remain upstream bytes. This navigation README on `main` is not a documentation treatment. A future installed generated README is selected from `.aideal/treatments/README.md` in the relevant condition.

Upstream license/notice files are copied byte-for-byte: [LICENSE](LICENSE). They retain their original attribution and terms; this setup does not relicense upstream source.

## Five conditions

| Condition | Intended difference from original | Actual state |
| --- | --- | --- |
| [Original](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/tree/preparation/2026-09-21-five-conditions/original) | Original documentation and APIs | Baseline; not evaluated |
| [README only](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/tree/preparation/2026-09-21-five-conditions/readme-only) | Select a reviewed generated README | Same baseline; treatment pending; not evaluated |
| [Alias only](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/tree/preparation/2026-09-21-five-conditions/alias-only) | Add tested delegating aliases and their interface | Same baseline; treatment pending; not evaluated |
| [Error hints only](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/tree/preparation/2026-09-21-five-conditions/error-hints-only) | Deliver matched development-error hints on repair | Same baseline; treatment pending; not evaluated |
| [Combined](https://github.com/ZhuochengShang/AIDEAL-MDAnalysis/tree/preparation/2026-09-21-five-conditions/combined) | Combine the same README, aliases, and error hints | Same baseline; treatment pending; not evaluated |

All rows have the same commit/tree today. No historical generated README, aliases, hints or evaluation artifacts have been installed here. Branch names express the study plan, not measured differences.

## Get the source

For one clean source checkout (private repository access required):

```sh
git clone -b preparation/2026-09-21-five-conditions/original https://github.com/ZhuochengShang/AIDEAL-MDAnalysis.git AIDEAL-MDAnalysis
```

Or clone the navigation branch once and create five **distinct named branches/worktrees**:

```sh
git clone https://github.com/ZhuochengShang/AIDEAL-MDAnalysis.git AIDEAL-MDAnalysis
cd AIDEAL-MDAnalysis
git worktree add -b review/original ../mdanalysis-original origin/preparation/2026-09-21-five-conditions/original
git worktree add -b review/readme-only ../mdanalysis-readme-only origin/preparation/2026-09-21-five-conditions/readme-only
git worktree add -b review/alias-only ../mdanalysis-alias-only origin/preparation/2026-09-21-five-conditions/alias-only
git worktree add -b review/error-hints-only ../mdanalysis-error-hints-only origin/preparation/2026-09-21-five-conditions/error-hints-only
git worktree add -b review/combined ../mdanalysis-combined origin/preparation/2026-09-21-five-conditions/combined
```

All five currently resolve to `89a9feae2cbeeb6ed90ec91706a16ef8a64fcc27`. Sharing a commit is intentional; branch names are different.
`main` contains this navigation guide. Use a preparation branch/worktree for the actual source, not `main`.


## Before evaluation

Clean setup source is distinct from the 13 tracked generated-file changes in historical built clones. Historical MDAnalysis jobs remain live and untouched; incomplete generated documentation is not imported.

Use the [shared attachment instructions](https://github.com/ZhuochengShang/AIDEAL/blob/setup/2026-09-21-library-five-conditions/studies/mdanalysis/2026-09-21-five-condition-setup/README.md#prepare-your-own-local-study). Complete and validate the library runtime, independent task bank and controls, treatment artifacts, per-condition builds, model/prompt/budget settings and a new local freeze. Documentation and draft configuration alone are not a runnable evaluator. No setup test or example execution is a measured semantic score.
