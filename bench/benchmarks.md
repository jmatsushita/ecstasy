# Benchmarks

## Before INLINE[phase] master branch

```
Benchmark ecstasy-bench: RUNNING...

benchmarking huge/init
time                 74.98 ms   (74.00 ms .. 75.75 ms)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 76.33 ms   (75.59 ms .. 77.35 ms)
std dev              1.477 ms   (1.002 ms .. 1.997 ms)

benchmarking huge/dumb
time                 193.6 ms   (178.8 ms .. 215.2 ms)
                     0.994 R²   (0.987 R² .. 1.000 R²)
mean                 183.5 ms   (180.1 ms .. 192.9 ms)
std dev              6.941 ms   (590.4 μs .. 8.893 ms)
variance introduced by outliers: 14% (moderately inflated)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).
```

## After INLINE[phase] master_inlined branch

```
Benchmark ecstasy-bench: RUNNING...

benchmarking huge/init
time                 78.20 ms   (76.92 ms .. 78.99 ms)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 80.25 ms   (79.31 ms .. 81.34 ms)
std dev              1.631 ms   (1.236 ms .. 2.185 ms)

benchmarking huge/dumb
time                 190.1 ms   (187.1 ms .. 195.7 ms)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 187.9 ms   (185.0 ms .. 190.1 ms)
std dev              3.130 ms   (1.792 ms .. 4.658 ms)
variance introduced by outliers: 14% (moderately inflated)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).
```

## Before INLINE[phase] insanity2 branch

```
Benchmark ecstasy-bench: RUNNING...
benchmarking huge/init
time                 10.07 ms   (9.645 ms .. 10.52 ms)
                     0.979 R²   (0.960 R² .. 0.991 R²)
mean                 12.70 ms   (11.91 ms .. 13.96 ms)
std dev              2.527 ms   (1.639 ms .. 3.456 ms)
variance introduced by outliers: 81% (severely inflated)

benchmarking huge/smart
time                 97.66 ms   (94.85 ms .. 101.2 ms)
                     0.999 R²   (0.997 R² .. 1.000 R²)
mean                 102.1 ms   (100.5 ms .. 104.3 ms)
std dev              2.896 ms   (1.837 ms .. 4.115 ms)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).
```

## Before INLINE[phase] insanity2_inlined branch

```
Benchmark ecstasy-bench: RUNNING...
benchmarking huge/init
time                 10.07 ms   (9.645 ms .. 10.52 ms)
                     0.979 R²   (0.960 R² .. 0.991 R²)
mean                 12.70 ms   (11.91 ms .. 13.96 ms)
std dev              2.527 ms   (1.639 ms .. 3.456 ms)
variance introduced by outliers: 81% (severely inflated)

benchmarking huge/smart
time                 97.66 ms   (94.85 ms .. 101.2 ms)
                     0.999 R²   (0.997 R² .. 1.000 R²)
mean                 102.1 ms   (100.5 ms .. 104.3 ms)
std dev              2.896 ms   (1.837 ms .. 4.115 ms)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).
```
