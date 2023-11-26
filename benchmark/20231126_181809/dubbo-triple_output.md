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
# Warmup Iteration   1: 4.947 ops/ms
# Warmup Iteration   2: 12.172 ops/ms
# Warmup Iteration   3: 12.546 ops/ms
Iteration   1: 12.666 ops/ms
Iteration   2: 12.740 ops/ms
Iteration   3: 12.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.746 ±(99.9%) 1.514 ops/ms [Average]
  (min, avg, max) = (12.666, 12.746, 12.831), stdev = 0.083
  CI (99.9%): [11.231, 14.260] (assumes normal distribution)


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
# Warmup Iteration   1: 8.068 ops/ms
# Warmup Iteration   2: 13.292 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.132 ops/ms
Iteration   2: 13.155 ops/ms
Iteration   3: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.085 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (12.967, 13.085, 13.155), stdev = 0.102
  CI (99.9%): [11.217, 14.952] (assumes normal distribution)


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
# Warmup Iteration   1: 7.938 ops/ms
# Warmup Iteration   2: 12.644 ops/ms
# Warmup Iteration   3: 12.796 ops/ms
Iteration   1: 12.879 ops/ms
Iteration   2: 12.773 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.850 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (12.773, 12.850, 12.898), stdev = 0.067
  CI (99.9%): [11.625, 14.075] (assumes normal distribution)


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
# Warmup Iteration   1: 6.703 ops/ms
# Warmup Iteration   2: 10.456 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.545 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (10.530, 10.545, 10.569), stdev = 0.021
  CI (99.9%): [10.169, 10.922] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.505, 2.528, 2.564), stdev = 0.032
  CI (99.9%): [1.952, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.443, 2.448, 2.453), stdev = 0.005
  CI (99.9%): [2.357, 2.539] (assumes normal distribution)


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.486, 2.494, 2.503), stdev = 0.009
  CI (99.9%): [2.335, 2.652] (assumes normal distribution)


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 2.998 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.004 ms/op
Iteration   3: 2.947 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.981 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (2.947, 2.981, 2.998), stdev = 0.029
  CI (99.9%): [2.452, 3.510] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  8.919 ms/op
                 createUser·p0.9999: 13.847 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.196 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.142 ms/op
                 createUser·p0.9999: 10.048 ms/op
                 createUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383654
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 186213 
    [ 2.500,  3.750) = 193046 
    [ 3.750,  5.000) = 3337 
    [ 5.000,  6.250) = 602 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.832 ms/op
     p(99.9000) =      8.137 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.270 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  11.194 ms/op
                 existUser·p0.9999: 13.754 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.140 ms/op
                 existUser·p0.9999: 15.174 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  8.407 ms/op
                 existUser·p0.9999: 11.875 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383420
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 187846 
    [ 2.500,  3.750) = 191737 
    [ 3.750,  5.000) = 3002 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.771 ms/op
     p(99.9900) =     14.134 ms/op
     p(99.9990) =     15.789 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  9.012 ms/op
                 getUser·p0.9999: 13.535 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  9.888 ms/op
                 getUser·p0.9999: 12.685 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  5.767 ms/op
                 getUser·p0.9999: 15.990 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386366
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 193416 
    [ 2.500,  3.750) = 187778 
    [ 3.750,  5.000) = 4067 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      6.747 ms/op
     p(99.9900) =     13.836 ms/op
     p(99.9990) =     16.194 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.351 ms/op
                 listUser·p0.9999: 10.187 ms/op
                 listUser·p1.00:   10.699 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.901 ms/op
                 listUser·p0.9999: 11.688 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.327 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319131
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 91367 
    [ 2.500,  3.750) = 189121 
    [ 3.750,  5.000) = 31314 
    [ 5.000,  6.250) = 5833 
    [ 6.250,  7.500) = 748 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 220 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.601 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.013 ms/op
     p(99.9990) =     12.430 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.746 ± 1.514  ops/ms
ClientPb.existUser                       thrpt       3  13.085 ± 1.868  ops/ms
ClientPb.getUser                         thrpt       3  12.850 ± 1.225  ops/ms
ClientPb.listUser                        thrpt       3  10.545 ± 0.377  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.576   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.091   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   2.981 ± 0.529   ms/op
ClientPb.createUser                     sample  383654   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.832           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.137           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  383420   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.771           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.134           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.892           ms/op
ClientPb.getUser                        sample  386366   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.747           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.836           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.974           ms/op
ClientPb.listUser                       sample  319131   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.601           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.013           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
