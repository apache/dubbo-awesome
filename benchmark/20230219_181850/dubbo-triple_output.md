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
# Warmup Iteration   1: 1.060 ops/ms
# Warmup Iteration   2: 2.331 ops/ms
# Warmup Iteration   3: 5.199 ops/ms
Iteration   1: 5.470 ops/ms
Iteration   2: 5.084 ops/ms
Iteration   3: 5.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.301 ±(99.9%) 3.604 ops/ms [Average]
  (min, avg, max) = (5.084, 5.301, 5.470), stdev = 0.198
  CI (99.9%): [1.697, 8.906] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.469 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 5.808 ops/ms
Iteration   1: 5.636 ops/ms
Iteration   2: 5.797 ops/ms
Iteration   3: 5.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.720 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (5.636, 5.720, 5.797), stdev = 0.081
  CI (99.9%): [4.244, 7.195] (assumes normal distribution)


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
# Warmup Iteration   1: 1.522 ops/ms
# Warmup Iteration   2: 3.939 ops/ms
# Warmup Iteration   3: 5.381 ops/ms
Iteration   1: 5.600 ops/ms
Iteration   2: 5.959 ops/ms
Iteration   3: 5.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.748 ±(99.9%) 3.429 ops/ms [Average]
  (min, avg, max) = (5.600, 5.748, 5.959), stdev = 0.188
  CI (99.9%): [2.318, 9.177] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.396 ops/ms
