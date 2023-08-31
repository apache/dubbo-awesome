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
# Warmup Iteration   1: 2.001 ops/ms
# Warmup Iteration   2: 5.431 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.838 ops/ms
Iteration   2: 9.332 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.219 ±(99.9%) 6.200 ops/ms [Average]
  (min, avg, max) = (8.838, 9.219, 9.489), stdev = 0.340
  CI (99.9%): [3.020, 15.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.129 ops/ms
# Warmup Iteration   2: 8.675 ops/ms
# Warmup Iteration   3: 9.844 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.908 ops/ms
Iteration   3: 9.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.726 ±(99.9%) 4.556 ops/ms [Average]
  (min, avg, max) = (9.441, 9.726, 9.908), stdev = 0.250
  CI (99.9%): [5.169, 14.282] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 8.220 ops/ms
# Warmup Iteration   3: 9.187 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.426 ±(99.9%) 2.808 ops/ms [Average]
  (min, avg, max) = (9.249, 9.426, 9.527), stdev = 0.154
  CI (99.9%): [6.618, 12.234] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 7.205 ops/ms
# Warmup Iteration   3: 7.512 ops/ms
Iteration   1: 7.756 ops/ms
Iteration   2: 7.943 ops/ms
Iteration   3: 7.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.766 ±(99.9%) 3.150 ops/ms [Average]
  (min, avg, max) = (7.599, 7.766, 7.943), stdev = 0.173
  CI (99.9%): [4.616, 10.915] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.607 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.004 ms/op
Iteration   1: 3.459 ±(99.9%) 0.003 ms/op
Iteration   2: 3.473 ±(99.9%) 0.008 ms/op
Iteration   3: 3.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.483 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.459, 3.483, 3.516), stdev = 0.030
  CI (99.9%): [2.944, 4.022] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.874 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.006 ms/op
Iteration   1: 3.460 ±(99.9%) 0.006 ms/op
Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
Iteration   3: 3.459 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.423 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (3.349, 3.423, 3.460), stdev = 0.064
  CI (99.9%): [2.264, 4.581] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.503 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.006 ms/op
Iteration   1: 3.548 ±(99.9%) 0.006 ms/op
Iteration   2: 3.423 ±(99.9%) 0.004 ms/op
Iteration   3: 3.562 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.511 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.423, 3.511, 3.562), stdev = 0.076
  CI (99.9%): [2.117, 4.905] (assumes normal distribution)


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
# Warmup Iteration   1: 12.336 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.004 ms/op
Iteration   1: 4.127 ±(99.9%) 0.007 ms/op
Iteration   2: 4.041 ±(99.9%) 0.009 ms/op
Iteration   3: 4.002 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.056 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (4.002, 4.056, 4.127), stdev = 0.064
  CI (99.9%): [2.890, 5.223] (assumes normal distribution)


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
# Warmup Iteration   1: 10.503 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.018 ms/op
Iteration   1: 3.592 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  21.560 ms/op
                 createUser·p0.9999: 30.477 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 3.466 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.401 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  21.883 ms/op
                 createUser·p0.9999: 30.270 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   6.157 ms/op
                 createUser·p0.999:  24.070 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274678
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9338 
    [ 2.500,  5.000) = 255246 
    [ 5.000,  7.500) = 8545 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.849 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  9.663 ms/op
                 existUser·p0.9999: 23.966 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  21.688 ms/op
                 existUser·p0.9999: 25.513 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  21.037 ms/op
                 existUser·p0.9999: 25.579 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281989
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6300 
    [ 2.500,  5.000) = 269266 
    [ 5.000,  7.500) = 4892 
    [ 7.500, 10.000) = 1090 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     14.058 ms/op
     p(99.9900) =     25.258 ms/op
     p(99.9990) =     26.548 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 10.168 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.012 ms/op
Iteration   1: 3.666 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  21.955 ms/op
                 getUser·p0.9999: 38.084 ms/op
                 getUser·p1.00:   39.125 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.962 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  23.088 ms/op
                 getUser·p0.9999: 27.682 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  19.514 ms/op
                 getUser·p0.9999: 29.258 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270594
  mean =      3.547 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2472 
    [ 2.500,  5.000) = 257253 
    [ 5.000,  7.500) = 8332 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     20.244 ms/op
     p(99.9900) =     35.964 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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
# Warmup Iteration   1: 12.920 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.015 ms/op
Iteration   1: 4.113 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.071 ms/op
                 listUser·p0.999:  20.590 ms/op
                 listUser·p0.9999: 25.031 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  16.079 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.111 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.251 ms/op
                 listUser·p0.999:  14.032 ms/op
                 listUser·p0.9999: 22.421 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234453
  mean =      4.092 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 222577 
    [ 5.000,  7.500) = 8627 
    [ 7.500, 10.000) = 2074 
    [10.000, 12.500) = 580 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.470 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.219 ± 6.200  ops/ms
ClientPb.existUser                       thrpt       3   9.726 ± 4.556  ops/ms
ClientPb.getUser                         thrpt       3   9.426 ± 2.808  ops/ms
ClientPb.listUser                        thrpt       3   7.766 ± 3.150  ops/ms
ClientPb.createUser                       avgt       3   3.483 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   3.423 ± 1.159   ms/op
ClientPb.getUser                          avgt       3   3.511 ± 1.394   ms/op
ClientPb.listUser                         avgt       3   4.056 ± 1.167   ms/op
ClientPb.createUser                     sample  274678   3.492 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.806           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.950           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  281989   3.401 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.258           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  270594   3.547 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.244           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.964           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.125           ms/op
ClientPb.listUser                       sample  234453   4.092 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.351           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.690           ms/op
