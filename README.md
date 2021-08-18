# spec-state

[![Discord](https://img.shields.io/discord/607683947496734760)](https://discord.gg/QCe2tp2)
[![Twitter](https://img.shields.io/twitter/follow/artichokeruby?label=Follow&style=social)](https://twitter.com/artichokeruby)

This repository includes historical reports for [Artichoke]'s [ruby/spec]
compliance.

## Latest

**Tagged failing specs**:
[`reports/tagged/latest.json`](reports/tagged/latest.json)  
**Failing spec backtraces**:
[`reports/exceptions/latest.json`](reports/exceptions/latest.json)

## Spec Harness

Artichoke includes a custom harness for running the ruby/spec suite called the
`spec-runner`. Every push to [artichoke/artichoke@trunk][artichoke-trunk]
triggers a run of the spec harness and pushes the results to this repository.

Relevant source code for this pipeline:

- https://github.com/artichoke/artichoke/tree/trunk/spec-runner
- https://github.com/artichoke/artichoke/blob/trunk/.github/workflows/spec-state.yaml

The first Artichoke commit recorded in this repository is
[`artichoke/artichoke@566e775`][spec-state-first-commit].

[artichoke]: https://github.com/artichoke/artichoke
[ruby/spec]: https://github.com/ruby/spec
[artichoke-trunk]: https://github.com/artichoke/artichoke/commits/trunk
[spec-state-first-commit]:
  https://github.com/artichoke/artichoke/commit/566e77538d7deac076b35653ccd983152d1f884e
