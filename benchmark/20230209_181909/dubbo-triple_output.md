# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.033 ops/ms
# Warmup Iteration   2: 2.261 ops/ms
# Warmup Iteration   3: 4.528 ops/ms
Iteration   1: 5.213 ops/ms
Iteration   2: 5.602 ops/ms
Iteration   3: 5.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.590 ±(99.9%) 6.763 ops/ms [Average]
  (min, avg, max) = (5.213, 5.590, 5.954), stdev = 0.371
  CI (99.9%): [≈ 0, 12.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.633 ops/ms
# Warmup Iteration   2: 4.851 ops/ms
# Warmup Iteration   3: 5.645 ops/ms
Iteration   1: 5.821 ops/ms
Iteration   2: 5.983 ops/ms
Iteration   3: 6.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.964 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (5.821, 5.964, 6.089), stdev = 0.135
  CI (99.9%): [3.505, 8.424] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.493 ops/ms
# Warmup Iteration   2: 4.500 ops/ms
# Warmup Iteration   3: 5.594 ops/ms
Iteration   1: 5.541 ops/ms
Iteration   2: 5.434 ops/ms
Iteration   3: 5.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.625 ±(99.9%) 4.447 ops/ms [Average]
  (min, avg, max) = (5.434, 5.625, 5.899), stdev = 0.244
  CI (99.9%): [1.178, 10.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.535 ops/ms
# Warmup Iteration   2: 3.990 ops/ms
# Warmup Iteration   3: 5.020 ops/ms
Iteration   1: 4.843 ops/ms
Iteration   2: 4.842 ops/ms
Iteration   3: 4.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.887 ±(99.9%) 1.412 ops/ms [Average]
  (min, avg, max) = (4.842, 4.887, 4.976), stdev = 0.077
  CI (99.9%): [3.475, 6.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.477 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.708 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.063 ±(99.9%) 0.012 ms/op
Iteration   1: 5.854 ±(99.9%) 0.013 ms/op
Iteration   2: 5.717 ±(99.9%) 0.014 ms/op
Iteration   3: 5.789 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.786 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (5.717, 5.786, 5.854), stdev = 0.069
  CI (99.9%): [4.535, 7.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.027 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.668 ±(99.9%) 0.010 ms/op
Iteration   1: 5.525 ±(99.9%) 0.011 ms/op
Iteration   2: 5.320 ±(99.9%) 0.012 ms/op
Iteration   3: 5.350 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.399 ±(99.9%) 2.020 ms/op [Average]
  (min, avg, max) = (5.320, 5.399, 5.525), stdev = 0.111
  CI (99.9%): [3.379, 7.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.534 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.862 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.749 ±(99.9%) 0.010 ms/op
Iteration   1: 5.515 ±(99.9%) 0.012 ms/op
Iteration   2: 5.655 ±(99.9%) 0.010 ms/op
Iteration   3: 5.757 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.642 ±(99.9%) 2.212 ms/op [Average]
  (min, avg, max) = (5.515, 5.642, 5.757), stdev = 0.121
  CI (99.9%): [3.431, 7.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.996 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.860 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.939 ±(99.9%) 0.012 ms/op
Iteration   1: 6.526 ±(99.9%) 0.011 ms/op
Iteration   2: 6.599 ±(99.9%) 0.012 ms/op
Iteration   3: 6.608 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.578 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (6.526, 6.578, 6.608), stdev = 0.045
  CI (99.9%): [5.750, 7.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.253 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 7.920 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.114 ±(99.9%) 0.029 ms/op
Iteration   1: 5.518 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  16.877 ms/op
                 createUser·p0.9999: 30.724 ms/op
                 createUser·p1.00:   31.916 ms/op

Iteration   2: 5.623 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   11.066 ms/op
                 createUser·p0.999:  28.653 ms/op
                 createUser·p0.9999: 32.702 ms/op
                 createUser·p1.00:   37.945 ms/op

Iteration   3: 5.585 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   10.781 ms/op
                 createUser·p0.999:  27.995 ms/op
                 createUser·p0.9999: 31.681 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172015
  mean =      5.575 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 56716 
    [ 5.000,  7.500) = 104451 
    [ 7.500, 10.000) = 8139 
    [10.000, 12.500) = 1773 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     24.640 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     35.019 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.953 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 6.828 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.519 ±(99.9%) 0.022 ms/op
Iteration   1: 5.625 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   7.242 ms/op
                 existUser·p0.95:   8.552 ms/op
                 existUser·p0.99:   11.600 ms/op
                 existUser·p0.999:  16.855 ms/op
                 existUser·p0.9999: 26.925 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 5.328 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.007 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  15.875 ms/op
                 existUser·p0.9999: 31.457 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   3: 5.346 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   10.748 ms/op
                 existUser·p0.999:  26.340 ms/op
                 existUser·p0.9999: 30.115 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176789
  mean =      5.430 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 78321 
    [ 5.000,  7.500) = 87427 
    [ 7.500, 10.000) = 8263 
    [10.000, 12.500) = 1823 
    [12.500, 15.000) = 554 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     17.669 ms/op
     p(99.9900) =     30.714 ms/op
     p(99.9990) =     32.533 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.707 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.616 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.669 ±(99.9%) 0.022 ms/op
Iteration   1: 5.541 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   8.061 ms/op
                 getUser·p0.99:   10.901 ms/op
                 getUser·p0.999:  15.712 ms/op
                 getUser·p0.9999: 27.351 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 5.670 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   7.217 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   11.158 ms/op
                 getUser·p0.999:  26.890 ms/op
                 getUser·p0.9999: 39.773 ms/op
                 getUser·p1.00:   41.681 ms/op

Iteration   3: 5.489 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.993 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  27.984 ms/op
                 getUser·p0.9999: 31.588 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172370
  mean =      5.566 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64757 
    [ 5.000, 10.000) = 104982 
    [10.000, 15.000) = 2317 
    [15.000, 20.000) = 125 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 101 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     24.322 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     40.685 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.029 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.742 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.714 ±(99.9%) 0.030 ms/op
Iteration   1: 6.631 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 35.597 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   2: 6.441 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.432 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  29.491 ms/op
                 listUser·p0.9999: 37.161 ms/op
                 listUser·p1.00:   38.011 ms/op

Iteration   3: 6.635 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  30.796 ms/op
                 listUser·p0.9999: 37.468 ms/op
                 listUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146130
  mean =      6.568 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 5368 
    [ 5.000,  7.500) = 119472 
    [ 7.500, 10.000) = 16213 
    [10.000, 12.500) = 3698 
    [12.500, 15.000) = 799 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      6.193 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.372 ms/op
     p(99.0000) =     12.403 ms/op
     p(99.9000) =     29.426 ms/op
     p(99.9900) =     37.119 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.590 ± 6.763  ops/ms
ClientPb.existUser                       thrpt       3   5.964 ± 2.459  ops/ms
ClientPb.getUser                         thrpt       3   5.625 ± 4.447  ops/ms
ClientPb.listUser                        thrpt       3   4.887 ± 1.412  ops/ms
ClientPb.createUser                       avgt       3   5.786 ± 1.251   ms/op
ClientPb.existUser                        avgt       3   5.399 ± 2.020   ms/op
ClientPb.getUser                          avgt       3   5.642 ± 2.212   ms/op
ClientPb.listUser                         avgt       3   6.578 ± 0.828   ms/op
ClientPb.createUser                     sample  172015   5.575 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.913           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.912           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.640           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.440           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  176789   5.430 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.848           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.928           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.669           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.714           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  172370   5.566 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.537           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.118           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.043           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.322           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.191           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.681           ms/op
ClientPb.listUser                       sample  146130   6.568 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.193           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.403           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.119           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.666           ms/op
