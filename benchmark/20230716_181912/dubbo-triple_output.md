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
# Warmup Iteration   1: 1.084 ops/ms
# Warmup Iteration   2: 2.539 ops/ms
# Warmup Iteration   3: 4.911 ops/ms
Iteration   1: 5.575 ops/ms
Iteration   2: 5.539 ops/ms
Iteration   3: 5.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.681 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (5.539, 5.681, 5.929), stdev = 0.216
  CI (99.9%): [1.745, 9.617] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.540 ops/ms
# Warmup Iteration   2: 4.509 ops/ms
# Warmup Iteration   3: 5.943 ops/ms
Iteration   1: 5.879 ops/ms
Iteration   2: 6.233 ops/ms
Iteration   3: 6.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.068 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (5.879, 6.068, 6.233), stdev = 0.178
  CI (99.9%): [2.819, 9.316] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.454 ops/ms
# Warmup Iteration   2: 4.251 ops/ms
# Warmup Iteration   3: 5.784 ops/ms
Iteration   1: 5.597 ops/ms
Iteration   2: 5.932 ops/ms
Iteration   3: 5.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.767 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (5.597, 5.767, 5.932), stdev = 0.168
  CI (99.9%): [2.709, 8.825] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.553 ops/ms
# Warmup Iteration   2: 4.032 ops/ms
# Warmup Iteration   3: 4.706 ops/ms
Iteration   1: 4.922 ops/ms
Iteration   2: 4.915 ops/ms
Iteration   3: 4.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.924 ±(99.9%) 0.185 ops/ms [Average]
  (min, avg, max) = (4.915, 4.924, 4.935), stdev = 0.010
  CI (99.9%): [4.739, 5.109] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.626 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.659 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.009 ms/op
Iteration   1: 5.385 ±(99.9%) 0.016 ms/op
Iteration   2: 5.411 ±(99.9%) 0.020 ms/op
Iteration   3: 5.408 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.401 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (5.385, 5.401, 5.411), stdev = 0.014
  CI (99.9%): [5.146, 5.657] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.548 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.804 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.476 ±(99.9%) 0.006 ms/op
Iteration   1: 5.343 ±(99.9%) 0.009 ms/op
Iteration   2: 5.175 ±(99.9%) 0.016 ms/op
Iteration   3: 5.103 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.207 ±(99.9%) 2.251 ms/op [Average]
  (min, avg, max) = (5.103, 5.207, 5.343), stdev = 0.123
  CI (99.9%): [2.957, 7.458] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.573 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.556 ±(99.9%) 0.011 ms/op
Iteration   1: 5.354 ±(99.9%) 0.012 ms/op
Iteration   2: 5.401 ±(99.9%) 0.010 ms/op
Iteration   3: 5.382 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.379 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (5.354, 5.379, 5.401), stdev = 0.023
  CI (99.9%): [4.955, 5.804] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.221 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 7.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.345 ±(99.9%) 0.019 ms/op
Iteration   1: 6.793 ±(99.9%) 0.017 ms/op
Iteration   2: 6.321 ±(99.9%) 0.014 ms/op
Iteration   3: 6.618 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.577 ±(99.9%) 4.351 ms/op [Average]
  (min, avg, max) = (6.321, 6.577, 6.793), stdev = 0.238
  CI (99.9%): [2.227, 10.928] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.858 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.792 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.305 ±(99.9%) 0.036 ms/op
Iteration   1: 5.591 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.834 ms/op
                 createUser·p0.99:   10.955 ms/op
                 createUser·p0.999:  26.060 ms/op
                 createUser·p0.9999: 29.364 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   2: 5.331 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  28.542 ms/op
                 createUser·p0.9999: 37.619 ms/op
                 createUser·p1.00:   38.666 ms/op

