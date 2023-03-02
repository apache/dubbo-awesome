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
# Warmup Iteration   1: 1.863 ops/ms
# Warmup Iteration   2: 4.942 ops/ms
# Warmup Iteration   3: 8.774 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 8.927 ops/ms
Iteration   3: 9.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.063 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (8.927, 9.063, 9.179), stdev = 0.127
  CI (99.9%): [6.739, 11.387] (assumes normal distribution)


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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 8.862 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 9.727 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.855 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (9.727, 9.855, 9.935), stdev = 0.112
  CI (99.9%): [7.809, 11.901] (assumes normal distribution)


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
# Warmup Iteration   1: 2.709 ops/ms
# Warmup Iteration   2: 7.959 ops/ms
# Warmup Iteration   3: 8.509 ops/ms
Iteration   1: 9.272 ops/ms
Iteration   2: 9.138 ops/ms
Iteration   3: 9.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.275 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (9.138, 9.275, 9.416), stdev = 0.139
  CI (99.9%): [6.737, 11.814] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.659 ops/ms
# Warmup Iteration   2: 6.969 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 8.125 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 0.775 ops/ms [Average]
  (min, avg, max) = (8.049, 8.097, 8.125), stdev = 0.042
  CI (99.9%): [7.322, 8.873] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.610 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.005 ms/op
Iteration   1: 3.473 ±(99.9%) 0.008 ms/op
Iteration   2: 3.495 ±(99.9%) 0.009 ms/op
Iteration   3: 3.408 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.408, 3.459, 3.495), stdev = 0.046
  CI (99.9%): [2.629, 4.289] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.751 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.006 ms/op
Iteration   1: 3.216 ±(99.9%) 0.009 ms/op
Iteration   2: 3.366 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.271 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (3.216, 3.271, 3.366), stdev = 0.083
  CI (99.9%): [1.761, 4.781] (assumes normal distribution)


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
# Warmup Iteration   1: 9.800 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.007 ms/op
Iteration   1: 3.509 ±(99.9%) 0.005 ms/op
Iteration   2: 3.509 ±(99.9%) 0.005 ms/op
Iteration   3: 3.379 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.466 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.379, 3.466, 3.509), stdev = 0.075
  CI (99.9%): [2.096, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 11.376 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.006 ms/op
Iteration   1: 4.029 ±(99.9%) 0.009 ms/op
Iteration   2: 4.059 ±(99.9%) 0.009 ms/op
Iteration   3: 3.872 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.987 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (3.872, 3.987, 4.059), stdev = 0.101
  CI (99.9%): [2.150, 5.824] (assumes normal distribution)


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
# Warmup Iteration   1: 9.235 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
Iteration   1: 3.535 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 29.786 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   2: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  22.882 ms/op
                 createUser·p0.9999: 29.073 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  21.106 ms/op
                 createUser·p0.9999: 26.813 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273199
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7134 
    [ 2.500,  5.000) = 258577 
    [ 5.000,  7.500) = 6294 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     21.522 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     31.016 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.795 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  11.531 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   2: 3.466 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  10.410 ms/op
                 existUser·p0.9999: 28.589 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281837
  mean =      3.405 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12942 
    [ 2.500,  5.000) = 261405 
    [ 5.000,  7.500) = 6469 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     27.421 ms/op
     p(99.9990) =     28.788 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.173 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.011 ms/op
Iteration   1: 3.474 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  20.773 ms/op
                 getUser·p0.9999: 24.837 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.527 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  23.629 ms/op
                 getUser·p0.9999: 25.850 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  10.863 ms/op
                 getUser·p0.9999: 27.092 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274969
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11762 
    [ 2.500,  5.000) = 253162 
    [ 5.000,  7.500) = 8886 
    [ 7.500, 10.000) = 693 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     26.493 ms/op
     p(99.9990) =     27.435 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 10.638 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.013 ms/op
Iteration   1: 4.239 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  23.285 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.246 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  16.494 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.086 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228996
  mean =      4.189 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 218543 
    [ 5.000,  7.500) = 7776 
    [ 7.500, 10.000) = 1875 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 266 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.999 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     25.566 ms/op
     p(99.9990) =     26.578 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.063 ± 2.324  ops/ms
ClientPb.existUser                       thrpt       3   9.855 ± 2.046  ops/ms
ClientPb.getUser                         thrpt       3   9.275 ± 2.539  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 0.775  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.830   ms/op
ClientPb.existUser                        avgt       3   3.271 ± 1.510   ms/op
ClientPb.getUser                          avgt       3   3.466 ± 1.370   ms/op
ClientPb.listUser                         avgt       3   3.987 ± 1.837   ms/op
ClientPb.createUser                     sample  273199   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.522           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  281837   3.405 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.421           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.869           ms/op
ClientPb.getUser                        sample  274969   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.042           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.493           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  228996   4.189 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.999           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.566           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.001           ms/op
