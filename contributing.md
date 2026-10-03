# Contributing

Thanks for helping keep **Awesome Database Tools** awesome! This list is curated,
not a directory — every entry should earn its place and stay useful over time.
Please read the guidelines below before opening a pull request.

> **TL;DR** — one tool per PR, a neutral one-line description, the right category,
> and a tool that is **mature, maintained, and genuinely useful**. New, barely-used
> projects submitted mainly to gain traction will be asked to come back later.

## Table of contents

- [Scope](#scope)
- [Inclusion criteria](#inclusion-criteria)
  - [For everyone (both open-source and proprietary)](#for-everyone-both-open-source-and-proprietary)
  - [Open-source / public-repo tools](#open-source--public-repo-tools)
  - [Proprietary / commercial / no public repo](#proprietary--commercial--no-public-repo)
- [Self-submission & promotion](#self-submission--promotion)
- [Formatting rules](#formatting-rules)
- [Badges](#badges)
- [Pull request checklist](#pull-request-checklist)
- [How entries are reviewed](#how-entries-are-reviewed)
- [Maintenance & removal](#maintenance--removal)

## Scope

This is a list of **tools that make working with databases easier** — for DBAs,
DevOps, developers, and data people. Both **open-source** and **proprietary/commercial**
tools are welcome; this list is intentionally license-agnostic.

Out of scope: general-purpose libraries/ORMs with no standalone tooling value,
hosted databases themselves, blog posts and one-off tutorials (unless clearly a
durable resource that fits an existing section), and anything unrelated to working
with databases.

## Inclusion criteria

A good entry is **mature, maintained, documented, and useful to others** — not just
newly published. Because roughly half of this list is closed-source commercial
software without a GitHub repo, maturity is judged by different evidence depending
on the tool. There is **no fixed minimum star count** — stars are at most one weak
signal, never a gate (they would unfairly exclude good niche tools, e.g. for
Oracle or SQL Server).

### For everyone (both open-source and proprietary)

- **Solves a real problem** and is usable today — not a landing page, a promise, or
  a weekend prototype published to collect stars.
- **Documented**: a working README or docs page that explains what it is and how to
  start using it, in English.
- **Not a near-duplicate** of something already listed, unless it offers a clear,
  statable difference.
- **Neutral description**: factual, ends with a period, no marketing language
  (avoid "powerful", "blazing-fast", "the best", "revolutionary", "all-in-one",
  "premier", etc.). See [Formatting rules](#formatting-rules).
- **Correctly categorized** and placed alphabetically within its section.

### Open-source / public-repo tools

In addition to the shared criteria above:

- **At least ~6 months of history** since the first commit. Brand-new repos are
  welcome to resubmit once they have a track record.
- **A real release or usage history** — at least one tagged/versioned release, or
  demonstrable adoption/usage.
- **Actively maintained** — meaningful commits within roughly the last 12 months,
  or issues/PRs answered in reasonable time. Archived/abandoned projects are not
  accepted (and existing ones may be removed — see [Maintenance & removal](#maintenance--removal)).
- **An open-source license** (for anything claiming to be open-source).

### Proprietary / commercial / no public repo

Closed-source and commercial tools are welcome. Since stars and commit history
don't apply, maturity is judged by equivalent, verifiable evidence:

- **Product history** — a public version number and a **changelog / release notes**
  (not just a landing page).
- **Still alive** — a release or update within roughly the last 12 months.
- **Not vaporware** — a working website, a downloadable build / trial or hosted
  access, real documentation, and — for paid tools — a transparent pricing page.
- **Identifiable vendor** — a real company or author with a track record, not an
  anonymous page.
- **Independent third-party coverage** — **at least 3** materials/reviews from
  independent, third-party sites or blogs (not the vendor's own site, press
  releases, or paid placements). This is the proprietary-world equivalent of
  community adoption, since stars don't apply. Please include the links in the PR.

## Self-submission & promotion

Self-submissions are **allowed but must be disclosed**. If you are the author,
maintainer, or vendor of the tool:

- Say so explicitly in the PR description.
- The usual bar still applies — the tool must be **ready for others to use**, not
  freshly published to bootstrap traction from this list.
- Keep the description neutral; vendor marketing copy will be edited or rejected.

Mass submissions, duplicate PRs, and PRs that read as advertising will be closed.

## Formatting rules

- Submit **only one tool per pull request**.
- Check existing entries and the list of
  [removed/deprecated projects](https://github.com/mgramin/awesome-db-tools/issues?q=is%3Aissue+is%3Aclosed+label%3Adeprecation)
  before submitting, to avoid duplicates.
- If the tool has a GitHub repository, link to the repo; otherwise link to the
  official site.
- Use this exact shape (description ends with a period):

  ```markdown
  - [Tool Name](https://example.com) - A short, neutral description.
  ```

- Order entries **alphabetically** within each category.
- No trailing whitespace.
- Add a new category only if several tools would fit it and no existing section
  does; mention this in the PR.

## Badges

To keep the mixed open-source / commercial nature transparent, entries may carry
small emoji markers placed **at the end of the description, right before the final
period** (this keeps the `- [Title](url) - Description.` shape that `awesome-lint`
requires):

- 💰 — paid / commercial (a free tier may still exist).
- 🔒 — proprietary / closed-source.

The two markers are **independent axes** — one is about price, the other about
whether you can read the source — so they often combine:

| | Open source | Closed source |
|---|---|---|
| **Free** | no badge (e.g. DBeaver CE, pgAdmin) | 🔒 (e.g. Oracle SQL Developer, SSMS) |
| **Paid** | 💰 (e.g. an open-core paid edition) | 💰 🔒 (e.g. Navicat, Toad, DataGrip) |

They answer two different questions for the reader: 💰 — "will it cost me money?";
🔒 — "can I read/audit the source myself, or only try a trial?"

Example:

```markdown
- [Tool Name](https://example.com) - A short, neutral description 💰 🔒.
```

> Note: the badge scheme is being rolled out gradually; new proprietary/commercial
> entries should include the relevant marker.

## Pull request checklist

Before opening a PR, confirm:

- [ ] One tool only, placed in the correct category, alphabetically.
- [ ] Description is neutral, factual, and ends with a period.
- [ ] Not already listed or previously removed.
- [ ] **Open-source**: ≥ ~6 months old, has a release/usage history, and is
      actively maintained.
- [ ] **Proprietary/no-repo**: has public version history/changelog, is still
      updated, is not vaporware, (if paid) has a pricing page, and includes links
      to **≥ 3 independent third-party reviews/materials**.
- [ ] If you are the author/maintainer/vendor, you disclosed it in the PR.
- [ ] Added the appropriate badge(s) for paid/proprietary tools.

## How entries are reviewed

Maintainers check the PR against the criteria above. Tools that are promising but
too new or too thinly maintained may be **declined with a note to resubmit later**
rather than merged. This isn't personal — it keeps the list a curated signal rather
than a promotion channel.

## Maintenance & removal

This list is pruned periodically. Entries may be removed if a tool becomes
**unmaintained or archived**, its **links break**, it is **discontinued**, or it no
longer fits the scope. Removed projects are tracked under the
[`deprecation`](https://github.com/mgramin/awesome-db-tools/issues?q=is%3Aissue+label%3Adeprecation)
label. Keeping the removal process active is what makes the entry bar fair: we don't
only add, we also take away.