Iteration   3: 5.515 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.519 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  27.793 ms/op
                 createUser·p0.9999: 31.452 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175132
  mean =      5.477 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 70860 
    [ 5.000,  7.500) = 95113 
    [ 7.500, 10.000) = 6962 
    [10.000, 12.500) = 1391 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =     10.497 ms/op
     p(99.9000) =     26.562 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     38.420 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.629 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.498 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.022 ms/op
Iteration   1: 5.370 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  24.314 ms/op
                 existUser·p0.9999: 27.853 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 5.176 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   10.033 ms/op
                 existUser·p0.999:  16.286 ms/op
                 existUser·p0.9999: 33.674 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   3: 5.238 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.611 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  25.478 ms/op
                 existUser·p0.9999: 36.889 ms/op
                 existUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182445
  mean =      5.260 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 98275 
    [ 5.000,  7.500) = 75215 
    [ 7.500, 10.000) = 6891 
    [10.000, 12.500) = 1462 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     18.881 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     37.301 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.966 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.869 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.021 ms/op
Iteration   1: 5.668 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.962 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  25.387 ms/op
                 getUser·p0.9999: 40.136 ms/op
                 getUser·p1.00:   41.157 ms/op

Iteration   2: 5.530 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.511 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.554 ms/op
                 getUser·p0.95:   7.758 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  26.468 ms/op
                 getUser·p0.9999: 31.288 ms/op
                 getUser·p1.00:   31.523 ms/op

Iteration   3: 5.510 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.503 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   7.160 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  28.003 ms/op
                 getUser·p0.9999: 30.755 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172379
  mean =      5.568 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64271 
    [ 5.000, 10.000) = 104461 
    [10.000, 15.000) = 2919 
    [15.000, 20.000) = 483 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 124 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     25.940 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     40.635 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.889 ±(99.9%) 0.404 ms/op
# Warmup Iteration   2: 8.144 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.727 ±(99.9%) 0.030 ms/op
Iteration   1: 6.469 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  27.018 ms/op
                 listUser·p0.9999: 29.564 ms/op
                 listUser·p1.00:   30.376 ms/op

Iteration   2: 6.676 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.883 ms/op
                 listUser·p0.999:  32.149 ms/op
                 listUser·p0.9999: 35.717 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   3: 6.532 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   3.342 ms/op
                 listUser·p0.50:   6.087 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   14.370 ms/op
                 listUser·p0.999:  32.507 ms/op
                 listUser·p0.9999: 68.026 ms/op
                 listUser·p1.00:   73.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146431
  mean =      6.558 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6630 
    [ 5.000, 10.000) = 133910 
    [10.000, 15.000) = 4888 
    [15.000, 20.000) = 644 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 124 
    [30.000, 35.000) = 96 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 28 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     13.304 ms/op
     p(99.9000) =     29.631 ms/op
     p(99.9900) =     67.067 ms/op
     p(99.9990) =     70.966 ms/op
     p(99.9999) =     73.400 ms/op
    p(100.0000) =     73.400 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.681 ± 3.936  ops/ms
ClientPb.existUser                       thrpt       3   6.068 ± 3.249  ops/ms
ClientPb.getUser                         thrpt       3   5.767 ± 3.058  ops/ms
ClientPb.listUser                        thrpt       3   4.924 ± 0.185  ops/ms
ClientPb.createUser                       avgt       3   5.401 ± 0.255   ms/op
ClientPb.existUser                        avgt       3   5.207 ± 2.251   ms/op
ClientPb.getUser                          avgt       3   5.379 ± 0.424   ms/op
ClientPb.listUser                         avgt       3   6.577 ± 4.351   ms/op
ClientPb.createUser                     sample  175132   5.477 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.195           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.979           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.666           ms/op
ClientPb.existUser                      sample  182445   5.260 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.482           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.463           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.289           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.356           ms/op
ClientPb.getUser                        sample  172379   5.568 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.567           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.339           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.157           ms/op
ClientPb.listUser                       sample  146431   6.558 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.618           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          67.067           ms/op
ClientPb.listUser:listUser·p1.00        sample          73.400           ms/op
