# Miki Games

Static site: no build step.

## Deploy
1. Put this folder's contents in a GitHub repo.
2. Cloudflare Pages -> Create project -> connect the repo. Build command: none. Output directory: / (root).
3. Add your domain under Custom domains.

## Add a game
1. Make a folder `games/your-game/` with the game as `index.html`.
2. In `index.html`, copy the Flap Factory card (look for ADD A NEW GAME), then change the link, title, text and images.
3. Push. Cloudflare redeploys in about a minute.
