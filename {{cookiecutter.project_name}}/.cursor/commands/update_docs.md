# Update Docs

Run this command at the end of a work session to keep all project documentation current.

---

## 1. Update project.md (Session Log)

Run the update script to append a timestamped entry to `project.md` with the latest git commit and a status summary:

```bash
python scripts/update_project.py "Brief summary of what you worked on this session"
```

If running interactively (no argument), the script will prompt for the status update.

---

## 2. Update README.md (If Applicable)

If the project structure, setup steps, or high-level overview has changed this session, update `README.md` to reflect it.

Things to check:
- Does the **File Structure** section still match the actual layout?
- Does **Quick Start** reflect any new setup steps?
- Does **How it Works** accurately describe the current architecture?

[YOUR PROJECT: Add any project-specific README sections to check here]

---

## 3. Update Other Living Documents (If Applicable)

[YOUR PROJECT: Add any other docs that need to stay current. Examples:]

<!-- Example: Database / Schema Docs
If you modified any data models or database tables this session, update the schema doc:
- File: `docs/schema.md`
- What to update: table names, column types, relationships, any new indexes
-->

<!-- Example: API Reference
If you added or changed any API endpoints:
- File: `docs/api.md`
- What to update: endpoint paths, request/response shapes, auth requirements
-->

<!-- Example: Environment Variables
If you added new environment variables, add them to:
- `.env.example` (with a blank or placeholder value)
- `docs/setup.md` (with a description of what the var does)
-->

---

## 4. Commit the Doc Updates

After all docs are updated, commit the changes:

```bash
git add project.md README.md  # add whichever docs you updated
git commit -m "docs: update project log and docs for session [DATE]"
```
