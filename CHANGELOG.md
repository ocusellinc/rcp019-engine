# Changelog

## [2.0.0](https://github.com/ocusellinc/rcp019-engine/compare/v1.1.2...v2.0.0) (2026-11-10)


### ⚠ BREAKING CHANGES

* the package is now `rcp019-engine`. Dependents must update their Cargo.toml, either importing `rcp019_engine` or aliasing with `rets_expression = { git = "...", tag = "...", package = "rcp019-engine" }`.

### Features

* rename crate to rcp019-engine ([#14](https://github.com/ocusellinc/rcp019-engine/issues/14)) ([bf9e64a](https://github.com/ocusellinc/rcp019-engine/commit/bf9e64a74abcee10373c51a4fe9fac8b9afa6adc))

## [1.1.2](https://github.com/paulredmond/rets_expression/compare/v1.1.1...v1.1.2) (2026-11-10)


### Bug Fixes

* reject comparisons with a missing right-hand side ([#10](https://github.com/paulredmond/rets_expression/issues/10)) ([a64fa67](https://github.com/paulredmond/rets_expression/commit/a64fa674446fd40a893cacf6f4827d6d7836345f))

## [1.1.1](https://github.com/paulredmond/rets_expression/compare/v1.1.0...v1.1.1) (2026-08-20)


### Bug Fixes

* stop SUBSTR panicking on reversed ranges and multi-byte input ([#8](https://github.com/paulredmond/rets_expression/issues/8)) ([b73e247](https://github.com/paulredmond/rets_expression/commit/b73e247121089cc293e596019a952be0b151fdc6))

## [1.1.0](https://github.com/paulredmond/rets_expression/compare/v1.0.1...v1.1.0) (2026-03-24)


### Features

* add .ENTRY. and .OLDVALUE. keyword support ([#5](https://github.com/paulredmond/rets_expression/issues/5)) ([36d4f25](https://github.com/paulredmond/rets_expression/commit/36d4f25db49ca0c6dbfab8f0a7c16e851a9623da))

## [1.0.1](https://github.com/paulredmond/rets_expression/compare/v1.0.0...v1.0.1) (2026-03-09)


### Bug Fixes

* use signed integer arithmetic for NaiveDate day offsets ([d66afb9](https://github.com/paulredmond/rets_expression/commit/d66afb99cbf921005fb2de9fbd756f5e9d4fa242))
