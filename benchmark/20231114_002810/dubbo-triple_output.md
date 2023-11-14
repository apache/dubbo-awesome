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
# Warmup Iteration   1: 4.521 ops/ms
# Warmup Iteration   2: 11.746 ops/ms
# Warmup Iteration   3: 12.222 ops/ms
Iteration   1: 12.423 ops/ms
Iteration   2: 12.387 ops/ms
Iteration   3: 12.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.415 ±(99.9%) 0.441 ops/ms [Average]
  (min, avg, max) = (12.387, 12.415, 12.434), stdev = 0.024
  CI (99.9%): [11.974, 12.856] (assumes normal distribution)


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
# Warmup Iteration   1: 8.137 ops/ms
# Warmup Iteration   2: 12.903 ops/ms
# Warmup Iteration   3: 13.061 ops/ms
Iteration   1: 12.941 ops/ms
Iteration   2: 13.107 ops/ms
Iteration   3: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.010 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (12.941, 13.010, 13.107), stdev = 0.086
  CI (99.9%): [11.435, 14.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ops/ms
# Warmup Iteration   2: 12.386 ops/ms
# Warmup Iteration   3: 12.750 ops/ms
Iteration   1: 12.768 ops/ms
Iteration   2: 12.753 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.780 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (12.753, 12.780, 12.820), stdev = 0.035
  CI (99.9%): [12.144, 13.417] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.021 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.569 ±(99.9%) 1.372 ops/ms [Average]
  (min, avg, max) = (10.482, 10.569, 10.620), stdev = 0.075
  CI (99.9%): [9.197, 11.940] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.004 ms/op
Iteration   1: 2.625 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.583 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (2.562, 2.583, 2.625), stdev = 0.036
  CI (99.9%): [1.923, 3.243] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.003 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.456, 2.465, 2.476), stdev = 0.010
  CI (99.9%): [2.276, 2.653] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.511, 2.513, 2.519), stdev = 0.005
  CI (99.9%): [2.430, 2.597] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.004 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 3.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.009, 3.021, 3.028), stdev = 0.010
  CI (99.9%): [2.836, 3.205] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.692 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  10.778 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  9.878 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.711 ms/op
                 createUser·p0.9999: 11.502 ms/op
                 createUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375947
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 179801 
    [ 2.500,  3.750) = 192230 
    [ 3.750,  5.000) = 2900 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      9.013 ms/op
     p(99.9900) =     13.612 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  4.895 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.676 ms/op
                 existUser·p0.999:  7.984 ms/op
                 existUser·p0.9999: 14.009 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  8.480 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388317
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 190017 
    [ 2.500,  3.750) = 194728 
    [ 3.750,  5.000) = 2561 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      6.637 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.864 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  12.235 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 12.599 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.346 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374904
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181949 
    [ 2.500,  5.000) = 191844 
    [ 5.000,  7.500) = 719 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.423 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     19.514 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.258 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318720
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 93233 
    [ 2.500,  3.750) = 187005 
    [ 3.750,  5.000) = 31130 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 781 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.234 ms/op
     p(99.9990) =     15.182 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.415 ± 0.441  ops/ms
ClientPb.existUser                       thrpt       3  13.010 ± 1.575  ops/ms
ClientPb.getUser                         thrpt       3  12.780 ± 0.637  ops/ms
ClientPb.listUser                        thrpt       3  10.569 ± 1.372  ops/ms
ClientPb.createUser                       avgt       3   2.583 ± 0.660   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.188   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.084   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.184   ms/op
ClientPb.createUser                     sample  375947   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.013           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.612           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.547           ms/op
ClientPb.existUser                      sample  388317   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.671           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.637           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.777           ms/op
ClientPb.getUser                        sample  374904   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.423           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.185           ms/op
ClientPb.listUser                       sample  318720   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.234           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.024           ms/op
