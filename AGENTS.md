# Portfolio

Static site (`index.html`, `styles.css`, `case-study/*.html`) published on GitHub Pages at
<https://ctrl-alt-yash.github.io/portfolio/>. No build step.

## Keeping it up to date

Most of the content describes projects that live in their own local repos, and those repos move
faster than this one. Before editing a project entry or a case study, browse the project's repo
rather than relying on what the portfolio already says:

| Portfolio entry                         | Local repo (under `/Users/yash/WithAIAssistant/development/`)     |
| --------------------------------------- | ----------------------------------------------------------------- |
| Wedding Photo Platform                  | `personal/akrati/wedding`. The public demo is on the `demo-site` branch |
| Tenant Manager, Household Expense Module | `personal/whats-app/tenant-manager` (one repo: `/tenant` and `/expense`) |
| Ship Shooter                            | `maxsashlabs/ship shooter` (note the space)                        |
| Family Tree (in progress)               | `maxsashlabs/family-tree`. The status is in `Docs/Roadmap.md` and `Docs/WorkPlan.md` |
| Velora Rights (freelance section)       | `velorarights/velorarights-web`, live at velorarights.com          |
| maxsash.com (links here)                | `maxsashlabs/web`                                                  |

### Look for new projects too

New projects land in the same places: `personal/`, `personal/<group>/`, `maxsashlabs/`, and
client or brand folders at the top level of `development/` (for example `sabrix/` and
`velorarights/`). Some of these folders have no git repo of their own and only show the
workspace's snapshot commits, so check each project folder inside them.
On every update, list those folders and compare against the table above. For anything not in
it, look at its README and git log and judge whether it's portfolio-worthy: something real and
finished enough to describe, ideally with a demo. Suggest candidates to Yash rather than adding
them unasked. Add each one that's accepted to the table, and record the ones that were turned
down below so they aren't suggested again.

Not featured yet; suggest these again once they're finished or show real progress:

- `maxsashlabs/case-summary`: only a plan so far.
- `sabrix/` (`sabrix-web`, `surreal-black-web`): "coming soon" pages only.
- `maxsashlabs/BirthdayAnniversaryWidgets`: an early iOS widget.

Considered and not featured:

- `personal/web/yash-web`: an earlier personal site, replaced by maxsash.com.

### Updating a project

For each project:

1. Read its README, AGENTS.md and `docs/`, then `git log` since this repo's last commit that
   touched the entry. New features, date ranges and counts (test files, etc.) drift first.
2. Check every branch, not just the checked-out one. Work such as a public demo can sit on a
   branch that isn't merged.
3. **Prefer the public demo's data** (counts, names, what a visitor can see) wherever it can
   stand in. Use production figures only when they are the point, for example the scale of the
   full photo pipeline run, and say so on the page. Never publish details from the private
   deployments.
4. Update both the `index.html` entry and its `case-study/*.html` page, so they agree.

## Links in from maxsash.com

maxsash.com (`maxsashlabs/web`, `content/site.ts` and `content/projects.ts`) links to this site
and deep-links `case-study/tenant-manager.html` and `case-study/wedding-site.html`. Don't rename
or move case-study files without updating that repo. Demo URLs in the portfolio should match the
ones in `content/projects.ts`.

## Identity details

Keep these consistent with maxsash.com:

- **Location:** Tikamgarh, India (remote)
- **Email:** yash@maxsash.com
- **Studio:** Founder, Maxsash Studio, linking to maxsash.com
- **GitHub:** the personal account is `ctrl-alt-yash`. `Maxsash` is the studio's organisation,
  not the personal profile.
