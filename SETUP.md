# Installation

1. Create a **public** repository named `vladimir-koz` under the GitHub account `vladimir-koz` (or use it if it already exists).
2. Copy `README.md`, `assets/hero.svg`, and `.github/workflows/snake.yml` into that repository, preserving the paths.
3. Commit the files to the repository's default branch.
4. In repository Settings > Actions > General, ensure Actions are enabled and workflow permissions allow **Read and write permissions** if the snake workflow reports a permissions failure.
5. Open the Actions tab and run **Generate contribution snake** using **Run workflow**. The workflow publishes SVGs on the `output` branch. GitHub schedule executions may be delayed.
6. Reload your public profile after the workflow completes. The snake will not display until the `output` branch has the SVG files. Other animations require no workflow.

## Notes
- The header is a custom SVG with subtle SVG animation, but motion may be reduced or disabled by browser/GitHub rendering policies. Static appearance remains.
- The typing animation, stack icons, activity graph and profile counter use external image services; they may occasionally be unavailable.
- README GitHub Markdown does **not** permit arbitrary JavaScript/CSS effects.
- Project links and descriptions should be verified before replacing the current portfolio-category table.
- If you prefer to avoid third-party visitor counters, remove the `komarev.com` image line.
