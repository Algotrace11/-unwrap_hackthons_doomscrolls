# Automated Instagram Hackathon Publisher

Autonomous pipeline powered by GitHub Actions that curates and publishes top hackathons and competitions from Unstop.

## Automation Schedule
Runs twice daily during peak student & developer engagement hours:
- **10:00 PM IST (16:30 UTC)** — Late night peak / overnight reach
- **01:00 PM IST (07:30 UTC)** — Afternoon lunch break

## Configuration (GitHub Secrets)
Add your Instagram Graph API credentials in repository **Settings > Secrets and variables > Actions**:
- `INSTAGRAM_ACCOUNT_ID`
- `META_ACCESS_TOKEN`
- `CLOUDINARY_CLOUD_NAME` (Optional)
- `CLOUDINARY_API_KEY` (Optional)
- `CLOUDINARY_API_SECRET` (Optional)

*Note: If credentials are not yet added, the workflow runs in dry-run preview mode automatically.*
