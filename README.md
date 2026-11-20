# FLUXIAL

DirectMeds audition workspace: agent harness, deterministic QA fixtures, and creative asset preview.

## Current deployment scope
This repository initially hosts a browser-based preview. The evaluation scenarios are deterministic annotated fixtures; they test rule behavior, not automated visual inspection of arbitrary uploaded videos. Uploaded media currently remains in the browser session. A persistent API, database, shared object storage, authentication, and computer-vision/audio detectors are not yet connected.

## Run locally
Open `index.html` in a modern browser or serve the repository root with any static web server.

## Deploy
Configured for a Render Static Site from the `main` branch, publishing the repository root.
