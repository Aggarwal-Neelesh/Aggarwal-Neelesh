## PR Title
Integrate PR Buddy GitHub Action for Automated PR Review

## Changes:
- [x] Added `.github/workflows/pr-buddy.yml` for automated PR reviews.
- [x] Configured PR Buddy to trigger on `pull_request` events (`opened`, `synchronize`, `reopened`).
- [x] Included AI-based review options using `GEMINI_API_KEY` and `OPENAI_API_KEY`.
- [x] Ensured GitHub secrets (`GITHUB_API_TOKEN`, `GEMINI_API_KEY`, `OPENAI_API_KEY`) are utilized for authentication.

## Testing:
- [x] Created a test PR to verify PR Buddy triggers successfully.
- [x] Checked logs in GitHub Actions to ensure the workflow runs correctly.
- [x] Verified that AI-based PR review comments are generated (if AI review is enabled).
- [x] Ensured the workflow does not block the PR merge process.  
