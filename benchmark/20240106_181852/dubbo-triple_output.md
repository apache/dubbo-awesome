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
# Warmup Iteration   1: 5.138 ops/ms
# Warmup Iteration   2: 12.157 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.758 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.768 ±(99.9%) 0.162 ops/ms [Average]
  (min, avg, max) = (12.758, 12.768, 12.774), stdev = 0.009
  CI (99.9%): [12.606, 12.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.337 ops/ms
# Warmup Iteration   2: 13.214 ops/ms
# Warmup Iteration   3: 13.192 ops/ms
Iteration   1: 13.201 ops/ms
Iteration   2: 13.170 ops/ms
Iteration   3: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.167 ±(99.9%) 0.665 ops/ms [Average]
  (min, avg, max) = (13.128, 13.167, 13.201), stdev = 0.036
  CI (99.9%): [12.501, 13.832] (assumes normal distribution)


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
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 12.795 ops/ms
# Warmup Iteration   3: 12.950 ops/ms
Iteration   1: 12.992 ops/ms
Iteration   2: 13.048 ops/ms
Iteration   3: 13.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.054 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (12.992, 13.054, 13.122), stdev = 0.065
  CI (99.9%): [11.860, 14.248] (assumes normal distribution)


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
# Warmup Iteration   1: 6.575 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.621 ±(99.9%) 0.178 ops/ms [Average]
  (min, avg, max) = (10.615, 10.621, 10.632), stdev = 0.010
  CI (99.9%): [10.443, 10.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.003 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.510 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.487, 2.510, 2.534), stdev = 0.024
  CI (99.9%): [2.078, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.425 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.411, 2.425, 2.443), stdev = 0.016
  CI (99.9%): [2.129, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.003 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.442 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.429, 2.442, 2.450), stdev = 0.011
  CI (99.9%): [2.235, 2.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
Iteration   3: 2.941 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.953 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.941, 2.953, 2.969), stdev = 0.014
  CI (99.9%): [2.698, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  11.034 ms/op
                 createUser·p0.9999: 13.243 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  9.345 ms/op
                 createUser·p0.9999: 12.030 ms/op
                 createUser·p1.00:   12.304 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 10.830 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381525
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183488 
    [ 2.500,  3.750) = 193707 
    [ 3.750,  5.000) = 3457 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.505 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.395 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.296 ms/op
                 existUser·p0.9999: 13.936 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  9.092 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402292
  mean =      2.384 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 211454 
    [ 2.500,  3.750) = 188528 
    [ 3.750,  5.000) = 1671 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      9.170 ms/op
     p(99.9900) =     13.103 ms/op
     p(99.9990) =     14.531 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  5.478 ms/op
                 getUser·p0.9999: 13.663 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.201 ms/op
                 getUser·p0.999:  9.192 ms/op
                 getUser·p0.9999: 11.982 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  6.845 ms/op
                 getUser·p0.9999: 10.831 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388683
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 196584 
    [ 2.500,  3.750) = 187292 
    [ 3.750,  5.000) = 3784 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.113 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.961 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 11.169 ms/op
                 listUser·p1.00:   12.321 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 12.801 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.361 ms/op
                 listUser·p0.9999: 12.556 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320591
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 96132 
    [ 2.500,  3.750) = 185363 
    [ 3.750,  5.000) = 31904 
    [ 5.000,  6.250) = 5764 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.631 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.979 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.768 ± 0.162  ops/ms
ClientPb.existUser                       thrpt       3  13.167 ± 0.665  ops/ms
ClientPb.getUser                         thrpt       3  13.054 ± 1.194  ops/ms
ClientPb.listUser                        thrpt       3  10.621 ± 0.178  ops/ms
ClientPb.createUser                       avgt       3   2.510 ± 0.432   ms/op
ClientPb.existUser                        avgt       3   2.425 ± 0.296   ms/op
ClientPb.getUser                          avgt       3   2.442 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   2.953 ± 0.255   ms/op
ClientPb.createUser                     sample  381525   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.829           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.779           ms/op
ClientPb.existUser                      sample  402292   2.384 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.953           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.417           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.170           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.103           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.237           ms/op
ClientPb.getUser                        sample  388683   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.113           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.911           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  320591   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
