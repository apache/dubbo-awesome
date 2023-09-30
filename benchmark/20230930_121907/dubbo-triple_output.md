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
# Warmup Iteration   1: 1.968 ops/ms
# Warmup Iteration   2: 5.398 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 8.831 ops/ms
Iteration   2: 9.008 ops/ms
Iteration   3: 9.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.999 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (8.831, 8.999, 9.158), stdev = 0.164
  CI (99.9%): [6.013, 11.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.115 ops/ms
# Warmup Iteration   2: 8.660 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 9.731 ops/ms
Iteration   2: 9.830 ops/ms
Iteration   3: 9.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.721 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (9.603, 9.721, 9.830), stdev = 0.114
  CI (99.9%): [7.642, 11.801] (assumes normal distribution)


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
# Warmup Iteration   1: 2.964 ops/ms
# Warmup Iteration   2: 8.864 ops/ms
# Warmup Iteration   3: 9.069 ops/ms
Iteration   1: 9.128 ops/ms
Iteration   2: 9.370 ops/ms
Iteration   3: 9.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.180 ±(99.9%) 3.087 ops/ms [Average]
  (min, avg, max) = (9.044, 9.180, 9.370), stdev = 0.169
  CI (99.9%): [6.094, 12.267] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.805 ops/ms
# Warmup Iteration   2: 7.023 ops/ms
# Warmup Iteration   3: 7.560 ops/ms
Iteration   1: 7.594 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.738 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (7.594, 7.738, 7.833), stdev = 0.127
  CI (99.9%): [5.425, 10.051] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.749 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.004 ms/op
Iteration   1: 3.512 ±(99.9%) 0.005 ms/op
Iteration   2: 3.452 ±(99.9%) 0.004 ms/op
Iteration   3: 3.479 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.452, 3.481, 3.512), stdev = 0.030
  CI (99.9%): [2.925, 4.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.187 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.002 ms/op
Iteration   1: 3.412 ±(99.9%) 0.003 ms/op
Iteration   2: 3.373 ±(99.9%) 0.003 ms/op
Iteration   3: 3.390 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.392 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.373, 3.392, 3.412), stdev = 0.020
  CI (99.9%): [3.033, 3.751] (assumes normal distribution)


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
# Warmup Iteration   1: 9.588 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.005 ms/op
Iteration   1: 3.570 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
Iteration   3: 3.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.500 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (3.446, 3.500, 3.570), stdev = 0.064
  CI (99.9%): [2.338, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 10.973 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.741 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.007 ms/op
Iteration   1: 4.160 ±(99.9%) 0.008 ms/op
Iteration   2: 4.151 ±(99.9%) 0.003 ms/op
Iteration   3: 4.184 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.165 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (4.151, 4.165, 4.184), stdev = 0.017
  CI (99.9%): [3.853, 4.477] (assumes normal distribution)


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
# Warmup Iteration   1: 9.472 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.010 ms/op
Iteration   1: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  22.574 ms/op
                 createUser·p0.9999: 24.374 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  23.606 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.466 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.410 ms/op
                 createUser·p0.999:  19.543 ms/op
                 createUser·p0.9999: 25.275 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274404
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5614 
    [ 2.500,  5.000) = 263961 
    [ 5.000,  7.500) = 3838 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 186 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     20.617 ms/op
     p(99.9900) =     25.563 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 8.736 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.359 ms/op
                 existUser·p0.999:  21.067 ms/op
                 existUser·p0.9999: 28.396 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.387 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  21.610 ms/op
                 existUser·p0.9999: 25.783 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  18.882 ms/op
                 existUser·p0.9999: 27.971 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282552
  mean =      3.397 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10534 
    [ 2.500,  5.000) = 265942 
    [ 5.000,  7.500) = 5144 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.943 ms/op
     p(99.9000) =     19.151 ms/op
     p(99.9900) =     28.033 ms/op
     p(99.9990) =     29.300 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 8.837 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.013 ms/op
Iteration   1: 3.468 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 20.669 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.527 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  18.799 ms/op
                 getUser·p0.9999: 20.906 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.196 ms/op
                 getUser·p0.999:  19.368 ms/op
                 getUser·p0.9999: 24.059 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273814
  mean =      3.503 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2374 
    [ 2.500,  5.000) = 265593 
    [ 5.000,  7.500) = 4713 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     14.898 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     25.478 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 10.802 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.011 ms/op
Iteration   1: 4.205 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 4.199 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.728 ms/op
                 listUser·p0.9999: 18.165 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.231 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.096 ms/op
                 listUser·p0.999:  14.907 ms/op
                 listUser·p0.9999: 17.472 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227711
  mean =      4.212 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 217879 
    [ 5.000,  7.500) = 7597 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     15.602 ms/op
     p(99.9900) =     19.636 ms/op
     p(99.9990) =     21.407 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.999 ± 2.986  ops/ms
ClientPb.existUser                       thrpt       3   9.721 ± 2.079  ops/ms
ClientPb.getUser                         thrpt       3   9.180 ± 3.087  ops/ms
ClientPb.listUser                        thrpt       3   7.738 ± 2.313  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 0.556   ms/op
ClientPb.existUser                        avgt       3   3.392 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   3.500 ± 1.161   ms/op
ClientPb.listUser                         avgt       3   4.165 ± 0.312   ms/op
ClientPb.createUser                     sample  274404   3.497 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.419           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.563           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  282552   3.397 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.943           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.033           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  273814   3.503 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.898           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.577           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.592           ms/op
ClientPb.listUser                       sample  227711   4.212 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.602           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.636           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.758           ms/op
