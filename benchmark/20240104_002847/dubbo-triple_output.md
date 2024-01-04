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
# Warmup Iteration   1: 4.489 ops/ms
# Warmup Iteration   2: 11.845 ops/ms
# Warmup Iteration   3: 12.284 ops/ms
Iteration   1: 12.553 ops/ms
Iteration   2: 12.353 ops/ms
Iteration   3: 12.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.488 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (12.353, 12.488, 12.558), stdev = 0.117
  CI (99.9%): [10.358, 14.618] (assumes normal distribution)


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
# Warmup Iteration   1: 8.287 ops/ms
# Warmup Iteration   2: 13.047 ops/ms
# Warmup Iteration   3: 13.190 ops/ms
Iteration   1: 13.056 ops/ms
Iteration   2: 13.134 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.035 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (12.914, 13.035, 13.134), stdev = 0.112
  CI (99.9%): [10.996, 15.074] (assumes normal distribution)


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
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 12.716 ops/ms
# Warmup Iteration   3: 12.727 ops/ms
Iteration   1: 12.968 ops/ms
Iteration   2: 12.907 ops/ms
Iteration   3: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.902 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (12.830, 12.902, 12.968), stdev = 0.070
  CI (99.9%): [11.633, 14.171] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 10.422 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.425 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (10.363, 10.425, 10.508), stdev = 0.075
  CI (99.9%): [9.059, 11.791] (assumes normal distribution)


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (2.489, 2.523, 2.557), stdev = 0.034
  CI (99.9%): [1.904, 3.141] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.470, 2.471, 2.474), stdev = 0.003
  CI (99.9%): [2.423, 2.520] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (2.483, 2.501, 2.532), stdev = 0.026
  CI (99.9%): [2.023, 2.980] (assumes normal distribution)


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.005 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
Iteration   3: 3.056 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.056 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.051, 3.056, 3.059), stdev = 0.004
  CI (99.9%): [2.977, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.690 ms/op
                 createUser·p0.9999: 14.358 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  10.685 ms/op
                 createUser·p0.9999: 12.004 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.603 ms/op
                 createUser·p0.9999: 14.062 ms/op
                 createUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382218
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 186002 
    [ 2.500,  3.750) = 192157 
    [ 3.750,  5.000) = 3175 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.483 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.803 ms/op
                 existUser·p0.9999: 13.994 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 12.569 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388649
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 190534 
    [ 2.500,  3.750) = 195070 
    [ 3.750,  5.000) = 2299 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     13.372 ms/op
     p(99.9990) =     14.505 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  10.699 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  9.012 ms/op
                 getUser·p0.9999: 14.537 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  8.769 ms/op
                 getUser·p0.9999: 11.435 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382648
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 189321 
    [ 2.500,  3.750) = 187894 
    [ 3.750,  5.000) = 4394 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.804 ms/op
     p(99.9900) =     14.245 ms/op
     p(99.9990) =     14.645 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.229 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.477 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.654 ms/op
                 listUser·p0.9999: 11.120 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313607
  mean =      3.058 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 82165 
    [ 2.500,  3.750) = 188301 
    [ 3.750,  5.000) = 35050 
    [ 5.000,  6.250) = 6709 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 259 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.581 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.488 ± 2.130  ops/ms
ClientPb.existUser                       thrpt       3  13.035 ± 2.039  ops/ms
ClientPb.getUser                         thrpt       3  12.902 ± 1.269  ops/ms
ClientPb.listUser                        thrpt       3  10.425 ± 1.366  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.618   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.049   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.478   ms/op
ClientPb.listUser                         avgt       3   3.056 ± 0.078   ms/op
ClientPb.createUser                     sample  382218   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.828           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  388649   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.836           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.119           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.372           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  382648   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.682           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  313607   3.058 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.674           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.747           ms/op
