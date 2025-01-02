# Immer Immutability Perf Benchmarks

This is an updated set of benchmarks for testing immutable update performance of various versions of Immer against a vanilla reducer, as well as `mutative` and `mutative-compat`.

I've also included a copy of Immer 10 built from the `faster-iteration-experiment` branch.

The reducers were copied from https://github.com/gentlee/state-manager-benchmarks , rather than using Immer's existing benchmarks.

Install with PNPM, and run `pnpm start` to run the benchmark.

(Note: the "freeze" variable is irrelevant with the vanilla reducer, but it was easiest to run that twice same as all the other implementations.)