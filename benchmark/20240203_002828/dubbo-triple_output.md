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
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 11.966 ops/ms
# Warmup Iteration   3: 12.410 ops/ms
Iteration   1: 12.830 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.749 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (12.678, 12.749, 12.830), stdev = 0.076
  CI (99.9%): [11.355, 14.143] (assumes normal distribution)


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
# Warmup Iteration   1: 8.547 ops/ms
# Warmup Iteration   2: 13.333 ops/ms
# Warmup Iteration   3: 13.322 ops/ms
Iteration   1: 13.310 ops/ms
Iteration   2: 13.342 ops/ms
Iteration   3: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.283 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (13.197, 13.283, 13.342), stdev = 0.076
  CI (99.9%): [11.888, 14.678] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 12.547 ops/ms
# Warmup Iteration   3: 12.923 ops/ms
Iteration   1: 12.971 ops/ms
Iteration   2: 12.778 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.822 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (12.718, 12.822, 12.971), stdev = 0.132
  CI (99.9%): [10.415, 15.230] (assumes normal distribution)


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
# Warmup Iteration   1: 6.724 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.816 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.813 ±(99.9%) 0.366 ops/ms [Average]
  (min, avg, max) = (10.791, 10.813, 10.831), stdev = 0.020
  CI (99.9%): [10.447, 11.179] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.487, 2.494, 2.503), stdev = 0.008
  CI (99.9%): [2.346, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.439, 2.442, 2.446), stdev = 0.004
  CI (99.9%): [2.377, 2.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.449 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.438, 2.449, 2.465), stdev = 0.014
  CI (99.9%): [2.192, 2.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
Iteration   2: 2.957 ±(99.9%) 0.007 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.949, 2.958, 2.968), stdev = 0.010
  CI (99.9%): [2.782, 3.134] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  10.006 ms/op
                 createUser·p0.9999: 14.585 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  8.899 ms/op
                 createUser·p0.9999: 12.536 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.060 ms/op
                 createUser·p0.9999: 10.562 ms/op
                 createUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385124
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 187650 
    [ 2.500,  3.750) = 194241 
    [ 3.750,  5.000) = 2505 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      8.060 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     15.387 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 12.877 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.761 ms/op
                 existUser·p0.9999: 14.530 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393783
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 197114 
    [ 2.500,  3.750) = 193248 
    [ 3.750,  5.000) = 2545 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      6.598 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     15.238 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  5.518 ms/op
                 getUser·p0.9999: 13.904 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  8.482 ms/op
                 getUser·p0.9999: 14.013 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  8.299 ms/op
                 getUser·p0.9999: 11.489 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379921
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 187007 
    [ 2.500,  3.750) = 186472 
    [ 3.750,  5.000) = 4607 
    [ 5.000,  6.250) = 1251 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.357 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.175 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.008 ms/op
Iteration   1: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 12.147 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 2.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.740 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.045 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   3: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.335 ms/op
                 listUser·p0.9999: 11.288 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325169
  mean =      2.948 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 105036 
    [ 2.500,  3.750) = 185244 
    [ 3.750,  5.000) = 28164 
    [ 5.000,  6.250) = 5225 
    [ 6.250,  7.500) = 653 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     12.017 ms/op
     p(99.9990) =     18.375 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.749 ± 1.394  ops/ms
ClientPb.existUser                       thrpt       3  13.283 ± 1.395  ops/ms
ClientPb.getUser                         thrpt       3  12.822 ± 2.407  ops/ms
ClientPb.listUser                        thrpt       3  10.813 ± 0.366  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.148   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.065   ms/op
ClientPb.getUser                          avgt       3   2.449 ± 0.256   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.176   ms/op
ClientPb.createUser                     sample  385124   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.484           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.663           ms/op
ClientPb.existUser                      sample  393783   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.598           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.303           ms/op
ClientPb.getUser                        sample  379921   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.690           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.357           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  325169   2.948 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.842           ms/op
