# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 4.879 ops/ms
# Warmup Iteration   3: 8.828 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.430 ops/ms
Iteration   3: 9.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 3.646 ops/ms [Average]
  (min, avg, max) = (9.059, 9.288, 9.430), stdev = 0.200
  CI (99.9%): [5.641, 12.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 8.278 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 9.895 ops/ms
Iteration   2: 9.623 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.719 ±(99.9%) 2.778 ops/ms [Average]
  (min, avg, max) = (9.623, 9.719, 9.895), stdev = 0.152
  CI (99.9%): [6.941, 12.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.448 ops/ms
Iteration   1: 8.811 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.799 ±(99.9%) 5.742 ops/ms [Average]
  (min, avg, max) = (8.478, 8.799, 9.107), stdev = 0.315
  CI (99.9%): [3.057, 14.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 6.549 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 7.801 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.852 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (7.801, 7.852, 7.910), stdev = 0.055
  CI (99.9%): [6.845, 8.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.778 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.009 ms/op
Iteration   1: 3.398 ±(99.9%) 0.007 ms/op
Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
Iteration   3: 3.403 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.471 ±(99.9%) 2.215 ms/op [Average]
  (min, avg, max) = (3.398, 3.471, 3.611), stdev = 0.121
  CI (99.9%): [1.255, 5.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.490 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.006 ms/op
Iteration   1: 3.325 ±(99.9%) 0.005 ms/op
Iteration   2: 3.370 ±(99.9%) 0.006 ms/op
Iteration   3: 3.406 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.325, 3.367, 3.406), stdev = 0.041
  CI (99.9%): [2.619, 4.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.623 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.005 ms/op
Iteration   1: 3.569 ±(99.9%) 0.004 ms/op
Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
Iteration   3: 3.291 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 2.561 ms/op [Average]
  (min, avg, max) = (3.291, 3.418, 3.569), stdev = 0.140
  CI (99.9%): [0.856, 5.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.683 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.004 ms/op
Iteration   1: 4.092 ±(99.9%) 0.009 ms/op
Iteration   2: 3.947 ±(99.9%) 0.009 ms/op
Iteration   3: 4.004 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.014 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (3.947, 4.014, 4.092), stdev = 0.073
  CI (99.9%): [2.683, 5.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.810 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.009 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  18.200 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.539 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.117 ms/op
                 createUser·p0.999:  20.633 ms/op
                 createUser·p0.9999: 26.312 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.542 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  17.115 ms/op
                 createUser·p0.9999: 31.850 ms/op
                 createUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274131
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9028 
    [ 2.500,  5.000) = 256135 
    [ 5.000,  7.500) = 7789 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     30.189 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.334 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 21.861 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.753 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.645 ms/op
                 existUser·p0.999:  13.671 ms/op
                 existUser·p0.9999: 23.752 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290228
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14085 
    [ 2.500,  5.000) = 269635 
    [ 5.000,  7.500) = 5535 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     26.246 ms/op
     p(99.9990) =     27.499 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.418 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
Iteration   1: 3.454 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  20.691 ms/op
                 getUser·p0.9999: 28.860 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  20.893 ms/op
                 getUser·p0.9999: 25.057 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  18.261 ms/op
                 getUser·p0.9999: 24.678 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281395
  mean =      3.409 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4535 
    [ 2.500,  5.000) = 269129 
    [ 5.000,  7.500) = 6295 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     28.101 ms/op
     p(99.9990) =     29.417 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.341 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.015 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  19.814 ms/op
                 listUser·p0.9999: 24.260 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.314 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 3.993 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  14.777 ms/op
                 listUser·p0.9999: 15.352 ms/op
                 listUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240023
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 230665 
    [ 5.000,  7.500) = 6138 
    [ 7.500, 10.000) = 2326 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 3.646  ops/ms
ClientPb.existUser                       thrpt       3   9.719 ± 2.778  ops/ms
ClientPb.getUser                         thrpt       3   8.799 ± 5.742  ops/ms
ClientPb.listUser                        thrpt       3   7.852 ± 1.007  ops/ms
ClientPb.createUser                       avgt       3   3.471 ± 2.215   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 0.748   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 2.561   ms/op
ClientPb.listUser                         avgt       3   4.014 ± 1.332   ms/op
ClientPb.createUser                     sample  274131   3.497 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.537           ms/op
ClientPb.existUser                      sample  290228   3.306 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.246           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.591           ms/op
ClientPb.getUser                        sample  281395   3.409 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.101           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  240023   3.998 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.167           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
