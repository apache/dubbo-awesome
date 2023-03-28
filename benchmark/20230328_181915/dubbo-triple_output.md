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
# Warmup Iteration   1: 1.794 ops/ms
# Warmup Iteration   2: 4.695 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 9.002 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.834 ±(99.9%) 7.410 ops/ms [Average]
  (min, avg, max) = (8.371, 8.834, 9.129), stdev = 0.406
  CI (99.9%): [1.424, 16.244] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 8.006 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.379 ops/ms
Iteration   2: 9.532 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.443 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (9.379, 9.443, 9.532), stdev = 0.079
  CI (99.9%): [7.998, 10.889] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.510 ops/ms
# Warmup Iteration   2: 7.739 ops/ms
# Warmup Iteration   3: 8.745 ops/ms
Iteration   1: 9.173 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 9.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.260 ±(99.9%) 3.486 ops/ms [Average]
  (min, avg, max) = (9.128, 9.260, 9.479), stdev = 0.191
  CI (99.9%): [5.774, 12.746] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.463 ops/ms
# Warmup Iteration   2: 6.532 ops/ms
# Warmup Iteration   3: 7.344 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 7.564 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.818 ±(99.9%) 4.445 ops/ms [Average]
  (min, avg, max) = (7.564, 7.818, 8.050), stdev = 0.244
  CI (99.9%): [3.372, 12.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.551 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.007 ms/op
Iteration   1: 3.583 ±(99.9%) 0.006 ms/op
Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
Iteration   3: 3.652 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.570 ±(99.9%) 1.620 ms/op [Average]
  (min, avg, max) = (3.476, 3.570, 3.652), stdev = 0.089
  CI (99.9%): [1.951, 5.190] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.352 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.006 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
Iteration   2: 3.368 ±(99.9%) 0.010 ms/op
Iteration   3: 3.340 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.286, 3.332, 3.368), stdev = 0.042
  CI (99.9%): [2.574, 4.089] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.349 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.007 ms/op
Iteration   1: 3.421 ±(99.9%) 0.011 ms/op
Iteration   2: 3.614 ±(99.9%) 0.005 ms/op
Iteration   3: 3.466 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.500 ±(99.9%) 1.843 ms/op [Average]
  (min, avg, max) = (3.421, 3.500, 3.614), stdev = 0.101
  CI (99.9%): [1.657, 5.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.792 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.009 ms/op
Iteration   1: 4.272 ±(99.9%) 0.010 ms/op
Iteration   2: 4.244 ±(99.9%) 0.011 ms/op
Iteration   3: 3.943 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.153 ±(99.9%) 3.328 ms/op [Average]
  (min, avg, max) = (3.943, 4.153, 4.272), stdev = 0.182
  CI (99.9%): [0.825, 7.482] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.920 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.015 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  21.301 ms/op
                 createUser·p0.9999: 26.571 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.417 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  21.903 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.599 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  20.850 ms/op
                 createUser·p0.9999: 31.953 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273568
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4715 
    [ 2.500,  5.000) = 260813 
    [ 5.000,  7.500) = 6426 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     31.169 ms/op
     p(99.9990) =     33.434 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.739 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  11.447 ms/op
                 existUser·p0.9999: 26.985 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   2: 3.537 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  21.561 ms/op
                 existUser·p0.9999: 32.110 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.083 ms/op
                 existUser·p0.999:  22.107 ms/op
                 existUser·p0.9999: 30.796 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273550
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10247 
    [ 2.500,  5.000) = 256665 
    [ 5.000,  7.500) = 5291 
    [ 7.500, 10.000) = 850 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     31.748 ms/op
     p(99.9990) =     32.639 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.329 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.013 ms/op
Iteration   1: 3.630 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 24.239 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.712 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  22.179 ms/op
                 getUser·p0.9999: 25.499 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.495 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  23.837 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265807
  mean =      3.610 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2421 
    [ 2.500,  5.000) = 253579 
    [ 5.000,  7.500) = 8632 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     27.452 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.390 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.013 ms/op
Iteration   1: 4.247 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   28.410 ms/op

Iteration   2: 4.027 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.922 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 19.308 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.497 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.544 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  19.430 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225835
  mean =      4.249 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 210613 
    [ 5.000,  7.500) = 12166 
    [ 7.500, 10.000) = 2169 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     19.044 ms/op
     p(99.9900) =     26.242 ms/op
     p(99.9990) =     28.227 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.834 ± 7.410  ops/ms
ClientPb.existUser                       thrpt       3   9.443 ± 1.446  ops/ms
ClientPb.getUser                         thrpt       3   9.260 ± 3.486  ops/ms
ClientPb.listUser                        thrpt       3   7.818 ± 4.445  ops/ms
ClientPb.createUser                       avgt       3   3.570 ± 1.620   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 0.758   ms/op
ClientPb.getUser                          avgt       3   3.500 ± 1.843   ms/op
ClientPb.listUser                         avgt       3   4.153 ± 3.328   ms/op
ClientPb.createUser                     sample  273568   3.508 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.444           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.169           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  273550   3.508 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.561           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.450           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.748           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  265807   3.610 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.460           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.289           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.690           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  225835   4.249 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.242           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.410           ms/op
