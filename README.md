# crashlink-asv

Accumulated [airspeed velocity](https://asv.readthedocs.io/) benchmark
results for [crashlink](https://github.com/N3rdL0rd/crashlink).

This repo holds nothing but `results/` — the JSON history that `asv publish`
needs to draw trend graphs across commits. It exists separately from
`crashlink` so that the benchmark workflow (which commits a new result file
on every push to `crashlink`'s `main` branch) doesn't add noise to
`crashlink`'s own commit history.

The benchmark suite itself (`asv.conf.json`, `benchmarks/`) lives in
[N3rdL0rd/crashlink](https://github.com/N3rdL0rd/crashlink). The published
dashboard is at <https://n3rdl0rd.github.io/crashlink/benchmarks/>.

Nothing here is meant to be edited by hand.
