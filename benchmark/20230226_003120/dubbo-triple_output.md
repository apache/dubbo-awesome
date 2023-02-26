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
# Warmup Iteration   1: 2.089 ops/ms
# Warmup Iteration   2: 5.530 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 9.190 ops/ms
Iteration   2: 9.586 ops/ms
Iteration   3: 9.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.405 ±(99.9%) 3.650 ops/ms [Average]
  (min, avg, max) = (9.190, 9.405, 9.586), stdev = 0.200
  CI (99.9%): [5.755, 13.055] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ops/ms
# Warmup Iteration   2: 8.867 ops/ms
# Warmup Iteration   3: 9.253 ops/ms
Iteration   1: 9.562 ops/ms
Iteration   2: 9.437 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.568 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (9.437, 9.568, 9.704), stdev = 0.133
  CI (99.9%): [7.135, 12.001] (assumes normal distribution)


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
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 8.197 ops/ms
# Warmup Iteration   3: 9.370 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.100 ops/ms
Iteration   3: 9.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.271 ±(99.9%) 4.474 ops/ms [Average]
  (min, avg, max) = (9.100, 9.271, 9.552), stdev = 0.245
  CI (99.9%): [4.797, 13.744] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.137 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (7.895, 8.137, 8.280), stdev = 0.211
  CI (99.9%): [4.292, 11.983] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.283 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.006 ms/op
Iteration   1: 3.409 ±(99.9%) 0.010 ms/op
Iteration   2: 3.373 ±(99.9%) 0.008 ms/op
Iteration   3: 3.444 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.409 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.373, 3.409, 3.444), stdev = 0.035
  CI (99.9%): [2.762, 4.056] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.007 ms/op
Iteration   1: 3.280 ±(99.9%) 0.005 ms/op
Iteration   2: 3.284 ±(99.9%) 0.005 ms/op
Iteration   3: 3.312 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.280, 3.292, 3.312), stdev = 0.017
  CI (99.9%): [2.975, 3.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.076 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.005 ms/op
Iteration   1: 3.371 ±(99.9%) 0.006 ms/op
Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
Iteration   3: 3.546 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (3.367, 3.428, 3.546), stdev = 0.102
  CI (99.9%): [1.561, 5.296] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.335 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
Iteration   2: 3.870 ±(99.9%) 0.013 ms/op
Iteration   3: 3.891 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.870, 3.913, 3.976), stdev = 0.056
  CI (99.9%): [2.886, 4.939] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.875 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
Iteration   1: 3.351 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  19.606 ms/op
                 createUser·p0.9999: 23.191 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  22.885 ms/op
                 createUser·p0.9999: 26.370 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   6.026 ms/op
                 createUser·p0.999:  16.845 ms/op
                 createUser·p0.9999: 26.229 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283679
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7865 
    [ 2.500,  5.000) = 268832 
    [ 5.000,  7.500) = 5604 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     17.224 ms/op
     p(99.9900) =     25.928 ms/op
     p(99.9990) =     27.541 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 8.467 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
Iteration   1: 3.289 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.848 ms/op
                 existUser·p0.9999: 21.745 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 26.190 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  11.157 ms/op
                 existUser·p0.9999: 26.678 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296083
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14825 
    [ 2.500,  5.000) = 276675 
    [ 5.000,  7.500) = 3666 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.613 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.106 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 9.597 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.010 ms/op
Iteration   1: 3.608 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  18.396 ms/op
                 getUser·p0.9999: 22.165 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   2: 3.477 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  9.424 ms/op
                 getUser·p0.9999: 28.451 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  10.535 ms/op
                 getUser·p0.9999: 28.095 ms/op
                 getUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273612
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8627 
    [ 2.500,  5.000) = 254269 
    [ 5.000,  7.500) = 8761 
    [ 7.500, 10.000) = 1554 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     11.162 ms/op
     p(99.9900) =     27.579 ms/op
     p(99.9990) =     28.779 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 10.803 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.014 ms/op
Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 3.864 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.689 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.250 ms/op
                 listUser·p0.9999: 22.142 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242901
  mean =      3.949 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 235613 
    [ 5.000,  7.500) = 5467 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.649 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.777 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.405 ± 3.650  ops/ms
ClientPb.existUser                       thrpt       3   9.568 ± 2.433  ops/ms
ClientPb.getUser                         thrpt       3   9.271 ± 4.474  ops/ms
ClientPb.listUser                        thrpt       3   8.137 ± 3.846  ops/ms
ClientPb.createUser                       avgt       3   3.409 ± 0.647   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 0.316   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 1.868   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 1.026   ms/op
ClientPb.createUser                     sample  283679   3.385 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.566           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.928           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  296083   3.242 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.613           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.466           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.558           ms/op
ClientPb.getUser                        sample  273612   3.506 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.685           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.086           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.162           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.579           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  242901   3.949 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.649           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526           ms/op
