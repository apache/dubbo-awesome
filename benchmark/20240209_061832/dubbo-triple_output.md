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
# Warmup Iteration   1: 5.219 ops/ms
# Warmup Iteration   2: 12.570 ops/ms
# Warmup Iteration   3: 12.579 ops/ms
Iteration   1: 12.965 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.939 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (12.896, 12.939, 12.965), stdev = 0.038
  CI (99.9%): [12.247, 13.632] (assumes normal distribution)


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
# Warmup Iteration   1: 8.107 ops/ms
# Warmup Iteration   2: 13.263 ops/ms
# Warmup Iteration   3: 13.277 ops/ms
Iteration   1: 13.299 ops/ms
Iteration   2: 13.364 ops/ms
Iteration   3: 13.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.310 ±(99.9%) 0.894 ops/ms [Average]
  (min, avg, max) = (13.267, 13.310, 13.364), stdev = 0.049
  CI (99.9%): [12.416, 14.204] (assumes normal distribution)


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
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 12.920 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 13.251 ops/ms
Iteration   2: 13.613 ops/ms
Iteration   3: 13.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.386 ±(99.9%) 3.602 ops/ms [Average]
  (min, avg, max) = (13.251, 13.386, 13.613), stdev = 0.197
  CI (99.9%): [9.784, 16.989] (assumes normal distribution)


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
# Warmup Iteration   1: 7.321 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.916 ops/ms
Iteration   1: 11.021 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.914 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (10.843, 10.914, 11.021), stdev = 0.095
  CI (99.9%): [9.188, 12.639] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.480 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.466, 2.480, 2.495), stdev = 0.014
  CI (99.9%): [2.218, 2.743] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.386 ±(99.9%) 0.005 ms/op
Iteration   1: 2.374 ±(99.9%) 0.004 ms/op
Iteration   2: 2.382 ±(99.9%) 0.005 ms/op
Iteration   3: 2.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.374, 2.381, 2.387), stdev = 0.007
  CI (99.9%): [2.256, 2.506] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.454, 2.457, 2.460), stdev = 0.003
  CI (99.9%): [2.403, 2.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.005 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
Iteration   2: 2.925 ±(99.9%) 0.004 ms/op
Iteration   3: 2.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.928 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.923, 2.928, 2.936), stdev = 0.007
  CI (99.9%): [2.801, 3.055] (assumes normal distribution)


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  6.027 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  6.930 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.708 ms/op
                 createUser·p0.999:  8.453 ms/op
                 createUser·p0.9999: 12.275 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389398
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 191541 
    [ 2.500,  3.750) = 194424 
    [ 3.750,  5.000) = 2675 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.192 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     14.277 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  5.786 ms/op
                 existUser·p0.9999: 16.343 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.227 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395502
  mean =      2.425 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 196106 
    [ 2.500,  3.750) = 196623 
    [ 3.750,  5.000) = 1941 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =      7.147 ms/op
     p(99.9900) =     13.326 ms/op
     p(99.9990) =     16.713 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  7.299 ms/op
                 getUser·p0.9999: 14.448 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.639 ms/op
                 getUser·p0.9999: 11.571 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  5.534 ms/op
                 getUser·p0.9999: 11.944 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 394213
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 201957 
    [ 2.500,  3.750) = 187507 
    [ 3.750,  5.000) = 3307 
    [ 5.000,  6.250) = 873 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.202 ms/op
     p(99.9900) =     13.199 ms/op
     p(99.9990) =     15.205 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.733 ms/op
                 listUser·p0.9999: 9.884 ms/op
                 listUser·p1.00:   10.502 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.275 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.122 ms/op
                 listUser·p0.9999: 11.558 ms/op
                 listUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323068
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 100912 
    [ 2.500,  3.750) = 185259 
    [ 3.750,  5.000) = 30152 
    [ 5.000,  6.250) = 5524 
    [ 6.250,  7.500) = 468 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     11.251 ms/op
     p(99.9990) =     12.153 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.939 ± 0.693  ops/ms
ClientPb.existUser                       thrpt       3  13.310 ± 0.894  ops/ms
ClientPb.getUser                         thrpt       3  13.386 ± 3.602  ops/ms
ClientPb.listUser                        thrpt       3  10.914 ± 1.725  ops/ms
ClientPb.createUser                       avgt       3   2.480 ± 0.263   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.125   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.054   ms/op
ClientPb.listUser                         avgt       3   2.928 ± 0.127   ms/op
ClientPb.createUser                     sample  389398   2.463 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.192           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.632           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  395502   2.425 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.852           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.147           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.326           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.105           ms/op
ClientPb.getUser                        sample  394213   2.433 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.821           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.202           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.199           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.286           ms/op
ClientPb.listUser                       sample  323068   2.969 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.897           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.251           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.009           ms/op
