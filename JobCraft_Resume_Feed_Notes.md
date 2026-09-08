# Job Craft resume feed review

Local source review: 5 September 2026. No Job Craft application code or stored data was changed.

## Files
- `Master_Resume.md`: canonical career profile followed by full evidence and tailoring notes.
- `Master_Resume_JobCraft.md`: exact text between the master’s `JOBCRAFT_PROFILE_START` and `JOBCRAFT_PROFILE_END` markers. Use as the Markdown profile feed. It is not a finished application resume.

## Regenerating the feed
After editing the canonical block, extract the text between the markers, trim surrounding blank lines, and add one final newline. Keep supporting notes outside that block.

## Observed integration behavior
- `worker/src/profile-routes.ts` accepts `{ content: string }` at the profile POST route; `repository.ts:saveProfile` stores the complete text. No PB/PJ Markdown heading conversion into evidence modules occurs in that save path.
- `profile_modules` is a separate store, loaded separately during generation. `job-intelligence.ts` filters selected modules by `verified`. Existing modules need a separate review against the corrected career facts before use. This review did not inspect or change live modules.
- The candidate name fallback reads the first level-one heading. The feed therefore starts with `# Rasoul Veisi`, without a “Master Resume” suffix.

## Application issues that remain
- `worker/src/workflow.ts`: `targetedSummary`, `technicalSkills`, `pharmaBitsBullets`, `profileRoles`, `profileProjects`, and `profileEducation` include hardcoded history or skills instead of consistently extracting the supplied profile. They can reintroduce NgRx, unsupported performance/coverage metrics, obsolete Ketab claims, wrong project stacks, and altered degree names.
- `targetedHeadline` can inject NgRx. The AI draft/compression prompts assert immediate relocation readiness, while the record only supports openness to relocation and a sponsorship requirement.
- `worker/src/ai-prompts.ts` and the workflow evidence prompt favour old technologies such as NgRx; the supplied profile must remain the factual authority.
- The full master and the feed cannot repair these application behaviors. Make fallback output evidence-based and audit existing modules before treating generated resumes as reliable. A negative instruction in Markdown is not a substitute for that fix.

## Validation performed
The feed matches the canonical master block; its first heading is the candidate name. The main profile contains all employment entries, research, the 10 selected personal projects, education, and tailoring boundaries. Private board metrics remain excluded. No AI generation, database upload, live export, or production deployment was performed.
