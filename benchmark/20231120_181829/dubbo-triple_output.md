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
# Warmup Iteration   1: 4.607 ops/ms
# Warmup Iteration   2: 12.114 ops/ms
# Warmup Iteration   3: 12.169 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 12.517 ops/ms
Iteration   3: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.621 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (12.517, 12.621, 12.732), stdev = 0.107
  CI (99.9%): [10.665, 14.577] (assumes normal distribution)


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
# Warmup Iteration   1: 8.094 ops/ms
# Warmup Iteration   2: 13.130 ops/ms
# Warmup Iteration   3: 13.235 ops/ms
Iteration   1: 13.100 ops/ms
Iteration   2: 13.328 ops/ms
Iteration   3: 13.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.167 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (13.073, 13.167, 13.328), stdev = 0.140
  CI (99.9%): [10.609, 15.726] (assumes normal distribution)


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
# Warmup Iteration   1: 7.971 ops/ms
# Warmup Iteration   2: 12.651 ops/ms
# Warmup Iteration   3: 12.777 ops/ms
Iteration   1: 12.748 ops/ms
Iteration   2: 12.934 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.828 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (12.748, 12.828, 12.934), stdev = 0.096
  CI (99.9%): [11.086, 14.571] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.650 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.607, 10.650, 10.711), stdev = 0.054
  CI (99.9%): [9.664, 11.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.510 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.494, 2.510, 2.522), stdev = 0.014
  CI (99.9%): [2.247, 2.773] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.411, 2.424, 2.434), stdev = 0.012
  CI (99.9%): [2.210, 2.639] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
Iteration   3: 2.468 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.468, 2.488, 2.500), stdev = 0.017
  CI (99.9%): [2.172, 2.804] (assumes normal distribution)


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
# Warmup Iteration   1: 4.925 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
Iteration   3: 3.022 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (3.003, 3.015, 3.022), stdev = 0.010
  CI (99.9%): [2.829, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  12.475 ms/op
                 createUser·p0.9999: 15.669 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 16.359 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.150 ms/op
                 createUser·p0.9999: 11.226 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383676
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 184439 
    [ 2.500,  3.750) = 194928 
    [ 3.750,  5.000) = 3460 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      9.868 ms/op
     p(99.9900) =     15.460 ms/op
     p(99.9990) =     16.667 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.362 ms/op
                 existUser·p0.999:  6.025 ms/op
                 existUser·p0.9999: 13.448 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  6.511 ms/op
                 existUser·p0.9999: 12.270 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  8.776 ms/op
                 existUser·p0.9999: 10.813 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393061
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 194593 
    [ 2.500,  3.750) = 194780 
    [ 3.750,  5.000) = 2681 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.715 ms/op
     p(99.9900) =     12.814 ms/op
     p(99.9990) =     13.897 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.346 ms/op
                 getUser·p0.9999: 17.310 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  7.042 ms/op
                 getUser·p0.9999: 15.944 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  7.994 ms/op
                 getUser·p0.9999: 11.918 ms/op
                 getUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383344
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 188235 
    [ 2.500,  3.750) = 188722 
    [ 3.750,  5.000) = 4293 
    [ 5.000,  6.250) = 1493 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.930 ms/op
     p(99.9900) =     16.078 ms/op
     p(99.9990) =     17.733 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.904 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.139 ms/op
                 listUser·p0.9999: 11.960 ms/op
                 listUser·p1.00:   13.959 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.083 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319242
  mean =      3.004 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 95131 
    [ 2.500,  3.750) = 185232 
    [ 3.750,  5.000) = 31539 
    [ 5.000,  6.250) = 5805 
    [ 6.250,  7.500) = 788 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.437 ms/op
     p(99.9990) =     13.781 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.621 ± 1.956  ops/ms
ClientPb.existUser                       thrpt       3  13.167 ± 2.559  ops/ms
ClientPb.getUser                         thrpt       3  12.828 ± 1.742  ops/ms
ClientPb.listUser                        thrpt       3  10.650 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   2.510 ± 0.263   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.215   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.316   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.185   ms/op
ClientPb.createUser                     sample  383676   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.836           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.868           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.564           ms/op
ClientPb.existUser                      sample  393061   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.478           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.814           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.877           ms/op
ClientPb.getUser                        sample  383344   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.930           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.078           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.957           ms/op
ClientPb.listUser                       sample  319242   3.004 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.437           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.959           ms/op
