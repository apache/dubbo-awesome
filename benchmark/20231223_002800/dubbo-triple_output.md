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
# Warmup Iteration   1: 5.010 ops/ms
# Warmup Iteration   2: 12.089 ops/ms
# Warmup Iteration   3: 12.532 ops/ms
Iteration   1: 12.657 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.715 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (12.657, 12.715, 12.761), stdev = 0.053
  CI (99.9%): [11.751, 13.679] (assumes normal distribution)


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
# Warmup Iteration   1: 8.020 ops/ms
# Warmup Iteration   2: 12.976 ops/ms
# Warmup Iteration   3: 13.007 ops/ms
Iteration   1: 12.922 ops/ms
Iteration   2: 13.059 ops/ms
Iteration   3: 12.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.985 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (12.922, 12.985, 13.059), stdev = 0.069
  CI (99.9%): [11.725, 14.246] (assumes normal distribution)


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
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 12.515 ops/ms
# Warmup Iteration   3: 12.720 ops/ms
Iteration   1: 12.867 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.859 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (12.784, 12.859, 12.926), stdev = 0.071
  CI (99.9%): [11.558, 14.160] (assumes normal distribution)


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
# Warmup Iteration   1: 6.883 ops/ms
# Warmup Iteration   2: 10.644 ops/ms
# Warmup Iteration   3: 10.761 ops/ms
Iteration   1: 10.876 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.878 ±(99.9%) 0.499 ops/ms [Average]
  (min, avg, max) = (10.851, 10.878, 10.906), stdev = 0.027
  CI (99.9%): [10.378, 11.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.003 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.518, 2.525, 2.535), stdev = 0.009
  CI (99.9%): [2.356, 2.693] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.451, 2.470, 2.488), stdev = 0.018
  CI (99.9%): [2.138, 2.802] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.483, 2.501, 2.515), stdev = 0.016
  CI (99.9%): [2.207, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
Iteration   3: 2.991 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.982, 2.988, 2.991), stdev = 0.005
  CI (99.9%): [2.905, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  11.471 ms/op
                 createUser·p0.9999: 13.528 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.578 ms/op
                 createUser·p0.999:  9.357 ms/op
                 createUser·p0.9999: 12.845 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.267 ms/op
                 createUser·p0.99:   4.094 ms/op
                 createUser·p0.999:  8.483 ms/op
                 createUser·p0.9999: 11.174 ms/op
                 createUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380801
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185894 
    [ 2.500,  3.750) = 190977 
    [ 3.750,  5.000) = 3170 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.851 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     13.667 ms/op
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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  7.519 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.549 ms/op
                 existUser·p0.999:  7.179 ms/op
                 existUser·p0.9999: 13.766 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.762 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 13.174 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387774
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 190956 
    [ 2.500,  3.750) = 193685 
    [ 3.750,  5.000) = 2453 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.406 ms/op
     p(99.9990) =     14.244 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  7.138 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.988 ms/op
                 getUser·p0.999:  7.989 ms/op
                 getUser·p0.9999: 12.571 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  7.824 ms/op
                 getUser·p0.9999: 11.076 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387817
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 194893 
    [ 2.500,  3.750) = 188863 
    [ 3.750,  5.000) = 3076 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.265 ms/op
     p(99.9900) =     13.455 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.065 ms/op
                 listUser·p0.9999: 10.393 ms/op
                 listUser·p1.00:   10.699 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.203 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   3: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.585 ms/op
                 listUser·p0.9999: 10.956 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321873
  mean =      2.980 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 98259 
    [ 2.500,  3.750) = 186292 
    [ 3.750,  5.000) = 30395 
    [ 5.000,  6.250) = 5377 
    [ 6.250,  7.500) = 717 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     11.524 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.715 ± 0.964  ops/ms
ClientPb.existUser                       thrpt       3  12.985 ± 1.261  ops/ms
ClientPb.getUser                         thrpt       3  12.859 ± 1.301  ops/ms
ClientPb.listUser                        thrpt       3  10.878 ± 0.499  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.168   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.332   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.294   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.083   ms/op
ClientPb.createUser                     sample  380801   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.851           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.779           ms/op
ClientPb.existUser                      sample  387774   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.950           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  387817   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.872           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.265           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.455           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  321873   2.980 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.882           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.665           ms/op
