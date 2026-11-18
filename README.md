# One Day, One Page — Wednesday 18 November 2026

[![Built for make.fun](https://img.shields.io/badge/built%20for-make.fun-6C4CF1)](https://make.fun)
[![Competition entry](https://img.shields.io/badge/competition-entry-0E7C86)](https://make.fun/bounty/news-image-20261118)
[![GitHub repo](https://img.shields.io/badge/GitHub-Nugroho281%2Fnews--image--20261118-181717?logo=github)](https://github.com/Nugroho281/news-image-20261118)

A program/v1 entry for the make.fun competition "Sum up 18 November's world news in one image": a deterministic program that outputs a single PNG or JPEG summing up the day. Built with make.fun.

## The image

One newspaper front page for **Wednesday 18 November 2026** — 16 stories, 5 continents plus deep space, 7 of them illustrated:

- **Hero:** US strikes an IRGC missile site on Qeshm Island in the Strait of Hormuz; Iran answers with drone attacks on US bases in Bahrain and Kuwait.
- **Ukraine:** a second day of strikes collapses a road span of the Kerch Bridge to Crimea.
- **China:** Xi and Putin denounce sanctions at APEC in Shenzhen as Trump lands for Thursday's three-way talks.
- **Space:** Voyager 1 becomes the first human-made object a full light-day from Earth.
- **DR Congo:** the Ebola outbreak passes 11,000 cases and 5,400 deaths.
- **United States:** Mary Peltola wins Alaska, giving Democrats the Senate 56–44; and America loses its measles elimination status after 26 years.
- **In brief:** the Siberia plane crash (19 killed), Category 5 Cyclone Xavier in the Cook Islands, the World Court's Myanmar genocide ruling, Israel's new Knesset speaker, the Gaza ceasefire warning, sliding European markets, a Ukrainian drone hit on a Russian warship in the Gulf of Finland, Europe's 8,000 bomb threats, and Cambridge Dictionary's Word of the Year: "Human".

Every headline, date and figure on the page is rendered by code, so nothing is misspelled or garbled; the illustrations were drawn for this page in a matching editorial style and carry no text of their own.

## Run it

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png — the front page, byte for byte, every run
```

`main.py` uses only the Python 3 standard library, reads nothing but the `entry.png` beside it, and first checks that image against the competition's gate (PNG or JPEG, at most 1 MiB, at most 1024×1024).

## Competition

This repository is a submission to the make.fun bounty **"Sum up 18 November's world news in one image"**: https://make.fun/bounty/news-image-20261118

---
🤖 Entry built with the make.fun kit · [make.fun](https://make.fun)
