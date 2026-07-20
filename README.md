# QA Radar v3 consumer

External consumer validation for the published
[`LeoguiatoM5/QA_Radar@v3`](https://github.com/LeoguiatoM5/QA_Radar) composite
GitHub Action.

The workflow scans `https://example.com` twice. The first run creates an
accepted baseline; the second run validates that the published action reports
no regressions and emits HTML, JSON, JUnit XML, and SARIF artifacts using QA
Radar `3.0.1` and schema `1.0`.
