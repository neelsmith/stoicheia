

## Overview

`stoicheia` is a javascript library and single-page webapp for a digital edition of Euclid's *Elements of Geometry* that coordinates text and diagram.

## Functionality

The web app should be contained in a single HTML file (with javascript and CSS) that can either be served from a web server or opened from a file in the local file system.

## Architecture & Directory Structure

- `quarto`, `docs`, `README.md` and `releases.md` are all user-readable content owned by me; Claude should not touch them
- `notes` is for documentation and notes that Claude writes, includes session summaries so I can reliably pick up working with Claude from different machines
- `src` is for source code


## Testing Guidelines

- Write unit tests for utility functions and integration/component tests for critical UI flows.
- Run relevant tests before proposing significant refactors.