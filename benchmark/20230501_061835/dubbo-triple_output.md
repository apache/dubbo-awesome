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
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 5.790 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 9.118 ops/ms
Iteration   2: 9.277 ops/ms
Iteration   3: 9.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.330 ±(99.9%) 4.443 ops/ms [Average]
  (min, avg, max) = (9.118, 9.330, 9.596), stdev = 0.244
  CI (99.9%): [4.887, 13.773] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.482 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 9.603 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.711 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (9.603, 9.711, 9.855), stdev = 0.130
  CI (99.9%): [7.341, 12.080] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 8.391 ops/ms
# Warmup Iteration   3: 9.122 ops/ms
Iteration   1: 9.381 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 8.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.202 ±(99.9%) 4.186 ops/ms [Average]
  (min, avg, max) = (8.943, 9.202, 9.381), stdev = 0.229
  CI (99.9%): [5.016, 13.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.894 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.801 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (7.702, 7.801, 7.931), stdev = 0.118
  CI (99.9%): [5.648, 9.953] (assumes normal distribution)


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
# Warmup Iteration   1: 9.743 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.007 ms/op
Iteration   1: 3.507 ±(99.9%) 0.008 ms/op
Iteration   2: 3.443 ±(99.9%) 0.009 ms/op
Iteration   3: 3.488 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.443, 3.479, 3.507), stdev = 0.033
  CI (99.9%): [2.878, 4.080] (assumes normal distribution)


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
# Warmup Iteration   1: 8.491 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.007 ms/op
Iteration   1: 3.366 ±(99.9%) 0.004 ms/op
Iteration   2: 3.309 ±(99.9%) 0.004 ms/op
Iteration   3: 3.356 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.344 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.309, 3.344, 3.366), stdev = 0.030
  CI (99.9%): [2.790, 3.897] (assumes normal distribution)


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
# Warmup Iteration   1: 9.343 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.003 ms/op
Iteration   1: 3.457 ±(99.9%) 0.003 ms/op
Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
Iteration   3: 3.521 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.497 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.457, 3.497, 3.521), stdev = 0.034
  CI (99.9%): [2.871, 4.122] (assumes normal distribution)


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
# Warmup Iteration   1: 10.933 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.004 ms/op
Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
Iteration   3: 3.982 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.033 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.982, 4.033, 4.064), stdev = 0.045
  CI (99.9%): [3.212, 4.854] (assumes normal distribution)


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
# Warmup Iteration   1: 9.988 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
Iteration   1: 3.620 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  21.234 ms/op
                 createUser·p0.9999: 22.943 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.431 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  22.340 ms/op
                 createUser·p0.9999: 31.534 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.223 ms/op
                 createUser·p0.999:  15.662 ms/op
                 createUser·p0.9999: 27.151 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275635
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11635 
    [ 2.500,  5.000) = 254836 
    [ 5.000,  7.500) = 7841 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     21.278 ms/op
     p(99.9900) =     30.423 ms/op
     p(99.9990) =     31.768 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 7.817 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
Iteration   1: 3.277 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 23.756 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.790 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  12.637 ms/op
                 existUser·p0.9999: 25.437 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  18.537 ms/op
                 existUser·p0.9999: 27.155 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289195
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5780 
    [ 2.500,  5.000) = 277348 
    [ 5.000,  7.500) = 5106 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.782 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.010 ms/op
Iteration   1: 3.631 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   2: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  21.872 ms/op
                 getUser·p0.9999: 24.919 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270747
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3159 
    [ 2.500,  5.000) = 257272 
    [ 5.000,  7.500) = 8735 
    [ 7.500, 10.000) = 1108 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     19.309 ms/op
     p(99.9900) =     26.867 ms/op
     p(99.9990) =     28.513 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 11.085 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 29.566 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   2: 3.978 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 18.742 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.059 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.574 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 15.548 ms/op
                 listUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236382
  mean =      4.057 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 228844 
    [ 5.000,  7.500) = 5225 
    [ 7.500, 10.000) = 1443 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.399 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     26.554 ms/op
     p(99.9990) =     30.528 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.330 ± 4.443  ops/ms
ClientPb.existUser                       thrpt       3   9.711 ± 2.369  ops/ms
ClientPb.getUser                         thrpt       3   9.202 ± 4.186  ops/ms
ClientPb.listUser                        thrpt       3   7.801 ± 2.152  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 0.601   ms/op
ClientPb.existUser                        avgt       3   3.344 ± 0.553   ms/op
ClientPb.getUser                          avgt       3   3.497 ± 0.626   ms/op
ClientPb.listUser                         avgt       3   4.033 ± 0.821   ms/op
ClientPb.createUser                     sample  275635   3.482 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.423           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  289195   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.397           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.625           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  270747   3.542 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.991           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.309           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.867           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  236382   4.057 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.399           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.532           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.867           ms/op
