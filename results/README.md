# VGAP GitHub Search Results

This repository will store the full dataset of GitHub repositories matching the query:

`VGA Planets OR VGAPlanets OR "VGA Planets Assistant" OR VPA`

Search range: 2000-01-01 .. 2026-06-26

Status: Collection started.

What I will produce here:

- results/all_repos.csv — CSV with columns: full_name, html_url, description, language, stargazers_count, forks_count, created_at, updated_at, archived, license
- results/all_repos.json — JSON array with full repo objects
- results/README.md — this file (summary and instructions)

Progress:
- Initial search completed and I have begun iterating by created-date windows to collect all ~7,876 results. This may take several minutes and multiple API calls.

Next steps (automatic):
1. Continue querying GitHub Search split by created-date intervals and aggregate results.
2. Deduplicate results and write CSV and JSON.
3. Commit results to this repository under the `results/` directory.

If you prefer I stop or change the output format/path, tell me now — otherwise I will continue and report progress as I go.
