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
# Warmup Iteration   1: 5.215 ops/ms
# Warmup Iteration   2: 12.421 ops/ms
# Warmup Iteration   3: 12.385 ops/ms
Iteration   1: 12.799 ops/ms
Iteration   2: 12.845 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.847 ±(99.9%) 0.900 ops/ms [Average]
  (min, avg, max) = (12.799, 12.847, 12.897), stdev = 0.049
  CI (99.9%): [11.947, 13.747] (assumes normal distribution)


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
# Warmup Iteration   1: 8.606 ops/ms
# Warmup Iteration   2: 12.987 ops/ms
# Warmup Iteration   3: 13.225 ops/ms
Iteration   1: 13.161 ops/ms
Iteration   2: 13.178 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.154 ±(99.9%) 0.497 ops/ms [Average]
  (min, avg, max) = (13.124, 13.154, 13.178), stdev = 0.027
  CI (99.9%): [12.658, 13.651] (assumes normal distribution)


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
# Warmup Iteration   1: 8.243 ops/ms
# Warmup Iteration   2: 12.850 ops/ms
# Warmup Iteration   3: 12.843 ops/ms
Iteration   1: 13.105 ops/ms
Iteration   2: 13.259 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.128 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (13.021, 13.128, 13.259), stdev = 0.121
  CI (99.9%): [10.922, 15.334] (assumes normal distribution)


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
# Warmup Iteration   1: 6.838 ops/ms
# Warmup Iteration   2: 10.768 ops/ms
# Warmup Iteration   3: 10.847 ops/ms
Iteration   1: 10.824 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 10.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.846 ±(99.9%) 0.355 ops/ms [Average]
  (min, avg, max) = (10.824, 10.846, 10.861), stdev = 0.019
  CI (99.9%): [10.492, 11.201] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.031 ms/op [Average]
  (min, avg, max) = (2.493, 2.494, 2.496), stdev = 0.002
  CI (99.9%): [2.463, 2.526] (assumes normal distribution)


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.003 ms/op
Iteration   1: 2.390 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.418 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.390, 2.419, 2.448), stdev = 0.029
  CI (99.9%): [1.897, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.440 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.431, 2.440, 2.446), stdev = 0.008
  CI (99.9%): [2.299, 2.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.936 ±(99.9%) 0.006 ms/op
Iteration   3: 2.938 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.948 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.936, 2.948, 2.969), stdev = 0.019
  CI (99.9%): [2.606, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  7.474 ms/op
                 createUser·p0.9999: 16.548 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  7.450 ms/op
                 createUser·p0.9999: 12.405 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 10.669 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385486
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 186893 
    [ 2.500,  3.750) = 194902 
    [ 3.750,  5.000) = 3016 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.626 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     16.616 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  6.726 ms/op
                 existUser·p0.9999: 13.628 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  5.073 ms/op
                 existUser·p0.9999: 13.529 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 11.957 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395832
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 197661 
    [ 2.500,  3.750) = 194837 
    [ 3.750,  5.000) = 2476 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      7.120 ms/op
     p(99.9900) =     13.393 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  6.941 ms/op
                 getUser·p0.9999: 16.061 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.295 ms/op
                 getUser·p0.999:  6.339 ms/op
                 getUser·p0.9999: 16.894 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 13.421 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386766
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 192346 
    [ 2.500,  3.750) = 189271 
    [ 3.750,  5.000) = 3910 
    [ 5.000,  6.250) = 728 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      6.596 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     17.376 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.457 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 10.300 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.492 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 16.621 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321855
  mean =      2.980 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 99523 
    [ 2.500,  3.750) = 184406 
    [ 3.750,  5.000) = 30516 
    [ 5.000,  6.250) = 5872 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 318 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     14.407 ms/op
     p(99.9990) =     17.444 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.847 ± 0.900  ops/ms
ClientPb.existUser                       thrpt       3  13.154 ± 0.497  ops/ms
ClientPb.getUser                         thrpt       3  13.128 ± 2.206  ops/ms
ClientPb.listUser                        thrpt       3  10.846 ± 0.355  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.031   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.522   ms/op
ClientPb.getUser                          avgt       3   2.440 ± 0.141   ms/op
ClientPb.listUser                         avgt       3   2.948 ± 0.342   ms/op
ClientPb.createUser                     sample  385486   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.663           ms/op
ClientPb.existUser                      sample  395832   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.721           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.120           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.393           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  386766   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.717           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.596           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.596           ms/op
ClientPb.listUser                       sample  321855   2.980 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.407           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.629           ms/op
