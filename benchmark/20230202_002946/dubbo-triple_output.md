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
# Warmup Iteration   1: 0.954 ops/ms
# Warmup Iteration   2: 2.267 ops/ms
# Warmup Iteration   3: 5.479 ops/ms
Iteration   1: 5.545 ops/ms
Iteration   2: 5.892 ops/ms
Iteration   3: 6.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.843 ±(99.9%) 5.041 ops/ms [Average]
  (min, avg, max) = (5.545, 5.843, 6.091), stdev = 0.276
  CI (99.9%): [0.802, 10.883] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.767 ops/ms
# Warmup Iteration   2: 5.242 ops/ms
# Warmup Iteration   3: 5.953 ops/ms
Iteration   1: 5.891 ops/ms
Iteration   2: 6.161 ops/ms
Iteration   3: 6.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.108 ±(99.9%) 3.587 ops/ms [Average]
  (min, avg, max) = (5.891, 6.108, 6.273), stdev = 0.197
  CI (99.9%): [2.522, 9.695] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.476 ops/ms
# Warmup Iteration   2: 4.652 ops/ms
# Warmup Iteration   3: 5.895 ops/ms
Iteration   1: 5.798 ops/ms
Iteration   2: 5.725 ops/ms
Iteration   3: 5.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.788 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (5.725, 5.788, 5.842), stdev = 0.059
  CI (99.9%): [4.706, 6.871] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.401 ops/ms
# Warmup Iteration   2: 4.393 ops/ms
# Warmup Iteration   3: 4.990 ops/ms
Iteration   1: 5.156 ops/ms
Iteration   2: 5.146 ops/ms
Iteration   3: 5.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.121 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (5.061, 5.121, 5.156), stdev = 0.052
  CI (99.9%): [4.167, 6.076] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 21.146 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 7.523 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.033 ±(99.9%) 0.015 ms/op
Iteration   1: 5.865 ±(99.9%) 0.008 ms/op
Iteration   2: 5.459 ±(99.9%) 0.017 ms/op
Iteration   3: 5.504 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.609 ±(99.9%) 4.056 ms/op [Average]
  (min, avg, max) = (5.459, 5.609, 5.865), stdev = 0.222
  CI (99.9%): [1.554, 9.665] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.556 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.138 ±(99.9%) 0.013 ms/op
Iteration   1: 4.960 ±(99.9%) 0.014 ms/op
Iteration   2: 4.972 ±(99.9%) 0.012 ms/op
Iteration   3: 5.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.010 ±(99.9%) 1.413 ms/op [Average]
  (min, avg, max) = (4.960, 5.010, 5.099), stdev = 0.077
  CI (99.9%): [3.598, 6.423] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.676 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.605 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.015 ms/op
Iteration   1: 5.594 ±(99.9%) 0.016 ms/op
Iteration   2: 5.291 ±(99.9%) 0.015 ms/op
Iteration   3: 5.317 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.401 ±(99.9%) 3.061 ms/op [Average]
  (min, avg, max) = (5.291, 5.401, 5.594), stdev = 0.168
  CI (99.9%): [2.340, 8.462] (assumes normal distribution)


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
# Warmup Iteration   1: 19.423 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.035 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.031 ±(99.9%) 0.022 ms/op
Iteration   1: 6.182 ±(99.9%) 0.017 ms/op
Iteration   2: 6.606 ±(99.9%) 0.012 ms/op
Iteration   3: 6.393 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.394 ±(99.9%) 3.870 ms/op [Average]
  (min, avg, max) = (6.182, 6.394, 6.606), stdev = 0.212
  CI (99.9%): [2.523, 10.264] (assumes normal distribution)


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
# Warmup Iteration   1: 19.139 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 6.965 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.764 ±(99.9%) 0.026 ms/op
Iteration   1: 5.525 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   11.067 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 5.311 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  22.334 ms/op
                 createUser·p0.9999: 29.827 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 5.313 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.638 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  15.466 ms/op
                 createUser·p0.9999: 28.999 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178253
  mean =      5.381 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 88022 
    [ 5.000,  7.500) = 79503 
    [ 7.500, 10.000) = 8175 
    [10.000, 12.500) = 1781 
    [12.500, 15.000) = 404 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     20.668 ms/op
     p(99.9900) =     28.710 ms/op
     p(99.9990) =     30.272 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 17.813 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.920 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.633 ±(99.9%) 0.021 ms/op
Iteration   1: 5.510 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   11.759 ms/op
                 existUser·p0.999:  15.351 ms/op
                 existUser·p0.9999: 24.713 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 5.285 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  21.578 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 5.449 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.609 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   8.135 ms/op
                 existUser·p0.99:   11.551 ms/op
                 existUser·p0.999:  23.928 ms/op
                 existUser·p0.9999: 25.802 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177291
  mean =      5.413 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 85830 
    [ 5.000,  7.500) = 79180 
    [ 7.500, 10.000) = 9140 
    [10.000, 12.500) = 2179 
    [12.500, 15.000) = 647 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     18.757 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     26.630 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 17.821 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.085 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.692 ±(99.9%) 0.025 ms/op
Iteration   1: 5.601 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   12.960 ms/op
                 getUser·p0.999:  23.655 ms/op
                 getUser·p0.9999: 27.563 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 5.512 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   3: 5.439 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.308 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.765 ms/op
                 getUser·p0.999:  26.548 ms/op
                 getUser·p0.9999: 30.482 ms/op
                 getUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173954
  mean =      5.517 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 63292 
    [ 5.000,  7.500) = 100596 
    [ 7.500, 10.000) = 7277 
    [10.000, 12.500) = 1612 
    [12.500, 15.000) = 622 
    [15.000, 17.500) = 275 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     11.312 ms/op
     p(99.9000) =     21.923 ms/op
     p(99.9900) =     29.858 ms/op
     p(99.9990) =     31.695 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 22.259 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.840 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.657 ±(99.9%) 0.030 ms/op
Iteration   1: 6.515 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   13.358 ms/op
                 listUser·p0.999:  23.751 ms/op
                 listUser·p0.9999: 26.962 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 6.257 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  27.197 ms/op
                 listUser·p0.9999: 32.187 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   3: 6.189 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  27.038 ms/op
                 listUser·p0.9999: 31.425 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151845
  mean =      6.318 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 6561 
    [ 5.000,  7.500) = 129682 
    [ 7.500, 10.000) = 11036 
    [10.000, 12.500) = 3084 
    [12.500, 15.000) = 853 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     26.088 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     32.681 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.843 ± 5.041  ops/ms
ClientPb.existUser                       thrpt       3   6.108 ± 3.587  ops/ms
ClientPb.getUser                         thrpt       3   5.788 ± 1.082  ops/ms
ClientPb.listUser                        thrpt       3   5.121 ± 0.954  ops/ms
ClientPb.createUser                       avgt       3   5.609 ± 4.056   ms/op
ClientPb.existUser                        avgt       3   5.010 ± 1.413   ms/op
ClientPb.getUser                          avgt       3   5.401 ± 3.061   ms/op
ClientPb.listUser                         avgt       3   6.394 ± 3.870   ms/op
ClientPb.createUser                     sample  178253   5.381 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.858           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.584           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.668           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.605           ms/op
ClientPb.existUser                      sample  177291   5.413 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.269           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.022           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.110           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.174           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.757           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.723           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  173954   5.517 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.821           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.791           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.312           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.858           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.719           ms/op
ClientPb.listUser                       sample  151845   6.318 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.419           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.088           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.425           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834           ms/op
