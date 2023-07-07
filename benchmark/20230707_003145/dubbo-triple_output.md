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
# Warmup Iteration   1: 1.406 ops/ms
# Warmup Iteration   2: 3.416 ops/ms
# Warmup Iteration   3: 6.237 ops/ms
Iteration   1: 6.100 ops/ms
Iteration   2: 6.629 ops/ms
Iteration   3: 6.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.535 ±(99.9%) 7.243 ops/ms [Average]
  (min, avg, max) = (6.100, 6.535, 6.877), stdev = 0.397
  CI (99.9%): [≈ 0, 13.778] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 5.430 ops/ms
# Warmup Iteration   3: 6.706 ops/ms
Iteration   1: 7.206 ops/ms
Iteration   2: 6.849 ops/ms
Iteration   3: 7.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.033 ±(99.9%) 3.259 ops/ms [Average]
  (min, avg, max) = (6.849, 7.033, 7.206), stdev = 0.179
  CI (99.9%): [3.774, 10.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 5.687 ops/ms
# Warmup Iteration   3: 6.813 ops/ms
Iteration   1: 7.028 ops/ms
Iteration   2: 6.507 ops/ms
Iteration   3: 6.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.782 ±(99.9%) 4.781 ops/ms [Average]
  (min, avg, max) = (6.507, 6.782, 7.028), stdev = 0.262
  CI (99.9%): [2.001, 11.563] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.855 ops/ms
# Warmup Iteration   2: 4.735 ops/ms
# Warmup Iteration   3: 5.790 ops/ms
Iteration   1: 5.869 ops/ms
Iteration   2: 6.248 ops/ms
Iteration   3: 5.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.952 ±(99.9%) 4.835 ops/ms [Average]
  (min, avg, max) = (5.737, 5.952, 6.248), stdev = 0.265
  CI (99.9%): [1.116, 10.787] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.292 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.587 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.012 ms/op
Iteration   1: 4.813 ±(99.9%) 0.007 ms/op
Iteration   2: 4.608 ±(99.9%) 0.016 ms/op
Iteration   3: 4.672 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.698 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (4.608, 4.698, 4.813), stdev = 0.105
  CI (99.9%): [2.784, 6.612] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.299 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.500 ±(99.9%) 0.011 ms/op
Iteration   1: 4.449 ±(99.9%) 0.007 ms/op
Iteration   2: 4.644 ±(99.9%) 0.007 ms/op
Iteration   3: 4.501 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.532 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (4.449, 4.532, 4.644), stdev = 0.101
  CI (99.9%): [2.686, 6.377] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.026 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.748 ±(99.9%) 0.010 ms/op
Iteration   1: 4.652 ±(99.9%) 0.013 ms/op
Iteration   2: 4.443 ±(99.9%) 0.011 ms/op
Iteration   3: 4.701 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.599 ±(99.9%) 2.496 ms/op [Average]
  (min, avg, max) = (4.443, 4.599, 4.701), stdev = 0.137
  CI (99.9%): [2.102, 7.095] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.954 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.365 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.547 ±(99.9%) 0.010 ms/op
Iteration   1: 5.599 ±(99.9%) 0.010 ms/op
Iteration   2: 5.366 ±(99.9%) 0.016 ms/op
Iteration   3: 5.505 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.490 ±(99.9%) 2.144 ms/op [Average]
  (min, avg, max) = (5.366, 5.490, 5.599), stdev = 0.118
  CI (99.9%): [3.346, 7.634] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.106 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.906 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.949 ±(99.9%) 0.018 ms/op
Iteration   1: 5.055 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   10.183 ms/op
                 createUser·p0.999:  20.423 ms/op
                 createUser·p0.9999: 24.611 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 4.806 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  15.394 ms/op
                 createUser·p0.9999: 26.140 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 4.931 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  25.366 ms/op
                 createUser·p0.9999: 37.356 ms/op
                 createUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 194655
  mean =      4.929 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 130550 
    [ 5.000,  7.500) = 57500 
    [ 7.500, 10.000) = 4909 
    [10.000, 12.500) = 1002 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     36.049 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.606 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.244 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.016 ms/op
Iteration   1: 4.651 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   6.947 ms/op
                 existUser·p0.99:   9.740 ms/op
                 existUser·p0.999:  15.913 ms/op
                 existUser·p0.9999: 25.768 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 4.502 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.347 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   6.160 ms/op
                 existUser·p0.99:   7.905 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 26.571 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 4.672 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.717 ms/op
                 existUser·p0.99:   8.667 ms/op
                 existUser·p0.999:  15.230 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 208317
  mean =      4.607 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 167468 
    [ 5.000,  7.500) = 35689 
    [ 7.500, 10.000) = 3922 
    [10.000, 12.500) = 718 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     26.624 ms/op
     p(99.9990) =     28.467 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.221 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.015 ms/op
Iteration   1: 4.826 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  23.977 ms/op
                 getUser·p0.9999: 29.483 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   2: 5.021 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.462 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   10.306 ms/op
                 getUser·p0.999:  24.269 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 4.679 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.060 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  15.723 ms/op
                 getUser·p0.9999: 29.689 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198145
  mean =      4.838 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 143939 
    [ 5.000,  7.500) = 47000 
    [ 7.500, 10.000) = 5500 
    [10.000, 12.500) = 947 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     24.014 ms/op
     p(99.9900) =     29.313 ms/op
     p(99.9990) =     30.772 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 16.010 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.310 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.839 ±(99.9%) 0.022 ms/op
Iteration   1: 5.522 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 28.386 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 5.434 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  24.841 ms/op
                 listUser·p0.9999: 28.348 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   3: 5.526 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  17.967 ms/op
                 listUser·p0.9999: 21.426 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 174637
  mean =      5.494 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 63068 
    [ 5.000,  7.500) = 102196 
    [ 7.500, 10.000) = 7612 
    [10.000, 12.500) = 1148 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     23.965 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     29.296 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.535 ± 7.243  ops/ms
ClientPb.existUser                       thrpt       3   7.033 ± 3.259  ops/ms
ClientPb.getUser                         thrpt       3   6.782 ± 4.781  ops/ms
ClientPb.listUser                        thrpt       3   5.952 ± 4.835  ops/ms
ClientPb.createUser                       avgt       3   4.698 ± 1.914   ms/op
ClientPb.existUser                        avgt       3   4.532 ± 1.846   ms/op
ClientPb.getUser                          avgt       3   4.599 ± 2.496   ms/op
ClientPb.listUser                         avgt       3   5.490 ± 2.144   ms/op
ClientPb.createUser                     sample  194655   4.929 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.523           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.634           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.643           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.552           ms/op
ClientPb.existUser                      sample  208317   4.607 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.499           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.624           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  198145   4.838 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.755           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.014           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.313           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  174637   5.494 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.965           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.148           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.688           ms/op
