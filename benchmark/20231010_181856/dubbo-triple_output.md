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
# Warmup Iteration   1: 1.977 ops/ms
# Warmup Iteration   2: 5.219 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 9.083 ops/ms
Iteration   3: 8.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.828 ±(99.9%) 4.562 ops/ms [Average]
  (min, avg, max) = (8.583, 8.828, 9.083), stdev = 0.250
  CI (99.9%): [4.266, 13.389] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.726 ops/ms
# Warmup Iteration   2: 8.157 ops/ms
# Warmup Iteration   3: 9.174 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (9.513, 9.539, 9.563), stdev = 0.025
  CI (99.9%): [9.088, 9.990] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 8.288 ops/ms
# Warmup Iteration   3: 8.821 ops/ms
Iteration   1: 8.847 ops/ms
Iteration   2: 9.020 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.968 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.847, 8.968, 9.036), stdev = 0.105
  CI (99.9%): [7.055, 10.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.588 ops/ms
# Warmup Iteration   2: 7.137 ops/ms
# Warmup Iteration   3: 7.486 ops/ms
Iteration   1: 7.426 ops/ms
Iteration   2: 7.701 ops/ms
Iteration   3: 7.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.531 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (7.426, 7.531, 7.701), stdev = 0.149
  CI (99.9%): [4.811, 10.250] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.258 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.004 ms/op
Iteration   1: 3.624 ±(99.9%) 0.006 ms/op
Iteration   2: 3.478 ±(99.9%) 0.006 ms/op
Iteration   3: 3.491 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.531 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (3.478, 3.531, 3.624), stdev = 0.081
  CI (99.9%): [2.062, 5.000] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.005 ms/op
Iteration   1: 3.369 ±(99.9%) 0.003 ms/op
Iteration   2: 3.340 ±(99.9%) 0.004 ms/op
Iteration   3: 3.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.391 ±(99.9%) 1.181 ms/op [Average]
  (min, avg, max) = (3.340, 3.391, 3.464), stdev = 0.065
  CI (99.9%): [2.210, 4.572] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.580 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.005 ms/op
Iteration   1: 3.698 ±(99.9%) 0.005 ms/op
Iteration   2: 3.473 ±(99.9%) 0.004 ms/op
Iteration   3: 3.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.582 ±(99.9%) 2.059 ms/op [Average]
  (min, avg, max) = (3.473, 3.582, 3.698), stdev = 0.113
  CI (99.9%): [1.523, 5.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.159 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.008 ms/op
Iteration   1: 4.021 ±(99.9%) 0.008 ms/op
Iteration   2: 4.112 ±(99.9%) 0.010 ms/op
Iteration   3: 4.111 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.081 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (4.021, 4.081, 4.112), stdev = 0.052
  CI (99.9%): [3.133, 5.029] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.461 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.011 ms/op
Iteration   1: 3.597 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  21.464 ms/op
                 createUser·p0.9999: 25.366 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 3.551 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.502 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 25.325 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270251
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4323 
    [ 2.500,  5.000) = 257513 
    [ 5.000,  7.500) = 6437 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     25.886 ms/op
     p(99.9990) =     27.439 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 9.129 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
Iteration   1: 3.515 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   7.153 ms/op
                 existUser·p0.999:  20.940 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.563 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 23.989 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.524 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  22.684 ms/op
                 existUser·p0.9999: 27.293 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271413
  mean =      3.534 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5066 
    [ 2.500,  5.000) = 257174 
    [ 5.000,  7.500) = 7031 
    [ 7.500, 10.000) = 1609 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.208 ms/op
     p(99.9000) =     20.630 ms/op
     p(99.9900) =     26.439 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 10.305 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.014 ms/op
Iteration   1: 3.695 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.436 ms/op
                 getUser·p0.999:  20.987 ms/op
                 getUser·p0.9999: 23.190 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  22.741 ms/op
                 getUser·p0.9999: 24.923 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.635 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.364 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.606 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  20.316 ms/op
                 getUser·p0.9999: 27.466 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266639
  mean =      3.597 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3251 
    [ 2.500,  5.000) = 252983 
    [ 5.000,  7.500) = 8404 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     20.831 ms/op
     p(99.9900) =     26.029 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 10.140 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.013 ms/op
Iteration   1: 4.273 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 26.624 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  18.426 ms/op
                 listUser·p0.9999: 25.439 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 4.282 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.664 ms/op
                 listUser·p0.9999: 16.943 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226180
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 214012 
    [ 5.000,  7.500) = 8572 
    [ 7.500, 10.000) = 2646 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     25.650 ms/op
     p(99.9990) =     27.189 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.828 ± 4.562  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 0.451  ops/ms
ClientPb.getUser                         thrpt       3   8.968 ± 1.912  ops/ms
ClientPb.listUser                        thrpt       3   7.531 ± 2.720  ops/ms
ClientPb.createUser                       avgt       3   3.531 ± 1.469   ms/op
ClientPb.existUser                        avgt       3   3.391 ± 1.181   ms/op
ClientPb.getUser                          avgt       3   3.582 ± 2.059   ms/op
ClientPb.listUser                         avgt       3   4.081 ± 0.948   ms/op
ClientPb.createUser                     sample  270251   3.550 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  271413   3.534 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.208           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.630           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.439           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.458           ms/op
ClientPb.getUser                        sample  266639   3.597 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.029           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.639           ms/op
ClientPb.listUser                       sample  226180   4.244 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.612           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.650           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.558           ms/op
