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
# Warmup Iteration   1: 0.956 ops/ms
# Warmup Iteration   2: 2.231 ops/ms
# Warmup Iteration   3: 4.430 ops/ms
Iteration   1: 5.501 ops/ms
Iteration   2: 5.590 ops/ms
Iteration   3: 5.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.598 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (5.501, 5.598, 5.703), stdev = 0.101
  CI (99.9%): [3.748, 7.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.667 ops/ms
# Warmup Iteration   2: 4.598 ops/ms
# Warmup Iteration   3: 5.813 ops/ms
Iteration   1: 6.156 ops/ms
Iteration   2: 6.252 ops/ms
Iteration   3: 5.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.091 ±(99.9%) 3.678 ops/ms [Average]
  (min, avg, max) = (5.865, 6.091, 6.252), stdev = 0.202
  CI (99.9%): [2.413, 9.769] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.495 ops/ms
# Warmup Iteration   2: 3.966 ops/ms
# Warmup Iteration   3: 5.550 ops/ms
Iteration   1: 5.397 ops/ms
Iteration   2: 5.610 ops/ms
Iteration   3: 5.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.586 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (5.397, 5.586, 5.752), stdev = 0.178
  CI (99.9%): [2.330, 8.843] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.403 ops/ms
# Warmup Iteration   2: 3.514 ops/ms
# Warmup Iteration   3: 4.810 ops/ms
Iteration   1: 4.830 ops/ms
Iteration   2: 5.142 ops/ms
Iteration   3: 4.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.952 ±(99.9%) 3.034 ops/ms [Average]
  (min, avg, max) = (4.830, 4.952, 5.142), stdev = 0.166
  CI (99.9%): [1.918, 7.986] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.043 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.808 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.031 ±(99.9%) 0.007 ms/op
Iteration   1: 5.552 ±(99.9%) 0.012 ms/op
Iteration   2: 5.302 ±(99.9%) 0.015 ms/op
Iteration   3: 5.480 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.445 ±(99.9%) 2.349 ms/op [Average]
  (min, avg, max) = (5.302, 5.445, 5.552), stdev = 0.129
  CI (99.9%): [3.095, 7.794] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.725 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.387 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.382 ±(99.9%) 0.008 ms/op
Iteration   1: 5.282 ±(99.9%) 0.011 ms/op
Iteration   2: 5.272 ±(99.9%) 0.011 ms/op
Iteration   3: 5.329 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.294 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (5.272, 5.294, 5.329), stdev = 0.030
  CI (99.9%): [4.741, 5.847] (assumes normal distribution)


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
# Warmup Iteration   1: 20.681 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.786 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.855 ±(99.9%) 0.010 ms/op
Iteration   1: 5.596 ±(99.9%) 0.015 ms/op
Iteration   2: 5.793 ±(99.9%) 0.008 ms/op
Iteration   3: 5.429 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.606 ±(99.9%) 3.322 ms/op [Average]
  (min, avg, max) = (5.429, 5.606, 5.793), stdev = 0.182
  CI (99.9%): [2.285, 8.928] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.506 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 8.046 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.704 ±(99.9%) 0.010 ms/op
Iteration   1: 6.388 ±(99.9%) 0.011 ms/op
Iteration   2: 6.493 ±(99.9%) 0.018 ms/op
Iteration   3: 6.390 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.424 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (6.388, 6.424, 6.493), stdev = 0.060
  CI (99.9%): [5.327, 7.520] (assumes normal distribution)


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
# Warmup Iteration   1: 19.488 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.056 ±(99.9%) 0.028 ms/op
Iteration   1: 5.764 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.437 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.635 ms/op
                 createUser·p0.95:   8.913 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  24.314 ms/op
                 createUser·p0.9999: 29.849 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   2: 5.575 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.701 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  16.056 ms/op
                 createUser·p0.9999: 30.238 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 5.466 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  16.548 ms/op
                 createUser·p0.9999: 31.210 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171433
  mean =      5.599 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 51889 
    [ 5.000,  7.500) = 108262 
    [ 7.500, 10.000) = 8535 
    [10.000, 12.500) = 2056 
    [12.500, 15.000) = 396 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     18.795 ms/op
     p(99.9900) =     30.699 ms/op
     p(99.9990) =     31.813 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 17.989 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.565 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.700 ±(99.9%) 0.024 ms/op
Iteration   1: 5.395 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.469 ms/op
                 existUser·p0.999:  23.768 ms/op
                 existUser·p0.9999: 26.658 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 5.382 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.611 ms/op
                 existUser·p0.95:   7.782 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  20.211 ms/op
                 existUser·p0.9999: 26.771 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   3: 5.342 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.580 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  27.374 ms/op
                 existUser·p0.9999: 31.791 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178536
  mean =      5.373 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 78444 
    [ 5.000,  7.500) = 90335 
    [ 7.500, 10.000) = 7286 
    [10.000, 12.500) = 1696 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     29.824 ms/op
     p(99.9990) =     32.431 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 20.786 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.671 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 5.848 ±(99.9%) 0.023 ms/op
Iteration   1: 5.625 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   6.799 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  24.350 ms/op
                 getUser·p0.9999: 32.653 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   2: 5.587 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  14.559 ms/op
                 getUser·p0.9999: 29.822 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   3: 5.532 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   11.928 ms/op
                 getUser·p0.999:  26.954 ms/op
                 getUser·p0.9999: 36.190 ms/op
                 getUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171940
  mean =      5.581 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 52627 
    [ 5.000,  7.500) = 109214 
    [ 7.500, 10.000) = 7446 
    [10.000, 12.500) = 1813 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     22.282 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.737 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 22.743 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 9.431 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 7.099 ±(99.9%) 0.031 ms/op
Iteration   1: 6.777 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   14.451 ms/op
                 listUser·p0.999:  24.925 ms/op
                 listUser·p0.9999: 36.213 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   2: 6.824 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.284 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 31.719 ms/op
                 listUser·p1.00:   35.193 ms/op

Iteration   3: 6.669 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.584 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.677 ms/op
                 listUser·p0.999:  26.381 ms/op
                 listUser·p0.9999: 32.933 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142028
  mean =      6.756 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2939 
    [ 5.000,  7.500) = 116819 
    [ 7.500, 10.000) = 16155 
    [10.000, 12.500) = 4269 
    [12.500, 15.000) = 1083 
    [15.000, 17.500) = 373 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      6.316 ms/op
     p(90.0000) =      8.290 ms/op
     p(95.0000) =      9.725 ms/op
     p(99.0000) =     13.287 ms/op
     p(99.9000) =     26.182 ms/op
     p(99.9900) =     33.803 ms/op
     p(99.9990) =     36.656 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.598 ± 1.850  ops/ms
ClientPb.existUser                       thrpt       3   6.091 ± 3.678  ops/ms
ClientPb.getUser                         thrpt       3   5.586 ± 3.256  ops/ms
ClientPb.listUser                        thrpt       3   4.952 ± 3.034  ops/ms
ClientPb.createUser                       avgt       3   5.445 ± 2.349   ms/op
ClientPb.existUser                        avgt       3   5.294 ± 0.553   ms/op
ClientPb.getUser                          avgt       3   5.606 ± 3.322   ms/op
ClientPb.listUser                         avgt       3   6.424 ± 1.097   ms/op
ClientPb.createUser                     sample  171433   5.599 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.712           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.995           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.795           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.699           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  178536   5.373 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.063           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.551           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.987           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.824           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.637           ms/op
ClientPb.getUser                        sample  171940   5.581 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.840           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.879           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.831           ms/op
ClientPb.listUser                       sample  142028   6.756 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.290           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.725           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.287           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.182           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.803           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.766           ms/op
