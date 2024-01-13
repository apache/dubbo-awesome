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
# Warmup Iteration   1: 4.852 ops/ms
# Warmup Iteration   2: 12.554 ops/ms
# Warmup Iteration   3: 12.504 ops/ms
Iteration   1: 12.852 ops/ms
Iteration   2: 12.740 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.811 ±(99.9%) 1.123 ops/ms [Average]
  (min, avg, max) = (12.740, 12.811, 12.852), stdev = 0.062
  CI (99.9%): [11.688, 13.934] (assumes normal distribution)


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
# Warmup Iteration   1: 7.951 ops/ms
# Warmup Iteration   2: 13.301 ops/ms
# Warmup Iteration   3: 13.309 ops/ms
Iteration   1: 13.234 ops/ms
Iteration   2: 13.312 ops/ms
Iteration   3: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.248 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (13.197, 13.248, 13.312), stdev = 0.059
  CI (99.9%): [12.173, 14.323] (assumes normal distribution)


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
# Warmup Iteration   1: 7.508 ops/ms
# Warmup Iteration   2: 12.719 ops/ms
# Warmup Iteration   3: 13.012 ops/ms
Iteration   1: 13.187 ops/ms
Iteration   2: 13.116 ops/ms
Iteration   3: 13.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.117 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (13.046, 13.117, 13.187), stdev = 0.071
  CI (99.9%): [11.828, 14.406] (assumes normal distribution)


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
# Warmup Iteration   1: 7.000 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.867 ops/ms
Iteration   1: 10.816 ops/ms
Iteration   2: 10.884 ops/ms
Iteration   3: 10.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.834 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (10.801, 10.834, 10.884), stdev = 0.044
  CI (99.9%): [10.025, 11.643] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.480, 2.502, 2.524), stdev = 0.022
  CI (99.9%): [2.096, 2.908] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.420, 2.430, 2.440), stdev = 0.010
  CI (99.9%): [2.254, 2.605] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.448, 2.468, 2.478), stdev = 0.018
  CI (99.9%): [2.146, 2.790] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
Iteration   2: 2.940 ±(99.9%) 0.004 ms/op
Iteration   3: 2.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.944 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.936, 2.944, 2.954), stdev = 0.010
  CI (99.9%): [2.770, 3.117] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 13.761 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  7.243 ms/op
                 createUser·p0.9999: 13.567 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 10.569 ms/op
                 createUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389593
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 191340 
    [ 2.500,  3.750) = 194588 
    [ 3.750,  5.000) = 2692 
    [ 5.000,  6.250) = 475 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      9.083 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.278 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.322 ms/op
                 existUser·p0.999:  5.320 ms/op
                 existUser·p0.9999: 13.302 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.030 ms/op
                 existUser·p0.9999: 13.008 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  8.468 ms/op
                 existUser·p0.9999: 11.992 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391696
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 197728 
    [ 2.500,  3.750) = 191553 
    [ 3.750,  5.000) = 1786 
    [ 5.000,  6.250) = 173 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.465 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.829 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.551 ms/op
                 getUser·p0.999:  5.803 ms/op
                 getUser·p0.9999: 14.169 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.329 ms/op
                 getUser·p0.9999: 13.323 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 12.587 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387170
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 194885 
    [ 2.500,  3.750) = 185174 
    [ 3.750,  5.000) = 5307 
    [ 5.000,  6.250) = 1266 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.906 ms/op
     p(99.9900) =     13.587 ms/op
     p(99.9990) =     14.649 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 10.961 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  8.920 ms/op
                 listUser·p0.9999: 10.300 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.955 ms/op
                 listUser·p0.9999: 11.477 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322739
  mean =      2.972 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 99639 
    [ 2.500,  3.750) = 186361 
    [ 3.750,  5.000) = 29888 
    [ 5.000,  6.250) = 5553 
    [ 6.250,  7.500) = 505 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     11.296 ms/op
     p(99.9990) =     12.122 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.811 ± 1.123  ops/ms
ClientPb.existUser                       thrpt       3  13.248 ± 1.075  ops/ms
ClientPb.getUser                         thrpt       3  13.117 ± 1.289  ops/ms
ClientPb.listUser                        thrpt       3  10.834 ± 0.809  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.406   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.175   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   2.944 ± 0.174   ms/op
ClientPb.createUser                     sample  389593   2.461 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.687           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.083           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.384           ms/op
ClientPb.existUser                      sample  391696   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.894           ms/op
ClientPb.getUser                        sample  387170   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.848           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.587           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  322739   2.972 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.756           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
