# Course Response Template

Skeleton for a per-class reading-response GitHub repo. Fork or "Use this
template" to create a course-specific response repo (e.g.
`censorship-responses`, `networking-responses`).

## For instructors

1. Click **"Use this template"** at the top of this page.
2. Owner: `noise-courses` (or wherever). Name: `<course-slug>-responses`.
3. In the new repo's **Settings → General**, check
   **"Template repository"** so students can then use it as *their* template.
4. Edit the following files for your course:
   - `README.md` — replace this content with the student-facing quickstart
     for your class.
   - `0-template.md` — adjust the response format if you want more or
     fewer sections.
   - `.github/workflows/lint.yml` — extend the placeholder lint rules with
     anything you want structurally enforced (naming convention, required
     sections, word counts, whatever).
5. Update the syllabus and student-onboarding instructions with the new
   repo URL and your GitHub username.

The [`noise-courses/instructor-tools`](https://github.com/noise-courses/instructor-tools)
repo has the shared grading tooling (`pull-responses.sh`, roster schema,
setup docs).

## For students (when this becomes your class's template)

Once your instructor has adapted this repo for your class, the README you
see will be the student-facing quickstart. Follow those instructions.

The rough shape:

1. **Use this template** → private repo in your own account.
2. Add instructor as a Read collaborator (Settings → Collaborators).
3. Submit your repo URL as instructed.
4. Each week: copy `0-template.md` to `week-NN.md`, fill it in, commit.

## What's in this skeleton

| File | Purpose |
|---|---|
| `README.md` | This file — replace with course-specific instructions. |
| `0-template.md` | Response format students copy into `week-NN.md`. |
| `.github/workflows/lint.yml` | Basic markdown-lint action so students see a green/red check on each push. Extend as needed. |
