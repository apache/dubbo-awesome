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
# Warmup Iteration   1: 5.290 ops/ms
# Warmup Iteration   2: 12.502 ops/ms
# Warmup Iteration   3: 12.679 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 13.153 ops/ms
Iteration   3: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.063 ±(99.9%) 3.441 ops/ms [Average]
  (min, avg, max) = (12.847, 13.063, 13.190), stdev = 0.189
  CI (99.9%): [9.622, 16.505] (assumes normal distribution)


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
# Warmup Iteration   1: 8.022 ops/ms
# Warmup Iteration   2: 13.062 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 12.940 ops/ms
Iteration   3: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.988 ±(99.9%) 0.961 ops/ms [Average]
  (min, avg, max) = (12.940, 12.988, 13.044), stdev = 0.053
  CI (99.9%): [12.027, 13.949] (assumes normal distribution)


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
# Warmup Iteration   1: 7.344 ops/ms
# Warmup Iteration   2: 12.667 ops/ms
# Warmup Iteration   3: 12.723 ops/ms
Iteration   1: 12.618 ops/ms
Iteration   2: 12.648 ops/ms
Iteration   3: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.669 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (12.618, 12.669, 12.740), stdev = 0.063
  CI (99.9%): [11.517, 13.821] (assumes normal distribution)


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
# Warmup Iteration   1: 6.216 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.643 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (10.460, 10.643, 10.850), stdev = 0.196
  CI (99.9%): [7.063, 14.223] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.483 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.483, 2.505, 2.525), stdev = 0.021
  CI (99.9%): [2.118, 2.893] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
Iteration   2: 2.433 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.433, 2.443, 2.451), stdev = 0.010
  CI (99.9%): [2.268, 2.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.003 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.468, 2.494, 2.517), stdev = 0.025
  CI (99.9%): [2.043, 2.946] (assumes normal distribution)


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.975, 2.987, 3.000), stdev = 0.013
  CI (99.9%): [2.757, 3.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  12.121 ms/op
                 createUser·p0.9999: 13.840 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  10.623 ms/op
                 createUser·p0.9999: 13.863 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.018 ms/op
                 createUser·p0.999:  8.556 ms/op
                 createUser·p0.9999: 9.863 ms/op
                 createUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385594
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 187401 
    [ 2.500,  3.750) = 193316 
    [ 3.750,  5.000) = 3473 
    [ 5.000,  6.250) = 781 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.001 ms/op
     p(99.9900) =     13.704 ms/op
     p(99.9990) =     16.396 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.006 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.413 ms/op
                 existUser·p0.9999: 14.447 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  6.881 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.819 ms/op
                 existUser·p0.9999: 14.701 ms/op
                 existUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394081
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 196426 
    [ 2.500,  3.750) = 193728 
    [ 3.750,  5.000) = 3085 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     14.346 ms/op
     p(99.9990) =     15.305 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  7.186 ms/op
                 getUser·p0.9999: 22.186 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  9.725 ms/op
                 getUser·p0.9999: 13.392 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.126 ms/op
                 getUser·p0.9999: 10.146 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385088
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190111 
    [ 2.500,  5.000) = 193495 
    [ 5.000,  7.500) = 1079 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     14.180 ms/op
     p(99.9990) =     22.877 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.009 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  8.848 ms/op
                 listUser·p0.9999: 10.224 ms/op
                 listUser·p1.00:   10.895 ms/op

Iteration   2: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.898 ms/op
                 listUser·p0.9999: 11.259 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.652 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.072 ms/op
                 listUser·p0.9999: 10.733 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322137
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 102666 
    [ 2.500,  3.750) = 181145 
    [ 3.750,  5.000) = 30375 
    [ 5.000,  6.250) = 6134 
    [ 6.250,  7.500) = 957 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     11.556 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.063 ± 3.441  ops/ms
ClientPb.existUser                       thrpt       3  12.988 ± 0.961  ops/ms
ClientPb.getUser                         thrpt       3  12.669 ± 1.152  ops/ms
ClientPb.listUser                        thrpt       3  10.643 ± 3.580  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.175   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.452   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.230   ms/op
ClientPb.createUser                     sample  385594   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.703           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.001           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.704           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.679           ms/op
ClientPb.existUser                      sample  394081   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.657           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.346           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.516           ms/op
ClientPb.getUser                        sample  385088   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.126           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.626           ms/op
ClientPb.listUser                       sample  322137   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.652           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.895           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.616           ms/op
