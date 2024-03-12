# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ops/ms
# Warmup Iteration   2: 12.279 ops/ms
# Warmup Iteration   3: 12.528 ops/ms
Iteration   1: 12.778 ops/ms
Iteration   2: 12.683 ops/ms
Iteration   3: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.804 ±(99.9%) 2.481 ops/ms [Average]
  (min, avg, max) = (12.683, 12.804, 12.951), stdev = 0.136
  CI (99.9%): [10.324, 15.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 13.381 ops/ms
# Warmup Iteration   3: 13.423 ops/ms
Iteration   1: 13.403 ops/ms
Iteration   2: 13.236 ops/ms
Iteration   3: 13.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.316 ±(99.9%) 1.531 ops/ms [Average]
  (min, avg, max) = (13.236, 13.316, 13.403), stdev = 0.084
  CI (99.9%): [11.784, 14.847] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.846 ops/ms
# Warmup Iteration   2: 13.085 ops/ms
# Warmup Iteration   3: 13.017 ops/ms
Iteration   1: 13.185 ops/ms
Iteration   2: 13.044 ops/ms
Iteration   3: 13.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.146 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (13.044, 13.146, 13.207), stdev = 0.088
  CI (99.9%): [11.531, 14.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.784 ops/ms
# Warmup Iteration   2: 10.661 ops/ms
# Warmup Iteration   3: 10.924 ops/ms
Iteration   1: 10.846 ops/ms
Iteration   2: 10.980 ops/ms
Iteration   3: 10.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.908 ±(99.9%) 1.232 ops/ms [Average]
  (min, avg, max) = (10.846, 10.908, 10.980), stdev = 0.068
  CI (99.9%): [9.676, 12.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.003 ms/op
Iteration   1: 2.517 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.492 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (2.468, 2.492, 2.517), stdev = 0.024
  CI (99.9%): [2.046, 2.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.402 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.402, 2.416, 2.424), stdev = 0.012
  CI (99.9%): [2.199, 2.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.003 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.433 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.420, 2.433, 2.445), stdev = 0.012
  CI (99.9%): [2.208, 2.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.005 ms/op
Iteration   1: 2.894 ±(99.9%) 0.006 ms/op
Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
Iteration   3: 2.887 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.886 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.877, 2.886, 2.894), stdev = 0.009
  CI (99.9%): [2.721, 3.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  7.712 ms/op
                 createUser·p0.9999: 13.135 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   3.535 ms/op
                 createUser·p0.999:  5.909 ms/op
                 createUser·p0.9999: 12.059 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  8.159 ms/op
                 createUser·p0.9999: 10.453 ms/op
                 createUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389824
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 190831 
    [ 2.500,  3.750) = 194912 
    [ 3.750,  5.000) = 3173 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.680 ms/op
     p(99.9900) =     12.813 ms/op
     p(99.9990) =     13.433 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.702 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.367 ±(99.9%) 0.005 ms/op
Iteration   1: 2.350 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.851 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.807 ms/op
                 existUser·p0.9999: 13.766 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.361 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.855 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.988 ms/op
                 existUser·p0.9999: 12.662 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 13.134 ms/op
                 existUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405178
  mean =      2.367 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 210160 
    [ 2.500,  3.750) = 191805 
    [ 3.750,  5.000) = 2246 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      6.683 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.317 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.535 ms/op
                 getUser·p0.999:  6.377 ms/op
                 getUser·p0.9999: 13.758 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  7.467 ms/op
                 getUser·p0.9999: 12.437 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.773 ms/op
                 getUser·p0.9999: 11.631 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390112
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 195446 
    [ 2.500,  3.750) = 190473 
    [ 3.750,  5.000) = 3278 
    [ 5.000,  6.250) = 399 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      6.798 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.009 ms/op
Iteration   1: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.902 ms/op
                 listUser·p0.9999: 10.338 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   2: 2.935 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 12.341 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.911 ms/op
                 listUser·p0.9999: 11.213 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324764
  mean =      2.953 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 190 
    [ 1.250,  2.500) = 104279 
    [ 2.500,  3.750) = 184074 
    [ 3.750,  5.000) = 29309 
    [ 5.000,  6.250) = 5573 
    [ 6.250,  7.500) = 616 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 270 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.534 ms/op
     p(99.9990) =     12.464 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.804 ± 2.481  ops/ms
ClientPb.existUser                       thrpt       3  13.316 ± 1.531  ops/ms
ClientPb.getUser                         thrpt       3  13.146 ± 1.614  ops/ms
ClientPb.listUser                        thrpt       3  10.908 ± 1.232  ops/ms
ClientPb.createUser                       avgt       3   2.492 ± 0.446   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.433 ± 0.225   ms/op
ClientPb.listUser                         avgt       3   2.886 ± 0.165   ms/op
ClientPb.createUser                     sample  389824   2.460 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.662           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.680           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  405178   2.367 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.461           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.683           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.271           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  390112   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.837           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  324764   2.953 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.877           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.747           ms/op
