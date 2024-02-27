# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ops/ms
# Warmup Iteration   2: 12.011 ops/ms
# Warmup Iteration   3: 12.380 ops/ms
Iteration   1: 12.649 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.700 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (12.649, 12.700, 12.739), stdev = 0.046
  CI (99.9%): [11.864, 13.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.069 ops/ms
# Warmup Iteration   2: 12.785 ops/ms
# Warmup Iteration   3: 13.032 ops/ms
Iteration   1: 12.928 ops/ms
Iteration   2: 13.166 ops/ms
Iteration   3: 13.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.106 ±(99.9%) 2.874 ops/ms [Average]
  (min, avg, max) = (12.928, 13.106, 13.226), stdev = 0.158
  CI (99.9%): [10.232, 15.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.715 ops/ms
# Warmup Iteration   2: 12.727 ops/ms
# Warmup Iteration   3: 12.848 ops/ms
Iteration   1: 12.899 ops/ms
Iteration   2: 12.951 ops/ms
Iteration   3: 12.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.910 ±(99.9%) 0.684 ops/ms [Average]
  (min, avg, max) = (12.879, 12.910, 12.951), stdev = 0.037
  CI (99.9%): [12.226, 13.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.622 ±(99.9%) 0.195 ops/ms [Average]
  (min, avg, max) = (10.613, 10.622, 10.634), stdev = 0.011
  CI (99.9%): [10.427, 10.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (2.521, 2.541, 2.555), stdev = 0.018
  CI (99.9%): [2.210, 2.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.422, 2.437, 2.451), stdev = 0.015
  CI (99.9%): [2.172, 2.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.463, 2.474, 2.488), stdev = 0.012
  CI (99.9%): [2.248, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.624 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (3.012, 3.020, 3.027), stdev = 0.008
  CI (99.9%): [2.877, 3.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.385 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  11.502 ms/op
                 createUser·p0.9999: 14.845 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 12.116 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.060 ms/op
                 createUser·p0.9999: 11.600 ms/op
                 createUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376793
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 181355 
    [ 2.500,  3.750) = 191232 
    [ 3.750,  5.000) = 3441 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.138 ms/op
     p(99.9900) =     13.855 ms/op
     p(99.9990) =     15.228 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  8.199 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.374 ms/op
                 existUser·p0.9999: 13.552 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  5.874 ms/op
                 existUser·p0.9999: 12.000 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386841
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 189013 
    [ 2.500,  3.750) = 194771 
    [ 3.750,  5.000) = 2307 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     13.226 ms/op
     p(99.9990) =     14.863 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  7.382 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  8.730 ms/op
                 getUser·p0.9999: 13.832 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  8.290 ms/op
                 getUser·p0.9999: 10.986 ms/op
                 getUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385256
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 190930 
    [ 2.500,  3.750) = 189155 
    [ 3.750,  5.000) = 3882 
    [ 5.000,  6.250) = 815 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.261 ms/op
     p(99.9900) =     13.508 ms/op
     p(99.9990) =     14.617 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.713 ms/op
                 listUser·p0.9999: 10.212 ms/op
                 listUser·p1.00:   10.715 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.646 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.860 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 11.243 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.638 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321941
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 97485 
    [ 2.500,  3.750) = 186687 
    [ 3.750,  5.000) = 30806 
    [ 5.000,  6.250) = 5368 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 331 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     11.171 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.700 ± 0.836  ops/ms
ClientPb.existUser                       thrpt       3  13.106 ± 2.874  ops/ms
ClientPb.getUser                         thrpt       3  12.910 ± 0.684  ops/ms
ClientPb.listUser                        thrpt       3  10.622 ± 0.195  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.331   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.265   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.226   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.143   ms/op
ClientPb.createUser                     sample  376793   2.545 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.727           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.581           ms/op
ClientPb.existUser                      sample  386841   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.291           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  385256   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.859           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.508           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  321941   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.646           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.171           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.452           ms/op
