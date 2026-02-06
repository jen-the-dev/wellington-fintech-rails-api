# Demo walkthrough

## Fastest demo (Codespaces)
1. Open a Codespace from the repo (recommended).
2. Wait for setup to finish (devcontainer postCreate).
3. Run the server: `bundle exec rails server -b 0.0.0.0 -p 3000`
4. Run a few requests from `samples/requests.http`.

## What to point out
- Endpoint structure and versioning (`/api/v1/...`)
- Seed data realism (`db/seeds.rb`)
- Compliance-minded audit endpoints
