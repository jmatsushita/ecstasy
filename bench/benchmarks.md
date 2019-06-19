# Benchmarks

Before useing inlining phases.

Benchmark ecstasy-bench: RUNNING...
benchmarking micro/init
time                 6.851 μs   (6.740 μs .. 7.030 μs)
                     0.993 R²   (0.988 R² .. 0.997 R²)
mean                 7.195 μs   (7.058 μs .. 7.403 μs)
std dev              545.5 ns   (388.3 ns .. 775.3 ns)
variance introduced by outliers: 79% (severely inflated)

benchmarking micro/dumb
time                 11.61 μs   (11.35 μs .. 11.81 μs)
                     0.998 R²   (0.998 R² .. 0.999 R²)
mean                 11.61 μs   (11.49 μs .. 11.74 μs)
std dev              445.8 ns   (395.9 ns .. 516.8 ns)
variance introduced by outliers: 47% (moderately inflated)

benchmarking micro/sparse_dumb
time                 10.92 μs   (10.82 μs .. 11.05 μs)
                     0.999 R²   (0.998 R² .. 0.999 R²)
mean                 11.25 μs   (11.11 μs .. 11.39 μs)
std dev              459.9 ns   (391.4 ns .. 535.7 ns)
variance introduced by outliers: 50% (severely inflated)

benchmarking tiny/init
time                 63.27 μs   (62.42 μs .. 64.11 μs)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 62.63 μs   (62.23 μs .. 63.12 μs)
std dev              1.445 μs   (1.156 μs .. 1.808 μs)
variance introduced by outliers: 20% (moderately inflated)

benchmarking tiny/dumb
time                 105.0 μs   (103.1 μs .. 106.5 μs)
                     0.999 R²   (0.998 R² .. 1.000 R²)
mean                 103.0 μs   (102.3 μs .. 103.9 μs)
std dev              2.466 μs   (1.917 μs .. 3.393 μs)
variance introduced by outliers: 20% (moderately inflated)

benchmarking tiny/sparse_dumb
time                 95.64 μs   (95.21 μs .. 96.04 μs)
                     1.000 R²   (1.000 R² .. 1.000 R²)
mean                 96.20 μs   (95.70 μs .. 96.89 μs)
std dev              1.888 μs   (1.465 μs .. 2.452 μs)
variance introduced by outliers: 15% (moderately inflated)

benchmarking small/init
time                 731.1 μs   (726.9 μs .. 736.2 μs)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 733.7 μs   (728.2 μs .. 741.3 μs)
std dev              21.06 μs   (15.87 μs .. 32.38 μs)
variance introduced by outliers: 19% (moderately inflated)

benchmarking small/dumb
time                 1.257 ms   (1.249 ms .. 1.264 ms)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 1.258 ms   (1.249 ms .. 1.268 ms)
std dev              33.50 μs   (24.80 μs .. 46.53 μs)
variance introduced by outliers: 14% (moderately inflated)

benchmarking small/sparse_dumb
time                 1.323 ms   (1.284 ms .. 1.360 ms)
                     0.996 R²   (0.994 R² .. 0.999 R²)
mean                 1.270 ms   (1.256 ms .. 1.290 ms)
std dev              55.03 μs   (43.77 μs .. 70.41 μs)
variance introduced by outliers: 32% (moderately inflated)

> benchmarking big/init
> time                 7.338 ms   (7.176 ms .. 7.578 ms)
>                      0.996 R²   (0.991 R² .. 0.999 R²)
> mean                 7.560 ms   (7.479 ms .. 7.682 ms)
> std dev              290.0 μs   (217.0 μs .. 418.8 μs)
> variance introduced by outliers: 17% (moderately inflated)
>
> benchmarking big/dumb
> time                 15.42 ms   (14.88 ms .. 16.05 ms)
>                      0.995 R²   (0.991 R² .. 1.000 R²)
> mean                 15.32 ms   (15.16 ms .. 15.57 ms)
> std dev              490.3 μs   (355.8 μs .. 649.1 μs)
> variance introduced by outliers: 12% (moderately inflated)

benchmarking big/sparse_dumb
time                 13.97 ms   (13.77 ms .. 14.12 ms)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 14.07 ms   (13.98 ms .. 14.17 ms)
std dev              247.7 μs   (184.9 μs .. 327.2 μs)

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

benchmarking huge/sparse_dumb
time                 178.5 ms   (159.8 ms .. 201.9 ms)
                     0.989 R²   (0.978 R² .. 1.000 R²)
mean                 173.9 ms   (169.1 ms .. 180.2 ms)
std dev              7.591 ms   (4.020 ms .. 10.68 ms)
variance introduced by outliers: 12% (moderately inflated)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).

