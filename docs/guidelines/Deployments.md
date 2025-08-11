# Deployment

- Start local > Staging > Release Candidate (RC) > Production
  1. Copy the project and make changes/experment with/updates locally
  2. Once it's good enough, create or merge to a staging branch
  3. Once it's good enough, create or merge to a RC branch
  4. Once it's tested and (mostly) bug-free, merge to Production branch
  5. If any changes, updates, fixes is needed on Production repeat steps 1-4.

- Use CI/CD pipelines (GitHub Actions, etc)

- Write deployment notes for future-you/colleagues

## Recommended branch names

- Local: No name
- Staging: Staging or Dev
- Release Candidate: RC or Beta
- Production: Main or Master
