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
# Warmup Iteration   1: 2.434 ops/ms
# Warmup Iteration   2: 6.584 ops/ms
# Warmup Iteration   3: 8.711 ops/ms
Iteration   1: 10.224 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.214 ±(99.9%) 2.109 ops/ms [Average]
  (min, avg, max) = (10.093, 10.214, 10.324), stdev = 0.116
  CI (99.9%): [8.105, 12.323] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.610 ops/ms
# Warmup Iteration   2: 9.363 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.246 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.280 ±(99.9%) 4.289 ops/ms [Average]
  (min, avg, max) = (10.063, 10.280, 10.530), stdev = 0.235
  CI (99.9%): [5.990, 14.569] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ops/ms
# Warmup Iteration   2: 8.627 ops/ms
# Warmup Iteration   3: 9.756 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 9.646 ops/ms
Iteration   3: 10.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.908 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (9.646, 9.908, 10.109), stdev = 0.238
  CI (99.9%): [5.571, 14.244] (assumes normal distribution)


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
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 8.340 ops/ms
Iteration   1: 8.462 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.279 ±(99.9%) 5.548 ops/ms [Average]
  (min, avg, max) = (7.928, 8.279, 8.462), stdev = 0.304
  CI (99.9%): [2.731, 13.827] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.424 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.005 ms/op
Iteration   1: 3.250 ±(99.9%) 0.009 ms/op
Iteration   2: 3.292 ±(99.9%) 0.005 ms/op
Iteration   3: 3.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.236 ±(99.9%) 1.178 ms/op [Average]
  (min, avg, max) = (3.166, 3.236, 3.292), stdev = 0.065
  CI (99.9%): [2.058, 4.414] (assumes normal distribution)


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
# Warmup Iteration   1: 7.834 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
Iteration   3: 3.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (3.042, 3.131, 3.248), stdev = 0.106
  CI (99.9%): [1.196, 5.067] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.610 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.002 ms/op
Iteration   1: 3.307 ±(99.9%) 0.004 ms/op
Iteration   2: 3.159 ±(99.9%) 0.004 ms/op
Iteration   3: 3.136 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (3.136, 3.201, 3.307), stdev = 0.093
  CI (99.9%): [1.505, 4.896] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.210 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.007 ms/op
Iteration   1: 3.790 ±(99.9%) 0.009 ms/op
Iteration   2: 3.850 ±(99.9%) 0.007 ms/op
Iteration   3: 3.824 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.821 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.790, 3.821, 3.850), stdev = 0.030
  CI (99.9%): [3.277, 4.366] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.801 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  16.056 ms/op
                 createUser·p0.9999: 27.118 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  19.404 ms/op
                 createUser·p0.9999: 22.775 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.720 ms/op
                 createUser·p0.999:  16.024 ms/op
                 createUser·p0.9999: 22.763 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297576
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21725 
    [ 2.500,  5.000) = 270242 
    [ 5.000,  7.500) = 4621 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.955 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     28.149 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 7.371 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  8.646 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  13.384 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 24.335 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304821
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16379 
    [ 2.500,  5.000) = 283127 
    [ 5.000,  7.500) = 4609 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     11.685 ms/op
     p(99.9900) =     25.576 ms/op
     p(99.9990) =     28.166 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 7.343 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.012 ms/op
Iteration   1: 3.225 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 23.219 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296600
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15567 
    [ 2.500,  5.000) = 274379 
    [ 5.000,  7.500) = 5754 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     24.030 ms/op
     p(99.9990) =     25.353 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 9.409 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.012 ms/op
Iteration   1: 3.822 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 24.113 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.776 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 14.754 ms/op
                 listUser·p1.00:   16.155 ms/op

Iteration   3: 3.863 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  12.974 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251122
  mean =      3.820 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 243917 
    [ 5.000,  7.500) = 5039 
    [ 7.500, 10.000) = 1477 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     21.951 ms/op
     p(99.9990) =     24.345 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.214 ± 2.109  ops/ms
ClientPb.existUser                       thrpt       3  10.280 ± 4.289  ops/ms
ClientPb.getUser                         thrpt       3   9.908 ± 4.337  ops/ms
ClientPb.listUser                        thrpt       3   8.279 ± 5.548  ops/ms
ClientPb.createUser                       avgt       3   3.236 ± 1.178   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 1.936   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 1.696   ms/op
ClientPb.listUser                         avgt       3   3.821 ± 0.545   ms/op
ClientPb.createUser                     sample  297576   3.224 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.279           ms/op
ClientPb.existUser                      sample  304821   3.150 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.685           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  296600   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.941           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.030           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.083           ms/op
ClientPb.listUser                       sample  251122   3.820 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.682           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.951           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