## After INLINE[phase]

Benchmark ecstasy-bench: RUNNING...
benchmarking micro/init
time                 6.914 μs   (6.863 μs .. 6.982 μs)
                     0.997 R²   (0.995 R² .. 0.998 R²)
mean                 7.329 μs   (7.199 μs .. 7.515 μs)
std dev              521.8 ns   (388.2 ns .. 730.5 ns)
variance introduced by outliers: 77% (severely inflated)

benchmarking micro/dumb
time                 11.37 μs   (11.32 μs .. 11.42 μs)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 11.38 μs   (11.31 μs .. 11.46 μs)
std dev              250.7 ns   (190.2 ns .. 336.3 ns)
variance introduced by outliers: 22% (moderately inflated)

benchmarking micro/sparse_dumb
time                 10.93 μs   (10.85 μs .. 11.02 μs)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 10.92 μs   (10.86 μs .. 11.01 μs)
std dev              253.1 ns   (201.0 ns .. 406.1 ns)
variance introduced by outliers: 24% (moderately inflated)

benchmarking tiny/init
time                 64.70 μs   (64.23 μs .. 65.44 μs)
                     0.999 R²   (0.997 R² .. 1.000 R²)
mean                 66.13 μs   (65.52 μs .. 67.20 μs)
std dev              2.686 μs   (1.710 μs .. 4.303 μs)
variance introduced by outliers: 43% (moderately inflated)

benchmarking tiny/dumb
time                 104.1 μs   (103.3 μs .. 105.0 μs)
                     0.999 R²   (0.997 R² .. 0.999 R²)
mean                 106.6 μs   (105.1 μs .. 108.9 μs)
std dev              5.939 μs   (4.119 μs .. 9.015 μs)
variance introduced by outliers: 57% (severely inflated)

benchmarking tiny/sparse_dumb
time                 97.27 μs   (96.51 μs .. 98.27 μs)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 97.04 μs   (96.30 μs .. 97.89 μs)
std dev              2.901 μs   (2.310 μs .. 3.852 μs)
variance introduced by outliers: 28% (moderately inflated)

benchmarking small/init
time                 730.5 μs   (727.3 μs .. 734.6 μs)
                     1.000 R²   (0.999 R² .. 1.000 R²)
mean                 737.5 μs   (733.5 μs .. 745.2 μs)
std dev              17.53 μs   (11.59 μs .. 28.29 μs)
variance introduced by outliers: 14% (moderately inflated)

benchmarking small/dumb
time                 1.269 ms   (1.259 ms .. 1.277 ms)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 1.273 ms   (1.264 ms .. 1.285 ms)
std dev              33.65 μs   (26.22 μs .. 42.58 μs)
variance introduced by outliers: 14% (moderately inflated)

benchmarking small/sparse_dumb
time                 1.254 ms   (1.241 ms .. 1.267 ms)
                     0.999 R²   (0.999 R² .. 1.000 R²)
mean                 1.249 ms   (1.241 ms .. 1.259 ms)
std dev              29.78 μs   (23.53 μs .. 38.75 μs)
variance introduced by outliers: 13% (moderately inflated)

> benchmarking big/init
> time                 7.597 ms   (7.375 ms .. 7.832 ms)
>                      0.997 R²   (0.995 R² .. 1.000 R²)
> mean                 7.471 ms   (7.422 ms .. 7.546 ms)
> std dev              177.0 μs   (124.0 μs .. 275.5 μs)
>
> benchmarking big/dumb
> time                 15.12 ms   (14.87 ms .. 15.31 ms)
>                      0.999 R²   (0.998 R² .. 0.999 R²)
> mean                 15.40 ms   (15.25 ms .. 15.63 ms)
> std dev              445.8 μs   (354.1 μs .. 560.5 μs)

benchmarking big/sparse_dumb
time                 14.93 ms   (14.57 ms .. 15.27 ms)
                     0.998 R²   (0.996 R² .. 0.999 R²)
mean                 14.38 ms   (14.24 ms .. 14.56 ms)
std dev              373.0 μs   (296.3 μs .. 516.4 μs)

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

benchmarking huge/sparse_dumb
time                 175.3 ms   (169.1 ms .. 186.7 ms)
                     0.997 R²   (0.989 R² .. 1.000 R²)
mean                 173.6 ms   (170.4 ms .. 177.5 ms)
std dev              4.826 ms   (2.984 ms .. 6.332 ms)
variance introduced by outliers: 12% (moderately inflated)

Benchmark ecstasy-bench: FINISH
Completed 2 action(s).
