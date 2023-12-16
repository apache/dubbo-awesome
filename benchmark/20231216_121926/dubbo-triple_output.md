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
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 11.737 ops/ms
# Warmup Iteration   3: 12.215 ops/ms
Iteration   1: 12.784 ops/ms
Iteration   2: 13.064 ops/ms
Iteration   3: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.987 ±(99.9%) 3.247 ops/ms [Average]
  (min, avg, max) = (12.784, 12.987, 13.114), stdev = 0.178
  CI (99.9%): [9.740, 16.235] (assumes normal distribution)


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
# Warmup Iteration   1: 8.449 ops/ms
# Warmup Iteration   2: 13.534 ops/ms
# Warmup Iteration   3: 13.429 ops/ms
Iteration   1: 13.558 ops/ms
Iteration   2: 13.409 ops/ms
Iteration   3: 13.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.402 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (13.238, 13.402, 13.558), stdev = 0.160
  CI (99.9%): [10.479, 16.324] (assumes normal distribution)


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
# Warmup Iteration   1: 7.509 ops/ms
# Warmup Iteration   2: 12.755 ops/ms
# Warmup Iteration   3: 12.961 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 12.819 ops/ms
Iteration   3: 12.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.832 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (12.797, 12.832, 12.880), stdev = 0.043
  CI (99.9%): [12.052, 13.612] (assumes normal distribution)


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
# Warmup Iteration   1: 6.886 ops/ms
# Warmup Iteration   2: 10.708 ops/ms
# Warmup Iteration   3: 10.663 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.766 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (10.733, 10.766, 10.797), stdev = 0.032
  CI (99.9%): [10.184, 11.347] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (2.496, 2.516, 2.530), stdev = 0.018
  CI (99.9%): [2.186, 2.847] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.015 ms/op [Average]
  (min, avg, max) = (2.444, 2.445, 2.446), stdev = 0.001
  CI (99.9%): [2.430, 2.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.496, 2.521, 2.537), stdev = 0.022
  CI (99.9%): [2.121, 2.921] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.007 ms/op
Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
Iteration   3: 2.924 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.934 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.924, 2.934, 2.950), stdev = 0.014
  CI (99.9%): [2.678, 3.191] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.877 ms/op
                 createUser·p0.999:  11.735 ms/op
                 createUser·p0.9999: 14.806 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.434 ms/op
                 createUser·p0.9999: 13.539 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.732 ms/op
                 createUser·p0.9999: 18.168 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378709
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 184784 
    [ 2.500,  3.750) = 188706 
    [ 3.750,  5.000) = 3926 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      8.808 ms/op
     p(99.9900) =     15.206 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  5.238 ms/op
                 existUser·p0.9999: 13.498 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.790 ms/op
                 existUser·p0.9999: 14.083 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.376 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.696 ms/op
                 existUser·p0.9999: 11.280 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389565
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 191809 
    [ 2.500,  3.750) = 194674 
    [ 3.750,  5.000) = 2299 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.336 ms/op
     p(99.9900) =     13.501 ms/op
     p(99.9990) =     14.323 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.935 ms/op
                 getUser·p0.999:  7.338 ms/op
                 getUser·p0.9999: 14.747 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.929 ms/op
                 getUser·p0.9999: 12.879 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.864 ms/op
                 getUser·p0.9999: 11.390 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385143
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 190959 
    [ 2.500,  3.750) = 188516 
    [ 3.750,  5.000) = 4397 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      6.872 ms/op
     p(99.9900) =     13.721 ms/op
     p(99.9990) =     16.013 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 14.364 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  10.107 ms/op
                 listUser·p0.9999: 13.582 ms/op
                 listUser·p1.00:   15.106 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.451 ms/op
                 listUser·p0.999:  9.582 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319146
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 91730 
    [ 2.500,  3.750) = 188786 
    [ 3.750,  5.000) = 31383 
    [ 5.000,  6.250) = 5823 
    [ 6.250,  7.500) = 582 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 190 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.894 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     15.034 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.987 ± 3.247  ops/ms
ClientPb.existUser                       thrpt       3  13.402 ± 2.923  ops/ms
ClientPb.getUser                         thrpt       3  12.832 ± 0.780  ops/ms
ClientPb.listUser                        thrpt       3  10.766 ± 0.582  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.330   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.015   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.400   ms/op
ClientPb.listUser                         avgt       3   2.934 ± 0.257   ms/op
ClientPb.createUser                     sample  378709   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.379           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.842           ms/op
ClientPb.existUser                      sample  389565   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.376           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.336           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.501           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  385143   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.872           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.721           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.384           ms/op
ClientPb.listUser                       sample  319146   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.582           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.106           ms/op
