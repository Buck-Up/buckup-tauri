# Windows Development

Oh boy... so many fun surprises.

## cargo?

lol `cargo` is actually `rustup`:

```txt
$ cargo --version
rustup 1.28.2 (e4f3ad6f8 2025-04-28)
info: This is the version for the rustup toolchain manager, not the rustc compiler.
info: The currently active `rustc` version is `rustc 1.87.0 (17067e9ac 2025-05-09)`
```

in order to run `cargo ...` commands:

```txt
$ rustup run stable cargo --version
cargo 1.87.0 (99624be96 2025-05-06)
```

## nodejs? pnpm?

this project did not run on the previously-installed verison of nodejs, so I
updated to the latest LTS version:

```txt
$ node --version
v22.16.0
```

perhaps from my previous installation of nodejs...? I already had
[chocolately](https://chocolatey.org/) installed.

I upgraded chocolatey (it was a very old version):

```txt
$ choco upgrade chocolatey
$ choco --version
2.4.3
```

now we can install pnpm:

```txt
$ choco install pnpm
$ pnpm --version
10.11.0
```
