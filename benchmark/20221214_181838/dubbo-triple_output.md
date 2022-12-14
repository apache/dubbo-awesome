# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 3.995 ops/ms
# Warmup Iteration   3: 7.308 ops/ms
Iteration   1: 7.729 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.767 ±(99.9%) 3.398 ops/ms [Average]
  (min, avg, max) = (7.603, 7.767, 7.970), stdev = 0.186
  CI (99.9%): [4.369, 11.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.377 ops/ms
# Warmup Iteration   2: 6.795 ops/ms
# Warmup Iteration   3: 7.685 ops/ms
Iteration   1: 8.308 ops/ms
Iteration   2: 8.665 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.383 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (8.177, 8.383, 8.665), stdev = 0.252
  CI (99.9%): [3.782, 12.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 6.262 ops/ms
# Warmup Iteration   3: 7.689 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.205 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (8.072, 8.205, 8.376), stdev = 0.155
  CI (99.9%): [5.372, 11.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.872 ops/ms
# Warmup Iteration   3: 6.839 ops/ms
Iteration   1: 6.987 ops/ms
Iteration   2: 6.835 ops/ms
Iteration   3: 6.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.912 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (6.835, 6.912, 6.987), stdev = 0.076
  CI (99.9%): [5.525, 8.300] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.263 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.647 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.984 ±(99.9%) 0.010 ms/op
Iteration   2: 3.956 ±(99.9%) 0.009 ms/op
Iteration   3: 3.877 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.939 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.877, 3.939, 3.984), stdev = 0.055
  CI (99.9%): [2.932, 4.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.049 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.005 ms/op
Iteration   1: 3.812 ±(99.9%) 0.006 ms/op
Iteration   2: 3.783 ±(99.9%) 0.011 ms/op
Iteration   3: 3.766 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.787 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.766, 3.787, 3.812), stdev = 0.023
  CI (99.9%): [3.360, 4.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.188 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.009 ms/op
Iteration   1: 3.810 ±(99.9%) 0.005 ms/op
Iteration   2: 4.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.761 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.887 ±(99.9%) 3.249 ms/op [Average]
  (min, avg, max) = (3.761, 3.887, 4.091), stdev = 0.178
  CI (99.9%): [0.638, 7.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.323 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.010 ms/op
Iteration   1: 4.607 ±(99.9%) 0.009 ms/op
Iteration   2: 4.721 ±(99.9%) 0.009 ms/op
Iteration   3: 4.514 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.614 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (4.514, 4.614, 4.721), stdev = 0.103
  CI (99.9%): [2.731, 6.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.151 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 5.218 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.019 ms/op
Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.940 ms/op
                 createUser·p0.999:  12.665 ms/op
                 createUser·p0.9999: 28.669 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  25.031 ms/op
                 createUser·p0.9999: 27.423 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  25.349 ms/op
                 createUser·p0.9999: 32.178 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249933
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 241903 
    [ 5.000,  7.500) = 6171 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 170 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     24.773 ms/op
     p(99.9900) =     30.868 ms/op
     p(99.9990) =     33.407 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.718 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.014 ms/op
Iteration   1: 3.785 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 31.115 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   2: 3.762 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  15.434 ms/op
                 existUser·p0.9999: 29.655 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252529
  mean =      3.798 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 242070 
    [ 5.000,  7.500) = 8411 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     16.244 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     31.502 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.806 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.827 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.015 ms/op
Iteration   1: 3.987 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  23.200 ms/op
                 getUser·p0.9999: 25.846 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 26.659 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 4.063 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  27.001 ms/op
                 getUser·p0.9999: 30.504 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243258
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 234056 
    [ 5.000,  7.500) = 6277 
    [ 7.500, 10.000) = 2073 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     23.150 ms/op
     p(99.9900) =     29.284 ms/op
     p(99.9990) =     31.264 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.652 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.833 ±(99.9%) 0.017 ms/op
Iteration   1: 4.592 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  25.441 ms/op
                 listUser·p0.9999: 29.786 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 4.596 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  18.067 ms/op
                 listUser·p0.9999: 20.774 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 4.731 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.308 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206892
  mean =      4.639 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 186442 
    [ 5.000,  7.500) = 15236 
    [ 7.500, 10.000) = 4068 
    [10.000, 12.500) = 472 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.991 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     19.304 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.421 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.767 ± 3.398  ops/ms
ClientPb.existUser                       thrpt       3   8.383 ± 4.602  ops/ms
ClientPb.getUser                         thrpt       3   8.205 ± 2.833  ops/ms
ClientPb.listUser                        thrpt       3   6.912 ± 1.387  ops/ms
ClientPb.createUser                       avgt       3   3.939 ± 1.007   ms/op
ClientPb.existUser                        avgt       3   3.787 ± 0.427   ms/op
ClientPb.getUser                          avgt       3   3.887 ± 3.249   ms/op
ClientPb.listUser                         avgt       3   4.614 ± 1.883   ms/op
ClientPb.createUser                     sample  249933   3.841 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.773           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.868           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  252529   3.798 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.244           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.753           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  243258   3.943 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.284           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.047           ms/op
ClientPb.listUser                       sample  206892   4.639 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.991           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.262           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
