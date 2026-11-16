# 🎓 CS50W — Projects

Six projects from [CS50's Web Programming with Python and JavaScript](https://cs50.harvard.edu/web/),
each built as its own repository. This is the index for the set.

## The projects

| Project | What it is | Stack | Repository |
|---|---|---|---|
| Search | Front-end for Google Search, Image Search, and Advanced Search | HTML / CSS / JS | [cs50w-search](https://github.com/mr-wolf-rsh/cs50w-search) |
| Wiki | A Wikipedia-like online encyclopedia | Python / Django | [cs50w-wiki](https://github.com/mr-wolf-rsh/cs50w-wiki) |
| Commerce | eBay-like auction site: listings, bids, comments, watchlist | Python / Django + SQL | [cs50w-commerce](https://github.com/mr-wolf-rsh/cs50w-commerce) |
| Mail | Email client front-end that calls an API to send and receive mail | Python / Django + JS | [cs50w-mail](https://github.com/mr-wolf-rsh/cs50w-mail) |
| Network | Threads-like social network: posts and following | Python / Django + JS | [cs50w-network](https://github.com/mr-wolf-rsh/cs50w-network) |
| Capstone — Voter Aid | Mobile-responsive voting aid app | Django + React + PostgreSQL | [cs50w-capstone](https://github.com/mr-wolf-rsh/cs50w-capstone) |

All six are complete and **archived** on GitHub — the set is finished, not active work.

## Highlights

### Search — HTML / CSS / JS
Three hand-built pages — text, image, and advanced search — each with its own stylesheet,
with forms driven by query parameters.

### Wiki — Python / Django
A Wikipedia-like encyclopedia: entry pages, search, create and edit, and a random-page view.
Entries are rendered from **Markdown** (`markdown2`), with a small `util` layer for saving entries.

### Commerce — Python / Django + SQL
An auction site on Django models (`Listing`, `ListingState`, `Bid`, `Comment`) with
authentication: all listings and my listings, listing pages with **highest-bid tracking**,
a watchlist, bids, and comments.

### Mail — Python / Django + JS
An email client front-end backed by JSON endpoints (`emails`, `emails/<id>`, `emails/<mailbox>`,
`recipients`, `user`): compose, mailbox views, and email detail, with login/logout.

### Network — Python / Django + JS
A Threads-like social network: post creation, a paginated feed (`_get_paginator`), profiles, and
follower/following lists.

### Capstone — Voter Aid — Django + React + PostgreSQL
A mobile-responsive app where voters explore candidates and parties: background, campaign
promises, political ideology, interest compatibility, ratings, and weekly polls with results.

- **Docker** — three containers: backend, frontend, and database (`docker-compose` + a rebuild script).
- **Backend** — Django + **Django REST Framework**, with Gunicorn, Pillow, and Whitenoise.
- **Frontend** — React with **Material UI**, React Router, Redux Toolkit, Axios, and ApexCharts.
- **Data** — PostgreSQL + pgAdmin; **20+ related Django models**; the database is auto-seeded from a
  JSON file and media at startup; passwords are hashed.
- **Detail** — custom user manager (email instead of username), custom renderer and exception
  handler, Redux slices with async thunks, and custom hooks.
- [Demo video](https://youtu.be/25ysHddm28Q)

## License

[GNU General Public License v3.0](LICENSE)
