# Why this fork exists

An organisation-owned fork of `pydantic/pydantic`, kept so mo-eval can mine a PYTHON benchmark and so
its results are visible to the whole organisation — access is scoped by a repository's owner.

Chosen on two measurements rather than on familiarity, after an earlier attempt on a mature library
selected zero tasks: 300 merged pull requests reach back only to 2026-03 (so none are rejected as too
old), and 17 of 30 recent ones touch non-test source. Recency alone is NOT fit — a repository can
merge constantly and still offer nothing to mine if the changes are docs and CI.

`repo` in `config.toml` names the UPSTREAM: the pull requests mined here are upstream's.
