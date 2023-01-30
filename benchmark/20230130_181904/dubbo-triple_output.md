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
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 3.270 ops/ms
# Warmup Iteration   3: 6.971 ops/ms
Iteration   1: 7.639 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 7.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.859 ±(99.9%) 3.691 ops/ms [Average]
  (min, avg, max) = (7.639, 7.859, 8.038), stdev = 0.202
  CI (99.9%): [4.169, 11.550] (assumes normal distribution)


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
# Warmup Iteration   1: 2.202 ops/ms
# Warmup Iteration   2: 6.988 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.495 ±(99.9%) 2.199 ops/ms [Average]
  (min, avg, max) = (8.369, 8.495, 8.609), stdev = 0.121
  CI (99.9%): [6.296, 10.694] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.256 ops/ms
# Warmup Iteration   2: 6.457 ops/ms
# Warmup Iteration   3: 7.546 ops/ms
Iteration   1: 8.113 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.125 ±(99.9%) 0.192 ops/ms [Average]
  (min, avg, max) = (8.113, 8.125, 8.133), stdev = 0.011
  CI (99.9%): [7.933, 8.318] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 5.485 ops/ms
# Warmup Iteration   3: 6.631 ops/ms
Iteration   1: 6.439 ops/ms
Iteration   2: 6.817 ops/ms
Iteration   3: 7.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.775 ±(99.9%) 5.790 ops/ms [Average]
  (min, avg, max) = (6.439, 6.775, 7.070), stdev = 0.317
  CI (99.9%): [0.985, 12.566] (assumes normal distribution)


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
# Warmup Iteration   1: 12.817 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.007 ms/op
Iteration   1: 4.006 ±(99.9%) 0.009 ms/op
Iteration   2: 4.056 ±(99.9%) 0.008 ms/op
Iteration   3: 3.961 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.007 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.961, 4.007, 4.056), stdev = 0.048
  CI (99.9%): [3.140, 4.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.750 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.007 ms/op
Iteration   1: 3.908 ±(99.9%) 0.007 ms/op
Iteration   2: 3.700 ±(99.9%) 0.007 ms/op
Iteration   3: 3.838 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.815 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (3.700, 3.815, 3.908), stdev = 0.106
  CI (99.9%): [1.888, 5.742] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.604 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.005 ms/op
Iteration   1: 4.137 ±(99.9%) 0.006 ms/op
Iteration   2: 4.113 ±(99.9%) 0.006 ms/op
Iteration   3: 3.884 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.045 ±(99.9%) 2.553 ms/op [Average]
  (min, avg, max) = (3.884, 4.045, 4.137), stdev = 0.140
  CI (99.9%): [1.492, 6.597] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.914 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.451 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.007 ms/op
Iteration   1: 4.785 ±(99.9%) 0.010 ms/op
Iteration   2: 4.669 ±(99.9%) 0.013 ms/op
Iteration   3: 4.705 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.720 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (4.669, 4.720, 4.785), stdev = 0.059
  CI (99.9%): [3.641, 5.798] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.415 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.465 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.021 ms/op
Iteration   1: 4.022 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  23.266 ms/op
                 createUser·p0.9999: 25.823 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.986 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.207 ms/op
                 createUser·p0.999:  14.664 ms/op
                 createUser·p0.9999: 27.322 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 4.216 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  34.745 ms/op
                 createUser·p0.9999: 37.093 ms/op
                 createUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235546
  mean =      4.072 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 314 
    [ 2.500,  5.000) = 214814 
    [ 5.000,  7.500) = 17277 
    [ 7.500, 10.000) = 2169 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     37.243 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 12.731 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  20.305 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  14.091 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 3.901 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  26.771 ms/op
                 existUser·p0.9999: 30.140 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241273
  mean =      3.979 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 227346 
    [ 5.000,  7.500) = 10436 
    [ 7.500, 10.000) = 2322 
    [10.000, 12.500) = 552 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     21.001 ms/op
     p(99.9900) =     31.711 ms/op
     p(99.9990) =     33.311 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.839 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.015 ms/op
Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.893 ms/op
                 getUser·p0.999:  23.247 ms/op
                 getUser·p0.9999: 26.331 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 28.172 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 3.869 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.420 ms/op
                 getUser·p0.999:  27.898 ms/op
                 getUser·p0.9999: 30.310 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245777
  mean =      3.904 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 236115 
    [ 5.000,  7.500) = 7792 
    [ 7.500, 10.000) = 1130 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     30.787 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 14.371 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.854 ±(99.9%) 0.016 ms/op
Iteration   1: 4.825 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  22.938 ms/op
                 listUser·p0.9999: 28.536 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.684 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 21.203 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.600 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 19.695 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204017
  mean =      4.701 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 173459 
    [ 5.000,  7.500) = 25127 
    [ 7.500, 10.000) = 4331 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     26.521 ms/op
     p(99.9990) =     29.091 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.859 ± 3.691  ops/ms
ClientPb.existUser                       thrpt       3   8.495 ± 2.199  ops/ms
ClientPb.getUser                         thrpt       3   8.125 ± 0.192  ops/ms
ClientPb.listUser                        thrpt       3   6.775 ± 5.790  ops/ms
ClientPb.createUser                       avgt       3   4.007 ± 0.867   ms/op
ClientPb.existUser                        avgt       3   3.815 ± 1.927   ms/op
ClientPb.getUser                          avgt       3   4.045 ± 2.553   ms/op
ClientPb.listUser                         avgt       3   4.720 ± 1.078   ms/op
ClientPb.createUser                     sample  235546   4.072 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.979           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.618           ms/op
ClientPb.existUser                      sample  241273   3.979 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.786           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.020           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.001           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.711           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  245777   3.904 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.534           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.101           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.884           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  204017   4.701 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.202           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
