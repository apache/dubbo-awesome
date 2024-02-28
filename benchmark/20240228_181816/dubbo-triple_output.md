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
# Warmup Iteration   1: 5.026 ops/ms
# Warmup Iteration   2: 12.388 ops/ms
# Warmup Iteration   3: 12.675 ops/ms
Iteration   1: 13.064 ops/ms
Iteration   2: 13.076 ops/ms
Iteration   3: 13.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.078 ±(99.9%) 0.277 ops/ms [Average]
  (min, avg, max) = (13.064, 13.078, 13.094), stdev = 0.015
  CI (99.9%): [12.801, 13.355] (assumes normal distribution)


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
# Warmup Iteration   1: 8.427 ops/ms
# Warmup Iteration   2: 13.399 ops/ms
# Warmup Iteration   3: 13.497 ops/ms
Iteration   1: 13.449 ops/ms
Iteration   2: 13.547 ops/ms
Iteration   3: 13.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.511 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (13.449, 13.511, 13.547), stdev = 0.054
  CI (99.9%): [12.532, 14.490] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.703 ops/ms
# Warmup Iteration   2: 12.933 ops/ms
# Warmup Iteration   3: 13.185 ops/ms
Iteration   1: 13.318 ops/ms
Iteration   2: 13.279 ops/ms
Iteration   3: 13.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.233 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (13.103, 13.233, 13.318), stdev = 0.115
  CI (99.9%): [11.140, 15.327] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.079 ops/ms
# Warmup Iteration   2: 10.811 ops/ms
# Warmup Iteration   3: 10.985 ops/ms
Iteration   1: 10.971 ops/ms
Iteration   2: 10.955 ops/ms
Iteration   3: 10.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.933 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.871, 10.933, 10.971), stdev = 0.054
  CI (99.9%): [9.947, 11.918] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.440 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.432, 2.440, 2.451), stdev = 0.010
  CI (99.9%): [2.262, 2.618] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.614 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.004 ms/op
Iteration   1: 2.408 ±(99.9%) 0.004 ms/op
Iteration   2: 2.415 ±(99.9%) 0.004 ms/op
Iteration   3: 2.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.395, 2.406, 2.415), stdev = 0.010
  CI (99.9%): [2.221, 2.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.428 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.424 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.419, 2.424, 2.428), stdev = 0.005
  CI (99.9%): [2.337, 2.510] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.004 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
Iteration   2: 2.907 ±(99.9%) 0.004 ms/op
Iteration   3: 2.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.939 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.907, 2.939, 2.961), stdev = 0.028
  CI (99.9%): [2.427, 3.451] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.454 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.027 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  5.639 ms/op
                 createUser·p0.9999: 13.195 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   3.473 ms/op
                 createUser·p0.999:  5.473 ms/op
                 createUser·p0.9999: 12.104 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   2.927 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  8.940 ms/op
                 createUser·p0.9999: 11.108 ms/op
                 createUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 397666
  mean =      2.412 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 202221 
    [ 2.500,  3.750) = 192541 
    [ 3.750,  5.000) = 2077 
    [ 5.000,  6.250) = 195 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 155 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     12.644 ms/op
     p(99.9990) =     13.437 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.355 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.369 ±(99.9%) 0.005 ms/op
Iteration   1: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.713 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.361 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.970 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 11.673 ms/op
                 existUser·p1.00:   12.501 ms/op

Iteration   3: 2.346 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.372 ms/op
                 existUser·p0.90:   2.859 ms/op
                 existUser·p0.95:   2.966 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.740 ms/op
                 existUser·p0.9999: 11.174 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405662
  mean =      2.365 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 214459 
    [ 2.500,  3.750) = 188713 
    [ 3.750,  5.000) = 1854 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     13.745 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.663 ms/op
                 getUser·p0.999:  5.787 ms/op
                 getUser·p0.9999: 13.207 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  7.726 ms/op
                 getUser·p0.9999: 12.727 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.925 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  6.452 ms/op
                 getUser·p0.9999: 10.284 ms/op
                 getUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 395778
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 203661 
    [ 2.500,  3.750) = 187752 
    [ 3.750,  5.000) = 3505 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.350 ms/op
     p(99.9900) =     12.819 ms/op
     p(99.9990) =     13.453 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
Iteration   1: 2.938 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.570 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.931 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.800 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.921 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.635 ms/op
                 listUser·p0.9999: 11.912 ms/op
                 listUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327355
  mean =      2.930 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 188 
    [ 1.250,  2.500) = 106667 
    [ 2.500,  3.750) = 186041 
    [ 3.750,  5.000) = 27938 
    [ 5.000,  6.250) = 5271 
    [ 6.250,  7.500) = 571 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.158 ms/op
     p(99.9990) =     12.267 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.078 ± 0.277  ops/ms
ClientPb.existUser                       thrpt       3  13.511 ± 0.979  ops/ms
ClientPb.getUser                         thrpt       3  13.233 ± 2.093  ops/ms
ClientPb.listUser                        thrpt       3  10.933 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   2.440 ± 0.178   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.184   ms/op
ClientPb.getUser                          avgt       3   2.424 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   2.939 ± 0.512   ms/op
ClientPb.createUser                     sample  397666   2.412 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.470           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.644           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.648           ms/op
ClientPb.existUser                      sample  405662   2.365 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.953           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.417           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.780           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  395778   2.424 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.852           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.350           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.828           ms/op
ClientPb.listUser                       sample  327355   2.930 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
