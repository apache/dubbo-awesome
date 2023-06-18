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
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 8.742 ops/ms
Iteration   1: 8.953 ops/ms
Iteration   2: 8.982 ops/ms
Iteration   3: 9.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.154 ±(99.9%) 5.899 ops/ms [Average]
  (min, avg, max) = (8.953, 9.154, 9.527), stdev = 0.323
  CI (99.9%): [3.255, 15.054] (assumes normal distribution)


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
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.550 ops/ms
# Warmup Iteration   3: 9.495 ops/ms
Iteration   1: 9.723 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.741 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (9.626, 9.741, 9.875), stdev = 0.125
  CI (99.9%): [7.452, 12.030] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.807 ops/ms
# Warmup Iteration   2: 8.282 ops/ms
# Warmup Iteration   3: 8.813 ops/ms
Iteration   1: 9.360 ops/ms
Iteration   2: 9.345 ops/ms
Iteration   3: 9.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.286 ±(99.9%) 2.109 ops/ms [Average]
  (min, avg, max) = (9.153, 9.286, 9.360), stdev = 0.116
  CI (99.9%): [7.177, 11.395] (assumes normal distribution)


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
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 7.223 ops/ms
# Warmup Iteration   3: 7.352 ops/ms
Iteration   1: 7.606 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 7.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.807 ±(99.9%) 3.601 ops/ms [Average]
  (min, avg, max) = (7.606, 7.807, 8.001), stdev = 0.197
  CI (99.9%): [4.205, 11.408] (assumes normal distribution)


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
# Warmup Iteration   1: 8.100 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.007 ms/op
Iteration   1: 3.555 ±(99.9%) 0.004 ms/op
Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
Iteration   3: 3.500 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.534 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.500, 3.534, 3.555), stdev = 0.029
  CI (99.9%): [2.998, 4.070] (assumes normal distribution)


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
# Warmup Iteration   1: 8.337 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.005 ms/op
Iteration   1: 3.315 ±(99.9%) 0.005 ms/op
Iteration   2: 3.269 ±(99.9%) 0.005 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (3.269, 3.328, 3.399), stdev = 0.066
  CI (99.9%): [2.130, 4.525] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.832 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.011 ms/op
Iteration   1: 3.457 ±(99.9%) 0.006 ms/op
Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
Iteration   3: 3.407 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.384 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.288, 3.384, 3.457), stdev = 0.087
  CI (99.9%): [1.793, 4.975] (assumes normal distribution)


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
# Warmup Iteration   1: 11.775 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.007 ms/op
Iteration   1: 4.130 ±(99.9%) 0.007 ms/op
Iteration   2: 3.994 ±(99.9%) 0.014 ms/op
Iteration   3: 4.155 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.093 ±(99.9%) 1.583 ms/op [Average]
  (min, avg, max) = (3.994, 4.093, 4.155), stdev = 0.087
  CI (99.9%): [2.510, 5.676] (assumes normal distribution)


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
# Warmup Iteration   1: 8.522 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.010 ms/op
Iteration   1: 3.405 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.667 ms/op
                 createUser·p0.999:  18.942 ms/op
                 createUser·p0.9999: 21.372 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.388 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.409 ms/op
                 createUser·p0.9999: 25.235 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.588 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  18.792 ms/op
                 createUser·p0.9999: 26.554 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277565
  mean =      3.458 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9975 
    [ 2.500,  5.000) = 259995 
    [ 5.000,  7.500) = 6772 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     18.856 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.511 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 7.666 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.008 ms/op
Iteration   1: 3.464 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.012 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  20.349 ms/op
                 existUser·p0.9999: 24.077 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 3.448 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  22.394 ms/op
                 existUser·p0.9999: 32.496 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   3: 3.385 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.618 ms/op
                 existUser·p0.9999: 25.529 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279593
  mean =      3.432 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13519 
    [ 2.500,  5.000) = 259057 
    [ 5.000,  7.500) = 6276 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     30.968 ms/op
     p(99.9990) =     33.208 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 11.113 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.011 ms/op
Iteration   1: 3.576 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  21.135 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  20.823 ms/op
                 getUser·p0.9999: 28.350 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   3: 3.556 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.134 ms/op
                 getUser·p0.999:  16.813 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270690
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1684 
    [ 2.500,  5.000) = 260456 
    [ 5.000,  7.500) = 6875 
    [ 7.500, 10.000) = 952 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.546 ms/op
     p(99.9000) =     19.626 ms/op
     p(99.9900) =     27.415 ms/op
     p(99.9990) =     28.704 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
Iteration   1: 4.206 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 30.029 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   2: 3.986 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.558 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.443 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 17.562 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.957 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 16.202 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237170
  mean =      4.047 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 228369 
    [ 5.000,  7.500) = 6280 
    [ 7.500, 10.000) = 1663 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     30.167 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.154 ± 5.899  ops/ms
ClientPb.existUser                       thrpt       3   9.741 ± 2.289  ops/ms
ClientPb.getUser                         thrpt       3   9.286 ± 2.109  ops/ms
ClientPb.listUser                        thrpt       3   7.807 ± 3.601  ops/ms
ClientPb.createUser                       avgt       3   3.534 ± 0.536   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 1.197   ms/op
ClientPb.getUser                          avgt       3   3.384 ± 1.591   ms/op
ClientPb.listUser                         avgt       3   4.093 ± 1.583   ms/op
ClientPb.createUser                     sample  277565   3.458 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.856           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.494           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  279593   3.432 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.968           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  270690   3.543 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.626           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  237170   4.047 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.558           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.327           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.245           ms/op
