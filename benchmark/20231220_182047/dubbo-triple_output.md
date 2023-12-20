# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 11.959 ops/ms
# Warmup Iteration   3: 12.186 ops/ms
Iteration   1: 12.607 ops/ms
Iteration   2: 12.520 ops/ms
Iteration   3: 12.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.544 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (12.506, 12.544, 12.607), stdev = 0.055
  CI (99.9%): [11.548, 13.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.406 ops/ms
# Warmup Iteration   2: 13.401 ops/ms
# Warmup Iteration   3: 13.350 ops/ms
Iteration   1: 13.324 ops/ms
Iteration   2: 13.491 ops/ms
Iteration   3: 13.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.384 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (13.324, 13.384, 13.491), stdev = 0.094
  CI (99.9%): [11.677, 15.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.683 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.756 ops/ms
Iteration   1: 13.040 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.869 ±(99.9%) 3.109 ops/ms [Average]
  (min, avg, max) = (12.699, 12.869, 13.040), stdev = 0.170
  CI (99.9%): [9.761, 15.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.702 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.566 ops/ms
Iteration   2: 10.437 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.510 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (10.437, 10.510, 10.566), stdev = 0.067
  CI (99.9%): [9.292, 11.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.003 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.468, 2.501, 2.518), stdev = 0.029
  CI (99.9%): [1.974, 3.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
Iteration   2: 2.436 ±(99.9%) 0.003 ms/op
Iteration   3: 2.420 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.420, 2.439, 2.462), stdev = 0.021
  CI (99.9%): [2.056, 2.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (2.515, 2.519, 2.525), stdev = 0.005
  CI (99.9%): [2.426, 2.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.967 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.089 ±(99.9%) 0.004 ms/op
Iteration   2: 3.083 ±(99.9%) 0.004 ms/op
Iteration   3: 3.082 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.085 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (3.082, 3.085, 3.089), stdev = 0.004
  CI (99.9%): [3.018, 3.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  11.736 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  8.263 ms/op
                 createUser·p0.9999: 12.156 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  8.846 ms/op
                 createUser·p0.9999: 10.705 ms/op
                 createUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383851
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 186178 
    [ 2.500,  3.750) = 193943 
    [ 3.750,  5.000) = 3033 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     13.101 ms/op
     p(99.9990) =     13.749 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.505 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  5.916 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.704 ms/op
                 existUser·p0.9999: 13.018 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  5.856 ms/op
                 existUser·p0.9999: 12.288 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391987
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 194191 
    [ 2.500,  3.750) = 194713 
    [ 3.750,  5.000) = 2255 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      5.882 ms/op
     p(99.9900) =     13.251 ms/op
     p(99.9990) =     14.206 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  5.543 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  8.654 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.214 ms/op
                 getUser·p0.9999: 11.829 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379076
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 185008 
    [ 2.500,  3.750) = 188047 
    [ 3.750,  5.000) = 5013 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      6.446 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.212 ms/op
                 listUser·p0.9999: 13.263 ms/op
                 listUser·p1.00:   13.959 ms/op

Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.879 ms/op
                 listUser·p0.9999: 12.154 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  10.580 ms/op
                 listUser·p0.9999: 12.271 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313947
  mean =      3.055 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 86971 
    [ 2.500,  3.750) = 183961 
    [ 3.750,  5.000) = 34572 
    [ 5.000,  6.250) = 6674 
    [ 6.250,  7.500) = 916 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 167 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     12.288 ms/op
     p(99.9990) =     13.814 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.544 ± 0.997  ops/ms
ClientPb.existUser                       thrpt       3  13.384 ± 1.706  ops/ms
ClientPb.getUser                         thrpt       3  12.869 ± 3.109  ops/ms
ClientPb.listUser                        thrpt       3  10.510 ± 1.218  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.383   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.093   ms/op
ClientPb.listUser                         avgt       3   3.085 ± 0.067   ms/op
ClientPb.createUser                     sample  383851   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.730           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.847           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.101           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.844           ms/op
ClientPb.existUser                      sample  391987   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.882           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.251           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  379076   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.446           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.350           ms/op
ClientPb.listUser                       sample  313947   3.055 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.043           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.959           ms/op
