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
# Warmup Iteration   1: 1.072 ops/ms
# Warmup Iteration   2: 2.349 ops/ms
# Warmup Iteration   3: 4.969 ops/ms
Iteration   1: 5.206 ops/ms
Iteration   2: 5.258 ops/ms
Iteration   3: 5.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.241 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (5.206, 5.241, 5.260), stdev = 0.030
  CI (99.9%): [4.685, 5.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.755 ops/ms
# Warmup Iteration   2: 4.328 ops/ms
# Warmup Iteration   3: 5.513 ops/ms
Iteration   1: 5.359 ops/ms
Iteration   2: 5.183 ops/ms
Iteration   3: 5.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.347 ±(99.9%) 2.903 ops/ms [Average]
  (min, avg, max) = (5.183, 5.347, 5.500), stdev = 0.159
  CI (99.9%): [2.445, 8.250] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 4.811 ops/ms
# Warmup Iteration   3: 5.490 ops/ms
Iteration   1: 5.622 ops/ms
Iteration   2: 5.933 ops/ms
Iteration   3: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.825 ±(99.9%) 3.200 ops/ms [Average]
  (min, avg, max) = (5.622, 5.825, 5.933), stdev = 0.175
  CI (99.9%): [2.624, 9.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 4.036 ops/ms
# Warmup Iteration   3: 4.482 ops/ms
Iteration   1: 4.612 ops/ms
Iteration   2: 4.550 ops/ms
Iteration   3: 4.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.564 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (4.530, 4.564, 4.612), stdev = 0.043
  CI (99.9%): [3.780, 5.348] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.545 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 6.918 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.122 ±(99.9%) 0.013 ms/op
Iteration   1: 6.215 ±(99.9%) 0.009 ms/op
Iteration   2: 6.040 ±(99.9%) 0.010 ms/op
Iteration   3: 5.975 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.077 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (5.975, 6.077, 6.215), stdev = 0.124
  CI (99.9%): [3.814, 8.340] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.673 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.824 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.730 ±(99.9%) 0.015 ms/op
Iteration   1: 5.459 ±(99.9%) 0.017 ms/op
Iteration   2: 5.533 ±(99.9%) 0.011 ms/op
Iteration   3: 5.418 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.470 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (5.418, 5.470, 5.533), stdev = 0.058
  CI (99.9%): [4.413, 6.528] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.639 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.447 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.917 ±(99.9%) 0.009 ms/op
Iteration   1: 6.192 ±(99.9%) 0.012 ms/op
Iteration   2: 5.749 ±(99.9%) 0.010 ms/op
Iteration   3: 5.794 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.912 ±(99.9%) 4.442 ms/op [Average]
  (min, avg, max) = (5.749, 5.912, 6.192), stdev = 0.243
  CI (99.9%): [1.470, 10.353] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.656 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 8.568 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.803 ±(99.9%) 0.012 ms/op
Iteration   1: 7.080 ±(99.9%) 0.013 ms/op
Iteration   2: 6.834 ±(99.9%) 0.015 ms/op
Iteration   3: 6.660 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.858 ±(99.9%) 3.851 ms/op [Average]
  (min, avg, max) = (6.660, 6.858, 7.080), stdev = 0.211
  CI (99.9%): [3.007, 10.709] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.337 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 8.186 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.392 ±(99.9%) 0.028 ms/op
Iteration   1: 5.700 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.184 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  23.384 ms/op
                 createUser·p0.9999: 28.120 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 6.060 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.849 ms/op
                 createUser·p0.90:   7.627 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   10.742 ms/op
                 createUser·p0.999:  30.623 ms/op
                 createUser·p0.9999: 38.583 ms/op
                 createUser·p1.00:   40.108 ms/op

Iteration   3: 6.094 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.931 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   8.208 ms/op
                 createUser·p0.99:   10.099 ms/op
                 createUser·p0.999:  27.939 ms/op
                 createUser·p0.9999: 34.587 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161316
  mean =      5.946 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 41001 
    [ 5.000, 10.000) = 118228 
    [10.000, 15.000) = 1675 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 79 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.743 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     10.385 ms/op
     p(99.9000) =     26.696 ms/op
     p(99.9900) =     36.216 ms/op
     p(99.9990) =     40.028 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.148 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 6.795 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.660 ±(99.9%) 0.020 ms/op
Iteration   1: 5.643 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   5.579 ms/op
                 existUser·p0.90:   6.840 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  20.927 ms/op
                 existUser·p0.9999: 32.134 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   2: 5.671 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.443 ms/op
                 existUser·p0.95:   8.208 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  19.399 ms/op
                 existUser·p0.9999: 26.685 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 5.527 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  27.606 ms/op
                 existUser·p0.9999: 34.529 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170953
  mean =      5.613 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 61261 
    [ 5.000,  7.500) = 98232 
    [ 7.500, 10.000) = 9479 
    [10.000, 12.500) = 1393 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     21.006 ms/op
     p(99.9900) =     32.529 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.630 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 7.117 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.022 ±(99.9%) 0.024 ms/op
Iteration   1: 5.735 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.753 ms/op
                 getUser·p0.50:   5.521 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   9.790 ms/op
                 getUser·p0.999:  13.046 ms/op
                 getUser·p0.9999: 28.915 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 6.249 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.494 ms/op
                 getUser·p0.50:   5.808 ms/op
                 getUser·p0.90:   8.552 ms/op
                 getUser·p0.95:   9.765 ms/op
                 getUser·p0.99:   13.648 ms/op
                 getUser·p0.999:  27.284 ms/op
                 getUser·p0.9999: 34.661 ms/op
                 getUser·p1.00:   39.059 ms/op

Iteration   3: 6.055 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   5.792 ms/op
                 getUser·p0.90:   7.578 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.420 ms/op
                 getUser·p0.999:  31.372 ms/op
                 getUser·p0.9999: 37.775 ms/op
                 getUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159725
  mean =      6.006 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 40416 
    [ 5.000,  7.500) = 101298 
    [ 7.500, 10.000) = 14200 
    [10.000, 12.500) = 2741 
    [12.500, 15.000) = 530 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     34.736 ms/op
     p(99.9990) =     38.668 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.553 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.963 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.748 ±(99.9%) 0.027 ms/op
Iteration   1: 6.891 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   6.636 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  27.860 ms/op
                 listUser·p0.9999: 31.505 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 7.015 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.404 ms/op
                 listUser·p0.50:   6.644 ms/op
                 listUser·p0.90:   9.142 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  30.212 ms/op
                 listUser·p0.9999: 32.371 ms/op
                 listUser·p1.00:   33.292 ms/op

Iteration   3: 6.738 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  25.955 ms/op
                 listUser·p0.9999: 32.047 ms/op
                 listUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139473
  mean =      6.879 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 5408 
    [ 5.000,  7.500) = 101152 
    [ 7.500, 10.000) = 26747 
    [10.000, 12.500) = 4682 
    [12.500, 15.000) = 967 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.798 ms/op
     p(95.0000) =      9.814 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     28.132 ms/op
     p(99.9900) =     31.985 ms/op
     p(99.9990) =     33.372 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.241 ± 0.556  ops/ms
ClientPb.existUser                       thrpt       3   5.347 ± 2.903  ops/ms
ClientPb.getUser                         thrpt       3   5.825 ± 3.200  ops/ms
ClientPb.listUser                        thrpt       3   4.564 ± 0.784  ops/ms
ClientPb.createUser                       avgt       3   6.077 ± 2.263   ms/op
ClientPb.existUser                        avgt       3   5.470 ± 1.058   ms/op
ClientPb.getUser                          avgt       3   5.912 ± 4.442   ms/op
ClientPb.listUser                         avgt       3   6.858 ± 3.851   ms/op
ClientPb.createUser                     sample  161316   5.946 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.385           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.696           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.216           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.108           ms/op
ClientPb.existUser                      sample  170953   5.613 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.006           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.529           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  159725   6.006 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.567           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.059           ms/op
ClientPb.listUser                       sample  139473   6.879 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.132           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.985           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.423           ms/op
