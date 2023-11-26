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
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 11.843 ops/ms
# Warmup Iteration   3: 12.017 ops/ms
Iteration   1: 12.434 ops/ms
Iteration   2: 12.257 ops/ms
Iteration   3: 12.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.329 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (12.257, 12.329, 12.434), stdev = 0.093
  CI (99.9%): [10.636, 14.022] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 12.820 ops/ms
# Warmup Iteration   3: 12.729 ops/ms
Iteration   1: 12.970 ops/ms
Iteration   2: 12.868 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.871 ±(99.9%) 1.773 ops/ms [Average]
  (min, avg, max) = (12.776, 12.871, 12.970), stdev = 0.097
  CI (99.9%): [11.098, 14.644] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ops/ms
# Warmup Iteration   2: 12.283 ops/ms
# Warmup Iteration   3: 12.625 ops/ms
Iteration   1: 12.642 ops/ms
Iteration   2: 12.668 ops/ms
Iteration   3: 12.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.624 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (12.564, 12.624, 12.668), stdev = 0.054
  CI (99.9%): [11.638, 13.611] (assumes normal distribution)


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
# Warmup Iteration   1: 6.303 ops/ms
# Warmup Iteration   2: 10.235 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.579 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (10.507, 10.579, 10.672), stdev = 0.085
  CI (99.9%): [9.037, 12.121] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.512 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (2.512, 2.538, 2.552), stdev = 0.023
  CI (99.9%): [2.118, 2.958] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.462, 2.482, 2.497), stdev = 0.018
  CI (99.9%): [2.150, 2.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.512, 2.534, 2.561), stdev = 0.025
  CI (99.9%): [2.076, 2.993] (assumes normal distribution)


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.053 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (3.043, 3.053, 3.060), stdev = 0.009
  CI (99.9%): [2.889, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.005 ms/op
Iteration   1: 2.603 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  12.815 ms/op
                 createUser·p0.9999: 14.360 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.582 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.142 ms/op
                 createUser·p0.999:  10.145 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 10.646 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370721
  mean =      2.587 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 175761 
    [ 2.500,  3.750) = 189653 
    [ 3.750,  5.000) = 4124 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  5.562 ms/op
                 existUser·p0.9999: 16.884 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  6.159 ms/op
                 existUser·p0.9999: 14.911 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.825 ms/op
                 existUser·p0.999:  9.055 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385371
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 190091 
    [ 2.500,  3.750) = 191357 
    [ 3.750,  5.000) = 3088 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      6.870 ms/op
     p(99.9900) =     15.139 ms/op
     p(99.9990) =     17.470 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  9.478 ms/op
                 getUser·p0.9999: 14.327 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  10.040 ms/op
                 getUser·p0.9999: 15.852 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  8.573 ms/op
                 getUser·p0.9999: 12.090 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382500
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189134 
    [ 2.500,  3.750) = 188080 
    [ 3.750,  5.000) = 4022 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.577 ms/op
     p(99.9900) =     14.569 ms/op
     p(99.9990) =     16.128 ms/op
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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.082 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.538 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.282 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.801 ms/op
                 listUser·p0.9999: 11.477 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.355 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313266
  mean =      3.062 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 85410 
    [ 2.500,  3.750) = 184017 
    [ 3.750,  5.000) = 35049 
    [ 5.000,  6.250) = 7056 
    [ 6.250,  7.500) = 874 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 234 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.737 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     11.742 ms/op
     p(99.9990) =     12.335 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.329 ± 1.693  ops/ms
ClientPb.existUser                       thrpt       3  12.871 ± 1.773  ops/ms
ClientPb.getUser                         thrpt       3  12.624 ± 0.987  ops/ms
ClientPb.listUser                        thrpt       3  10.579 ± 1.542  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.420   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.332   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 0.458   ms/op
ClientPb.listUser                         avgt       3   3.053 ± 0.163   ms/op
ClientPb.createUser                     sample  370721   2.587 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.979           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.675           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  385371   2.489 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.677           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.870           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.139           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.793           ms/op
ClientPb.getUser                        sample  382500   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.897           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.577           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.569           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.974           ms/op
ClientPb.listUser                       sample  313266   3.062 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.737           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.896           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
