# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.947 ops/ms
# Warmup Iteration   2: 4.544 ops/ms
# Warmup Iteration   3: 8.115 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.830 ops/ms
Iteration   3: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.819 ±(99.9%) 3.959 ops/ms [Average]
  (min, avg, max) = (8.597, 8.819, 9.030), stdev = 0.217
  CI (99.9%): [4.860, 12.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.604 ops/ms
# Warmup Iteration   2: 8.211 ops/ms
# Warmup Iteration   3: 8.603 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.357 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (9.292, 9.357, 9.436), stdev = 0.073
  CI (99.9%): [8.029, 10.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 8.195 ops/ms
# Warmup Iteration   3: 9.025 ops/ms
Iteration   1: 9.012 ops/ms
Iteration   2: 9.118 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.099 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (9.012, 9.099, 9.166), stdev = 0.079
  CI (99.9%): [7.657, 10.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.461 ops/ms
# Warmup Iteration   2: 6.767 ops/ms
# Warmup Iteration   3: 7.535 ops/ms
Iteration   1: 7.531 ops/ms
Iteration   2: 7.451 ops/ms
Iteration   3: 7.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.515 ±(99.9%) 1.051 ops/ms [Average]
  (min, avg, max) = (7.451, 7.515, 7.563), stdev = 0.058
  CI (99.9%): [6.464, 8.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.855 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.005 ms/op
Iteration   1: 3.410 ±(99.9%) 0.008 ms/op
Iteration   2: 3.491 ±(99.9%) 0.005 ms/op
Iteration   3: 3.473 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.410, 3.458, 3.491), stdev = 0.043
  CI (99.9%): [2.680, 4.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.288 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.004 ms/op
Iteration   1: 3.368 ±(99.9%) 0.005 ms/op
Iteration   2: 3.428 ±(99.9%) 0.004 ms/op
Iteration   3: 3.429 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.408 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.368, 3.408, 3.429), stdev = 0.035
  CI (99.9%): [2.765, 4.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.243 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.004 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.550 ±(99.9%) 0.005 ms/op
Iteration   3: 3.507 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.516 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.491, 3.516, 3.550), stdev = 0.031
  CI (99.9%): [2.954, 4.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.159 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.006 ms/op
Iteration   1: 4.303 ±(99.9%) 0.007 ms/op
Iteration   2: 4.202 ±(99.9%) 0.005 ms/op
Iteration   3: 4.190 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.232 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.190, 4.232, 4.303), stdev = 0.062
  CI (99.9%): [3.096, 5.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.210 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   8.290 ms/op
                 createUser·p0.999:  22.326 ms/op
                 createUser·p0.9999: 26.367 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.621 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   7.311 ms/op
                 createUser·p0.999:  22.575 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.805 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  17.494 ms/op
                 createUser·p0.9999: 36.477 ms/op
                 createUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254129
  mean =      3.780 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3359 
    [ 2.500,  5.000) = 234893 
    [ 5.000,  7.500) = 11956 
    [ 7.500, 10.000) = 3082 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     21.455 ms/op
     p(99.9900) =     34.495 ms/op
     p(99.9990) =     36.749 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.949 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.551 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  12.434 ms/op
                 existUser·p0.9999: 23.494 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.394 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  23.921 ms/op
                 existUser·p0.9999: 40.305 ms/op
                 existUser·p1.00:   44.106 ms/op

Iteration   3: 3.422 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   7.105 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 27.973 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277776
  mean =      3.454 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266459 
    [ 5.000, 10.000) = 10375 
    [10.000, 15.000) = 557 
    [15.000, 20.000) = 83 
    [20.000, 25.000) = 196 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     21.438 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     41.659 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.037 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.016 ms/op
Iteration   1: 3.628 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   5.531 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  20.409 ms/op
                 getUser·p0.9999: 24.534 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  13.939 ms/op
                 getUser·p0.9999: 24.940 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.481 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  23.894 ms/op
                 getUser·p0.9999: 33.423 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272241
  mean =      3.525 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2758 
    [ 2.500,  5.000) = 259230 
    [ 5.000,  7.500) = 7457 
    [ 7.500, 10.000) = 2139 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     19.007 ms/op
     p(99.9900) =     31.140 ms/op
     p(99.9990) =     34.534 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.049 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.331 ±(99.9%) 0.014 ms/op
Iteration   1: 4.185 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  18.367 ms/op
                 listUser·p0.9999: 20.536 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 4.224 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.213 ms/op
                 listUser·p0.9999: 17.699 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.267 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  18.284 ms/op
                 listUser·p0.9999: 36.569 ms/op
                 listUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227236
  mean =      4.225 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 215463 
    [ 5.000, 10.000) = 10451 
    [10.000, 15.000) = 779 
    [15.000, 20.000) = 482 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 14 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     35.932 ms/op
     p(99.9990) =     39.477 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.819 ± 3.959  ops/ms
ClientPb.existUser                       thrpt       3   9.357 ± 1.329  ops/ms
ClientPb.getUser                         thrpt       3   9.099 ± 1.442  ops/ms
ClientPb.listUser                        thrpt       3   7.515 ± 1.051  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 0.778   ms/op
ClientPb.existUser                        avgt       3   3.408 ± 0.643   ms/op
ClientPb.getUser                          avgt       3   3.516 ± 0.562   ms/op
ClientPb.listUser                         avgt       3   4.232 ± 1.135   ms/op
ClientPb.createUser                     sample  254129   3.780 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.270           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.864           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.455           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.487           ms/op
ClientPb.existUser                      sample  277776   3.454 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.491           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.438           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.082           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.106           ms/op
ClientPb.getUser                        sample  272241   3.525 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.140           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  227236   4.225 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.565           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.932           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.140           ms/op
