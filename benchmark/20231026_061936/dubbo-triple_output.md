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
# Warmup Iteration   1: 1.020 ops/ms
# Warmup Iteration   2: 2.134 ops/ms
# Warmup Iteration   3: 4.738 ops/ms
Iteration   1: 5.334 ops/ms
Iteration   2: 5.687 ops/ms
Iteration   3: 5.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.624 ±(99.9%) 4.805 ops/ms [Average]
  (min, avg, max) = (5.334, 5.624, 5.850), stdev = 0.263
  CI (99.9%): [0.819, 10.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 5.161 ops/ms
# Warmup Iteration   3: 6.027 ops/ms
Iteration   1: 5.965 ops/ms
Iteration   2: 6.040 ops/ms
Iteration   3: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.995 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (5.965, 5.995, 6.040), stdev = 0.039
  CI (99.9%): [5.278, 6.712] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.615 ops/ms
# Warmup Iteration   2: 4.980 ops/ms
# Warmup Iteration   3: 5.902 ops/ms
Iteration   1: 5.710 ops/ms
Iteration   2: 5.768 ops/ms
Iteration   3: 5.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.717 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (5.673, 5.717, 5.768), stdev = 0.048
  CI (99.9%): [4.845, 6.588] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.700 ops/ms
# Warmup Iteration   2: 4.280 ops/ms
# Warmup Iteration   3: 4.726 ops/ms
Iteration   1: 4.780 ops/ms
Iteration   2: 4.947 ops/ms
Iteration   3: 4.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.904 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (4.780, 4.904, 4.985), stdev = 0.109
  CI (99.9%): [2.918, 6.889] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.341 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.735 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.826 ±(99.9%) 0.008 ms/op
Iteration   1: 5.539 ±(99.9%) 0.010 ms/op
Iteration   2: 5.384 ±(99.9%) 0.009 ms/op
Iteration   3: 5.550 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.491 ±(99.9%) 1.685 ms/op [Average]
  (min, avg, max) = (5.384, 5.491, 5.550), stdev = 0.092
  CI (99.9%): [3.806, 7.176] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.360 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.530 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.006 ms/op
Iteration   1: 5.335 ±(99.9%) 0.009 ms/op
Iteration   2: 5.314 ±(99.9%) 0.009 ms/op
Iteration   3: 5.421 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.357 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (5.314, 5.357, 5.421), stdev = 0.057
  CI (99.9%): [4.317, 6.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.099 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.175 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.633 ±(99.9%) 0.006 ms/op
Iteration   1: 5.603 ±(99.9%) 0.005 ms/op
Iteration   2: 5.501 ±(99.9%) 0.008 ms/op
Iteration   3: 5.461 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.522 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (5.461, 5.522, 5.603), stdev = 0.074
  CI (99.9%): [4.180, 6.863] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.736 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.328 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.613 ±(99.9%) 0.009 ms/op
Iteration   1: 6.836 ±(99.9%) 0.007 ms/op
Iteration   2: 6.592 ±(99.9%) 0.014 ms/op
Iteration   3: 6.426 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.618 ±(99.9%) 3.764 ms/op [Average]
  (min, avg, max) = (6.426, 6.618, 6.836), stdev = 0.206
  CI (99.9%): [2.855, 10.382] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.782 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.844 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.102 ±(99.9%) 0.026 ms/op
Iteration   1: 5.611 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.458 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  24.968 ms/op
                 createUser·p0.9999: 26.529 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 5.598 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  27.132 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   39.256 ms/op

Iteration   3: 5.649 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.520 ms/op
                 createUser·p0.99:   10.556 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 32.702 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170608
  mean =      5.619 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 48072 
    [ 5.000,  7.500) = 114236 
    [ 7.500, 10.000) = 6379 
    [10.000, 12.500) = 1329 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     25.310 ms/op
     p(99.9900) =     32.465 ms/op
     p(99.9990) =     39.256 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.510 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 5.667 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.018 ms/op
Iteration   1: 5.313 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.864 ms/op
                 existUser·p0.99:   10.908 ms/op
                 existUser·p0.999:  25.166 ms/op
                 existUser·p0.9999: 32.866 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   2: 5.331 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.510 ms/op
                 existUser·p0.99:   11.157 ms/op
                 existUser·p0.999:  24.251 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.556 ms/op

Iteration   3: 5.247 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  19.037 ms/op
                 existUser·p0.9999: 31.057 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181177
  mean =      5.296 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 92069 
    [ 5.000,  7.500) = 80336 
    [ 7.500, 10.000) = 6021 
    [10.000, 12.500) = 1690 
    [12.500, 15.000) = 554 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     21.494 ms/op
     p(99.9900) =     32.007 ms/op
     p(99.9990) =     33.055 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.857 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.019 ms/op
Iteration   1: 5.592 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.687 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.414 ms/op
                 getUser·p0.95:   7.594 ms/op
                 getUser·p0.99:   12.473 ms/op
                 getUser·p0.999:  22.544 ms/op
                 getUser·p0.9999: 26.958 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 5.677 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   11.305 ms/op
                 getUser·p0.999:  24.497 ms/op
                 getUser·p0.9999: 28.389 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 5.549 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.929 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   11.235 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 30.816 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171204
  mean =      5.605 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 48464 
    [ 5.000,  7.500) = 113548 
    [ 7.500, 10.000) = 5952 
    [10.000, 12.500) = 1988 
    [12.500, 15.000) = 754 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     29.676 ms/op
     p(99.9990) =     31.389 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.502 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 8.047 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.610 ±(99.9%) 0.023 ms/op
Iteration   1: 6.564 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.879 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  29.925 ms/op
                 listUser·p0.9999: 37.504 ms/op
                 listUser·p1.00:   37.945 ms/op

Iteration   2: 6.450 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.187 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.711 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  30.062 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   3: 6.514 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  25.543 ms/op
                 listUser·p0.9999: 29.334 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147354
  mean =      6.509 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 3732 
    [ 5.000,  7.500) = 126786 
    [ 7.500, 10.000) = 12598 
    [10.000, 12.500) = 2753 
    [12.500, 15.000) = 851 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.347 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.517 ms/op
     p(99.9000) =     28.202 ms/op
     p(99.9900) =     35.507 ms/op
     p(99.9990) =     37.883 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.624 ± 4.805  ops/ms
ClientPb.existUser                       thrpt       3   5.995 ± 0.717  ops/ms
ClientPb.getUser                         thrpt       3   5.717 ± 0.871  ops/ms
ClientPb.listUser                        thrpt       3   4.904 ± 1.985  ops/ms
ClientPb.createUser                       avgt       3   5.491 ± 1.685   ms/op
ClientPb.existUser                        avgt       3   5.357 ± 1.039   ms/op
ClientPb.getUser                          avgt       3   5.522 ± 1.341   ms/op
ClientPb.listUser                         avgt       3   6.618 ± 3.764   ms/op
ClientPb.createUser                     sample  170608   5.619 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.755           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.463           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.191           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.310           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.465           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.256           ms/op
ClientPb.existUser                      sample  181177   5.296 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.346           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.414           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.494           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.007           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  171204   5.605 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.105           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.518           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.675           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.676           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  147354   6.509 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.347           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.517           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.202           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.507           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.945           ms/op
