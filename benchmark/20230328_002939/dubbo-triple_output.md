# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.956 ops/ms
# Warmup Iteration   2: 5.058 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 9.173 ops/ms
Iteration   2: 9.481 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.363 ±(99.9%) 3.028 ops/ms [Average]
  (min, avg, max) = (9.173, 9.363, 9.481), stdev = 0.166
  CI (99.9%): [6.335, 12.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ops/ms
# Warmup Iteration   2: 8.887 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.813 ops/ms
Iteration   3: 9.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (9.612, 9.686, 9.813), stdev = 0.110
  CI (99.9%): [7.673, 11.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 8.038 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.080 ops/ms
Iteration   2: 9.482 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.345 ±(99.9%) 4.191 ops/ms [Average]
  (min, avg, max) = (9.080, 9.345, 9.482), stdev = 0.230
  CI (99.9%): [5.154, 13.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.650 ops/ms
# Warmup Iteration   2: 7.293 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.937 ±(99.9%) 0.322 ops/ms [Average]
  (min, avg, max) = (7.923, 7.937, 7.956), stdev = 0.018
  CI (99.9%): [7.615, 8.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.225 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.006 ms/op
Iteration   1: 3.417 ±(99.9%) 0.008 ms/op
Iteration   2: 3.348 ±(99.9%) 0.006 ms/op
Iteration   3: 3.349 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.372 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.348, 3.372, 3.417), stdev = 0.039
  CI (99.9%): [2.651, 4.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.241 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.004 ms/op
Iteration   1: 3.286 ±(99.9%) 0.005 ms/op
Iteration   2: 3.286 ±(99.9%) 0.008 ms/op
Iteration   3: 3.282 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.285 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (3.282, 3.285, 3.286), stdev = 0.002
  CI (99.9%): [3.242, 3.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.006 ms/op
Iteration   1: 3.373 ±(99.9%) 0.010 ms/op
Iteration   2: 3.362 ±(99.9%) 0.007 ms/op
Iteration   3: 3.267 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.334 ±(99.9%) 1.060 ms/op [Average]
  (min, avg, max) = (3.267, 3.334, 3.373), stdev = 0.058
  CI (99.9%): [2.274, 4.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.917 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.008 ms/op
Iteration   1: 4.090 ±(99.9%) 0.009 ms/op
Iteration   2: 4.025 ±(99.9%) 0.008 ms/op
Iteration   3: 3.934 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.016 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.934, 4.016, 4.090), stdev = 0.079
  CI (99.9%): [2.581, 5.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.013 ms/op
Iteration   1: 3.489 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  21.312 ms/op
                 createUser·p0.9999: 24.003 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.581 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  24.397 ms/op
                 createUser·p0.9999: 29.264 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   3: 3.613 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.265 ms/op
                 createUser·p0.999:  24.523 ms/op
                 createUser·p0.9999: 39.125 ms/op
                 createUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269705
  mean =      3.560 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8501 
    [ 2.500,  5.000) = 252610 
    [ 5.000,  7.500) = 7355 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     21.852 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     39.210 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.283 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 29.792 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   2: 3.247 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  10.181 ms/op
                 existUser·p0.9999: 25.826 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.275 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  20.328 ms/op
                 existUser·p0.9999: 28.720 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293255
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10129 
    [ 2.500,  5.000) = 277236 
    [ 5.000,  7.500) = 4899 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.749 ms/op
     p(99.9900) =     29.022 ms/op
     p(99.9990) =     31.824 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.177 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.606 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 29.496 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  24.161 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.436 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.763 ms/op
                 getUser·p0.9999: 30.389 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276358
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10508 
    [ 2.500,  5.000) = 255932 
    [ 5.000,  7.500) = 8517 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     29.646 ms/op
     p(99.9990) =     30.941 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.847 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.014 ms/op
Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  21.320 ms/op
                 listUser·p0.9999: 25.394 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.029 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  17.325 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242797
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 234909 
    [ 5.000,  7.500) = 5568 
    [ 7.500, 10.000) = 1390 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.793 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.363 ± 3.028  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 2.013  ops/ms
ClientPb.getUser                         thrpt       3   9.345 ± 4.191  ops/ms
ClientPb.listUser                        thrpt       3   7.937 ± 0.322  ops/ms
ClientPb.createUser                       avgt       3   3.372 ± 0.720   ms/op
ClientPb.existUser                        avgt       3   3.285 ± 0.043   ms/op
ClientPb.getUser                          avgt       3   3.334 ± 1.060   ms/op
ClientPb.listUser                         avgt       3   4.016 ± 1.435   ms/op
ClientPb.createUser                     sample  269705   3.560 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.401           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.852           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.977           ms/op
ClientPb.existUser                      sample  293255   3.273 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.503           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.749           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.022           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  276358   3.470 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.667           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.627           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.646           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392           ms/op
ClientPb.listUser                       sample  242797   3.951 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.367           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.019           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
