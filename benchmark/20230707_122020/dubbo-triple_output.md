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
# Warmup Iteration   1: 1.883 ops/ms
# Warmup Iteration   2: 5.512 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 9.159 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.204 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (9.092, 9.204, 9.362), stdev = 0.140
  CI (99.9%): [6.645, 11.764] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 8.548 ops/ms
# Warmup Iteration   3: 9.416 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.611 ±(99.9%) 4.412 ops/ms [Average]
  (min, avg, max) = (9.347, 9.611, 9.822), stdev = 0.242
  CI (99.9%): [5.199, 14.023] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 7.810 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.281 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.219 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (9.101, 9.219, 9.281), stdev = 0.102
  CI (99.9%): [7.364, 11.073] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 7.644 ops/ms
Iteration   1: 7.682 ops/ms
Iteration   2: 7.811 ops/ms
Iteration   3: 7.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.795 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (7.682, 7.795, 7.894), stdev = 0.107
  CI (99.9%): [5.846, 9.745] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.534 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.006 ms/op
Iteration   2: 3.568 ±(99.9%) 0.009 ms/op
Iteration   3: 3.576 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.553 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.514, 3.553, 3.576), stdev = 0.034
  CI (99.9%): [2.937, 4.168] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.241 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.005 ms/op
Iteration   1: 3.368 ±(99.9%) 0.008 ms/op
Iteration   2: 3.512 ±(99.9%) 0.010 ms/op
Iteration   3: 3.343 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.407 ±(99.9%) 1.664 ms/op [Average]
  (min, avg, max) = (3.343, 3.407, 3.512), stdev = 0.091
  CI (99.9%): [1.744, 5.071] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.003 ms/op
Iteration   1: 3.558 ±(99.9%) 0.005 ms/op
Iteration   2: 3.418 ±(99.9%) 0.007 ms/op
Iteration   3: 3.419 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (3.418, 3.465, 3.558), stdev = 0.081
  CI (99.9%): [1.994, 4.935] (assumes normal distribution)


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
# Warmup Iteration   1: 11.159 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.009 ms/op
Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
Iteration   2: 4.129 ±(99.9%) 0.014 ms/op
Iteration   3: 3.944 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.051 ±(99.9%) 1.747 ms/op [Average]
  (min, avg, max) = (3.944, 4.051, 4.129), stdev = 0.096
  CI (99.9%): [2.305, 5.798] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  21.393 ms/op
                 createUser·p0.9999: 23.917 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  24.489 ms/op
                 createUser·p0.9999: 27.294 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.641 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 26.385 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269533
  mean =      3.561 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3569 
    [ 2.500,  5.000) = 259185 
    [ 5.000,  7.500) = 5573 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     18.610 ms/op
     p(99.9900) =     26.742 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.766 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.010 ms/op
                 existUser·p0.999:  21.703 ms/op
                 existUser·p0.9999: 27.750 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 3.570 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  24.229 ms/op
                 existUser·p0.9999: 27.537 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  10.320 ms/op
                 existUser·p0.9999: 30.179 ms/op
                 existUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275648
  mean =      3.480 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10800 
    [ 2.500,  5.000) = 256750 
    [ 5.000,  7.500) = 7019 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     28.424 ms/op
     p(99.9990) =     30.654 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 9.008 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
Iteration   1: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  20.670 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.919 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  22.234 ms/op
                 getUser·p0.9999: 26.527 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 3.582 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 28.123 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271482
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6124 
    [ 2.500,  5.000) = 257183 
    [ 5.000,  7.500) = 6757 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     20.988 ms/op
     p(99.9900) =     26.598 ms/op
     p(99.9990) =     28.522 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 10.831 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.016 ms/op
Iteration   1: 4.096 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.411 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  21.821 ms/op
                 listUser·p0.9999: 24.779 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.046 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 22.167 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 3.994 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237122
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 227601 
    [ 5.000,  7.500) = 7564 
    [ 7.500, 10.000) = 1114 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     24.094 ms/op
     p(99.9990) =     25.581 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.204 ± 2.559  ops/ms
ClientPb.existUser                       thrpt       3   9.611 ± 4.412  ops/ms
ClientPb.getUser                         thrpt       3   9.219 ± 1.854  ops/ms
ClientPb.listUser                        thrpt       3   7.795 ± 1.950  ops/ms
ClientPb.createUser                       avgt       3   3.553 ± 0.615   ms/op
ClientPb.existUser                        avgt       3   3.407 ± 1.664   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 1.470   ms/op
ClientPb.listUser                         avgt       3   4.051 ± 1.747   ms/op
ClientPb.createUser                     sample  269533   3.561 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.717           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.610           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.742           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.606           ms/op
ClientPb.existUser                      sample  275648   3.480 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.385           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.424           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  271482   3.535 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.260           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  237122   4.045 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.094           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
