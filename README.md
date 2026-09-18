# respond.io careers page — open roles mockup

Click-through mockup for moving open roles off `breezy.hr` and onto `respond.io`, as part of the Breezy → Rippling switch.

**View it:** https://aimanrespond.github.io/respond-careers-mockup/

## The flow

| Step | Screen | Stands for | File |
|---|---|---|---|
| 1 | Careers page | `respond.io/careers` — unchanged, only the “View Open Roles” button target changes | `careers.html` |
| 2 | Open roles | `respond.io/careers/open-roles` — new page, our design, list pulled live from Rippling | `open-roles.html` |
| 3 | Job description + apply | `ats.rippling.com/respond-io/jobs/…` — Rippling-hosted, our logo/font/colours (wireframe) | `job.html` |

Other states of step 2: `open-roles-phone.html` (390px) and `open-roles-empty.html` (nothing open).

`index.html` is the overview page with live previews of every screen.

## Notes

- Black pages are ours and follow the current respond.io site styling. The light page is Rippling's template.
- Roles, teams and locations are sample data from the Breezy board on 17 Sept 2026. On the real page they come live from Rippling's job board, so counts and groups will change.
- The small bar at the bottom of each screen is a prototype note (which real URL the screen stands for). It is not part of the design.
- Grey boxes stand for content that already exists on the live site (video, G2 badges, footer).

## Source

`source/` holds the original artboards (`*.dc.html`) and the canvas index (`canvas.json`) in the design-canvas format they were drawn in. The HTML pages in the root are plain, dependency-free renders of those artboards.
