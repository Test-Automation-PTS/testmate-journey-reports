# AIBot journey comparison reports

Published site: https://test-automation-pts.github.io/testmate-journey-reports/

This repository contains generated journey comparisons: old/new executed steps,
screenshots, business assessments and measured token usage. AIBot owns the renderer
and publication logic in `actions/publish-journey`; Testmate supplies the repository
and a publication credential. The `gh-pages` branch is served by GitHub Pages.

Each environment has a current report, `history.html`, and immutable reports in
`runs/<source-repository>-<run-id>-<attempt>/`. Publishing never changes a test verdict.
Application source, test source diffs, raw DOM, model prompts and raw failure logs
are excluded from this website. Screenshots use the masks captured by the test runner.

The `examples-*` scopes contain synthetic language-switch regression examples,
not results from the deployed Testmate application.
