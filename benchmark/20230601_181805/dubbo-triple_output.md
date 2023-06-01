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
# Warmup Iteration   1: 1.910 ops/ms
# Warmup Iteration   2: 5.816 ops/ms
# Warmup Iteration   3: 8.753 ops/ms
Iteration   1: 9.222 ops/ms
Iteration   2: 9.012 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.275 ±(99.9%) 5.341 ops/ms [Average]
  (min, avg, max) = (9.012, 9.275, 9.590), stdev = 0.293
  CI (99.9%): [3.933, 14.616] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.654 ops/ms
# Warmup Iteration   2: 8.012 ops/ms
# Warmup Iteration   3: 9.143 ops/ms
Iteration   1: 9.564 ops/ms
Iteration   2: 9.650 ops/ms
Iteration   3: 9.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.510 ±(99.9%) 3.148 ops/ms [Average]
  (min, avg, max) = (9.317, 9.510, 9.650), stdev = 0.173
  CI (99.9%): [6.362, 12.658] (assumes normal distribution)


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
# Warmup Iteration   1: 2.725 ops/ms
# Warmup Iteration   2: 8.406 ops/ms
# Warmup Iteration   3: 9.102 ops/ms
Iteration   1: 9.171 ops/ms
Iteration   2: 9.265 ops/ms
Iteration   3: 9.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.262 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (9.171, 9.262, 9.350), stdev = 0.090
  CI (99.9%): [7.627, 10.896] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 7.004 ops/ms
# Warmup Iteration   3: 7.615 ops/ms
Iteration   1: 7.555 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 7.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.805 ±(99.9%) 4.610 ops/ms [Average]
  (min, avg, max) = (7.555, 7.805, 8.060), stdev = 0.253
  CI (99.9%): [3.196, 12.415] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.732 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.005 ms/op
Iteration   1: 3.579 ±(99.9%) 0.009 ms/op
Iteration   2: 3.409 ±(99.9%) 0.007 ms/op
Iteration   3: 3.449 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 1.620 ms/op [Average]
  (min, avg, max) = (3.409, 3.479, 3.579), stdev = 0.089
  CI (99.9%): [1.860, 5.099] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.333 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.004 ms/op
Iteration   1: 3.318 ±(99.9%) 0.003 ms/op
Iteration   2: 3.456 ±(99.9%) 0.005 ms/op
Iteration   3: 3.279 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 1.693 ms/op [Average]
  (min, avg, max) = (3.279, 3.351, 3.456), stdev = 0.093
  CI (99.9%): [1.658, 5.044] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.476 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.004 ms/op
Iteration   1: 3.551 ±(99.9%) 0.007 ms/op
Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
Iteration   3: 3.400 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (3.393, 3.448, 3.551), stdev = 0.089
  CI (99.9%): [1.825, 5.071] (assumes normal distribution)


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
# Warmup Iteration   1: 11.273 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.008 ms/op
Iteration   1: 4.236 ±(99.9%) 0.005 ms/op
Iteration   2: 3.992 ±(99.9%) 0.014 ms/op
Iteration   3: 4.001 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.076 ±(99.9%) 2.531 ms/op [Average]
  (min, avg, max) = (3.992, 4.076, 4.236), stdev = 0.139
  CI (99.9%): [1.546, 6.607] (assumes normal distribution)


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
# Warmup Iteration   1: 9.372 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.011 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  20.661 ms/op
                 createUser·p0.9999: 22.682 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.466 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  22.964 ms/op
                 createUser·p0.9999: 26.043 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 26.859 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279006
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8093 
    [ 2.500,  5.000) = 264518 
    [ 5.000,  7.500) = 5195 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.860 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 10.387 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  20.607 ms/op
                 existUser·p0.9999: 26.538 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  19.933 ms/op
                 existUser·p0.9999: 24.009 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.032 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285557
  mean =      3.361 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6452 
    [ 2.500,  5.000) = 273912 
    [ 5.000,  7.500) = 4082 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     13.047 ms/op
     p(99.9900) =     26.291 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 11.279 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.009 ms/op
Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.066 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  19.323 ms/op
                 getUser·p0.9999: 24.047 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.488 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  21.515 ms/op
                 getUser·p0.9999: 26.635 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  18.270 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271738
  mean =      3.531 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 672 
    [ 2.500,  5.000) = 262609 
    [ 5.000,  7.500) = 7069 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     26.012 ms/op
     p(99.9990) =     26.963 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 11.589 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
Iteration   1: 4.048 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  21.853 ms/op
                 listUser·p0.9999: 28.714 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 4.152 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.681 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 21.113 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 4.005 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235777
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 225129 
    [ 5.000,  7.500) = 8079 
    [ 7.500, 10.000) = 1599 
    [10.000, 12.500) = 504 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     16.224 ms/op
     p(99.9900) =     27.225 ms/op
     p(99.9990) =     29.009 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.275 ± 5.341  ops/ms
ClientPb.existUser                       thrpt       3   9.510 ± 3.148  ops/ms
ClientPb.getUser                         thrpt       3   9.262 ± 1.634  ops/ms
ClientPb.listUser                        thrpt       3   7.805 ± 4.610  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 1.620   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 1.693   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 1.623   ms/op
ClientPb.listUser                         avgt       3   4.076 ± 2.531   ms/op
ClientPb.createUser                     sample  279006   3.436 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.964           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.952           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.017           ms/op
ClientPb.existUser                      sample  285557   3.361 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.047           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.291           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  271738   3.531 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.012           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  235777   4.067 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.225           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
