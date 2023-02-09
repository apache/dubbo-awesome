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
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 5.516 ops/ms
# Warmup Iteration   3: 8.685 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.429 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (9.343, 9.429, 9.540), stdev = 0.101
  CI (99.9%): [7.587, 11.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 9.600 ops/ms
Iteration   1: 10.180 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 10.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.037 ±(99.9%) 2.766 ops/ms [Average]
  (min, avg, max) = (9.878, 10.037, 10.180), stdev = 0.152
  CI (99.9%): [7.270, 12.803] (assumes normal distribution)


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
# Warmup Iteration   1: 2.806 ops/ms
# Warmup Iteration   2: 8.330 ops/ms
# Warmup Iteration   3: 9.437 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.377 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.399 ±(99.9%) 2.967 ops/ms [Average]
  (min, avg, max) = (9.248, 9.399, 9.571), stdev = 0.163
  CI (99.9%): [6.432, 12.366] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 7.369 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 7.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.961 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (7.822, 7.961, 8.092), stdev = 0.135
  CI (99.9%): [5.498, 10.424] (assumes normal distribution)


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
# Warmup Iteration   1: 9.946 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.005 ms/op
Iteration   1: 3.470 ±(99.9%) 0.006 ms/op
Iteration   2: 3.494 ±(99.9%) 0.003 ms/op
Iteration   3: 3.382 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.449 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.382, 3.449, 3.494), stdev = 0.059
  CI (99.9%): [2.375, 4.523] (assumes normal distribution)


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
# Warmup Iteration   1: 8.929 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.003 ms/op
Iteration   1: 3.258 ±(99.9%) 0.006 ms/op
Iteration   2: 3.334 ±(99.9%) 0.005 ms/op
Iteration   3: 3.161 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.161, 3.251, 3.334), stdev = 0.087
  CI (99.9%): [1.672, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 9.533 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.007 ms/op
Iteration   1: 3.399 ±(99.9%) 0.011 ms/op
Iteration   2: 3.393 ±(99.9%) 0.005 ms/op
Iteration   3: 3.376 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (3.376, 3.389, 3.399), stdev = 0.012
  CI (99.9%): [3.165, 3.614] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.883 ±(99.9%) 0.011 ms/op
Iteration   2: 3.842 ±(99.9%) 0.013 ms/op
Iteration   3: 3.844 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.856 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.842, 3.856, 3.883), stdev = 0.023
  CI (99.9%): [3.438, 4.274] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.805 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.994 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 21.420 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.498 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.399 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  22.279 ms/op
                 createUser·p0.9999: 24.697 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 24.928 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277212
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14457 
    [ 2.500,  5.000) = 255931 
    [ 5.000,  7.500) = 5558 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     19.785 ms/op
     p(99.9900) =     24.529 ms/op
     p(99.9990) =     26.386 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 8.692 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.198 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  11.130 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 24.644 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.374 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   6.720 ms/op
                 existUser·p0.999:  19.745 ms/op
                 existUser·p0.9999: 25.512 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294886
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7273 
    [ 2.500,  5.000) = 282719 
    [ 5.000,  7.500) = 4052 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.331 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     25.907 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.838 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.011 ms/op
Iteration   1: 3.567 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.832 ms/op
                 getUser·p0.999:  14.466 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  20.334 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.438 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277138
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4654 
    [ 2.500,  5.000) = 264383 
    [ 5.000,  7.500) = 5900 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     23.776 ms/op
     p(99.9990) =     24.598 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 11.561 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  18.207 ms/op
                 listUser·p0.9999: 22.844 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.674 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 17.748 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.896 ms/op
                 listUser·p0.999:  15.186 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239498
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 229618 
    [ 5.000,  7.500) = 7334 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.917 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.429 ± 1.842  ops/ms
ClientPb.existUser                       thrpt       3  10.037 ± 2.766  ops/ms
ClientPb.getUser                         thrpt       3   9.399 ± 2.967  ops/ms
ClientPb.listUser                        thrpt       3   7.961 ± 2.463  ops/ms
ClientPb.createUser                       avgt       3   3.449 ± 1.074   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 1.579   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 0.224   ms/op
ClientPb.listUser                         avgt       3   3.856 ± 0.418   ms/op
ClientPb.createUser                     sample  277212   3.462 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.785           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.529           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  294886   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.871           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.345           ms/op
ClientPb.getUser                        sample  277138   3.462 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.844           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.776           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.707           ms/op
ClientPb.listUser                       sample  239498   4.006 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.292           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.917           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.379           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
