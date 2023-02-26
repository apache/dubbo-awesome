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
# Warmup Iteration   1: 2.149 ops/ms
# Warmup Iteration   2: 5.466 ops/ms
# Warmup Iteration   3: 8.919 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.570 ±(99.9%) 5.462 ops/ms [Average]
  (min, avg, max) = (9.229, 9.570, 9.788), stdev = 0.299
  CI (99.9%): [4.108, 15.032] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 8.799 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.809 ±(99.9%) 2.767 ops/ms [Average]
  (min, avg, max) = (9.636, 9.809, 9.917), stdev = 0.152
  CI (99.9%): [7.042, 12.577] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.602 ops/ms
# Warmup Iteration   2: 8.245 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 9.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.562 ±(99.9%) 5.164 ops/ms [Average]
  (min, avg, max) = (9.282, 9.562, 9.848), stdev = 0.283
  CI (99.9%): [4.398, 14.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ops/ms
# Warmup Iteration   2: 7.449 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 7.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.754 ±(99.9%) 11.590 ops/ms [Average]
  (min, avg, max) = (7.044, 7.754, 8.269), stdev = 0.635
  CI (99.9%): [≈ 0, 19.344] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.252 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
Iteration   1: 3.379 ±(99.9%) 0.006 ms/op
Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
Iteration   3: 3.344 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.388 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.344, 3.388, 3.442), stdev = 0.050
  CI (99.9%): [2.480, 4.297] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.733 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.005 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.163 ±(99.9%) 0.010 ms/op
Iteration   3: 3.314 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.220 ±(99.9%) 1.495 ms/op [Average]
  (min, avg, max) = (3.163, 3.220, 3.314), stdev = 0.082
  CI (99.9%): [1.725, 4.715] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.276 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.005 ms/op
Iteration   1: 3.401 ±(99.9%) 0.002 ms/op
Iteration   2: 3.356 ±(99.9%) 0.005 ms/op
Iteration   3: 3.356 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.371 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.356, 3.371, 3.401), stdev = 0.026
  CI (99.9%): [2.896, 3.846] (assumes normal distribution)


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
# Warmup Iteration   1: 9.473 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.955 ±(99.9%) 0.008 ms/op
Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
Iteration   3: 3.819 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.908 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.819, 3.908, 3.955), stdev = 0.077
  CI (99.9%): [2.500, 5.316] (assumes normal distribution)


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
# Warmup Iteration   1: 10.205 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.008 ms/op
Iteration   1: 3.696 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   6.258 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  17.389 ms/op
                 createUser·p0.9999: 20.458 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.465 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  20.217 ms/op
                 createUser·p0.9999: 26.370 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272543
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9054 
    [ 2.500,  5.000) = 252059 
    [ 5.000,  7.500) = 9814 
    [ 7.500, 10.000) = 1025 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     18.201 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     26.775 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 7.944 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.898 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.218 ms/op
                 existUser·p0.9999: 21.745 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  12.728 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  11.484 ms/op
                 existUser·p0.9999: 24.019 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299666
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18861 
    [ 2.500,  5.000) = 277389 
    [ 5.000,  7.500) = 2536 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     10.519 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.798 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
Iteration   1: 3.360 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  20.179 ms/op
                 getUser·p0.9999: 23.723 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  19.731 ms/op
                 getUser·p0.9999: 23.137 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.633 ms/op
                 getUser·p0.9999: 25.774 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284141
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8848 
    [ 2.500,  5.000) = 268529 
    [ 5.000,  7.500) = 5430 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     18.828 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.032 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 8.497 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.013 ms/op
Iteration   1: 4.099 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.211 ms/op
                 listUser·p0.9999: 22.682 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.967 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240274
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 231482 
    [ 5.000,  7.500) = 6877 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     21.560 ms/op
     p(99.9990) =     22.878 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.570 ±  5.462  ops/ms
ClientPb.existUser                       thrpt       3   9.809 ±  2.767  ops/ms
ClientPb.getUser                         thrpt       3   9.562 ±  5.164  ops/ms
ClientPb.listUser                        thrpt       3   7.754 ± 11.590  ops/ms
ClientPb.createUser                       avgt       3   3.388 ±  0.908   ms/op
ClientPb.existUser                        avgt       3   3.220 ±  1.495   ms/op
ClientPb.getUser                          avgt       3   3.371 ±  0.475   ms/op
ClientPb.listUser                         avgt       3   3.908 ±  1.408   ms/op
ClientPb.createUser                     sample  272543   3.525 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.280            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.160            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.201            ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.495            ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689            ms/op
ClientPb.existUser                      sample  299666   3.201 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.300            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169            ms/op
ClientPb.existUser:existUser·p0.999     sample          10.519            ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.019            ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952            ms/op
ClientPb.getUser                        sample  284141   3.376 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.196            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.828            ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.707            ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345            ms/op
ClientPb.listUser                       sample  240274   3.994 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102            ms/op
ClientPb.listUser:listUser·p0.999       sample          14.811            ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.560            ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233            ms/op
