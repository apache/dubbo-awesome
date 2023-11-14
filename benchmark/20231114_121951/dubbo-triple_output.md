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
# Warmup Iteration   1: 4.839 ops/ms
# Warmup Iteration   2: 11.945 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.763 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.741 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (12.678, 12.741, 12.781), stdev = 0.055
  CI (99.9%): [11.736, 13.746] (assumes normal distribution)


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
# Warmup Iteration   1: 8.628 ops/ms
# Warmup Iteration   2: 13.197 ops/ms
# Warmup Iteration   3: 12.912 ops/ms
Iteration   1: 13.398 ops/ms
Iteration   2: 13.504 ops/ms
Iteration   3: 13.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.386 ±(99.9%) 2.275 ops/ms [Average]
  (min, avg, max) = (13.255, 13.386, 13.504), stdev = 0.125
  CI (99.9%): [11.111, 15.661] (assumes normal distribution)


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
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.927 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 12.663 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.813 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (12.663, 12.813, 12.973), stdev = 0.155
  CI (99.9%): [9.985, 15.641] (assumes normal distribution)


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
# Warmup Iteration   1: 6.792 ops/ms
# Warmup Iteration   2: 10.730 ops/ms
# Warmup Iteration   3: 10.834 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.789 ±(99.9%) 0.417 ops/ms [Average]
  (min, avg, max) = (10.765, 10.789, 10.811), stdev = 0.023
  CI (99.9%): [10.371, 11.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.477, 2.502, 2.526), stdev = 0.025
  CI (99.9%): [2.055, 2.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.447, 2.459, 2.475), stdev = 0.014
  CI (99.9%): [2.199, 2.719] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.501, 2.509, 2.523), stdev = 0.013
  CI (99.9%): [2.279, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.004 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.019 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.018, 3.024, 3.035), stdev = 0.009
  CI (99.9%): [2.853, 3.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 15.197 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   4.120 ms/op
                 createUser·p0.999:  9.640 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  8.704 ms/op
                 createUser·p0.9999: 10.340 ms/op
                 createUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384524
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 186245 
    [ 2.500,  3.750) = 192848 
    [ 3.750,  5.000) = 4187 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.084 ms/op
     p(99.9900) =     14.767 ms/op
     p(99.9990) =     15.681 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.162 ms/op
                 existUser·p0.9999: 13.895 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 11.466 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.634 ms/op
                 existUser·p0.999:  7.099 ms/op
                 existUser·p0.9999: 11.856 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391983
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 193758 
    [ 2.500,  3.750) = 194309 
    [ 3.750,  5.000) = 3015 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.513 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.358 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 14.832 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  9.947 ms/op
                 getUser·p0.9999: 12.309 ms/op
                 getUser·p1.00:   12.665 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.109 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386514
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 192465 
    [ 2.500,  3.750) = 187494 
    [ 3.750,  5.000) = 5160 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      8.261 ms/op
     p(99.9900) =     13.686 ms/op
     p(99.9990) =     15.297 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.009 ms/op
Iteration   1: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 12.141 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 14.024 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322472
  mean =      2.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 100805 
    [ 2.500,  3.750) = 184308 
    [ 3.750,  5.000) = 30061 
    [ 5.000,  6.250) = 5820 
    [ 6.250,  7.500) = 665 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     12.546 ms/op
     p(99.9990) =     15.932 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.741 ± 1.005  ops/ms
ClientPb.existUser                       thrpt       3  13.386 ± 2.275  ops/ms
ClientPb.getUser                         thrpt       3  12.813 ± 2.828  ops/ms
ClientPb.listUser                        thrpt       3  10.789 ± 0.417  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.448   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.260   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.171   ms/op
ClientPb.createUser                     sample  384524   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.764           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.084           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.767           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  391983   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.644           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.513           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  386514   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.368           ms/op
ClientPb.listUser                       sample  322472   2.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.873           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.546           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.105           ms/op
