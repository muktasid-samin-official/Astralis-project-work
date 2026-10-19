<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->


# Astralis — Codex Project Instructions

## Project overview
Astralis is an astrology-inspired landing page that displays
prewritten monthly horoscopes for the 12 Western zodiac signs.

The initial content is for October 2026.

This is a Next.js course project. The final deliverable
must include a working `page.tsx`.

## Technology
- Next.js App Router
- React and TypeScript
- Tailwind CSS
- Existing project dependencies whenever possible
- No backend, database, authentication, or external APIs

Inspect the existing project before assuming its structure.

## Development workflow
- Build one component or feature per task.
- Never implement unrequested future components.
- Make the smallest reasonable changes.
- Preserve working code and existing functionality.
- Prefer simple, maintainable solutions over abstractions.
- Avoid installing dependencies unless necessary.
- Ask before making significant architectural changes.
- Stop after completing the requested task.
- Briefly report changed files, tests, and remaining issues.

## Design system
Theme: Midnight Celestial.

- Deep midnight navy backgrounds
- Muted violet accents
- Restrained warm gold highlights
- Elegant, readable typography
- Subtle celestial motifs
- Generous spacing and consistent alignment
- Responsive layouts for desktop and mobile
- Minimal, purposeful animations

Avoid generic dashboard styling, excessive gradients,
unnecessary glass effects, and visual clutter.

## Code quality
- Use TypeScript with appropriate types.
- Prefer small, reusable React components.
- Use semantic HTML and accessible controls.
- Provide keyboard accessibility and visible focus states.
- Avoid unnecessary client-side JavaScript.
- Use "use client" only where interactivity requires it.
- Do not introduce unused imports or dependencies.
- Follow existing project conventions.

## Product behavior
- Support manual zodiac selection and birthday-based selection.
- Store all horoscope content locally.
- Display readings for general outlook, love, and career.
- Clearly identify readings as October 2026 content.
- Do not present astrology as scientifically proven prediction.
- Include an entertainment-only disclaimer.
- Do not collect or persist visitors' birthdays.

## Verification
After implementation:
- Check TypeScript for errors.
- Run available lint checks.
- Verify the requested behavior.
- Check mobile and desktop responsiveness.
- Report any checks that could not be completed.

Do not claim that tests passed unless they were run.

## Submission
The Udemy assignment requests `page.tsx`.

During development, separate components are permitted.
Before submission, ensure the deliverable is self-contained
or that all required dependencies are included as allowed.

## Scope control
Do not add features, dependencies, integrations,
or additional pages without explicit approval.

