# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ops/ms
# Warmup Iteration   2: 12.187 ops/ms
# Warmup Iteration   3: 12.441 ops/ms
Iteration   1: 12.647 ops/ms
Iteration   2: 12.615 ops/ms
Iteration   3: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.628 ±(99.9%) 0.309 ops/ms [Average]
  (min, avg, max) = (12.615, 12.628, 12.647), stdev = 0.017
  CI (99.9%): [12.319, 12.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.273 ops/ms
# Warmup Iteration   2: 13.063 ops/ms
# Warmup Iteration   3: 12.966 ops/ms
Iteration   1: 12.986 ops/ms
Iteration   2: 12.965 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.950 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (12.898, 12.950, 12.986), stdev = 0.046
  CI (99.9%): [12.106, 13.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ops/ms
# Warmup Iteration   2: 12.562 ops/ms
# Warmup Iteration   3: 12.606 ops/ms
Iteration   1: 12.944 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.793 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (12.690, 12.793, 12.944), stdev = 0.133
  CI (99.9%): [10.360, 15.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 10.759 ops/ms
Iteration   1: 10.806 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.754 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (10.707, 10.754, 10.806), stdev = 0.050
  CI (99.9%): [9.846, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.003 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.519, 2.522, 2.526), stdev = 0.004
  CI (99.9%): [2.453, 2.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.003 ms/op
Iteration   1: 2.422 ±(99.9%) 0.003 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.416, 2.423, 2.431), stdev = 0.007
  CI (99.9%): [2.290, 2.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.452, 2.458, 2.462), stdev = 0.005
  CI (99.9%): [2.361, 2.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.970 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.967, 2.970, 2.975), stdev = 0.004
  CI (99.9%): [2.894, 3.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.285 ms/op
                 createUser·p0.9999: 13.960 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  6.900 ms/op
                 createUser·p0.9999: 11.449 ms/op
                 createUser·p1.00:   12.304 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  8.661 ms/op
                 createUser·p0.9999: 10.962 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385813
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 187855 
    [ 2.500,  3.750) = 194309 
    [ 3.750,  5.000) = 2887 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.286 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.581 ms/op
                 existUser·p0.999:  5.890 ms/op
                 existUser·p0.9999: 15.629 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.589 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.409 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395077
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 197160 
    [ 2.500,  3.750) = 195014 
    [ 3.750,  5.000) = 2158 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      5.882 ms/op
     p(99.9900) =     13.607 ms/op
     p(99.9990) =     16.191 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.535 ms/op
                 getUser·p0.999:  5.929 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  8.268 ms/op
                 getUser·p0.9999: 13.978 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  6.296 ms/op
                 getUser·p0.9999: 10.948 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388538
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 194555 
    [ 2.500,  3.750) = 190183 
    [ 3.750,  5.000) = 2900 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.992 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.567 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.588 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.232 ms/op
                 listUser·p0.9999: 11.214 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.988 ms/op
                 listUser·p0.9999: 12.098 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.414 ms/op
                 listUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317911
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 92601 
    [ 2.500,  3.750) = 185603 
    [ 3.750,  5.000) = 31972 
    [ 5.000,  6.250) = 6140 
    [ 6.250,  7.500) = 741 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.741 ms/op
     p(99.9990) =     12.479 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.628 ± 0.309  ops/ms
ClientPb.existUser                       thrpt       3  12.950 ± 0.844  ops/ms
ClientPb.getUser                         thrpt       3  12.793 ± 2.433  ops/ms
ClientPb.listUser                        thrpt       3  10.754 ± 0.907  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.069   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.133   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.098   ms/op
ClientPb.listUser                         avgt       3   2.970 ± 0.077   ms/op
ClientPb.createUser                     sample  385813   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.417           ms/op
ClientPb.existUser                      sample  395077   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.882           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.607           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.335           ms/op
ClientPb.getUser                        sample  388538   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.793           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.992           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  317911   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
