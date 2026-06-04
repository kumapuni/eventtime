# eventtime

Responsive event timekeeper web app for smartphone and desktop browsers.

## Usage

1. Open the GitHub Pages URL for this repository (or open `/tmp/workspace/kumapuni/eventtime/index.html` locally).
2. Enter a target time.
3. The page shows live current time and the signed difference:
   - `+HH:MM:SS`: current time is ahead of target.
   - `-HH:MM:SS`: current time is behind target.

## GitHub Pages

The workflow at `/tmp/workspace/kumapuni/eventtime/.github/workflows/deploy-pages.yml` publishes the repository root as a static site on pushes to `main`.