# Warmup Iteration   2: 4.029 ops/ms
# Warmup Iteration   3: 4.988 ops/ms
Iteration   1: 4.681 ops/ms
Iteration   2: 4.735 ops/ms
Iteration   3: 4.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.754 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (4.681, 4.754, 4.844), stdev = 0.083
  CI (99.9%): [3.234, 6.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.024 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.008 ms/op
Iteration   1: 5.685 ±(99.9%) 0.014 ms/op
Iteration   2: 5.654 ±(99.9%) 0.015 ms/op
Iteration   3: 6.014 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.784 ±(99.9%) 3.642 ms/op [Average]
  (min, avg, max) = (5.654, 5.784, 6.014), stdev = 0.200
  CI (99.9%): [2.142, 9.426] (assumes normal distribution)


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
# Warmup Iteration   1: 20.284 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.737 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.347 ±(99.9%) 0.015 ms/op
Iteration   1: 5.136 ±(99.9%) 0.013 ms/op
Iteration   2: 5.407 ±(99.9%) 0.012 ms/op
Iteration   3: 5.123 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.222 ±(99.9%) 2.920 ms/op [Average]
  (min, avg, max) = (5.123, 5.222, 5.407), stdev = 0.160
  CI (99.9%): [2.302, 8.142] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.519 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 7.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.857 ±(99.9%) 0.013 ms/op
Iteration   1: 6.230 ±(99.9%) 0.014 ms/op
Iteration   2: 5.797 ±(99.9%) 0.008 ms/op
Iteration   3: 5.844 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.957 ±(99.9%) 4.340 ms/op [Average]
  (min, avg, max) = (5.797, 5.957, 6.230), stdev = 0.238
  CI (99.9%): [1.617, 10.297] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 24.960 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 8.351 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.820 ±(99.9%) 0.012 ms/op
Iteration   1: 6.828 ±(99.9%) 0.012 ms/op
Iteration   2: 6.484 ±(99.9%) 0.014 ms/op
Iteration   3: 6.590 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.634 ±(99.9%) 3.210 ms/op [Average]
  (min, avg, max) = (6.484, 6.634, 6.828), stdev = 0.176
  CI (99.9%): [3.424, 9.844] (assumes normal distribution)


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
# Warmup Iteration   1: 19.874 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.752 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.136 ±(99.9%) 0.029 ms/op
Iteration   1: 6.027 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.644 ms/op
                 createUser·p0.90:   7.971 ms/op
                 createUser·p0.95:   9.224 ms/op
                 createUser·p0.99:   12.556 ms/op
                 createUser·p0.999:  22.534 ms/op
                 createUser·p0.9999: 24.730 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 5.695 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  18.372 ms/op
                 createUser·p0.9999: 27.098 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 5.668 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.933 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.168 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  25.314 ms/op
                 createUser·p0.9999: 28.924 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165603
  mean =      5.792 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 51566 
    [ 5.000,  7.500) = 98121 
    [ 7.500, 10.000) = 12645 
    [10.000, 12.500) = 2263 
    [12.500, 15.000) = 533 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     28.093 ms/op
     p(99.9990) =     29.273 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 17.713 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.073 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.875 ±(99.9%) 0.030 ms/op
Iteration   1: 5.981 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.073 ms/op
                 existUser·p0.50:   5.587 ms/op
                 existUser·p0.90:   8.200 ms/op
                 existUser·p0.95:   9.355 ms/op
                 existUser·p0.99:   13.252 ms/op
                 existUser·p0.999:  22.921 ms/op
                 existUser·p0.9999: 27.826 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   2: 5.998 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   5.554 ms/op
                 existUser·p0.90:   8.233 ms/op
                 existUser·p0.95:   9.617 ms/op
                 existUser·p0.99:   13.337 ms/op
                 existUser·p0.999:  30.988 ms/op
                 existUser·p0.9999: 36.220 ms/op
                 existUser·p1.00:   36.504 ms/op

Iteration   3: 5.572 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.335 ms/op
                 existUser·p0.99:   11.289 ms/op
                 existUser·p0.999:  30.528 ms/op
                 existUser·p0.9999: 33.710 ms/op
                 existUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164209
  mean =      5.844 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 64395 
    [ 5.000,  7.500) = 79281 
    [ 7.500, 10.000) = 15140 
    [10.000, 12.500) = 3720 
    [12.500, 15.000) = 906 
    [15.000, 17.500) = 361 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.922 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     24.333 ms/op
     p(99.9900) =     34.569 ms/op
     p(99.9990) =     36.461 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 20.362 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.061 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.025 ms/op
Iteration   1: 5.623 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.564 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.380 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 27.247 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 6.063 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   8.094 ms/op
                 getUser·p0.95:   9.257 ms/op
                 getUser·p0.99:   14.010 ms/op
                 getUser·p0.999:  27.449 ms/op
                 getUser·p0.9999: 31.514 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   3: 5.979 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   8.004 ms/op
                 getUser·p0.95:   9.208 ms/op
                 getUser·p0.99:   12.150 ms/op
                 getUser·p0.999:  24.150 ms/op
                 getUser·p0.9999: 28.245 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163175
  mean =      5.882 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 56644 
    [ 5.000,  7.500) = 86864 
    [ 7.500, 10.000) = 14637 
    [10.000, 12.500) = 3323 
    [12.500, 15.000) = 905 
    [15.000, 17.500) = 284 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.791 ms/op
     p(95.0000) =      8.995 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     29.940 ms/op
     p(99.9990) =     33.796 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 22.976 ±(99.9%) 0.408 ms/op
# Warmup Iteration   2: 7.974 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.988 ±(99.9%) 0.035 ms/op
Iteration   1: 6.691 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.404 ms/op
                 listUser·p0.99:   13.795 ms/op
                 listUser·p0.999:  29.332 ms/op
                 listUser·p0.9999: 36.087 ms/op
                 listUser·p1.00:   38.142 ms/op

Iteration   2: 6.674 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   14.139 ms/op
                 listUser·p0.999:  29.262 ms/op
                 listUser·p0.9999: 32.178 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   3: 6.405 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.238 ms/op
                 listUser·p0.999:  30.414 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145827
  mean =      6.587 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 11036 
    [ 5.000,  7.500) = 106779 
    [ 7.500, 10.000) = 20805 
    [10.000, 12.500) = 4934 
    [12.500, 15.000) = 1322 
    [15.000, 17.500) = 527 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      8.667 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.713 ms/op
     p(99.9000) =     29.628 ms/op
     p(99.9900) =     35.417 ms/op
     p(99.9990) =     37.391 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.301 ± 3.604  ops/ms
ClientPb.existUser                       thrpt       3   5.720 ± 1.476  ops/ms
ClientPb.getUser                         thrpt       3   5.748 ± 3.429  ops/ms
ClientPb.listUser                        thrpt       3   4.754 ± 1.520  ops/ms
ClientPb.createUser                       avgt       3   5.784 ± 3.642   ms/op
ClientPb.existUser                        avgt       3   5.222 ± 2.920   ms/op
ClientPb.getUser                          avgt       3   5.957 ± 4.340   ms/op
ClientPb.listUser                         avgt       3   6.634 ± 3.210   ms/op
ClientPb.createUser                     sample  165603   5.792 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.356           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.370           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.151           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.093           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  164209   5.844 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.526           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.126           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.485           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.333           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.569           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.504           ms/op
ClientPb.getUser                        sample  163175   5.882 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.791           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.995           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.599           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.904           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.940           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  145827   6.587 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.975           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.713           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.628           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.417           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
