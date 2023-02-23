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
# Warmup Iteration   1: 1.535 ops/ms
# Warmup Iteration   2: 3.549 ops/ms
# Warmup Iteration   3: 7.700 ops/ms
Iteration   1: 7.560 ops/ms
Iteration   2: 7.813 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.917 ±(99.9%) 7.643 ops/ms [Average]
  (min, avg, max) = (7.560, 7.917, 8.378), stdev = 0.419
  CI (99.9%): [0.273, 15.560] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.396 ops/ms
# Warmup Iteration   2: 7.060 ops/ms
# Warmup Iteration   3: 7.781 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.145 ops/ms
Iteration   3: 8.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.150 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (7.997, 8.150, 8.307), stdev = 0.155
  CI (99.9%): [5.325, 10.975] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 7.800 ops/ms
Iteration   1: 8.147 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.180 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (8.054, 8.180, 8.340), stdev = 0.146
  CI (99.9%): [5.520, 10.840] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 5.866 ops/ms
# Warmup Iteration   3: 7.443 ops/ms
Iteration   1: 7.246 ops/ms
Iteration   2: 6.988 ops/ms
Iteration   3: 6.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.935 ±(99.9%) 6.214 ops/ms [Average]
  (min, avg, max) = (6.571, 6.935, 7.246), stdev = 0.341
  CI (99.9%): [0.721, 13.149] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.731 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
Iteration   2: 3.968 ±(99.9%) 0.006 ms/op
Iteration   3: 4.225 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.056 ±(99.9%) 2.664 ms/op [Average]
  (min, avg, max) = (3.968, 4.056, 4.225), stdev = 0.146
  CI (99.9%): [1.392, 6.721] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.174 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.008 ms/op
Iteration   1: 3.665 ±(99.9%) 0.006 ms/op
Iteration   2: 3.801 ±(99.9%) 0.006 ms/op
Iteration   3: 3.684 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.717 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (3.665, 3.717, 3.801), stdev = 0.074
  CI (99.9%): [2.368, 5.065] (assumes normal distribution)


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
# Warmup Iteration   1: 12.546 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.009 ms/op
Iteration   1: 3.881 ±(99.9%) 0.006 ms/op
Iteration   2: 3.862 ±(99.9%) 0.007 ms/op
Iteration   3: 3.868 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.870 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (3.862, 3.870, 3.881), stdev = 0.009
  CI (99.9%): [3.701, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 15.108 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.008 ms/op
Iteration   1: 4.894 ±(99.9%) 0.014 ms/op
Iteration   2: 4.570 ±(99.9%) 0.013 ms/op
Iteration   3: 4.329 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.597 ±(99.9%) 5.170 ms/op [Average]
  (min, avg, max) = (4.329, 4.597, 4.894), stdev = 0.283
  CI (99.9%): [≈ 0, 9.768] (assumes normal distribution)


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
# Warmup Iteration   1: 11.399 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.016 ms/op
Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  14.653 ms/op
                 createUser·p0.9999: 29.132 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 3.883 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  23.374 ms/op
                 createUser·p0.9999: 29.944 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 3.867 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  25.654 ms/op
                 createUser·p0.9999: 28.729 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244701
  mean =      3.920 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 644 
    [ 2.500,  5.000) = 230046 
    [ 5.000,  7.500) = 12218 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     22.685 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.751 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
Iteration   1: 3.734 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  23.822 ms/op
                 existUser·p0.9999: 26.098 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.818 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 26.845 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.780 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  25.676 ms/op
                 existUser·p0.9999: 30.593 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254044
  mean =      3.777 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 924 
    [ 2.500,  5.000) = 244075 
    [ 5.000,  7.500) = 7081 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     22.704 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.290 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  21.103 ms/op
                 getUser·p0.9999: 22.458 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.925 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.919 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   7.154 ms/op
                 getUser·p0.999:  18.466 ms/op
                 getUser·p0.9999: 30.413 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 3.967 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  24.132 ms/op
                 getUser·p0.9999: 26.376 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245127
  mean =      3.913 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1500 
    [ 2.500,  5.000) = 230619 
    [ 5.000,  7.500) = 11022 
    [ 7.500, 10.000) = 1283 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     21.361 ms/op
     p(99.9900) =     28.769 ms/op
     p(99.9990) =     31.023 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 13.660 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.136 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.717 ±(99.9%) 0.019 ms/op
Iteration   1: 4.502 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  23.891 ms/op
                 listUser·p0.9999: 27.081 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.474 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 4.450 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214166
  mean =      4.475 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 195415 
    [ 5.000,  7.500) = 14661 
    [ 7.500, 10.000) = 2898 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     26.037 ms/op
     p(99.9990) =     27.643 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.917 ± 7.643  ops/ms
ClientPb.existUser                       thrpt       3   8.150 ± 2.825  ops/ms
ClientPb.getUser                         thrpt       3   8.180 ± 2.660  ops/ms
ClientPb.listUser                        thrpt       3   6.935 ± 6.214  ops/ms
ClientPb.createUser                       avgt       3   4.056 ± 2.664   ms/op
ClientPb.existUser                        avgt       3   3.717 ± 1.349   ms/op
ClientPb.getUser                          avgt       3   3.870 ± 0.169   ms/op
ClientPb.listUser                         avgt       3   4.597 ± 5.170   ms/op
ClientPb.createUser                     sample  244701   3.920 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.741           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.685           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.262           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  254044   3.777 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.014           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.653           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.704           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.065           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.900           ms/op
ClientPb.getUser                        sample  245127   3.913 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.923           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.361           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.769           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  214166   4.475 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.973           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
