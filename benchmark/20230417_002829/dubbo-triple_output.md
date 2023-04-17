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
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.645 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (9.516, 9.645, 9.766), stdev = 0.125
  CI (99.9%): [7.357, 11.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 9.215 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.314 ±(99.9%) 5.050 ops/ms [Average]
  (min, avg, max) = (9.996, 10.314, 10.499), stdev = 0.277
  CI (99.9%): [5.263, 15.364] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 9.882 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.219 ±(99.9%) 4.151 ops/ms [Average]
  (min, avg, max) = (9.965, 10.219, 10.404), stdev = 0.228
  CI (99.9%): [6.068, 14.370] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.575 ops/ms
Iteration   2: 8.646 ops/ms
Iteration   3: 8.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.630 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (8.575, 8.630, 8.668), stdev = 0.049
  CI (99.9%): [7.741, 9.518] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.251 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.002 ms/op
Iteration   1: 3.304 ±(99.9%) 0.005 ms/op
Iteration   2: 3.180 ±(99.9%) 0.005 ms/op
Iteration   3: 3.255 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.247 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.180, 3.247, 3.304), stdev = 0.063
  CI (99.9%): [2.103, 4.390] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.665 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.109 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.086, 3.101, 3.109), stdev = 0.013
  CI (99.9%): [2.860, 3.342] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.573 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.002 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.129 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.144 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (3.129, 3.144, 3.156), stdev = 0.014
  CI (99.9%): [2.892, 3.395] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.975 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.005 ms/op
Iteration   1: 3.695 ±(99.9%) 0.004 ms/op
Iteration   2: 3.629 ±(99.9%) 0.010 ms/op
Iteration   3: 3.609 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.644 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.609, 3.644, 3.695), stdev = 0.045
  CI (99.9%): [2.818, 4.471] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.512 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
Iteration   1: 3.169 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 18.838 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 20.405 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.534 ms/op
                 createUser·p0.999:  15.146 ms/op
                 createUser·p0.9999: 20.254 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302097
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22568 
    [ 2.500,  5.000) = 274708 
    [ 5.000,  7.500) = 3656 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     15.742 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     20.807 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 7.093 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  11.762 ms/op
                 existUser·p0.9999: 19.978 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 24.941 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  12.657 ms/op
                 existUser·p0.9999: 21.121 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311853
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17371 
    [ 2.500,  5.000) = 287921 
    [ 5.000,  7.500) = 5554 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     12.274 ms/op
     p(99.9900) =     22.919 ms/op
     p(99.9990) =     25.474 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.894 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
Iteration   1: 3.343 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  16.428 ms/op
                 getUser·p0.9999: 19.741 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.711 ms/op
                 getUser·p0.9999: 20.877 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  12.563 ms/op
                 getUser·p0.9999: 22.685 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293122
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24542 
    [ 2.500,  5.000) = 261332 
    [ 5.000,  7.500) = 6171 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.293 ms/op
     p(99.9900) =     21.082 ms/op
     p(99.9990) =     23.171 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 8.577 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.013 ms/op
Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  18.007 ms/op
                 listUser·p0.9999: 21.481 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.822 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.049 ms/op
                 listUser·p0.999:  13.735 ms/op
                 listUser·p0.9999: 16.477 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 3.725 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.380 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253926
  mean =      3.776 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 245982 
    [ 5.000,  7.500) = 5916 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.911 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     22.186 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.645 ± 2.288  ops/ms
ClientPb.existUser                       thrpt       3  10.314 ± 5.050  ops/ms
ClientPb.getUser                         thrpt       3  10.219 ± 4.151  ops/ms
ClientPb.listUser                        thrpt       3   8.630 ± 0.889  ops/ms
ClientPb.createUser                       avgt       3   3.247 ± 1.143   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   3.144 ± 0.251   ms/op
ClientPb.listUser                         avgt       3   3.644 ± 0.826   ms/op
ClientPb.createUser                     sample  302097   3.177 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.759           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.627           ms/op
ClientPb.existUser                      sample  311853   3.078 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.077           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.274           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.919           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.788           ms/op
ClientPb.getUser                        sample  293122   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.902           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.293           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.082           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.298           ms/op
ClientPb.listUser                       sample  253926   3.776 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.911           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.644           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
