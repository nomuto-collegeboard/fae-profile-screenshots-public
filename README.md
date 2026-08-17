# fae-profile-screenshots-public

Public, images-only mirror of ticket screenshots produced by the private
[`fae-profile-screenshots`](https://github.com/nomuto-collegeboard/fae-profile-screenshots)
tooling. This repo exists so raw image URLs render inline in:

- GitHub PR descriptions (private-repo raw URLs 404 through Camo)
- Jira / Confluence via `<img>` tags

**Content policy:** UI screenshots only. Never PII / real applicant data. Never
credentials / secrets. Never source code.

Publish flow: from the private tooling repo, run
`npm run publish:public -- <TICKET>` — it copies `shots/<TICKET>/*.png` here,
commits, and pushes.
