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
# Warmup Iteration   1: 1.050 ops/ms
# Warmup Iteration   2: 2.469 ops/ms
# Warmup Iteration   3: 5.417 ops/ms
Iteration   1: 6.262 ops/ms
Iteration   2: 6.663 ops/ms
Iteration   3: 6.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.490 ±(99.9%) 3.749 ops/ms [Average]
  (min, avg, max) = (6.262, 6.490, 6.663), stdev = 0.205
  CI (99.9%): [2.741, 10.238] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.855 ops/ms
# Warmup Iteration   2: 5.202 ops/ms
# Warmup Iteration   3: 6.069 ops/ms
Iteration   1: 6.481 ops/ms
Iteration   2: 6.648 ops/ms
Iteration   3: 6.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.663 ±(99.9%) 3.446 ops/ms [Average]
  (min, avg, max) = (6.481, 6.663, 6.858), stdev = 0.189
  CI (99.9%): [3.217, 10.108] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 5.560 ops/ms
# Warmup Iteration   3: 6.150 ops/ms
Iteration   1: 6.346 ops/ms
Iteration   2: 6.695 ops/ms
Iteration   3: 6.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.559 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (6.346, 6.559, 6.695), stdev = 0.187
  CI (99.9%): [3.155, 9.963] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.795 ops/ms
# Warmup Iteration   2: 4.660 ops/ms
# Warmup Iteration   3: 4.931 ops/ms
Iteration   1: 5.603 ops/ms
Iteration   2: 5.446 ops/ms
Iteration   3: 5.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.487 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (5.412, 5.487, 5.603), stdev = 0.101
  CI (99.9%): [3.636, 7.338] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.476 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.586 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.012 ms/op
Iteration   1: 4.786 ±(99.9%) 0.010 ms/op
Iteration   2: 5.109 ±(99.9%) 0.012 ms/op
Iteration   3: 5.112 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.002 ±(99.9%) 3.420 ms/op [Average]
  (min, avg, max) = (4.786, 5.002, 5.112), stdev = 0.187
  CI (99.9%): [1.582, 8.422] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.298 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.009 ms/op
Iteration   1: 4.934 ±(99.9%) 0.009 ms/op
Iteration   2: 4.915 ±(99.9%) 0.015 ms/op
Iteration   3: 4.743 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.864 ±(99.9%) 1.923 ms/op [Average]
  (min, avg, max) = (4.743, 4.864, 4.934), stdev = 0.105
  CI (99.9%): [2.941, 6.787] (assumes normal distribution)


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
# Warmup Iteration   1: 14.886 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.567 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.008 ms/op
Iteration   1: 4.960 ±(99.9%) 0.008 ms/op
Iteration   2: 5.279 ±(99.9%) 0.010 ms/op
Iteration   3: 4.982 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.073 ±(99.9%) 3.251 ms/op [Average]
  (min, avg, max) = (4.960, 5.073, 5.279), stdev = 0.178
  CI (99.9%): [1.822, 8.325] (assumes normal distribution)


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
# Warmup Iteration   1: 16.239 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.461 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.003 ±(99.9%) 0.015 ms/op
Iteration   1: 5.975 ±(99.9%) 0.011 ms/op
Iteration   2: 5.913 ±(99.9%) 0.017 ms/op
Iteration   3: 5.795 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.894 ±(99.9%) 1.662 ms/op [Average]
  (min, avg, max) = (5.795, 5.894, 5.975), stdev = 0.091
  CI (99.9%): [4.232, 7.557] (assumes normal distribution)


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
# Warmup Iteration   1: 14.347 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 6.008 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.020 ms/op
Iteration   1: 4.771 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 25.176 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 5.027 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.037 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  24.521 ms/op
                 createUser·p0.9999: 29.136 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 5.455 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   7.045 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   13.517 ms/op
                 createUser·p0.999:  26.404 ms/op
                 createUser·p0.9999: 31.106 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189332
  mean =      5.069 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 118078 
    [ 5.000,  7.500) = 62543 
    [ 7.500, 10.000) = 6142 
    [10.000, 12.500) = 1445 
    [12.500, 15.000) = 602 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     22.686 ms/op
     p(99.9900) =     30.247 ms/op
     p(99.9990) =     31.525 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 16.133 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.016 ms/op
Iteration   1: 4.827 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.290 ms/op
                 existUser·p0.999:  19.303 ms/op
                 existUser·p0.9999: 27.832 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 4.877 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.960 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  18.658 ms/op
                 existUser·p0.9999: 26.891 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 5.294 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.922 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  27.926 ms/op
                 existUser·p0.9999: 37.149 ms/op
                 existUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192214
  mean =      4.991 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 126322 
    [ 5.000, 10.000) = 63647 
    [10.000, 15.000) = 1931 
    [15.000, 20.000) = 120 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     22.590 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     42.291 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 17.151 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.970 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.421 ±(99.9%) 0.020 ms/op
Iteration   1: 5.573 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   12.173 ms/op
                 getUser·p0.999:  24.347 ms/op
                 getUser·p0.9999: 30.614 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   2: 5.131 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  25.857 ms/op
                 getUser·p0.9999: 37.199 ms/op
                 getUser·p1.00:   38.011 ms/op

Iteration   3: 5.229 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   9.060 ms/op
                 getUser·p0.999:  26.277 ms/op
                 getUser·p0.9999: 34.698 ms/op
                 getUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180789
  mean =      5.305 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 86466 
    [ 5.000,  7.500) = 86111 
    [ 7.500, 10.000) = 5952 
    [10.000, 12.500) = 1436 
    [12.500, 15.000) = 446 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     24.636 ms/op
     p(99.9900) =     35.646 ms/op
     p(99.9990) =     37.746 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 18.613 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 6.920 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.023 ms/op
Iteration   1: 5.647 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  25.946 ms/op
                 listUser·p0.9999: 31.266 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 5.936 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.043 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  28.082 ms/op
                 listUser·p0.9999: 31.563 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   3: 5.830 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 23.202 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165408
  mean =      5.802 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 36042 
    [ 5.000,  7.500) = 118452 
    [ 7.500, 10.000) = 8691 
    [10.000, 12.500) = 1457 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.552 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     25.087 ms/op
     p(99.9900) =     31.210 ms/op
     p(99.9990) =     32.812 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.490 ± 3.749  ops/ms
ClientPb.existUser                       thrpt       3   6.663 ± 3.446  ops/ms
ClientPb.getUser                         thrpt       3   6.559 ± 3.404  ops/ms
ClientPb.listUser                        thrpt       3   5.487 ± 1.851  ops/ms
ClientPb.createUser                       avgt       3   5.002 ± 3.420   ms/op
ClientPb.existUser                        avgt       3   4.864 ± 1.923   ms/op
ClientPb.getUser                          avgt       3   5.073 ± 3.251   ms/op
ClientPb.listUser                         avgt       3   5.894 ± 1.662   ms/op
ClientPb.createUser                     sample  189332   5.069 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.686           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.247           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.818           ms/op
ClientPb.existUser                      sample  192214   4.991 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.655           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.590           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.533           ms/op
ClientPb.getUser                        sample  180789   5.305 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.453           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.646           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.011           ms/op
ClientPb.listUser                       sample  165408   5.802 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.552           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.087           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.391           ms/op
