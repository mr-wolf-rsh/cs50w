# 🎓 CS50W — Projects

Six projects from [CS50's Web Programming with Python and JavaScript](https://cs50.harvard.edu/web/),
each built as its own repository — running from plain HTML/CSS up to a Dockerized Django + React app.

## Descriptions

### Search — HTML / CSS / JS
A front-end for Google Search, Google Image Search, and Google Advanced Search: three hand-built
pages, each with its own stylesheet, with forms driven by query parameters.

[Repository](https://github.com/mr-wolf-rsh/cs50w-search)

### Wiki — Python / Django
A Wikipedia-like encyclopedia: entry pages, search, create and edit, and a random-page view.
Entries are rendered from Markdown (`markdown2`).

[Repository](https://github.com/mr-wolf-rsh/cs50w-wiki)

### Commerce — Python / Django + SQL
An eBay-like auction site on Django models (`Listing`, `ListingState`, `Bid`, `Comment`) with
authentication: all and my listings, listing pages with highest-bid tracking, a watchlist, bids,
and comments.

[Repository](https://github.com/mr-wolf-rsh/cs50w-commerce)

### Mail — Python / Django + JS
An email client front-end backed by JSON endpoints (`emails`, `emails/<id>`, `emails/<mailbox>`,
`recipients`, `user`): compose, mailbox views, and email detail.

[Repository](https://github.com/mr-wolf-rsh/cs50w-mail)

### Network — Python / Django + JS
A Threads-like social network: post creation, a paginated feed, profiles, and follower/following
lists.

[Repository](https://github.com/mr-wolf-rsh/cs50w-network)

### Capstone — Voter Aid — Django + React + PostgreSQL
A mobile-responsive app where voters explore candidates and parties: background, campaign
promises, political ideology, interest compatibility, ratings, and weekly polls with results.

- Dockerized into backend, frontend, and database containers.
- Backend: Django + Django REST Framework (Gunicorn, Pillow, Whitenoise).
- Frontend: React + Material UI, React Router, Redux Toolkit, Axios, ApexCharts.
- Data: PostgreSQL + pgAdmin, 20+ related Django models, auto-seeded from JSON at startup,
  hashed passwords.

[Repository](https://github.com/mr-wolf-rsh/cs50w-capstone) · [▶ Demo](https://youtu.be/25ysHddm28Q)

---

All six are complete and **archived** on GitHub — the set is finished, not active work.

## License

[GNU General Public License v3.0](LICENSE)
