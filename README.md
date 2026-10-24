# Sponsorship CV

A free plugin from [SPath Global](https://spathglobal.com) that turns your existing CV and a job description into a tailored, UK-style CV and a specific cover letter for that job.

It works only from the facts you give it. When something is missing or vague, it asks you a short question instead of inventing it, and it finishes every document with a checklist of what to verify before you apply.

## What's included

| Skill | What it does |
|---|---|
| `tailored-cv` | Reads the job description, maps your experience to what the employer needs, asks about gaps, then writes a two-page UK-style CV in plain, applicant-tracking-friendly text. |
| `cover-letter` | Picks the three requirements that matter most in the advert and writes a 250 to 400 word cover letter backed by real examples from your CV. |

## How to use it

Paste or upload your CV and the job description, then ask:

- "Tailor my CV to this job description."
- "Write a cover letter for this role using my CV."
- "Which requirements in this advert is my CV missing?"

In Claude Code you can also call the skills directly with `/sponsorship-cv:tailored-cv` and `/sponsorship-cv:cover-letter`.

## Install in Claude Code

```bash
claude plugin marketplace add richardogundele/sponsorship-cv
claude plugin install sponsorship-cv@spath-global
```

## What it will not do

- Invent employers, job titles, dates, qualifications, results or skills.
- Hide or misstate your immigration status. It only mentions right to work or sponsorship if you ask, using exactly what you tell it.
- Promise interviews, an applicant-tracking-system pass, sponsorship or a visa outcome.
- Search for jobs or submit applications for you.

## Data and privacy

This plugin is instructions only. It contains no code, makes no network requests, connects to no accounts and stores nothing. Your CV and job descriptions stay inside the AI app you are using (Claude or ChatGPT) and are handled under that app's own terms. SPath Global does not receive them.

Privacy policy: https://spathglobal.com/privacy
Terms: https://spathglobal.com/terms

## Support

Questions or problems: https://spathglobal.com/plugin-support

## Want the full job search system?

This plugin covers CVs and cover letters only. [SpathMax](https://spathglobal.com/max) adds sponsor-checked job discovery, interview preparation and application tracking.

## Licence

MIT. See [LICENSE](LICENSE).
