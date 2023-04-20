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
# Warmup Iteration   1: 1.481 ops/ms
# Warmup Iteration   2: 3.219 ops/ms
# Warmup Iteration   3: 6.281 ops/ms
Iteration   1: 6.621 ops/ms
Iteration   2: 7.213 ops/ms
Iteration   3: 6.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.924 ±(99.9%) 5.398 ops/ms [Average]
  (min, avg, max) = (6.621, 6.924, 7.213), stdev = 0.296
  CI (99.9%): [1.526, 12.322] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.875 ops/ms
# Warmup Iteration   2: 5.891 ops/ms
# Warmup Iteration   3: 7.146 ops/ms
Iteration   1: 7.282 ops/ms
Iteration   2: 7.511 ops/ms
Iteration   3: 7.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.282 ±(99.9%) 4.177 ops/ms [Average]
  (min, avg, max) = (7.053, 7.282, 7.511), stdev = 0.229
  CI (99.9%): [3.105, 11.460] (assumes normal distribution)


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
# Warmup Iteration   1: 2.011 ops/ms
# Warmup Iteration   2: 6.061 ops/ms
# Warmup Iteration   3: 7.077 ops/ms
Iteration   1: 7.164 ops/ms
Iteration   2: 7.061 ops/ms
Iteration   3: 7.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.085 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (7.030, 7.085, 7.164), stdev = 0.070
  CI (99.9%): [5.807, 8.364] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.955 ops/ms
# Warmup Iteration   2: 5.036 ops/ms
# Warmup Iteration   3: 5.668 ops/ms
Iteration   1: 5.723 ops/ms
Iteration   2: 5.808 ops/ms
Iteration   3: 6.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.874 ±(99.9%) 3.527 ops/ms [Average]
  (min, avg, max) = (5.723, 5.874, 6.092), stdev = 0.193
  CI (99.9%): [2.347, 9.401] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.251 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.013 ms/op
Iteration   1: 4.845 ±(99.9%) 0.009 ms/op
Iteration   2: 4.753 ±(99.9%) 0.011 ms/op
Iteration   3: 4.656 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.751 ±(99.9%) 1.725 ms/op [Average]
  (min, avg, max) = (4.656, 4.751, 4.845), stdev = 0.095
  CI (99.9%): [3.026, 6.476] (assumes normal distribution)


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
# Warmup Iteration   1: 11.670 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.821 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.646 ±(99.9%) 0.009 ms/op
Iteration   1: 4.518 ±(99.9%) 0.012 ms/op
Iteration   2: 4.361 ±(99.9%) 0.019 ms/op
Iteration   3: 4.546 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.475 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (4.361, 4.475, 4.546), stdev = 0.100
  CI (99.9%): [2.658, 6.292] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.906 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.009 ms/op
Iteration   1: 4.678 ±(99.9%) 0.011 ms/op
Iteration   2: 4.506 ±(99.9%) 0.017 ms/op
Iteration   3: 4.623 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.603 ±(99.9%) 1.604 ms/op [Average]
  (min, avg, max) = (4.506, 4.603, 4.678), stdev = 0.088
  CI (99.9%): [2.999, 6.206] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.311 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.743 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.013 ms/op
Iteration   1: 5.357 ±(99.9%) 0.014 ms/op
Iteration   2: 5.236 ±(99.9%) 0.017 ms/op
Iteration   3: 5.383 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.325 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (5.236, 5.325, 5.383), stdev = 0.078
  CI (99.9%): [3.895, 6.756] (assumes normal distribution)


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
# Warmup Iteration   1: 15.198 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 5.442 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.156 ±(99.9%) 0.023 ms/op
Iteration   1: 4.788 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.013 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   5.792 ms/op
                 createUser·p0.95:   6.660 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  14.575 ms/op
                 createUser·p0.9999: 23.079 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 4.701 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.264 ms/op
                 createUser·p0.999:  13.599 ms/op
                 createUser·p0.9999: 29.635 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 4.759 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.316 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  21.817 ms/op
                 createUser·p0.9999: 41.830 ms/op
                 createUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 201978
  mean =      4.749 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 144177 
    [ 5.000, 10.000) = 56888 
    [10.000, 15.000) = 685 
    [15.000, 20.000) = 24 
    [20.000, 25.000) = 105 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     40.279 ms/op
     p(99.9990) =     42.597 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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
# Warmup Iteration   1: 12.049 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.050 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.015 ms/op
Iteration   1: 4.492 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.952 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  16.701 ms/op
                 existUser·p0.9999: 25.609 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 4.359 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   6.013 ms/op
                 existUser·p0.99:   7.856 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 36.089 ms/op
                 existUser·p1.00:   36.569 ms/op

Iteration   3: 4.455 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   6.177 ms/op
                 existUser·p0.99:   9.529 ms/op
                 existUser·p0.999:  17.796 ms/op
                 existUser·p0.9999: 29.216 ms/op
                 existUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 216206
  mean =      4.435 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 184407 
    [ 5.000,  7.500) = 28495 
    [ 7.500, 10.000) = 2147 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     16.708 ms/op
     p(99.9900) =     35.021 ms/op
     p(99.9990) =     36.362 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 13.117 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.141 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.014 ms/op
Iteration   1: 4.918 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  19.594 ms/op
                 getUser·p0.9999: 29.753 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 4.640 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.919 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  12.484 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   34.865 ms/op

Iteration   3: 4.971 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.187 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  19.132 ms/op
                 getUser·p0.9999: 33.853 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198459
  mean =      4.838 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 132146 
    [ 5.000,  7.500) = 62478 
    [ 7.500, 10.000) = 3049 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     19.515 ms/op
     p(99.9900) =     33.761 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 15.324 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 6.500 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.888 ±(99.9%) 0.023 ms/op
Iteration   1: 5.638 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  24.281 ms/op
                 listUser·p0.9999: 31.960 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   2: 5.277 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  23.986 ms/op
                 listUser·p0.9999: 26.921 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 5.354 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   9.682 ms/op
                 listUser·p0.999:  21.014 ms/op
                 listUser·p0.9999: 29.459 ms/op
                 listUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 177077
  mean =      5.419 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 64760 
    [ 5.000,  7.500) = 106162 
    [ 7.500, 10.000) = 4517 
    [10.000, 12.500) = 992 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     23.064 ms/op
     p(99.9900) =     29.599 ms/op
     p(99.9990) =     32.667 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.924 ± 5.398  ops/ms
ClientPb.existUser                       thrpt       3   7.282 ± 4.177  ops/ms
ClientPb.getUser                         thrpt       3   7.085 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3   5.874 ± 3.527  ops/ms
ClientPb.createUser                       avgt       3   4.751 ± 1.725   ms/op
ClientPb.existUser                        avgt       3   4.475 ± 1.817   ms/op
ClientPb.getUser                          avgt       3   4.603 ± 1.604   ms/op
ClientPb.listUser                         avgt       3   5.325 ± 1.430   ms/op
ClientPb.createUser                     sample  201978   4.749 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.357           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.471           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.279           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.861           ms/op
ClientPb.existUser                      sample  216206   4.435 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.118           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.708           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  198459   4.838 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.496           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.865           ms/op
ClientPb.listUser                       sample  177077   5.419 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.064           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.599           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.768           ms/op
