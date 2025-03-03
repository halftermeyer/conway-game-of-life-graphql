# Conway’s Game of Life with GraphQL for Neo4j AuraDB Beta

This repository contains an implementation of Conway’s Game of Life using GraphQL and Neo4j AuraDB Beta, with a browser-based UI. It supports finite, toroidal, and infinite grids, as well as custom rules.

## Prerequisites
- Neo4j AuraDB account (sign up for a free 14-day trial, extendable by 7 days)
- Chrome or Firefox browser
- Node.js (v16+) and npm for frontend dependencies

## Installation
1. Clone this repository: `git clone <your-repo-url>`
2. Run this script: `./setup-env.sh`
3. Host the `src/frontend` files on a static hosting service (e.g., GitHub Pages).
4. Set up the GraphQL API in Neo4j AuraDB Beta using the schema in `src/schema/conway.graphql`.
5. Configure CORS in AuraDB to allow your webpage’s origin (e.g., `https://<your-username>.github.io`).
6. Obtain an AuraDB authentication token and update `src/frontend/script.js` with it.

## Usage
- Open `src/frontend/index.html` in Chrome or Firefox.
- Use the UI to set grid size, live cells, generations, grid type (finite/toroidal/infinite), and custom rules.
- Click "Start" to run the game, "Stop" to pause, or "Reset" to clear.

## Submission
Email the GitHub repository link to `jon.giffard@neo4j.com` by March 31, 2025, 5 p.m. GMT.

## License
This project is licensed under the GNU General Public License v3.0.
