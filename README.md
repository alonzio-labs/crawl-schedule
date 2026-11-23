# Alonzio crawl schedule

Runs [Alonzio](https://alonzio.com)'s crawler every 6 hours. This repository holds only the schedule: the crawl itself runs on
alonzio.com, which accepts each call only with a short-lived token GitHub signs for this repository's own workflow. There is
no secret here, and forks can't start a crawl.

Repository variable: `PUBLIC_URL` = `https://alonzio.com`.
