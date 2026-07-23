# omote (表) — shell-interface testing

The outward **face** of a program — its external command-line contract — proven as
a typed corpus. omote is the **`(defcase)` facet of [dojo](https://github.com/pleme-io/dojo)**
(the master testing vocabulary), not a standalone framework: it contributes the
shell-invocation quality, in three modes.

- **FIXED-EXPECTATION** — one program, matched against a declared exit/stdout/stderr.
- **DIFFERENTIAL** — two backends, one invocation, an equivalence relation.
- **directed-SUPERSET** — the candidate *accepts* every reference invocation (extras
  allowed) — the `alias nix=sui` conformance claim. A superset row has no
  `Exact`-output variant to name (truly-unrepresentable by construction).

## Status
Face/Surface **面** family (siblings `ura` 裏 internal-tests, `men` 面 surface). The
`alias nix=sui` SUPERSET passthrough is **shipped in sui** (`try_parse` →
`exec_cppnix_passthrough`, guaranteed superset by construction). omote's `(defcase)`
engine (`ShellEnvironment` + the 3 modes) is authored inside `dojo` from the start
(it consumes `dojo-types` + `dojo-differential`) — dojo M3. Doctrine:
[`theory/DOJO.md`] §5.
