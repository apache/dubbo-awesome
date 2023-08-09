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
# Warmup Iteration   1: 1.878 ops/ms
# Warmup Iteration   2: 5.007 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 9.003 ops/ms
Iteration   2: 9.138 ops/ms
Iteration   3: 9.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.079 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (9.003, 9.079, 9.138), stdev = 0.070
  CI (99.9%): [7.809, 10.350] (assumes normal distribution)


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
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 8.636 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.523 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.576 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (9.435, 9.576, 9.771), stdev = 0.174
  CI (99.9%): [6.397, 12.755] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.869 ops/ms
# Warmup Iteration   2: 8.148 ops/ms
# Warmup Iteration   3: 8.710 ops/ms
Iteration   1: 9.054 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.122 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (9.043, 9.122, 9.269), stdev = 0.128
  CI (99.9%): [6.791, 11.453] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.766 ops/ms
# Warmup Iteration   2: 6.842 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.787 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (7.711, 7.787, 7.894), stdev = 0.096
  CI (99.9%): [6.039, 9.534] (assumes normal distribution)


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
# Warmup Iteration   1: 10.267 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.006 ms/op
Iteration   1: 3.655 ±(99.9%) 0.007 ms/op
Iteration   2: 3.509 ±(99.9%) 0.007 ms/op
Iteration   3: 3.460 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.541 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (3.460, 3.541, 3.655), stdev = 0.101
  CI (99.9%): [1.693, 5.390] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.317 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.004 ms/op
Iteration   1: 3.391 ±(99.9%) 0.005 ms/op
Iteration   2: 3.300 ±(99.9%) 0.006 ms/op
Iteration   3: 3.399 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.363 ±(99.9%) 1.005 ms/op [Average]
  (min, avg, max) = (3.300, 3.363, 3.399), stdev = 0.055
  CI (99.9%): [2.358, 4.368] (assumes normal distribution)


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
# Warmup Iteration   1: 9.941 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.004 ms/op
Iteration   1: 3.493 ±(99.9%) 0.004 ms/op
Iteration   2: 3.613 ±(99.9%) 0.003 ms/op
Iteration   3: 3.425 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.510 ±(99.9%) 1.736 ms/op [Average]
  (min, avg, max) = (3.425, 3.510, 3.613), stdev = 0.095
  CI (99.9%): [1.774, 5.246] (assumes normal distribution)


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
# Warmup Iteration   1: 11.803 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.625 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.010 ms/op
Iteration   1: 4.193 ±(99.9%) 0.007 ms/op
Iteration   2: 4.152 ±(99.9%) 0.007 ms/op
Iteration   3: 4.130 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.158 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (4.130, 4.158, 4.193), stdev = 0.032
  CI (99.9%): [3.571, 4.745] (assumes normal distribution)


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
# Warmup Iteration   1: 9.188 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.011 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.909 ms/op
                 createUser·p0.999:  21.540 ms/op
                 createUser·p0.9999: 23.915 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.436 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  24.509 ms/op
                 createUser·p0.9999: 27.828 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277437
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6904 
    [ 2.500,  5.000) = 263037 
    [ 5.000,  7.500) = 5716 
    [ 7.500, 10.000) = 1186 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.501 ms/op
     p(99.9000) =     19.429 ms/op
     p(99.9900) =     27.304 ms/op
     p(99.9990) =     28.825 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.407 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  20.927 ms/op
                 existUser·p0.9999: 27.337 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 3.414 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.674 ms/op
                 existUser·p0.999:  23.069 ms/op
                 existUser·p0.9999: 28.013 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.466 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  10.680 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281653
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12456 
    [ 2.500,  5.000) = 260961 
    [ 5.000,  7.500) = 6598 
    [ 7.500, 10.000) = 1105 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 131 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.589 ms/op
     p(99.9900) =     29.137 ms/op
     p(99.9990) =     31.309 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 8.350 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.012 ms/op
Iteration   1: 3.822 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  22.404 ms/op
                 getUser·p0.9999: 52.928 ms/op
                 getUser·p1.00:   53.281 ms/op

Iteration   2: 3.507 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  20.539 ms/op
                 getUser·p0.9999: 25.081 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.563 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  20.537 ms/op
                 getUser·p0.9999: 30.019 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264575
  mean =      3.626 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 246180 
    [ 5.000, 10.000) = 17508 
    [10.000, 15.000) = 528 
    [15.000, 20.000) = 56 
    [20.000, 25.000) = 220 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     21.280 ms/op
     p(99.9900) =     51.779 ms/op
     p(99.9990) =     53.215 ms/op
     p(99.9999) =     53.281 ms/op
    p(100.0000) =     53.281 ms/op


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
# Warmup Iteration   1: 11.729 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.112 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  23.003 ms/op
                 listUser·p0.9999: 25.828 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  20.066 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 4.197 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   7.981 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 20.066 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230992
  mean =      4.156 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 216421 
    [ 5.000,  7.500) = 11109 
    [ 7.500, 10.000) = 2147 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     25.254 ms/op
     p(99.9990) =     26.398 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.079 ± 1.270  ops/ms
ClientPb.existUser                       thrpt       3   9.576 ± 3.179  ops/ms
ClientPb.getUser                         thrpt       3   9.122 ± 2.331  ops/ms
ClientPb.listUser                        thrpt       3   7.787 ± 1.748  ops/ms
ClientPb.createUser                       avgt       3   3.541 ± 1.849   ms/op
ClientPb.existUser                        avgt       3   3.363 ± 1.005   ms/op
ClientPb.getUser                          avgt       3   3.510 ± 1.736   ms/op
ClientPb.listUser                         avgt       3   4.158 ± 0.587   ms/op
ClientPb.createUser                     sample  277437   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.422           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.501           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.196           ms/op
ClientPb.existUser                      sample  281653   3.406 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.037           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.137           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.785           ms/op
ClientPb.getUser                        sample  264575   3.626 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.850           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.382           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.280           ms/op
ClientPb.getUser:getUser·p0.9999        sample          51.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          53.281           ms/op
ClientPb.listUser                       sample  230992   4.156 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.311           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.988           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
