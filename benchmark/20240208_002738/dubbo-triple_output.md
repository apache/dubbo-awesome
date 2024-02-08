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
# Warmup Iteration   1: 4.517 ops/ms
# Warmup Iteration   2: 12.063 ops/ms
# Warmup Iteration   3: 12.455 ops/ms
Iteration   1: 12.657 ops/ms
Iteration   2: 12.737 ops/ms
Iteration   3: 12.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.765 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (12.657, 12.765, 12.901), stdev = 0.125
  CI (99.9%): [10.492, 15.038] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.065 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.256 ops/ms
Iteration   1: 13.367 ops/ms
Iteration   2: 13.257 ops/ms
Iteration   3: 13.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.248 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (13.120, 13.248, 13.367), stdev = 0.124
  CI (99.9%): [10.985, 15.511] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.892 ops/ms
# Warmup Iteration   2: 12.856 ops/ms
# Warmup Iteration   3: 12.982 ops/ms
Iteration   1: 12.903 ops/ms
Iteration   2: 12.998 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.933 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (12.897, 12.933, 12.998), stdev = 0.057
  CI (99.9%): [11.901, 13.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.622 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.702 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (10.554, 10.702, 10.791), stdev = 0.129
  CI (99.9%): [8.348, 13.056] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
Iteration   3: 2.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.536, 2.541, 2.546), stdev = 0.005
  CI (99.9%): [2.455, 2.628] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.443, 2.458, 2.469), stdev = 0.013
  CI (99.9%): [2.215, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (2.479, 2.483, 2.486), stdev = 0.004
  CI (99.9%): [2.416, 2.550] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.007 ms/op
Iteration   1: 2.931 ±(99.9%) 0.004 ms/op
Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
Iteration   3: 2.934 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.935 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.931, 2.935, 2.941), stdev = 0.005
  CI (99.9%): [2.836, 3.035] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.331 ms/op
                 createUser·p0.9999: 13.406 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.441 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 12.636 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 11.081 ms/op
                 createUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380693
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 184150 
    [ 2.500,  3.750) = 193411 
    [ 3.750,  5.000) = 2256 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     13.540 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.544 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  5.642 ms/op
                 existUser·p0.9999: 12.500 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  7.874 ms/op
                 existUser·p0.9999: 15.700 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396926
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 200550 
    [ 2.500,  3.750) = 193457 
    [ 3.750,  5.000) = 2096 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      7.341 ms/op
     p(99.9900) =     13.609 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  10.729 ms/op
                 getUser·p0.9999: 14.039 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.922 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  9.228 ms/op
                 getUser·p0.9999: 11.538 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381501
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 188674 
    [ 2.500,  3.750) = 188381 
    [ 3.750,  5.000) = 3273 
    [ 5.000,  6.250) = 743 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.954 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     15.186 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.737 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.482 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.318 ms/op
                 listUser·p0.9999: 11.684 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.064 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320463
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 95311 
    [ 2.500,  3.750) = 188280 
    [ 3.750,  5.000) = 30329 
    [ 5.000,  6.250) = 5350 
    [ 6.250,  7.500) = 431 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 198 
    [10.000, 11.250) = 244 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.872 ms/op
     p(99.9900) =     11.435 ms/op
     p(99.9990) =     12.383 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.765 ± 2.273  ops/ms
ClientPb.existUser                       thrpt       3  13.248 ± 2.263  ops/ms
ClientPb.getUser                         thrpt       3  12.933 ± 1.031  ops/ms
ClientPb.listUser                        thrpt       3  10.702 ± 2.354  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.086   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.243   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.067   ms/op
ClientPb.listUser                         avgt       3   2.935 ± 0.100   ms/op
ClientPb.createUser                     sample  380693   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.799           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.929           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  396926   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.341           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.609           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.777           ms/op
ClientPb.getUser                        sample  381501   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.883           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.954           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.614           ms/op
ClientPb.listUser                       sample  320463   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.872           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
