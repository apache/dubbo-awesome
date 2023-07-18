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
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 6.158 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 9.071 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.335 ±(99.9%) 4.704 ops/ms [Average]
  (min, avg, max) = (9.071, 9.335, 9.586), stdev = 0.258
  CI (99.9%): [4.631, 14.039] (assumes normal distribution)


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
# Warmup Iteration   1: 3.090 ops/ms
# Warmup Iteration   2: 8.692 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.790 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (9.652, 9.790, 9.978), stdev = 0.168
  CI (99.9%): [6.716, 12.864] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
# Warmup Iteration   2: 8.507 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 9.565 ops/ms
Iteration   3: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.529 ±(99.9%) 1.455 ops/ms [Average]
  (min, avg, max) = (9.438, 9.529, 9.585), stdev = 0.080
  CI (99.9%): [8.074, 10.985] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.871 ops/ms
# Warmup Iteration   2: 7.424 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.092 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (8.030, 8.092, 8.167), stdev = 0.069
  CI (99.9%): [6.828, 9.357] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.129 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.006 ms/op
Iteration   1: 3.473 ±(99.9%) 0.008 ms/op
Iteration   2: 3.379 ±(99.9%) 0.011 ms/op
Iteration   3: 3.649 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.500 ±(99.9%) 2.504 ms/op [Average]
  (min, avg, max) = (3.379, 3.500, 3.649), stdev = 0.137
  CI (99.9%): [0.996, 6.004] (assumes normal distribution)


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
# Warmup Iteration   1: 9.702 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.007 ms/op
Iteration   1: 3.310 ±(99.9%) 0.005 ms/op
Iteration   2: 3.285 ±(99.9%) 0.005 ms/op
Iteration   3: 3.240 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (3.240, 3.278, 3.310), stdev = 0.035
  CI (99.9%): [2.639, 3.918] (assumes normal distribution)


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
# Warmup Iteration   1: 9.799 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.007 ms/op
Iteration   1: 3.399 ±(99.9%) 0.003 ms/op
Iteration   2: 3.430 ±(99.9%) 0.007 ms/op
Iteration   3: 3.500 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.443 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.399, 3.443, 3.500), stdev = 0.052
  CI (99.9%): [2.502, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 9.891 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.009 ms/op
Iteration   1: 3.949 ±(99.9%) 0.013 ms/op
Iteration   2: 3.981 ±(99.9%) 0.008 ms/op
Iteration   3: 3.884 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.938 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.884, 3.938, 3.981), stdev = 0.049
  CI (99.9%): [3.038, 4.838] (assumes normal distribution)


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
# Warmup Iteration   1: 9.525 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.011 ms/op
Iteration   1: 3.530 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  20.100 ms/op
                 createUser·p0.9999: 22.608 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.907 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 24.897 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  21.900 ms/op
                 createUser·p0.9999: 24.310 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272270
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11999 
    [ 2.500,  5.000) = 252451 
    [ 5.000,  7.500) = 6716 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     20.528 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.217 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 9.456 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  12.186 ms/op
                 existUser·p0.9999: 24.393 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  19.596 ms/op
                 existUser·p0.9999: 27.405 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  22.512 ms/op
                 existUser·p0.9999: 28.112 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287893
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3027 
    [ 2.500,  5.000) = 279108 
    [ 5.000,  7.500) = 4730 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.961 ms/op
     p(99.9900) =     27.532 ms/op
     p(99.9990) =     28.316 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.011 ms/op
Iteration   1: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  20.551 ms/op
                 getUser·p0.9999: 22.568 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.579 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 25.659 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  19.518 ms/op
                 getUser·p0.9999: 26.435 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274898
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7513 
    [ 2.500,  5.000) = 258995 
    [ 5.000,  7.500) = 7106 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     14.587 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     26.813 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 10.479 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.014 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  17.509 ms/op
                 listUser·p0.9999: 24.317 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 3.974 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.121 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.944 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.665 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240649
  mean =      3.989 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 231936 
    [ 5.000,  7.500) = 6705 
    [ 7.500, 10.000) = 1128 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     22.608 ms/op
     p(99.9990) =     24.621 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.335 ± 4.704  ops/ms
ClientPb.existUser                       thrpt       3   9.790 ± 3.074  ops/ms
ClientPb.getUser                         thrpt       3   9.529 ± 1.455  ops/ms
ClientPb.listUser                        thrpt       3   8.092 ± 1.264  ops/ms
ClientPb.createUser                       avgt       3   3.500 ± 2.504   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 0.640   ms/op
ClientPb.getUser                          avgt       3   3.443 ± 0.941   ms/op
ClientPb.listUser                         avgt       3   3.938 ± 0.900   ms/op
ClientPb.createUser                     sample  272270   3.523 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.468           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.528           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.445           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.788           ms/op
ClientPb.existUser                      sample  287893   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.961           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.532           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  274898   3.491 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.473           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.587           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  240649   3.989 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.071           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.319           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.608           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
