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
# Warmup Iteration   1: 4.905 ops/ms
# Warmup Iteration   2: 12.230 ops/ms
# Warmup Iteration   3: 12.617 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.841 ops/ms
Iteration   3: 12.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.839 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (12.809, 12.839, 12.866), stdev = 0.028
  CI (99.9%): [12.322, 13.355] (assumes normal distribution)


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
# Warmup Iteration   1: 8.172 ops/ms
# Warmup Iteration   2: 13.295 ops/ms
# Warmup Iteration   3: 13.358 ops/ms
Iteration   1: 13.275 ops/ms
Iteration   2: 13.425 ops/ms
Iteration   3: 13.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.333 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (13.275, 13.333, 13.425), stdev = 0.081
  CI (99.9%): [11.861, 14.805] (assumes normal distribution)


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
# Warmup Iteration   1: 7.427 ops/ms
# Warmup Iteration   2: 12.445 ops/ms
# Warmup Iteration   3: 12.878 ops/ms
Iteration   1: 12.877 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.829 ±(99.9%) 1.840 ops/ms [Average]
  (min, avg, max) = (12.713, 12.829, 12.896), stdev = 0.101
  CI (99.9%): [10.988, 14.669] (assumes normal distribution)


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
# Warmup Iteration   1: 6.371 ops/ms
# Warmup Iteration   2: 10.492 ops/ms
# Warmup Iteration   3: 10.583 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.653 ±(99.9%) 0.336 ops/ms [Average]
  (min, avg, max) = (10.639, 10.653, 10.674), stdev = 0.018
  CI (99.9%): [10.317, 10.989] (assumes normal distribution)


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.536, 2.559, 2.585), stdev = 0.025
  CI (99.9%): [2.105, 3.012] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.379 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.394 ±(99.9%) 0.004 ms/op
Iteration   1: 2.369 ±(99.9%) 0.003 ms/op
Iteration   2: 2.384 ±(99.9%) 0.005 ms/op
Iteration   3: 2.385 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.379 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.369, 2.379, 2.385), stdev = 0.009
  CI (99.9%): [2.217, 2.542] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.460 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.434, 2.460, 2.479), stdev = 0.023
  CI (99.9%): [2.037, 2.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
Iteration   3: 2.940 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.948 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.940, 2.948, 2.953), stdev = 0.007
  CI (99.9%): [2.820, 3.076] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  9.639 ms/op
                 createUser·p0.9999: 14.223 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 12.850 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.693 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 13.799 ms/op
                 createUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383575
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 185768 
    [ 2.500,  3.750) = 192919 
    [ 3.750,  5.000) = 3840 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.969 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     15.010 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.774 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  7.205 ms/op
                 existUser·p0.9999: 12.729 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393332
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 196347 
    [ 2.500,  3.750) = 193806 
    [ 3.750,  5.000) = 2501 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      5.745 ms/op
     p(99.9900) =     13.178 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  9.665 ms/op
                 getUser·p0.9999: 13.634 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  7.956 ms/op
                 getUser·p0.9999: 11.928 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  7.310 ms/op
                 getUser·p0.9999: 11.158 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386566
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 191482 
    [ 2.500,  3.750) = 190613 
    [ 3.750,  5.000) = 3395 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.293 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.538 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 13.160 ms/op
                 listUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322348
  mean =      2.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 98060 
    [ 2.500,  3.750) = 187795 
    [ 3.750,  5.000) = 30155 
    [ 5.000,  6.250) = 5085 
    [ 6.250,  7.500) = 463 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.314 ms/op
     p(99.9990) =     13.497 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.839 ± 0.517  ops/ms
ClientPb.existUser                       thrpt       3  13.333 ± 1.472  ops/ms
ClientPb.getUser                         thrpt       3  12.829 ± 1.840  ops/ms
ClientPb.listUser                        thrpt       3  10.653 ± 0.336  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   2.379 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   2.460 ± 0.423   ms/op
ClientPb.listUser                         avgt       3   2.948 ± 0.128   ms/op
ClientPb.createUser                     sample  383575   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.969           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  393332   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.745           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.178           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.500           ms/op
ClientPb.getUser                        sample  386566   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.648           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.293           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.451           ms/op
ClientPb.listUser                       sample  322348   2.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.314           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
