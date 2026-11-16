<p align="center">
  <img alt="CS50W" src="https://img.shields.io/badge/CS50W-Web%20Programming-A51C30?style=for-the-badge">
</p>

<h1 align="center">🎓 CS50W — Projects</h1>

<p align="center"><i>Six projects from CS50's Web Programming with Python and JavaScript — from hand-written HTML/CSS to a Dockerized Django + React app.</i></p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Django" src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</p>

---

## 🔎 Search
`HTML` `CSS` `JavaScript`

A front-end for Google Search, Google Image Search, and Google Advanced Search. Three hand-built
pages — text, image, and advanced — each with its own stylesheet, where the form sends the query
as URL parameters and opens the results in Google itself.

**[Code](https://github.com/mr-wolf-rsh/cs50w-search)** · **[Spec](https://cs50.harvard.edu/web/projects/0/search/)** · **[▶ Demo](https://youtu.be/as8lFGnDHr4/)**

## 📚 Wiki
`Python` `Django`

A Wikipedia-like encyclopedia on Django: entry pages rendered from Markdown, search across titles
and content, create and edit forms, and a random-page button for the curious.

**[Code](https://github.com/mr-wolf-rsh/cs50w-wiki)** · **[Spec](https://cs50.harvard.edu/web/projects/1/wiki/)** · **[▶ Demo](https://youtu.be/BgMmqo4kXQQ/)**

## 🛒 Commerce
`Python` `Django` `SQL`

An eBay-style auction site on Django models (`Listing`, `ListingState`, `Bid`, `Comment`) with full
authentication. Organizers post listings; visitors bid, comment, and build a watchlist, and every
listing page tracks the current highest bid.

**[Code](https://github.com/mr-wolf-rsh/cs50w-commerce)** · **[Spec](https://cs50.harvard.edu/web/projects/2/commerce/)** · **[▶ Demo](https://youtu.be/4Ko1P9H3B3k/)**

## ✉️ Mail
`Python` `Django` `JavaScript`

A single-page email client whose front-end talks to JSON endpoints (`emails`, `emails/<id>`,
`emails/<mailbox>`, `recipients`, `user`) instead of reloading pages — compose, browse mailboxes,
and open individual emails without a full refresh.

**[Code](https://github.com/mr-wolf-rsh/cs50w-mail)** · **[Spec](https://cs50.harvard.edu/web/projects/3/mail/)** · **[▶ Demo](https://youtu.be/l59l3fkW4Mk/)**

## 🌐 Network
`Python` `Django` `JavaScript`

A Threads-like social network where users post, follow each other, and browse a paginated feed —
with profile pages, follower/following lists, and an authenticated API under the hood.

**[Code](https://github.com/mr-wolf-rsh/cs50w-network)** · **[Spec](https://cs50.harvard.edu/web/projects/4/network/)** · **[▶ Demo](https://youtu.be/mj8vEnJ3k8w/)**

## 🗳️ Capstone — Voter Aid
`Django` `React` `PostgreSQL` `Docker`

A mobile-responsive app where voters explore candidates and parties: background, campaign
promises, political ideology, interest compatibility, ratings, and weekly polls with results.

- Dockerized into backend, frontend, and database containers.
- Backend: Django + Django REST Framework (Gunicorn, Pillow, Whitenoise).
- Frontend: React + Material UI, React Router, Redux Toolkit, Axios, ApexCharts.
- Data: PostgreSQL + pgAdmin, 20+ related Django models, auto-seeded from JSON at startup,
  hashed passwords.

**[Code](https://github.com/mr-wolf-rsh/cs50w-capstone)** · **[Spec](https://cs50.harvard.edu/web/projects/final/capstone/)** · **[▶ Demo](https://youtu.be/25ysHddm28Q)**

<p align="center">
  <img src="https://raw.githubusercontent.com/mr-wolf-rsh/cs50w-capstone/main/voter_aid.gif" alt="Voter Aid demo" width="400">
</p>

---

<p align="center"><i>All six are complete and archived on GitHub.</i></p>

<p align="center">Built by <a href="https://github.com/mr-wolf-rsh">Renzo S.</a> · Licensed under <a href="LICENSE">GPL-3.0</a></p>
