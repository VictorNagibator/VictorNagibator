<div align="center">

# Hi, I'm Viktor 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=336791&center=true&vCenter=true&width=600&lines=Software+Engineer;PostgreSQL+extensions)](https://github.com/VictorNagibator)

</div>

```sql
viktor=# SELECT * FROM about_me;
```
```text
 name   | education                                        | focus
--------+--------------------------------------------------+-----------------------------
 Viktor | BSc Software Engineering, AltSTU                 | PostgreSQL internals, C, C++
        |   (diploma with honours, straight A's)           | systems programming
        | MSc Software Engineering, AltSTU (in progress)   |
(1 row)
```

- Building **PostgreSQL extensions in C**
- BSc in Software Engineering from Altai State Technical University **with honours**, now doing my MSc there
- **Open to job opportunities**: [my resume as a psql session](https://victornagibator.github.io/resume/) · CV in PDF: [EN](https://victornagibator.github.io/resume/Donskoi_Viktor_CV_EN.pdf) · [RU](https://victornagibator.github.io/resume/Donskoi_Viktor_CV_RU.pdf)

Reach me: [Telegram](https://t.me/VictorNagibator) · [Email](mailto:vityadonskoy2004@gmail.com)

---

## Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,postgres,linux,bash,git,githubactions,python&perline=9" alt="Tech stack" />
</p>

---

## Featured projects

### [pg_integrity_checksums](https://github.com/VictorNagibator/pg_integrity_checksums)

[![CI](https://github.com/VictorNagibator/pg_integrity_checksums/actions/workflows/ci.yml/badge.svg)](https://github.com/VictorNagibator/pg_integrity_checksums/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/VictorNagibator/pg_integrity_checksums/branch/main/graph/badge.svg)](https://codecov.io/gh/VictorNagibator/pg_integrity_checksums)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16732/badge)](https://www.bestpractices.dev/projects/16732)
[![PostgreSQL 12-19](https://img.shields.io/badge/PostgreSQL-12--19-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)

A PostgreSQL extension in **C** with a companion **Go CLI**. Verifies that a replica, a restored backup or a migrated database holds *exactly* the same data as the source.

- Cell, row, table, index and database checksums
- Logical checksums survive `pg_dump`/restore, `VACUUM FULL`, `REINDEX` and moves across CPU architectures
- Pinpoints differing rows via key-bucket checksums
- Multiple algorithms: FNV-1a 32/64, CRC-32C, XXH3-64; parallel scanning
- CI, CodeQL, test coverage, OpenSSF Scorecard
- Published on PGXN and PGEXT.CLOUD, Docker image and [online docs](https://victornagibator.github.io/pg_integrity_checksums/)

```sql
SELECT pg_table_logical_checksum('public.orders'::regclass);
```

### [pg_achievements](https://github.com/VictorNagibator/pg_achievements)

Gamified achievements for PostgreSQL users, written in **C**. Unlock bronze, silver, gold and platinum for things like running `EXPLAIN ANALYZE` (or daring an `UPDATE` without `WHERE`), with `psql` notifications and a leaderboard.

### [pg_scheduler](https://github.com/VictorNagibator/pg_scheduler)

A PostgreSQL extension in **C** for scheduling and running SQL and shell jobs right inside the database.

---

## GitHub activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=VictorNagibator&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="Contribution streak" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VictorNagibator/VictorNagibator/output/github-snake-dark.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/VictorNagibator/VictorNagibator/output/github-snake.svg" />
  </picture>
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=VictorNagibator&theme=github-compact&hide_border=true&area=true&color=336791&line=336791&point=336791" alt="Contribution graph" />
</div>
