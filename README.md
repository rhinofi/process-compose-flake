# process-compose-flake
A [flake-parts](https://github.com/hercules-ci/flake-parts) module for [process-compose](https://github.com/F1bonacc1/process-compose).

## Documentation

https://zero-to-flakes.com/process-compose-flake

## Contributing

Please run `nix run github:srid/nixci` on a NixOS machine to run the full suite of tests before pushing changes to the main branch. Our CI (Github Actions) cannot do this yet.

## Related projects

- [`proc-flake`](https://github.com/srid/proc-flake): A similar module that uses a `Procfile`-based runner. It is less feature-rich, but [at times more reliable](https://github.com/Platonic-Systems/process-compose-flake/issues/30) than process-compose.
- [`services-flake`](https://github.com/juspay/services-flake): NixOS-like services built on top of process-compose-flake.
