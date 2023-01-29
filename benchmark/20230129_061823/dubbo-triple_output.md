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
# Warmup Iteration   2: 5.236 ops/ms
# Warmup Iteration   3: 8.915 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 8.959 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.217 ±(99.9%) 4.388 ops/ms [Average]
  (min, avg, max) = (8.959, 9.217, 9.435), stdev = 0.241
  CI (99.9%): [4.829, 13.605] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.788 ops/ms
# Warmup Iteration   2: 8.447 ops/ms
# Warmup Iteration   3: 8.953 ops/ms
Iteration   1: 9.694 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.454 ±(99.9%) 4.792 ops/ms [Average]
  (min, avg, max) = (9.173, 9.454, 9.694), stdev = 0.263
  CI (99.9%): [4.663, 14.246] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.716 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.020 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.316 ±(99.9%) 4.675 ops/ms [Average]
  (min, avg, max) = (9.020, 9.316, 9.470), stdev = 0.256
  CI (99.9%): [4.641, 13.991] (assumes normal distribution)


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
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 6.892 ops/ms
# Warmup Iteration   3: 7.884 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 7.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.963 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (7.827, 7.963, 8.067), stdev = 0.123
  CI (99.9%): [5.721, 10.205] (assumes normal distribution)


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
# Warmup Iteration   1: 9.431 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.007 ms/op
Iteration   1: 3.629 ±(99.9%) 0.004 ms/op
Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
Iteration   3: 3.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 2.700 ms/op [Average]
  (min, avg, max) = (3.365, 3.459, 3.629), stdev = 0.148
  CI (99.9%): [0.759, 6.158] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.348 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.006 ms/op
Iteration   1: 3.207 ±(99.9%) 0.007 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.360 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.207, 3.308, 3.360), stdev = 0.087
  CI (99.9%): [1.716, 4.901] (assumes normal distribution)


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
# Warmup Iteration   1: 8.802 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.008 ms/op
Iteration   1: 3.390 ±(99.9%) 0.004 ms/op
Iteration   2: 3.418 ±(99.9%) 0.005 ms/op
Iteration   3: 3.517 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.442 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (3.390, 3.442, 3.517), stdev = 0.067
  CI (99.9%): [2.226, 4.658] (assumes normal distribution)


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
# Warmup Iteration   1: 10.584 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
Iteration   1: 4.075 ±(99.9%) 0.008 ms/op
Iteration   2: 3.855 ±(99.9%) 0.013 ms/op
Iteration   3: 3.911 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.947 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (3.855, 3.947, 4.075), stdev = 0.114
  CI (99.9%): [1.867, 6.027] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.605 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.015 ms/op
Iteration   1: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  22.987 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 3.651 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  26.116 ms/op
                 createUser·p0.9999: 29.696 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 3.449 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 35.972 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271816
  mean =      3.530 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3700 
    [ 2.500,  5.000) = 260957 
    [ 5.000,  7.500) = 5878 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     23.873 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     36.672 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 8.916 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  20.447 ms/op
                 existUser·p0.9999: 23.053 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.383 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  21.962 ms/op
                 existUser·p0.9999: 24.383 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  10.059 ms/op
                 existUser·p0.9999: 27.735 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285370
  mean =      3.365 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7899 
    [ 2.500,  5.000) = 272819 
    [ 5.000,  7.500) = 3855 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.989 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 10.813 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.014 ms/op
Iteration   1: 3.588 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  13.840 ms/op
                 getUser·p0.9999: 42.603 ms/op
                 getUser·p1.00:   43.385 ms/op

Iteration   2: 3.728 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  23.771 ms/op
                 getUser·p0.9999: 34.565 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 3.579 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  22.816 ms/op
                 getUser·p0.9999: 33.034 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264399
  mean =      3.630 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 252469 
    [ 5.000, 10.000) = 11470 
    [10.000, 15.000) = 204 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 98 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     40.050 ms/op
     p(99.9990) =     43.080 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


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
# Warmup Iteration   1: 11.657 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.015 ms/op
Iteration   1: 4.285 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  23.579 ms/op
                 listUser·p0.9999: 30.199 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235406
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 224772 
    [ 5.000,  7.500) = 8041 
    [ 7.500, 10.000) = 1683 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 259 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     16.829 ms/op
     p(99.9900) =     29.388 ms/op
     p(99.9990) =     31.311 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.217 ± 4.388  ops/ms
ClientPb.existUser                       thrpt       3   9.454 ± 4.792  ops/ms
ClientPb.getUser                         thrpt       3   9.316 ± 4.675  ops/ms
ClientPb.listUser                        thrpt       3   7.963 ± 2.242  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 2.700   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 1.593   ms/op
ClientPb.getUser                          avgt       3   3.442 ± 1.216   ms/op
ClientPb.listUser                         avgt       3   3.947 ± 2.080   ms/op
ClientPb.createUser                     sample  271816   3.530 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.360           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  285370   3.365 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.542           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  264399   3.630 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.196           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.336           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.050           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.385           ms/op
ClientPb.listUser                       sample  235406   4.075 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.493           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.829           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.388           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.490           ms/op
