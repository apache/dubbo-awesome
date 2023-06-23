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
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 4.258 ops/ms
# Warmup Iteration   3: 7.156 ops/ms
Iteration   1: 7.798 ops/ms
Iteration   2: 8.380 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.032 ±(99.9%) 5.597 ops/ms [Average]
  (min, avg, max) = (7.798, 8.032, 8.380), stdev = 0.307
  CI (99.9%): [2.435, 13.630] (assumes normal distribution)


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
# Warmup Iteration   1: 2.375 ops/ms
# Warmup Iteration   2: 6.323 ops/ms
# Warmup Iteration   3: 7.565 ops/ms
Iteration   1: 8.494 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.520 ±(99.9%) 3.243 ops/ms [Average]
  (min, avg, max) = (8.356, 8.520, 8.709), stdev = 0.178
  CI (99.9%): [5.277, 11.763] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.439 ops/ms
# Warmup Iteration   2: 7.273 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 8.493 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.233 ±(99.9%) 4.855 ops/ms [Average]
  (min, avg, max) = (7.961, 8.233, 8.493), stdev = 0.266
  CI (99.9%): [3.377, 13.088] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.774 ops/ms
# Warmup Iteration   3: 7.048 ops/ms
Iteration   1: 7.163 ops/ms
Iteration   2: 7.307 ops/ms
Iteration   3: 6.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.119 ±(99.9%) 3.899 ops/ms [Average]
  (min, avg, max) = (6.886, 7.119, 7.307), stdev = 0.214
  CI (99.9%): [3.220, 11.017] (assumes normal distribution)


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
# Warmup Iteration   1: 11.466 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.995 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.953 ±(99.9%) 0.008 ms/op
Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
Iteration   3: 3.724 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.858 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (3.724, 3.858, 3.953), stdev = 0.119
  CI (99.9%): [1.683, 6.032] (assumes normal distribution)


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
# Warmup Iteration   1: 10.703 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.003 ms/op
Iteration   1: 3.678 ±(99.9%) 0.011 ms/op
Iteration   2: 3.772 ±(99.9%) 0.007 ms/op
Iteration   3: 3.658 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.703 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.658, 3.703, 3.772), stdev = 0.061
  CI (99.9%): [2.590, 4.815] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.338 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.873 ±(99.9%) 0.004 ms/op
Iteration   2: 3.845 ±(99.9%) 0.004 ms/op
Iteration   3: 3.831 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.850 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.831, 3.850, 3.873), stdev = 0.021
  CI (99.9%): [3.463, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 12.981 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.687 ±(99.9%) 0.007 ms/op
Iteration   1: 4.566 ±(99.9%) 0.007 ms/op
Iteration   2: 4.457 ±(99.9%) 0.015 ms/op
Iteration   3: 4.363 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.462 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (4.363, 4.462, 4.566), stdev = 0.101
  CI (99.9%): [2.611, 6.313] (assumes normal distribution)


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
# Warmup Iteration   1: 11.353 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.017 ms/op
Iteration   1: 3.888 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  20.044 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  11.590 ms/op
                 createUser·p0.9999: 29.757 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   3: 4.136 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.853 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  25.953 ms/op
                 createUser·p0.9999: 32.145 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242863
  mean =      3.952 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 548 
    [ 2.500,  5.000) = 225497 
    [ 5.000,  7.500) = 14048 
    [ 7.500, 10.000) = 2240 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     20.026 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     32.745 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 10.987 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.012 ms/op
Iteration   1: 3.642 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 26.484 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 3.743 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  24.609 ms/op
                 existUser·p0.9999: 28.122 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.597 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 30.544 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 262264
  mean =      3.660 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1272 
    [ 2.500,  5.000) = 254072 
    [ 5.000,  7.500) = 5455 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     14.709 ms/op
     p(99.9900) =     29.287 ms/op
     p(99.9990) =     31.462 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 11.572 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.015 ms/op
Iteration   1: 3.811 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 26.536 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.855 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   5.987 ms/op
                 getUser·p0.999:  25.791 ms/op
                 getUser·p0.9999: 28.194 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  11.065 ms/op
                 getUser·p0.9999: 33.039 ms/op
                 getUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250447
  mean =      3.831 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 847 
    [ 2.500,  5.000) = 238415 
    [ 5.000,  7.500) = 9965 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 146 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     32.013 ms/op
     p(99.9990) =     33.652 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 12.918 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.739 ±(99.9%) 0.018 ms/op
Iteration   1: 4.504 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  25.449 ms/op
                 listUser·p0.9999: 28.246 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 4.435 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.771 ms/op
                 listUser·p0.999:  18.018 ms/op
                 listUser·p0.9999: 23.066 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.496 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 18.146 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214364
  mean =      4.478 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 194718 
    [ 5.000,  7.500) = 15601 
    [ 7.500, 10.000) = 3178 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     27.544 ms/op
     p(99.9990) =     29.697 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.032 ± 5.597  ops/ms
ClientPb.existUser                       thrpt       3   8.520 ± 3.243  ops/ms
ClientPb.getUser                         thrpt       3   8.233 ± 4.855  ops/ms
ClientPb.listUser                        thrpt       3   7.119 ± 3.899  ops/ms
ClientPb.createUser                       avgt       3   3.858 ± 2.175   ms/op
ClientPb.existUser                        avgt       3   3.703 ± 1.112   ms/op
ClientPb.getUser                          avgt       3   3.850 ± 0.387   ms/op
ClientPb.listUser                         avgt       3   4.462 ± 1.851   ms/op
ClientPb.createUser                     sample  242863   3.952 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.651           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.026           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  262264   3.660 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.243           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  250447   3.831 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.059           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.691           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.013           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.817           ms/op
ClientPb.listUser                       sample  214364   4.478 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.786           ms/op
