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
# Warmup Iteration   1: 5.141 ops/ms
# Warmup Iteration   2: 12.094 ops/ms
# Warmup Iteration   3: 12.007 ops/ms
Iteration   1: 12.324 ops/ms
Iteration   2: 12.440 ops/ms
Iteration   3: 12.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.399 ±(99.9%) 1.181 ops/ms [Average]
  (min, avg, max) = (12.324, 12.399, 12.440), stdev = 0.065
  CI (99.9%): [11.218, 13.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 13.093 ops/ms
# Warmup Iteration   3: 12.914 ops/ms
Iteration   1: 12.880 ops/ms
Iteration   2: 13.084 ops/ms
Iteration   3: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.971 ±(99.9%) 1.894 ops/ms [Average]
  (min, avg, max) = (12.880, 12.971, 13.084), stdev = 0.104
  CI (99.9%): [11.077, 14.865] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 12.173 ops/ms
# Warmup Iteration   3: 12.441 ops/ms
Iteration   1: 12.397 ops/ms
Iteration   2: 12.670 ops/ms
Iteration   3: 12.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.572 ±(99.9%) 2.770 ops/ms [Average]
  (min, avg, max) = (12.397, 12.572, 12.670), stdev = 0.152
  CI (99.9%): [9.802, 15.342] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.708 ops/ms
# Warmup Iteration   2: 10.315 ops/ms
# Warmup Iteration   3: 10.511 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.563 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (10.461, 10.535, 10.580), stdev = 0.064
  CI (99.9%): [9.362, 11.708] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.270 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.574 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.568, 2.574, 2.582), stdev = 0.008
  CI (99.9%): [2.434, 2.713] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.487, 2.496, 2.503), stdev = 0.008
  CI (99.9%): [2.344, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
Iteration   1: 2.539 ±(99.9%) 0.003 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.543 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.529, 2.543, 2.561), stdev = 0.017
  CI (99.9%): [2.239, 2.847] (assumes normal distribution)


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
Iteration   3: 3.084 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.067 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.045, 3.067, 3.084), stdev = 0.020
  CI (99.9%): [2.699, 3.435] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.707 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.988 ms/op
                 createUser·p0.999:  11.653 ms/op
                 createUser·p0.9999: 13.869 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.944 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.192 ms/op
                 createUser·p0.9999: 10.479 ms/op
                 createUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374296
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 178348 
    [ 2.500,  3.750) = 189798 
    [ 3.750,  5.000) = 4719 
    [ 5.000,  6.250) = 903 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.248 ms/op
     p(99.9900) =     13.688 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.924 ms/op
                 existUser·p0.9999: 14.092 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 13.062 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  9.264 ms/op
                 existUser·p0.9999: 12.279 ms/op
                 existUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384951
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 187417 
    [ 2.500,  3.750) = 193826 
    [ 3.750,  5.000) = 2743 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     13.755 ms/op
     p(99.9990) =     14.601 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  10.207 ms/op
                 getUser·p0.9999: 15.000 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 2.580 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.334 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  9.323 ms/op
                 getUser·p0.9999: 13.161 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373816
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 180562 
    [ 2.500,  3.750) = 186022 
    [ 3.750,  5.000) = 5178 
    [ 5.000,  6.250) = 1417 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     14.510 ms/op
     p(99.9990) =     15.536 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 4.939 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
Iteration   1: 3.095 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.334 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 12.780 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.888 ms/op
                 listUser·p0.9999: 11.143 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312166
  mean =      3.072 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 82129 
    [ 2.500,  3.750) = 185349 
    [ 3.750,  5.000) = 36003 
    [ 5.000,  6.250) = 6875 
    [ 6.250,  7.500) = 893 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 219 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     16.999 ms/op
     p(99.9990) =     18.440 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.399 ± 1.181  ops/ms
ClientPb.existUser                       thrpt       3  12.971 ± 1.894  ops/ms
ClientPb.getUser                         thrpt       3  12.572 ± 2.770  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 1.173  ops/ms
ClientPb.createUser                       avgt       3   2.574 ± 0.140   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.152   ms/op
ClientPb.getUser                          avgt       3   2.543 ± 0.304   ms/op
ClientPb.listUser                         avgt       3   3.067 ± 0.368   ms/op
ClientPb.createUser                     sample  374296   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.688           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.286           ms/op
ClientPb.existUser                      sample  384951   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.807           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  373816   2.566 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.601           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  312166   3.072 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.912           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.999           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.711           ms/op
