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
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 4.834 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 8.470 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.273 ±(99.9%) 4.535 ops/ms [Average]
  (min, avg, max) = (7.994, 8.273, 8.470), stdev = 0.249
  CI (99.9%): [3.738, 12.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.588 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.430 ops/ms
Iteration   3: 8.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.643 ±(99.9%) 3.797 ops/ms [Average]
  (min, avg, max) = (8.430, 8.643, 8.846), stdev = 0.208
  CI (99.9%): [4.846, 12.439] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.802 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 8.212 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.349 ±(99.9%) 2.169 ops/ms [Average]
  (min, avg, max) = (8.212, 8.349, 8.425), stdev = 0.119
  CI (99.9%): [6.179, 10.518] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.462 ops/ms
# Warmup Iteration   2: 6.140 ops/ms
# Warmup Iteration   3: 6.838 ops/ms
Iteration   1: 7.269 ops/ms
Iteration   2: 7.064 ops/ms
Iteration   3: 7.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.142 ±(99.9%) 2.029 ops/ms [Average]
  (min, avg, max) = (7.064, 7.142, 7.269), stdev = 0.111
  CI (99.9%): [5.113, 9.170] (assumes normal distribution)


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
# Warmup Iteration   1: 11.435 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.013 ms/op
Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
Iteration   2: 3.751 ±(99.9%) 0.011 ms/op
Iteration   3: 3.624 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.757 ±(99.9%) 2.485 ms/op [Average]
  (min, avg, max) = (3.624, 3.757, 3.897), stdev = 0.136
  CI (99.9%): [1.272, 6.243] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.630 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.008 ms/op
Iteration   1: 3.620 ±(99.9%) 0.012 ms/op
Iteration   2: 3.660 ±(99.9%) 0.007 ms/op
Iteration   3: 3.657 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.645 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.620, 3.645, 3.660), stdev = 0.022
  CI (99.9%): [3.237, 4.054] (assumes normal distribution)


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
# Warmup Iteration   1: 12.903 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.008 ms/op
Iteration   1: 3.873 ±(99.9%) 0.005 ms/op
Iteration   2: 3.785 ±(99.9%) 0.015 ms/op
Iteration   3: 3.830 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.829 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.785, 3.829, 3.873), stdev = 0.044
  CI (99.9%): [3.029, 4.629] (assumes normal distribution)


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
# Warmup Iteration   1: 12.001 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.486 ±(99.9%) 0.009 ms/op
Iteration   1: 4.437 ±(99.9%) 0.012 ms/op
Iteration   2: 4.577 ±(99.9%) 0.008 ms/op
Iteration   3: 4.493 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.502 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (4.437, 4.502, 4.577), stdev = 0.070
  CI (99.9%): [3.221, 5.784] (assumes normal distribution)


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
# Warmup Iteration   1: 13.215 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.751 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.015 ms/op
Iteration   1: 3.891 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  14.660 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  25.428 ms/op
                 createUser·p0.9999: 27.650 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.876 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  23.362 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246485
  mean =      3.891 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 696 
    [ 2.500,  5.000) = 234434 
    [ 5.000,  7.500) = 9480 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     22.743 ms/op
     p(99.9900) =     29.514 ms/op
     p(99.9990) =     31.835 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.257 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.011 ms/op
Iteration   1: 3.767 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.534 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  23.560 ms/op
                 existUser·p0.9999: 27.865 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260395
  mean =      3.685 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2234 
    [ 2.500,  5.000) = 250577 
    [ 5.000,  7.500) = 6435 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     25.951 ms/op
     p(99.9990) =     28.225 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 10.208 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.016 ms/op
Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 23.978 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.895 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  27.717 ms/op
                 getUser·p0.9999: 40.684 ms/op
                 getUser·p1.00:   41.353 ms/op

Iteration   3: 3.755 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  13.366 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249768
  mean =      3.842 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 238513 
    [ 5.000, 10.000) = 10767 
    [10.000, 15.000) = 264 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.308 ms/op
     p(99.9900) =     38.994 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


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
# Warmup Iteration   1: 13.548 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.201 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.016 ms/op
Iteration   1: 4.455 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  24.904 ms/op
                 listUser·p0.9999: 31.657 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   2: 4.483 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 19.672 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.578 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.558 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.442 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212969
  mean =      4.505 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 189935 
    [ 5.000,  7.500) = 19572 
    [ 7.500, 10.000) = 2589 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     28.730 ms/op
     p(99.9990) =     33.050 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.273 ± 4.535  ops/ms
ClientPb.existUser                       thrpt       3   8.643 ± 3.797  ops/ms
ClientPb.getUser                         thrpt       3   8.349 ± 2.169  ops/ms
ClientPb.listUser                        thrpt       3   7.142 ± 2.029  ops/ms
ClientPb.createUser                       avgt       3   3.757 ± 2.485   ms/op
ClientPb.existUser                        avgt       3   3.645 ± 0.408   ms/op
ClientPb.getUser                          avgt       3   3.829 ± 0.800   ms/op
ClientPb.listUser                         avgt       3   4.502 ± 1.282   ms/op
ClientPb.createUser                     sample  246485   3.891 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.127           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.743           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.514           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  260395   3.685 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  249768   3.842 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.569           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.308           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.994           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.353           ms/op
ClientPb.listUser                       sample  212969   4.505 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.730           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.128           ms/op
