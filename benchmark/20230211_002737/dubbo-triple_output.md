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
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 5.856 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.202 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 9.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.038 ±(99.9%) 3.621 ops/ms [Average]
  (min, avg, max) = (9.817, 10.038, 10.202), stdev = 0.198
  CI (99.9%): [6.417, 13.659] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ops/ms
# Warmup Iteration   2: 9.394 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.424 ±(99.9%) 3.073 ops/ms [Average]
  (min, avg, max) = (10.253, 10.424, 10.590), stdev = 0.168
  CI (99.9%): [7.351, 13.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.275 ±(99.9%) 3.688 ops/ms [Average]
  (min, avg, max) = (10.080, 10.275, 10.484), stdev = 0.202
  CI (99.9%): [6.587, 13.962] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 7.828 ops/ms
# Warmup Iteration   3: 8.349 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.601 ops/ms
Iteration   3: 8.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 2.249 ops/ms [Average]
  (min, avg, max) = (8.422, 8.561, 8.659), stdev = 0.123
  CI (99.9%): [6.312, 10.809] (assumes normal distribution)


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
# Warmup Iteration   1: 7.699 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.004 ms/op
Iteration   1: 3.305 ±(99.9%) 0.004 ms/op
Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
Iteration   3: 3.180 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.226 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.180, 3.226, 3.305), stdev = 0.069
  CI (99.9%): [1.972, 4.480] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.081 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.005 ms/op
Iteration   1: 3.096 ±(99.9%) 0.010 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 3.211 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.100 ±(99.9%) 2.000 ms/op [Average]
  (min, avg, max) = (2.992, 3.100, 3.211), stdev = 0.110
  CI (99.9%): [1.100, 5.099] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.170 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.005 ms/op
Iteration   2: 3.162 ±(99.9%) 0.001 ms/op
Iteration   3: 3.147 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.147, 3.163, 3.179), stdev = 0.016
  CI (99.9%): [2.875, 3.450] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.439 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.003 ms/op
Iteration   1: 3.829 ±(99.9%) 0.008 ms/op
Iteration   2: 3.756 ±(99.9%) 0.005 ms/op
Iteration   3: 3.596 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 2.181 ms/op [Average]
  (min, avg, max) = (3.596, 3.727, 3.829), stdev = 0.120
  CI (99.9%): [1.546, 5.908] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.462 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
Iteration   1: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 21.000 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  18.390 ms/op
                 createUser·p0.9999: 24.360 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  16.572 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294569
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22158 
    [ 2.500,  5.000) = 266354 
    [ 5.000,  7.500) = 5057 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.905 ms/op
     p(99.9900) =     24.332 ms/op
     p(99.9990) =     27.010 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.089 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.501 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  13.131 ms/op
                 existUser·p0.9999: 28.246 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   2: 3.137 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.265 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  14.302 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.352 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  13.963 ms/op
                 existUser·p0.9999: 22.819 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300997
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18530 
    [ 2.500,  5.000) = 270322 
    [ 5.000,  7.500) = 10983 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.265 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      4.539 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     28.866 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 7.072 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.013 ms/op
Iteration   1: 3.209 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.969 ms/op
                 getUser·p0.999:  16.666 ms/op
                 getUser·p0.9999: 21.268 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  19.981 ms/op
                 getUser·p0.9999: 22.774 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 20.904 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302590
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11878 
    [ 2.500,  5.000) = 286995 
    [ 5.000,  7.500) = 2987 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     17.191 ms/op
     p(99.9900) =     22.175 ms/op
     p(99.9990) =     23.584 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 9.608 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 3.650 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.601 ms/op
                 listUser·p0.9999: 16.951 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259604
  mean =      3.692 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 252184 
    [ 5.000,  7.500) = 5451 
    [ 7.500, 10.000) = 1236 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     20.451 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.038 ± 3.621  ops/ms
ClientPb.existUser                       thrpt       3  10.424 ± 3.073  ops/ms
ClientPb.getUser                         thrpt       3  10.275 ± 3.688  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 2.249  ops/ms
ClientPb.createUser                       avgt       3   3.226 ± 1.254   ms/op
ClientPb.existUser                        avgt       3   3.100 ± 2.000   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 2.181   ms/op
ClientPb.createUser                     sample  294569   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.905           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.332           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  300997   3.189 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.265           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.539           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.201           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  302590   3.170 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.175           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  259604   3.692 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.568           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.451           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
