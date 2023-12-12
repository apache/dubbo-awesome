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
# Warmup Iteration   1: 5.128 ops/ms
# Warmup Iteration   2: 12.200 ops/ms
# Warmup Iteration   3: 12.520 ops/ms
Iteration   1: 12.723 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.762 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (12.695, 12.762, 12.869), stdev = 0.093
  CI (99.9%): [11.063, 14.462] (assumes normal distribution)


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
# Warmup Iteration   1: 8.046 ops/ms
# Warmup Iteration   2: 13.170 ops/ms
# Warmup Iteration   3: 13.189 ops/ms
Iteration   1: 13.178 ops/ms
Iteration   2: 13.198 ops/ms
Iteration   3: 13.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.199 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (13.178, 13.199, 13.221), stdev = 0.022
  CI (99.9%): [12.806, 13.592] (assumes normal distribution)


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
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 12.662 ops/ms
# Warmup Iteration   3: 12.792 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 13.082 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.015 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (12.973, 13.015, 13.082), stdev = 0.059
  CI (99.9%): [11.946, 14.085] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 10.771 ops/ms
# Warmup Iteration   3: 10.762 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 11.028 ops/ms
Iteration   3: 11.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.984 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (10.904, 10.984, 11.028), stdev = 0.069
  CI (99.9%): [9.727, 12.240] (assumes normal distribution)


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.003 ms/op
Iteration   1: 2.487 ±(99.9%) 0.003 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (2.487, 2.512, 2.539), stdev = 0.026
  CI (99.9%): [2.042, 2.983] (assumes normal distribution)


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.457, 2.463, 2.469), stdev = 0.006
  CI (99.9%): [2.349, 2.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.449 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.440, 2.449, 2.464), stdev = 0.013
  CI (99.9%): [2.208, 2.690] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.990, 3.006, 3.021), stdev = 0.016
  CI (99.9%): [2.723, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  11.296 ms/op
                 createUser·p0.9999: 13.570 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  8.099 ms/op
                 createUser·p0.9999: 12.503 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  8.592 ms/op
                 createUser·p0.9999: 10.837 ms/op
                 createUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384632
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185671 
    [ 2.500,  3.750) = 195491 
    [ 3.750,  5.000) = 2731 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.697 ms/op
     p(99.9000) =      8.603 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.789 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  6.098 ms/op
                 existUser·p0.9999: 14.220 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.602 ms/op
                 existUser·p0.9999: 12.258 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389289
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 191774 
    [ 2.500,  3.750) = 194700 
    [ 3.750,  5.000) = 2110 
    [ 5.000,  6.250) = 194 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      8.198 ms/op
     p(99.9900) =     13.436 ms/op
     p(99.9990) =     14.310 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.921 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  7.837 ms/op
                 getUser·p0.9999: 12.637 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 17.618 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387495
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 194369 
    [ 2.500,  3.750) = 188681 
    [ 3.750,  5.000) = 3449 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.604 ms/op
                 listUser·p1.00:   13.369 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.106 ms/op
                 listUser·p0.9999: 11.911 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 12.424 ms/op
                 listUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318909
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 93023 
    [ 2.500,  3.750) = 186805 
    [ 3.750,  5.000) = 31972 
    [ 5.000,  6.250) = 5664 
    [ 6.250,  7.500) = 672 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 183 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     12.288 ms/op
     p(99.9990) =     13.574 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.762 ± 1.699  ops/ms
ClientPb.existUser                       thrpt       3  13.199 ± 0.393  ops/ms
ClientPb.getUser                         thrpt       3  13.015 ± 1.070  ops/ms
ClientPb.listUser                        thrpt       3  10.984 ± 1.256  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.471   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.114   ms/op
ClientPb.getUser                          avgt       3   2.449 ± 0.241   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.283   ms/op
ClientPb.createUser                     sample  384632   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.697           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.603           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  389289   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.676           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.198           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.436           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.385           ms/op
ClientPb.getUser                        sample  387495   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.728           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.123           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.776           ms/op
ClientPb.listUser                       sample  318909   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.834           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.959           ms/op
