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
# Warmup Iteration   1: 5.342 ops/ms
# Warmup Iteration   2: 12.348 ops/ms
# Warmup Iteration   3: 12.524 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.724 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (12.652, 12.724, 12.776), stdev = 0.064
  CI (99.9%): [11.556, 13.891] (assumes normal distribution)


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
# Warmup Iteration   1: 8.740 ops/ms
# Warmup Iteration   2: 13.200 ops/ms
# Warmup Iteration   3: 13.342 ops/ms
Iteration   1: 13.186 ops/ms
Iteration   2: 13.290 ops/ms
Iteration   3: 13.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.235 ±(99.9%) 0.957 ops/ms [Average]
  (min, avg, max) = (13.186, 13.235, 13.290), stdev = 0.052
  CI (99.9%): [12.278, 14.192] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ops/ms
# Warmup Iteration   2: 12.737 ops/ms
# Warmup Iteration   3: 12.899 ops/ms
Iteration   1: 13.037 ops/ms
Iteration   2: 12.993 ops/ms
Iteration   3: 13.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.054 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (12.993, 13.054, 13.131), stdev = 0.070
  CI (99.9%): [11.773, 14.334] (assumes normal distribution)


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
# Warmup Iteration   1: 6.694 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.695 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.691 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (10.639, 10.691, 10.727), stdev = 0.046
  CI (99.9%): [9.848, 11.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.003 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.549, 2.565, 2.583), stdev = 0.017
  CI (99.9%): [2.259, 2.871] (assumes normal distribution)


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.004 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.409 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.409, 2.416, 2.431), stdev = 0.013
  CI (99.9%): [2.181, 2.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.003 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.480, 2.502, 2.525), stdev = 0.022
  CI (99.9%): [2.094, 2.911] (assumes normal distribution)


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.994 ±(99.9%) 0.004 ms/op
Iteration   3: 2.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.976, 2.986, 2.994), stdev = 0.009
  CI (99.9%): [2.822, 3.150] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  6.926 ms/op
                 createUser·p0.9999: 13.912 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.473 ms/op
                 createUser·p0.999:  6.551 ms/op
                 createUser·p0.9999: 12.650 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.207 ms/op
                 createUser·p0.9999: 15.142 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386652
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 189118 
    [ 2.500,  3.750) = 194480 
    [ 3.750,  5.000) = 2308 
    [ 5.000,  6.250) = 236 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.915 ms/op
     p(99.9990) =     15.827 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.277 ms/op
                 existUser·p0.9999: 13.012 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.509 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.338 ms/op
                 existUser·p0.9999: 12.530 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   3: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 10.895 ms/op
                 existUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397872
  mean =      2.410 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 202153 
    [ 2.500,  3.750) = 192754 
    [ 3.750,  5.000) = 2154 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.343 ms/op
     p(99.9900) =     12.537 ms/op
     p(99.9990) =     13.522 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.730 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.851 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  5.512 ms/op
                 getUser·p0.9999: 14.875 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389117
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 194567 
    [ 2.500,  3.750) = 190782 
    [ 3.750,  5.000) = 2888 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.436 ms/op
     p(99.9900) =     13.682 ms/op
     p(99.9990) =     15.042 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.984 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  10.161 ms/op
                 listUser·p0.9999: 11.267 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.320 ms/op
                 listUser·p0.9999: 12.140 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322322
  mean =      2.976 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 98495 
    [ 2.500,  3.750) = 186133 
    [ 3.750,  5.000) = 30638 
    [ 5.000,  6.250) = 5766 
    [ 6.250,  7.500) = 507 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.392 ms/op
     p(99.9990) =     12.614 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.724 ± 1.167  ops/ms
ClientPb.existUser                       thrpt       3  13.235 ± 0.957  ops/ms
ClientPb.getUser                         thrpt       3  13.054 ± 1.281  ops/ms
ClientPb.listUser                        thrpt       3  10.691 ± 0.843  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.306   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.235   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.408   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.164   ms/op
ClientPb.createUser                     sample  386652   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.834           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.915           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.777           ms/op
ClientPb.existUser                      sample  397872   2.410 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.734           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.343           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.795           ms/op
ClientPb.getUser                        sample  389117   2.465 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.465           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.682           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  322322   2.976 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.392           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
