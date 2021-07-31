> Welcome to the main README.

**This repo consists of 3 projects.**

## Branches

- `ap` - Alpha prototype
- `bp` - Beta prototype
- `p` - Final prototype
- `v1` - Version number

### DClone Essential

> v1 - v6

- The core features of Discord.

### DClone Full

> v6 - v12

- In development.

---

## API

- The backend of the website.
- Includes the WebSocket and REST API.

## Utils

- API and Website are both dependent on utils.
- Used for shared files in both websites (i.e. types, utils).
- Reduce need for syncing files between projects.
- Reduces code duplication

## Website

- The UI.
- Cool but useless without the API running in the background.

---

# Setup

`api/.env`

```
API_PORT=3000
API_PREFIX="/api/v1"
JWT_SECRET_KEY="something secret"
MONGO_URI="mongodb://localhost/dclone-essential"
WEBSITE_PORT=4200
```
