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
# Warmup Iteration   1: 5.120 ops/ms
# Warmup Iteration   2: 12.173 ops/ms
# Warmup Iteration   3: 12.319 ops/ms
Iteration   1: 12.555 ops/ms
Iteration   2: 12.685 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.673 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (12.555, 12.673, 12.778), stdev = 0.112
  CI (99.9%): [10.628, 14.717] (assumes normal distribution)


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
# Warmup Iteration   1: 8.146 ops/ms
# Warmup Iteration   2: 13.159 ops/ms
# Warmup Iteration   3: 13.261 ops/ms
Iteration   1: 13.258 ops/ms
Iteration   2: 13.361 ops/ms
Iteration   3: 13.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.267 ±(99.9%) 1.639 ops/ms [Average]
  (min, avg, max) = (13.182, 13.267, 13.361), stdev = 0.090
  CI (99.9%): [11.628, 14.905] (assumes normal distribution)


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
# Warmup Iteration   1: 7.617 ops/ms
# Warmup Iteration   2: 12.668 ops/ms
# Warmup Iteration   3: 12.810 ops/ms
Iteration   1: 12.867 ops/ms
Iteration   2: 12.814 ops/ms
Iteration   3: 13.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.900 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (12.814, 12.900, 13.020), stdev = 0.107
  CI (99.9%): [10.946, 14.855] (assumes normal distribution)


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
# Warmup Iteration   1: 6.646 ops/ms
# Warmup Iteration   2: 10.664 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.778 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.736 ±(99.9%) 1.913 ops/ms [Average]
  (min, avg, max) = (10.617, 10.736, 10.814), stdev = 0.105
  CI (99.9%): [8.823, 12.649] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.475, 2.493, 2.518), stdev = 0.023
  CI (99.9%): [2.080, 2.905] (assumes normal distribution)


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.003 ms/op
Iteration   3: 2.428 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.412, 2.426, 2.438), stdev = 0.013
  CI (99.9%): [2.192, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.468, 2.492, 2.518), stdev = 0.025
  CI (99.9%): [2.035, 2.949] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.957 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.948, 2.957, 2.966), stdev = 0.009
  CI (99.9%): [2.792, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 14.389 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.578 ms/op
                 createUser·p0.9999: 12.169 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.265 ms/op
                 createUser·p0.9999: 10.306 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382066
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 183981 
    [ 2.500,  3.750) = 193326 
    [ 3.750,  5.000) = 3643 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.897 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     13.530 ms/op
     p(99.9990) =     14.992 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.608 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 12.224 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.379 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.634 ms/op
                 existUser·p0.999:  8.385 ms/op
                 existUser·p0.9999: 11.470 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388573
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 188966 
    [ 2.500,  3.750) = 196367 
    [ 3.750,  5.000) = 2371 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.655 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  7.329 ms/op
                 getUser·p0.9999: 15.789 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  6.747 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  7.883 ms/op
                 getUser·p0.9999: 10.311 ms/op
                 getUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386018
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 192330 
    [ 2.500,  3.750) = 189771 
    [ 3.750,  5.000) = 3158 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     13.710 ms/op
     p(99.9990) =     16.735 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.674 ms/op
                 listUser·p0.9999: 11.846 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 12.376 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.654 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.495 ms/op
                 listUser·p0.9999: 12.561 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319633
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 93800 
    [ 2.500,  3.750) = 187161 
    [ 3.750,  5.000) = 31148 
    [ 5.000,  6.250) = 6047 
    [ 6.250,  7.500) = 672 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.673 ± 2.045  ops/ms
ClientPb.existUser                       thrpt       3  13.267 ± 1.639  ops/ms
ClientPb.getUser                         thrpt       3  12.900 ± 1.955  ops/ms
ClientPb.listUser                        thrpt       3  10.736 ± 1.913  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.412   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.234   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.457   ms/op
ClientPb.listUser                         avgt       3   2.957 ± 0.165   ms/op
ClientPb.createUser                     sample  382066   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.770           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.897           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.530           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.956           ms/op
ClientPb.existUser                      sample  388573   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.379           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.655           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  386018   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.836           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.710           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.843           ms/op
ClientPb.listUser                       sample  319633   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.654           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
