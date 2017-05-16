## Pros

- **Deterministic algorithm** for installs
- **Flat mode** avoids creating duplicates
- **Network Resilience:** Requests are retried upon failure.
- Offline cache
- Commands are similar to NPM
- Fetches dependencies from the NPM registry
- Backed by Facebook and Google and still maintained

**Yarn** always creates and updates `yarn.lock`, while **npm** doesn't create one by default and only updates `npm-shrinkwrap.json` when it exists.