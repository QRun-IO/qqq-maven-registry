# qqq-maven-registry - AI Context

Placeholder/anchor repo for the legacy GitHub Packages Maven registry
(`maven.pkg.github.com/Kingsrook/qqq-maven-registry`). No code — QQQ artifact
publishing moved to Sonatype Central (Aug 2025). The name survives as the
CircleCI context `qqq-maven-registry-credentials` and in stale build files
elsewhere in the org.

## Knowledge base

A reviewed dossier for this repo lives in the second-brain vault:

- Hub: `R:/Git.Local/KofTwentyTwo/second-brain/knowledge/qqq/qqq-hub.md`
- Dossier: `R:/Git.Local/KofTwentyTwo/second-brain/knowledge/qqq/repos/qqq-maven-registry.md`
- Reviewed commit: `0d5aa60cea30` (branch `main`, 2026-07-04)

Consult the dossier before "cleaning up" anything named after this repo: the
CircleCI context carries the live Sonatype Central + GPG credentials for every
Java pipeline, and the GitHub Packages registry attached to this repo is the
only host of pre-0.24.1 timestamped snapshot artifacts still pinned by
`qqq-app-starter`. Retirement checklist is in the dossier's
"Maturity & risks" section.
