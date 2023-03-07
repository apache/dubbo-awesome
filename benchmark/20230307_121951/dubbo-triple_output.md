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
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 5.252 ops/ms
# Warmup Iteration   3: 8.425 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 9.223 ops/ms
Iteration   3: 9.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.279 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (9.182, 9.279, 9.432), stdev = 0.134
  CI (99.9%): [6.834, 11.724] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.222 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 8.977 ops/ms
Iteration   1: 9.823 ops/ms
Iteration   2: 9.419 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.678 ±(99.9%) 4.103 ops/ms [Average]
  (min, avg, max) = (9.419, 9.678, 9.823), stdev = 0.225
  CI (99.9%): [5.575, 13.781] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.853 ops/ms
# Warmup Iteration   2: 8.092 ops/ms
# Warmup Iteration   3: 8.911 ops/ms
Iteration   1: 9.062 ops/ms
Iteration   2: 9.104 ops/ms
Iteration   3: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.059 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (9.012, 9.059, 9.104), stdev = 0.046
  CI (99.9%): [8.222, 9.896] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.456 ops/ms
# Warmup Iteration   2: 6.866 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.032 ±(99.9%) 1.558 ops/ms [Average]
  (min, avg, max) = (7.945, 8.032, 8.116), stdev = 0.085
  CI (99.9%): [6.474, 9.591] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.652 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
Iteration   3: 3.481 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.441 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.413, 3.441, 3.481), stdev = 0.036
  CI (99.9%): [2.793, 4.089] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.167 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
Iteration   1: 3.402 ±(99.9%) 0.006 ms/op
Iteration   2: 3.376 ±(99.9%) 0.009 ms/op
Iteration   3: 3.323 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.323, 3.367, 3.402), stdev = 0.040
  CI (99.9%): [2.632, 4.101] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.752 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.004 ms/op
Iteration   2: 3.486 ±(99.9%) 0.006 ms/op
Iteration   3: 3.401 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.475 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (3.401, 3.475, 3.537), stdev = 0.069
  CI (99.9%): [2.219, 4.730] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.671 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.009 ms/op
Iteration   1: 4.108 ±(99.9%) 0.008 ms/op
Iteration   2: 4.064 ±(99.9%) 0.007 ms/op
Iteration   3: 3.970 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.047 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.970, 4.047, 4.108), stdev = 0.070
  CI (99.9%): [2.764, 5.331] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.533 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.013 ms/op
Iteration   1: 3.594 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 22.814 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  21.827 ms/op
                 createUser·p0.9999: 26.244 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  19.390 ms/op
                 createUser·p0.9999: 26.741 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273090
  mean =      3.512 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3582 
    [ 2.500,  5.000) = 263884 
    [ 5.000,  7.500) = 4551 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     20.444 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.739 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.612 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
Iteration   1: 3.439 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  20.021 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.458 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  13.509 ms/op
                 existUser·p0.9999: 30.594 ms/op
                 existUser·p1.00:   32.342 ms/op

Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.829 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.716 ms/op
                 existUser·p0.9999: 28.164 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287678
  mean =      3.336 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18923 
    [ 2.500,  5.000) = 262461 
    [ 5.000,  7.500) = 5245 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.734 ms/op
     p(99.9900) =     28.876 ms/op
     p(99.9990) =     31.236 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 9.011 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.011 ms/op
Iteration   1: 3.676 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 20.490 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 24.548 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  18.299 ms/op
                 getUser·p0.9999: 25.601 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273438
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3301 
    [ 2.500,  5.000) = 259143 
    [ 5.000,  7.500) = 9553 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     18.157 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     27.206 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 10.244 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.012 ms/op
Iteration   1: 4.199 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 23.086 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   2: 4.110 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.852 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.993 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.042 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233970
  mean =      4.099 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 224428 
    [ 5.000,  7.500) = 6639 
    [ 7.500, 10.000) = 2023 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     16.975 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     24.061 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.279 ± 2.445  ops/ms
ClientPb.existUser                       thrpt       3   9.678 ± 4.103  ops/ms
ClientPb.getUser                         thrpt       3   9.059 ± 0.837  ops/ms
ClientPb.listUser                        thrpt       3   8.032 ± 1.558  ops/ms
ClientPb.createUser                       avgt       3   3.441 ± 0.648   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 0.735   ms/op
ClientPb.getUser                          avgt       3   3.475 ± 1.256   ms/op
ClientPb.listUser                         avgt       3   4.047 ± 1.283   ms/op
ClientPb.createUser                     sample  273090   3.512 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.444           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  287678   3.336 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.876           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.342           ms/op
ClientPb.getUser                        sample  273438   3.509 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.157           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.642           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  233970   4.099 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.186           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.975           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.395           ms/op
