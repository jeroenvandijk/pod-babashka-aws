# Changelog

## v0.1.1

- feat [#46](https://github.com/babashka/pod-babashka-aws/issues/46): Provide aarch64 binary ([@cap10morgan](https://github.com/cap10morgan))
- chore: update deps (see `deps.edn`)

## v0.1.0

- Bump deps (see `deps.edn`)
- Add `pod.babashka.aws.logging` namespace with `set-level!` function. See [docs](https://github.com/babashka/pod-babashka-aws#logging). [#41](https://github.com/babashka/pod-babashka-aws/issues/41)
- Fix transit serialization of `Throwable` and `Class` in `:Error` payload. [#30](https://github.com/babashka/pod-babashka-aws/issues/30)

## v0.0.6

- Bump deps (see `deps.edn`)
- Provide static linux version linked against musl ([@lispyclouds](https://github.com/lispyclouds), [@thiagokokada](https://github.com/thiagokokada))

## v0.0.4

- Bump deps (see `deps.edn`)
- Add forwarding of `aws.sessionToken` system property ([@digash](https://github.com/digash))

## v0.0.3

- Add `pod.babashka.aws.credentials` namespace ([@jeroenvandijk](https://github.com/jeroenvandijk))

## v0.0.2

- Support passing files as blob uploads directly for better memory consumption [#18](https://github.com/babashka/pod-babashka-aws/issues/18)

## v0.0.1

Initial release
