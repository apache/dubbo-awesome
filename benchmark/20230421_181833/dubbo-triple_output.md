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
# Warmup Iteration   1: 2.138 ops/ms
# Warmup Iteration   2: 5.783 ops/ms
# Warmup Iteration   3: 8.977 ops/ms
Iteration   1: 9.413 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 9.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.567 ±(99.9%) 2.557 ops/ms [Average]
  (min, avg, max) = (9.413, 9.567, 9.688), stdev = 0.140
  CI (99.9%): [7.009, 12.124] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 8.732 ops/ms
# Warmup Iteration   3: 9.362 ops/ms
Iteration   1: 10.020 ops/ms
Iteration   2: 9.551 ops/ms
Iteration   3: 9.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.743 ±(99.9%) 4.480 ops/ms [Average]
  (min, avg, max) = (9.551, 9.743, 10.020), stdev = 0.246
  CI (99.9%): [5.264, 14.223] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 9.316 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 8.817 ops/ms
Iteration   3: 9.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.167 ±(99.9%) 5.685 ops/ms [Average]
  (min, avg, max) = (8.817, 9.167, 9.416), stdev = 0.312
  CI (99.9%): [3.481, 14.852] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 7.285 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 7.857 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 7.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.814 ±(99.9%) 5.353 ops/ms [Average]
  (min, avg, max) = (7.501, 7.814, 8.083), stdev = 0.293
  CI (99.9%): [2.460, 13.167] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.470 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.010 ms/op
Iteration   2: 3.362 ±(99.9%) 0.010 ms/op
Iteration   3: 3.303 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.335 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.303, 3.335, 3.362), stdev = 0.030
  CI (99.9%): [2.792, 3.878] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.861 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.006 ms/op
Iteration   1: 3.218 ±(99.9%) 0.010 ms/op
Iteration   2: 3.321 ±(99.9%) 0.006 ms/op
Iteration   3: 3.283 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.274 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (3.218, 3.274, 3.321), stdev = 0.052
  CI (99.9%): [2.327, 4.221] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.518 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.005 ms/op
Iteration   1: 3.528 ±(99.9%) 0.004 ms/op
Iteration   2: 3.369 ±(99.9%) 0.007 ms/op
Iteration   3: 3.350 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (3.350, 3.416, 3.528), stdev = 0.098
  CI (99.9%): [1.634, 5.198] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.205 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
Iteration   2: 4.017 ±(99.9%) 0.012 ms/op
Iteration   3: 4.060 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.018 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.978, 4.018, 4.060), stdev = 0.041
  CI (99.9%): [3.268, 4.769] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.445 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.008 ms/op
Iteration   1: 3.528 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 22.210 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 25.420 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.415 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.158 ms/op
                 createUser·p0.999:  23.233 ms/op
                 createUser·p0.9999: 30.954 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275346
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6403 
    [ 2.500,  5.000) = 262600 
    [ 5.000,  7.500) = 5151 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     20.764 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     31.498 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.168 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.469 ms/op
                 existUser·p0.9999: 25.948 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  21.300 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.233 ms/op
                 existUser·p0.999:  13.353 ms/op
                 existUser·p0.9999: 31.132 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285798
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16489 
    [ 2.500,  5.000) = 261620 
    [ 5.000,  7.500) = 6654 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     29.865 ms/op
     p(99.9990) =     31.822 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.439 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  21.182 ms/op
                 getUser·p0.9999: 23.796 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.435 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  21.496 ms/op
                 getUser·p0.9999: 25.215 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  17.661 ms/op
                 getUser·p0.9999: 26.957 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280004
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1424 
    [ 2.500,  5.000) = 271458 
    [ 5.000,  7.500) = 5688 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     28.095 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.738 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.014 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  22.361 ms/op
                 listUser·p0.9999: 26.307 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  19.136 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.761 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241433
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 234301 
    [ 5.000,  7.500) = 4897 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      2.007 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     25.512 ms/op
     p(99.9990) =     27.058 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.567 ± 2.557  ops/ms
ClientPb.existUser                       thrpt       3   9.743 ± 4.480  ops/ms
ClientPb.getUser                         thrpt       3   9.167 ± 5.685  ops/ms
ClientPb.listUser                        thrpt       3   7.814 ± 5.353  ops/ms
ClientPb.createUser                       avgt       3   3.335 ± 0.543   ms/op
ClientPb.existUser                        avgt       3   3.274 ± 0.947   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 1.782   ms/op
ClientPb.listUser                         avgt       3   4.018 ± 0.751   ms/op
ClientPb.createUser                     sample  275346   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.764           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.001           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.621           ms/op
ClientPb.existUser                      sample  285798   3.360 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.723           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.865           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  280004   3.430 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.907           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.723           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  241433   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.007           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.169           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.512           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
