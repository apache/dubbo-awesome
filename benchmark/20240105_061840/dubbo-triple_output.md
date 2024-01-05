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
# Warmup Iteration   1: 4.568 ops/ms
# Warmup Iteration   2: 11.437 ops/ms
# Warmup Iteration   3: 12.012 ops/ms
Iteration   1: 12.285 ops/ms
Iteration   2: 12.342 ops/ms
Iteration   3: 12.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.324 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (12.285, 12.324, 12.346), stdev = 0.034
  CI (99.9%): [11.698, 12.950] (assumes normal distribution)


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
# Warmup Iteration   1: 7.826 ops/ms
# Warmup Iteration   2: 12.702 ops/ms
# Warmup Iteration   3: 12.801 ops/ms
Iteration   1: 12.749 ops/ms
Iteration   2: 12.760 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.779 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (12.749, 12.779, 12.829), stdev = 0.043
  CI (99.9%): [11.989, 13.570] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ops/ms
# Warmup Iteration   2: 12.416 ops/ms
# Warmup Iteration   3: 12.703 ops/ms
Iteration   1: 12.796 ops/ms
Iteration   2: 12.620 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.694 ±(99.9%) 1.661 ops/ms [Average]
  (min, avg, max) = (12.620, 12.694, 12.796), stdev = 0.091
  CI (99.9%): [11.032, 14.355] (assumes normal distribution)


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
# Warmup Iteration   1: 6.198 ops/ms
# Warmup Iteration   2: 10.280 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.345 ops/ms
Iteration   2: 10.414 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.410 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (10.345, 10.410, 10.470), stdev = 0.062
  CI (99.9%): [9.270, 11.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.593 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.561, 2.572, 2.593), stdev = 0.018
  CI (99.9%): [2.238, 2.906] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.520 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.513, 2.520, 2.530), stdev = 0.009
  CI (99.9%): [2.355, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.003 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (2.461, 2.478, 2.506), stdev = 0.024
  CI (99.9%): [2.033, 2.923] (assumes normal distribution)


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.004 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.018, 3.035, 3.055), stdev = 0.019
  CI (99.9%): [2.691, 3.379] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.406 ms/op
                 createUser·p0.9999: 14.148 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.486 ms/op
                 createUser·p0.999:  9.928 ms/op
                 createUser·p0.9999: 12.124 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 10.804 ms/op
                 createUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380155
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183604 
    [ 2.500,  3.750) = 192708 
    [ 3.750,  5.000) = 2935 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.465 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.650 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  11.228 ms/op
                 existUser·p0.9999: 15.868 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.787 ms/op
                 existUser·p0.9999: 13.701 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  9.187 ms/op
                 existUser·p0.9999: 11.867 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382920
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 185002 
    [ 2.500,  3.750) = 194512 
    [ 3.750,  5.000) = 2608 
    [ 5.000,  6.250) = 288 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      7.054 ms/op
     p(99.9900) =     15.052 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 13.989 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 9.891 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376564
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 184020 
    [ 2.500,  3.750) = 188227 
    [ 3.750,  5.000) = 3299 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.261 ms/op
     p(99.9900) =     13.850 ms/op
     p(99.9990) =     14.479 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 11.412 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 15.089 ms/op
                 listUser·p1.00:   15.548 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.389 ms/op
                 listUser·p0.9999: 10.912 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316010
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 86556 
    [ 2.500,  3.750) = 189569 
    [ 3.750,  5.000) = 32554 
    [ 5.000,  6.250) = 5978 
    [ 6.250,  7.500) = 611 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     15.503 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.324 ± 0.626  ops/ms
ClientPb.existUser                       thrpt       3  12.779 ± 0.791  ops/ms
ClientPb.getUser                         thrpt       3  12.694 ± 1.661  ops/ms
ClientPb.listUser                        thrpt       3  10.410 ± 1.139  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.520 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.445   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.344   ms/op
ClientPb.createUser                     sample  380155   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.465           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  382920   2.505 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.054           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.052           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.368           ms/op
ClientPb.getUser                        sample  376564   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.995           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.850           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.975           ms/op
ClientPb.listUser                       sample  316010   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.916           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.107           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.056           ms/op
